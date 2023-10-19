# Упражнения

### Подготовка

1. Форкните текущий репозиторий на свою учетную запись github
2. Склонируйте свой репозиторий на компьютер
3. Переключитесь в ветку `exercise_02`
4. Выполните команду: `npm ci`

# Задание
- в папке `src` создайте файл `functions.js`, в котором напишите пять функций (одно задание – одна функция) и экспортируйте их.

Для проверки решения выполните push в ветку `exercise_02`, после чего на вкладке `actions` посмотрите результат выполнения тестов.

### Локальная проверка
Для локальной проверки используйте `npm test`

### Задание 1
Оригинал задачи с [codewars](https://www.codewars.com/kata/55685cd7ad70877c23000102/train/javascript)
В этом простом задании вам дается число, и вы должны сделать его положительным.

Примечания
- число уже может быть положительным, и в этом случае никаких изменений не требуется.
```js
makePositive(1);     // 1
makePositive(-5);    // 5
makePositive(0);     // 0
makePositive(-0.12); // 0.12
```

### Задание 2
Оригинал задачи с [codewars](https://www.codewars.com/kata/55a70521798b14d4750000a4/train/javascript)
Создайте функцию, которая будет возвращать оператор приветствия, использующий входные данные; ваша программа должна возвращать, 'Hi <name>!'. Если передаётся пустая строка - возвращается 'Hi!'

```js
greet('John'); ➞ 'Hi John!'
greet('Elise'); ➞ 'Hi Elise!'
greet(''); ➞ 'Hi!'
```

### Задание 3
Создать функцию, которая принимает имя и фамилию пользователя, а возвращает имя и первую букву фамилии.

```js
getShotFullName('Oliver', 'Smith'); ➞ 'Oliver S.'
getShotFullName('Jack', 'Johnson'); ➞ 'Jack J.'
getShotFullName('Harry', 'Williams'); ➞ 'Harry W.'
getShotFullName('Jacob', 'Brown'); ➞ 'Jacob B.'
getShotFullName('Charley', 'Jones'); ➞ 'Charley J.'
```

### Задание 4
Оригинал задачи с [codewars](https://www.codewars.com/kata/65128732b5aff40032a3d8f0/train/javascript)
Реализуйте функцию, которая принимает две строки, состоящие из `t` и `f`, возвращает новую строку, которая показывает, как две строки взаимодействуют между собой.\
Правила взаимодействия:
- когда в одной строке символов меньше чем в другой, получается '-'.
- когда символ `t` взаимодействует с символом `t`, получается символ `t`.
- когда символ `f` взаимодействует с символом `f`, получается символ `f`.
- когда символ `f` взаимодействует с символом `t`, получается символ `.`.

```js
neutralise("ffttff", "ttfftt") ➞ "......"
neutralise("ftftft", "ftftft") ➞ "ftftft"
neutralise("fttf", "ftft") ➞ "ft.."
```

### Задание 5
Оригинал задачи с [codewars](https://www.codewars.com/kata/57356c55867b9b7a60000bd7/);
Ваша задача - создать функцию, которая выполняет три основные математические операции и возвращает результат вычисления.
Функция должна принимать строку, представляющую арифметическое выражение.
Функция должна возвращать результат вычисления после применения выбранной операции.
Операции: `+`,`-`,`*`

```js
basicOp('4+7'); ➞ 11
basicOp('1-2'); ➞ -1
basicOp('3*2'); ➞ 6
```
