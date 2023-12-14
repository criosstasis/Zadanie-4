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
Научиться работать с персептроном
## Задание 1
### в проекте Unity реализовать перцептрон, который умеет производить вычисления:
### OR | дать комментарии о корректности работы
### AND | дать комментарии о корректности работы
### NAND | дать комментарии о корректности работы
### XOR | дать комментарии о корректности работы

Ход работы:

- OR
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-4/blob/main/perc1.PNG)
В результате работы выяснилось, что данному виду вычислений персептрон обучается за 4-5 эпох. 
- AND
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-4/blob/main/perc2.PNG)
Вычислениям AND персептрон обучается медленнее, за 6-7 эпох.
- NAND
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-4/blob/main/perc3.PNG)
Этим вычилениям персептрон обучается с тем же количеством эпох, что и AND, то есть за 6-7.
- XOR
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-4/blob/main/perc4.PNG)
Данным вычислением персептрон так и не смог обучиться.





## Задание 2
### Построить графики зависимости количества эпох от ошибки  обучения. Указать от чего зависит необходимое количество эпох обучения.

Ход работы:
- Был создан график зависимости количества эпох от ошибок обучения.
![Иллюстрация к проекту](https://github.com/criosstasis/Zadanie-4/blob/main/TABLperc.PNG)

По графикам можно понять, что количество ошибок зависит от сложности выичилений.



## Задание 3
### Построить визуальную модель работы перцептрона на сцене Unity.

## Выводы

В результате выполненой работы я узнал про то, как работать с персептронами и вычислениями.

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
