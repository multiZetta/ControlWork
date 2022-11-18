> # Контрольные работы

**№1**

**По итогу прохождения первого блока обучения**

Необходимо:

1. Создать репозиторий на GitHub

2. Нарисовать блок-схему алгоритм (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)

3. Снабдить репозиторий оформленны текстовым описанием решения (файл README.md)

4. Написать программу, решающую поставленную задачу

5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)

>Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры:

[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]

[“1234”, “1567”, “-2”, “computer science”] → [“-2”]

[“Russia”, “Denmark”, “Kazan”] → []


Описание решения

* Вводим текст с набором символов (слова, цифры, знаки и прочее)

* Из введенного текста формируем одномерный массив, где элементы будут всё что в находится в тексте разделенные пробелом

* Есть такой оператор foreach. Про него можно узнать на стр [Microsoft](https://learn.microsoft.com/ru-ru/dotnet/csharp/language-reference/statements/iteration-statements), которую давал преподаватель для дополнительного изучения. При решении данной задачи, на предыдушем шаге мы перевели текст на отдельные строки, которые стали отдельными массивами и этот оператор foreach подходит, т.к. необходимо как раз проверить каждую строку на определенные условия. 

* Затем берем каждую строку (которая стала отдельным массивом) и проверяем её на размер, длина которых меньше, либо равна 3

* И выводим в консоль те строки, которые нашлись. А если бы не было таких, то выводится []




Решение

[Код](FirstControlWork/Program.cs)   |   [Блок схема](FirstControlWork/FirstControlWork.drawio.png)