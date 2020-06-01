# Go-Commander
Project for a deeper study of golang libraries

COMMANDER v 0.01

Цель - рабочий удобный терминал, способный полностью заменить терминал GNOME и т.п. Работа из командной строки, названия комманд должны быть аналогичными linux командам (не вижу смысла изобретать велосипед)
Функционал:

        1. Работа с файлами и дирректориями - чтение, редактирование, поиск, удаление, создание и т.п.
        2. Работа с накопителями - подключение, отключение, сбор информации
        3. Работа с сетью (функционал не определен)
        4. Встроенный сервер (функционал не определен)
        5. Встроенный файловый менеджер (аналог mc)


exit            -       выход из программы

ls              -       вывод файлов в текущей дирректории

ls [path]       -       вывод файлов по указанному пути

show [filename] -       показывает содержимое файла

cd              -       смена каталога

clear           -       очистить экран

mkdir           -       создать дирректорию

rmdir           -       удалить дирректорию






ЗАДАЧИ (до 7.06.20):
1) выводить в первую очередь каталоги, потом файлы при команде ls (выделять разным цветом) (+)
2) помещять курсор после абсолютного пути (как и в стандартных терминалах) (+)
3) при выводе файлов и каталогов - форматировать в виде одинаковых отступов (+)
4) прописать команды:
        - создание каталога (+)
        - удаление каталога (+)
        - переименование каталога
        - создание файла
        - удаление файла
        - переименование файла
