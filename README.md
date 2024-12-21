# Репозиторий для написания РК по программированию, Федин Андрей ИУ7-34Б
## РК номер №3

Формат входных данных. Задание.
В текстовом файле хранятся строки, каждая из которых представляет собой имя. 
Пример.
Vasiliy
Lionel
Harry
Vladimir
Eve
Bob


Задача:
Прочитать уникальные строки из файла in.txt и сохранить их в динамическом массиве строк. 
Отсортировать массив имен в алфавитном порядке. Вы можете использовать функцию qsort() для сортировки.
Подсчитать количество вхождений каждого имени в исходном файле и сохранить эту информацию. Это можно сделать во время чтения файла (п. 1), а можно после.
Записать отсортированный массив имен и их количество в текстовый файл out.txt.
Пояснения:
Необходимо использовать malloc() / calloc() / realloc() для хранения данных.
Аргументы имени файлов можно как захардкодить, так и передавать через аргументы командной строки.
МОЖНО использовать _GNU_SOURCE.
НЕЛЬЗЯ сохранить в памяти только имена и подсчитывать их количество во время печати. Необходимо обязательно сохранить информацию о количестве в памяти.
Данные в памяти могут быть представлены как угодно (можно использовать как один общий массив для имён и количеств, так и два разных).
Третий пункт МОЖНО выполнить во время выполнения первого пункта. Т.е разрешается сохранить информацию о количестве имён сразу во время чтения файла. 




Пример работы программы.
Если файл in.txt содержит:
Andrey
Zan
Lionel
Andrey
Eve
Eve

То выходной файл out.txt должен содержать:
Andrey: 2
Eve: 2
Lionel: 1
Zan: 1


Тесты, оформление, требования


Задание оформляется как многофайловый ( > 1) проект (Makefile) Обязательно наличие файла main.c, в котором находится только функция main() и директивы #include <..>.


Исходный код РК располагается в отдельной ветке rk_03 (2-ой семестр, 1-ый рубежный контроль). В ветке rk_03 создается папка rk_03, в которой располагаются исходные файлы.
