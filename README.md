# В этом репозитории будут храниться мои работы C#

## Первое занятие. Запуск консольного приложения

* *dotnet new console* создаёт новое консольное приложение в той папке где она была вызвана.
* *dotnet run* запускает консольное приложение.

**Команды, используемые для общения с консолью:**

1. Console.WriteLine() - вывод информации на консоль.

1.1. Console.WriteLine("Text") - вывод комментария осуществяется в двойных кавычках; 

1.2. Console.WriteLine(num) - Вывод переменной осуществяется указанием имени переменной;

1.3. Console.WriteLine("Text" + num) - смешанный вывод данных производится через конкатенацию (Сложение строк);

1.4. Console.Write() - версия команды вывода без перехода на новую строку.

2. Console.ReadLine() - получение информации из консоли;

2.1. Console.Read() - получение информации до пробела.

*NB:* При работе с кансолью мы оперируем только строками.

**Преобразование типов**

При получении данных из консоли для получения нужного типа используется команда *Convert.ToInt32()*(ToDouble - для вещественных чисел)

## Второе занятие. Массивы и функиции

**Массивы**

1.1. int[] array = new int[число] - создаёт целочисленный массив и выделяет под него память;

1.2. int[] array = {1,2,3} - создаёт массив из заданных чисел.

1.3. Вывод массива.
*for(int i=0;i<число эл. в массиве;i++)*
*Console.Write(array[i])*

**Функции**

1. Возвращяющие переменные(int)

1.1. return "переменная" - служит для возврата переменной в главную программу;

1.2. int "название функции" (тип данных"," переменная) - вызов функции в главной программе.

2. Не возвращяющие переменные(void)

2.1. void "название функции" (тип данных"," переменная) - вызов функции в главной программе.

3. Логический тип (bool)

3.1. bool "название функции" (тип данных"," переменная) - вызов функции в главной программе.

3.2. return True/False - служит для возврата переменной в главную программу;

## Третье занятие. Повторение мать учения

1.ch = new Random().Next(число "1",число "2") - записывает в переменную ch число от число "1" до числа "2".

## Четвёртое занятие. Двумерные массивы

1. Двумерный массив - это таблица.

2. int[,] arr = new int[,] - создание массива;

2.1. массив заполняется с помощью двух циклов (по строкам и по столбцам)

for(int i=0;i<sh;i++)
{
    for(int j=0;j<dl;j++)
    {
        array[i,j]=Convert.ToInt32(Console.ReadLine());
    }
    Console.WriteLine();
}

3. arr.GetLength(0) - количество строк массива;

3.1. arr.GetLength(1) - количество столбцов в массиве.

4. arr[i,j] - к элементам массива следует обращяться по строке и столбцу.


