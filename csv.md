CSV или Comma separated values е файлов формат, който ви ползволява бързо и лесно да създавате таблични документи.
Както можеби се досещате Comma separated values се превежда като "стойности разделени със запетая".
Файловият формат е следния:

1. Всеки ред трябва да садържа еднакъв брои колонки (брои запетаии)
2. Накаря на реда не трябва да има запетая (на англ. No trailing comma)
3. Ако някоя стойност садържа запетайка, то тя трябва да бъде обградена от двоини кавички (термина на англ. е symbol escaping)

Пример:

Файл:

```
id,user name,email
1,NoHomey,ivo.stratev.tues@gmail.com
2,IvoStratev,ivo.stratev.tues@gmail.com
```

Резултат:

| id | user name  | email                      | 
|----|------------|----------------------------|
| 1  | NoHomey    | ivo.stratev.tues@gmail.com |
| 2  | IvoStratev | ivo.stratev.tues@gmail.com |
