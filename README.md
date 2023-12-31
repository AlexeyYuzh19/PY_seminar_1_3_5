# Знакомство с языком Python (семинары)
## Урок 1. Ввод-Вывод, операторы ветвления
Для решения данного домашнего задания вам необходимо воспользоваться сервисом автоматической проверки написанного кода.
### Задача 1. Сумма цифр трехзначного числа
Найдите сумму цифр трехзначного числа n.<br>
Результат сохраните в перменную res.<br>
__*Пример*__:<br>
n = 123 -> res = 6 (1 + 2 + 3)<br>
n = 100 -> res = 1 (1 + 0 + 0)

### Задача 2. Бумажные журавлики
Петя, Катя и Сережа делают из бумаги журавликов. Вместе они сделали n журавликов.<br>Сколько журавликов сделал каждый ребенок, если известно, что Петя и Сережа сделали одинаковое количество журавликов, а Катя сделала в два раза больше журавликов, чем Петя и Сережа вместе?<br>Выведите через пробел количество журавликов, сделанных Петей, Катей и Сережей.<br>
__*Пример*__:<br>n = 6 -> 1 4 1<br>
n = 24 -> 4 16 4<br>
n = 60 -> 10 40 10

### Задача 3. Счастливый билет
Вы пользуетесь общественным транспортом? Вероятно, вы расплачивались за проезд и получали билет с номером.<br>
Счастливым билетом называют такой билет с шестизначным номером, где сумма первых трех цифр равна сумме последних трех.<br>
Т.е. билет с номером 385916 – счастливый, т.к. 3+8+5=9+1+6.<br>
Вам требуется написать программу, которая проверяет счастливость билета с номером n и выводит на экран yes или no.<br>
__*Пример*__:<br>
n = 385916 -> yes<br>
n = 123456 -> no

### Задача 3. Деление шоколадки
Определите, можно ли от шоколадки размером a × b долек отломить c долек, если разрешается сделать один разлом по прямой между дольками (то есть разломить шоколадку на два прямоугольника).<br>
Выведите yes или no соответственно.<br>
__*Пример*__:<br>
a, b, c = 3, 2, 4 -> yes<br>
a, b, c = 3, 2, 1 -> no

## Урок 3. Списки и словари
Для решения данного домашнего задания вам необходимо воспользоваться сервисом автоматической проверки написанного кода.
### Задача 1. Встречаемость элемента в массиве
Требуется вычислить, сколько раз встречается некоторое число k в массиве list_1.<br>
Найдите количество и выведите его.<br>
__*Пример*__:<br>
list_1 = [1, 2, 3, 4, 5]<br>
k = 3 -> 1

### Задача 2. Ближайший элемент в массиве
Требуется найти в массиве list_1 самый близкий по величине элемент к заданному числу k и вывести его.<br>
__*Пример*__:<br>
list_1 = [1, 2, 3, 4, 5]<br>
k = 6 -> 5

### Задача 3. Скрабл
В настольной игре Скрабл (Scrabble) каждая буква имеет определенную ценность.<br>
В случае с английским алфавитом очки распределяются так:<br>
A, E, I, O, U, L, N, S, T, R – 1 очко;<br>
D, G – 2 очка;<br>
B, C, M, P – 3 очка;<br>
F, H, V, W, Y – 4 очка;<br>
K – 5 очков;<br>
J, X – 8 очков;<br>
Q, Z – 10 очков.<br>
А русские буквы оцениваются так:<br>
А, В, Е, И, Н, О, Р, С, Т – 1 очко;<br>
Д, К, Л, М, П, У – 2 очка;<br>
Б, Г, Ё, Ь, Я – 3 очка;<br>
Й, Ы – 4 очка;<br>
Ж, З, Х, Ц, Ч – 5 очков;<br>
Ш, Э, Ю – 8 очков;<br>
Ф, Щ, Ъ – 10 очков.<br>
Напишите программу, которая вычисляет стоимость введенного пользователем слова k и выводит его. Будем считать, что на вход подается только одно слово, которое содержит либо только английские, либо только русские буквы.<br>
__*Пример*__:<br>
k = 'ноутбук' -> 12

## Урок 5. Рекурсия и алгоритмы
Для решения данного домашнего задания вам необходимо воспользоваться сервисом автоматической проверки написанного кода.
### Задача 1. Возведение в степень
Напишите функцию f, которая на вход принимает два числа a и b, и возводит число a в целую степень b с помощью рекурсии.<br>
Функция не должна ничего выводить, только возвращать значение.<br>
__*Пример*__:<br>
a = 3; b = 5 -> 243 (3⁵)<br>
a = 2; b = 3 -> 8 

### Задача 2. Рекурсивная сумма
Напишите рекурсивную функцию sum(a, b), возвращающую сумму двух целых неотрицательных чисел.<br>Из всех арифметических операций допускаются только +1 и -1. Также нельзя использовать циклы.<br>
Функция не должна ничего выводить, только возвращать значение.<br>
__*Пример*__:<br>
sum(2, 2) -> 4
