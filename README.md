# Контрольное задание 

Данная программа формирует массив из строк, длинна которых меньше, либо равна 3 из строк начального массива.

Начальный массив задается на старте выполнения.

Программа имеет 1 метод, который принимает начальный массив и возвращает новый масиив с отобранными по заданному параметру элемеентами.

Внутри, метод OnlyThreeOrLess() создает пустой список exitArray.
Далее с помощью цикла элементы входящего массива array проверяются на параметр " <= 3 ", если параметр подходит, данный элемент добавляется в exitArray.

По завершению цикла сформированный лист exitArray преобразуется в массив.

Цикл foreach применяется только для наглядности: в консоль будут выведены элементы existArray.

Блок-схема представлена ниже:

![рис. 1 Блок-схема программы](/control_task1/img/sheme.jpg)