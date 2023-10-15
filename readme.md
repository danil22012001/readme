# Инструкция по работе с Git и удаленными репозиториями

## Что такое Git?
Git - это одна из реализаций распределенных систем контроля версий, имеющая как и локальные, так и удаленные репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория

## Создание коммитов

### ***git init*** - Инициализация репозитория.

### ***git add "file_name"*** - Добавит файлу с названием __file_name__ вермионность.

### ***git reset "file_name"*** - Удалить у файла с названием __file_name__ версионность

### ***git add*** - Добавить всем файлам в папке версионность 

### ***git reset*** - Убрать у всех файлов в папке версионность 

### ***git commit -m "commit_massege"*** - Упрощенный вариант ввода комита

### ***git commit*** - Обычный вариант коммита (долгий)

### ***git commit -am*** - Если файл имеет состояние __modified__ (т.е был tracked ранее и мы его добавили с помощью git add ), то можно пропустить этап с коиандой __git add__ посредством использования данной команды 

### ***git checkout "hash_numder"*** - Переместить на коммит c хэшем "hash_number" (для того, чтобы вернуться git checkout master/main)

### ***git diff*** - Последние изменения (начиная от коммита)

### ***git merge*** - совместить две ветки 

### ***git branch -d*** - удалить ненуную ветку (черновик)

# Инструкция для работы с Markdown

## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его звездочками(*) или знаком нижнего подчеркивания ( _ ). _Например_, *вот так* или _вот так_.

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**) или двойным знаком нижнего подчеркивания ( __ ). _Например_, **вот так** или __вот так__.

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.

## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком + .
*Например*, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4
* Элемент 5 

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать.
1. Первый пункт
2. Второй пункт
3. Третий пункт

## Работа с изображениями

Чтобы вставить изображение в текст, достаточно написать следущее: ![Привет это тефтелька!](images.jpg)
 
## Ссылки

## Работа с таблицами

## Цитаты

## Заключение