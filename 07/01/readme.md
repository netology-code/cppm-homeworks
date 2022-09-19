# Задача 1. Препроцессорные директивы
В этом задании мы используем некоторые изученные нами препроцессорные директивы


В вашей программе:
 - объявите символьную константу MODE с целочисленным значением
 - проверьте, что константа определена - иначе программа не должна скомпилироваться и должна выдать сообщение о необходимости определить MODE 
 - в случае, если MODE имеет значение 0 - выведите на консоль "Работаю в режиме тренировки"
 - если MODE имеет значение 1 - определите функцию `add`, которая должна складывать два числа, выведите на консоль "Работаю в боевом режиме", попросите пользователя ввести два числа и выведите результат сложения с помощью функции add на консоль
 - если MODE имеет любое другое значение, выведите на консоль "Неизвестный режим. Завершение работы"
 
 Обратите внимание - функция `add` должна быть определена **только** если MODE имеет значение 1

### Пример работы программы
#### Консоль
```
Работаю в боевом режиме
Введите число 1: 4
Введите число 2: 6
Результат сложения: 10
```
#### Подсказки

> Не читайте этот раздел сразу, попытайтесь сначала решить задачу самостоятельно :)

<details>

<summary>Подсказка. Что использовать для решения?</summary>

Для определения константы используйте директиву `#define`

Для проверки, определена ли константа, используйте одну из директив: `#ifdef`, `#ifndef`, `#if defined` или `#if !defined`

Для прекращения компиляции и вывода сообщения об ошибке используйте директиву `#error`

Для проверки значения константы используйте директивы `#if`, `#elif`, `#else`

</details>