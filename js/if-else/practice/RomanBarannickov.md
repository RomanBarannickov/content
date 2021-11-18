🛠 Так же частым случаем бывает вызов функции по условию используя логическое И `&&`

Простая реализация:

```js
const someFunction = () => {
  // ...полезный код
}

if (day === "Tuesday") {
  someFunction()
}
```

Более короткая и лаконичная запись:

```js
const someFunction = () => {
  // ...полезный код
}

const isTuesday = day === "Tuesday";

isTuesday && someFunction(); // если isTuesday === true произойдет вызов функции справа от &&
```
