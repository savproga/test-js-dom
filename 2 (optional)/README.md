# Задание 2 (JS)

### Задание, которое получает студент

После открывающего тега `<body>` создайте теги `<script></script>` и напишите в них свой первый JS-код:

```javascript
alert('Привет, мир!');
```

### Структура этого репозитория

В папке `pre` лежит начальный код студента. В папке `post` — конечный код (код верно решённого задания). Ваш код должен быть написан в файле `__test__/index.js`.

### Ваше задание

1. Написать список того, что необходимо проверить в коде студента;
2. Написать код, который это проверял бы.

Вся ваша работа должна быть в файле `__test__/index.js`. В нём в массив `errors` должны добавляться ошибки студента. Формат ошибок — произвольная строка (например: "Функция alert не вызвана"). Если код в файле `index.html` верный — массив после проверок должен быть пустым. Если неверный, в массиве должны быть ошибки. Свой код можете проверять в консоли в файлах `pre/index.html` и `post/index.html`. Чтобы проверять JS код, мы подключили файл `__test__/lib.js`. Он делает доступными две глобальных переменных: `esprima` и `esquery`. Используйте их в проверках.

### FAQ

* Тесты должны работать Я.Браузере, Chrome, Firefox, Safari, Opera, Edge, IE11;