### Задание:
Создать репозиторий на GitHub
Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете ее в отдельный метод)
Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
Написать программу, решающую поставленную задачу
Использовать контроль версий в работе над этим небольшим проектом (не должно быть так что все залито одним коммитом, как минимум этапы 2, 3 и 4 должны быть расположены в разных коммитах)

Задача:
 Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

 ### Алгоритм программы:
Инициализируем данные исходных массивов.
Инициализируем вспомогательную переменную count = 0, в которую Запишем количество строк, длина которых 3 символа и меньше.

Вычисляем количество строк, длинна которых меньше либо равна 3 символа.

Запустим цикл по каждой строке массива, где будем сверять длинну каждой переменной масства- если длина меньше или равна трём заносим переменную count и продолжаем счётчик цикла. Если длина больше трёх пропускаем переменную и берем следующую.

Инициализируем массив результатов размером count.

Формируем массив с результатами.

Снова в цикле проходим по каждой строке и также сравниваем на каждой итерации длину строки. Однако, теперь если длина меньше или равна трём, мы в текущий массив добавляем данную строку, Что бы определить длинну  полученного массива мы из размера массива вычитаем текущее значение данного счётчика.

Выводим массив результатов в консоль
По заданию , для примера, используем вводные данные :

["hello", "2", "world", ":-)"] -> ["2", ":-)"]

["1234", "1567", "-2", "computer science"] -> ["-2"]

["Russia", "Denmark", "Kazan"] -> []
