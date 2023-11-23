# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #4 выполнил(а):
- Александров Андрей Александрович
- РИ000024
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)



## Цель работы
Разработать оптимальный баланс для десяти уровней игры Dragon Picker

## Задание 1
### в проекте Unity реализовать перцептрон, который умеет производить вычисления:
### OR | дать комментарии о корректности работы
### AND | дать комментарии о корректности работы
### NAND | дать комментарии о корректности работы
### XOR | дать комментарии о корректности работы

Ход работы:
- Было выбранно 3 переменные, которые влияют на сложность игры. Переменная Speed влияет на скорость перемещения дракона. Time between egg drops влияет на частоту сброса яиц драконом. Изменения Этих параметров между уровнями сложности представлены в таблице

|Уровень сложности| Speed | Time between egg drops | Change Direction |
| ------ | ------ | ------ | ------ |
|1| 4 | 2 | 0,01 |
|2|4.5| 1,8 | 0,012 |
|3| 5  | 1,6 | 0,014 |
|4| 5,5 | 1,4 | 0,016 |
|5| 6 | 1,2 | 0,018 |
|6|6,5 | 1 | 0,02 |
|7| 7 | 0,8 | 0,022 |
|8|7,5 | 0,6 | 0,024 |
|9|8 | 0,4 | 0,026 |
|10|8,5 | 0,2 | 0,028 |



## Задание 2
### Создайте 10 сцен на Unity с изменяющимся уровнем сложности.
Ход работы:
- Было создано 10 сцен в Unity, где в соответствии с таблицей были изменены параметры. Картинки, на которых показаны эти изменения, представлены ниже.
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-3/blob/main/Снимок.PNG)
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-3/blob/main/Снимок2.PNG)
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-3/blob/main/Снимок3.PNG)
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-3/blob/main/Снимок4.PNG)
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-3/blob/main/Снимок5.PNG)
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-3/blob/main/Снимок6.PNG)
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-3/blob/main/Снимок7.PNG)
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-3/blob/main/Снимок8.PNG)
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-3/blob/main/Снимок9.PNG)
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-3/blob/main/Снимок10.PNG)



## Задание 3
### Решение должно заполнять google-таблицу данными из Python. В Python данные также должны быть визуализированы.

## Выводы

В результате выполненой работы я узнал про то, как правильно разрабатывать оптимальный баланс.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
