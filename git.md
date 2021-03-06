# Регистрация в github
> препоръчително е при регистрация да изпозлвате вашето име

# Създаване на хранлище
> изполвайте + в горния десен ъгъл, до картинката на профила ви

# Инсталиране на git
[За Windows кликни тук](https://git-scm.com/download/win)
> Ако се чудите, коя опция да изберете преди **finish**, избере първатата

# Конфигуриране на git
```
git config --global user.email "<имейла, с който сте се регистрира ли>"
git config --global user.name "<името, под което сте се регистрира ли>"
```

Пример:
```
git config --global user.email "ivo.stratev.tues@gmail.com"
git config --global user.name "NoHomey"
```

Проверка дали правилно сте си конфигурирали git:
```
git config user.email
ivo.stratev.tues@gmail.com
git config user.name
NoHomey
```

# Преглед на текущата работна директория (папка)
`pwd`

Пример:
```
pwd
C:/Users/Nt-anex/
```

# Създаване на папка (директория) в текущата
`mkdir <име на папка>`

Пример:
`mkdir ivo`

# Сменяне на текущата работна директория (папка) с нейна поддиректория (подпапка)
`cd <име на подпапка>`

Пример:
```
pwd
C:/Users/Nt-anex/
mkdir ivo
cd ivo
pwd
C:/Users/Nt-anex/ivo
```

# Сваляне на хранилището на вашата машина (клониране)
`git clone htpps://github.com/<потребителско име>/<име на хранилището>.git`

Пример:
`git clone https://github.com/NoHomey/git-talks.git`

#***Важно преди да изпозлвате git команда различна от git clone сменете текущата директория с тази на хранилището***:

Следвайки предния пример:
```
cd git-talks
pwd
C:/Users/Nt-anex/ivo/git-talks
```

# Добавяне на всички промени към commit
`git add -A`

# Правене на commit
`git commit -m "<съобщение>"`

# Пращане към хранилището (добавяне на локалните ви промени от commit-а/тите в хранилището)
`git push`

# Синхронизиране (обновяване)
`git pull`

За повече информация и примери: (http://gitref.org/)

#***Ако искате да добавя обяснение за друга git команда или да  обясня някоя по-подробно отворете едно issue***
