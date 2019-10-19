# bash_test_task_1

Тестовое задание, полученное на одном из собеседований.

## Текст задания

Please write script in bash or other shell which receive as input path to directory and script go over directories and subdirectories and in each directory create file with name `dirname_<timestamp>` with list of files inside this directory 

## Выполнение

Задание было выполнено в текстовом редакторе GVIM под ОС Windows 7, для проверки была создана структура папок, некоторые из которых содержали вложенные папки и/или произвольно именованные пустые файлы.

Файлу-скрипту в качестве параметра передается корневая папка указанной структуры.

В результате работы скрипта в каждой папке создается файл с именем, соответствующим заданию. В файле перечислены остальные файлы из текущей папки.

Файл скрипта для проверки работоспособности запускался в git bash.
