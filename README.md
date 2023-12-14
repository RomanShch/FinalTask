# FinalTask

## Задача
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

## Описание решения
Сначало объявляю ***два массива***. Далее создаю ***метод***, в котором прохожусь по исходному массиву с условием ***( <=3 )***, если условие выполняется записываю текущее значение в новый массив. Перменная ***count*** служит счетчиков для записи по порядку во второй массив. После присвоения увеличиваю переменная ***count*** на 1 и возвращается к циклу for и тем самым провераю весь исходный массив.