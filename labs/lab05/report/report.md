---
## Front matter
title: "Отчет по лабораторной работе №5"
subtitle: "Основы работы с Midnight Commander"
author: "Ромицына Анасатсия Романовна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Освоить инструкции языка ассамблера mov. Преобрести знания использования Midnight Commander.

# Задание
Написать 2 программы по примеру и впоследствии изменить их по условию.


# Выполнение лабораторной работы

Открываем Midnight Commander (рис. @fig:001).

![Вводим команду  mc](image/1.jpg){#fig:001 width=70%}

Переходим в каталог, созданный при выполнении 4 ЛБ (рис. @fig:002).

![Переходим в каталог](image/2.jpg){#fig:002 width=70%}

Создаем каталог lab05 (рис. @fig:003).

![Создаем каталог функциональной клавишей F7](image/3.jpg){#fig:003 width=70%}

Создаем файл lab5-1.asm (рис. @fig:004).

![Воспользуемся командой touch](image/4.jpg){#fig:004 width=70%}

Открываем файл для редактирования и заполняем его по листингу (рис. @fig:005).

![Открывем файл функциональной клавишей, заполняем и сохраняем](image/5.jpg){#fig:005 width=70%}

Открывем файл для просмотра (рис. @fig:006).

![Открываем файл и убеждаемся, что файл содержит текст программы](image/6.jpg){#fig:006 width=70%}

Транслируем текст программы и запускаем исполняемый файл (рис. @fig:007).

![Проверяем, как работает данная программа](image/7.jpg){#fig:007 width=70%}

Скачиваем файл со страницы курса (рис. @fig:008).

![Скачиваем файл](image/8.jpg){#fig:008 width=70%}

Копируем файл в нужную директорию (рис. @fig:009).

![Копируем скаченный файл](image/9.jpg){#fig:009 width=70%}

Создаем копию файла lab5-1.asm (рис. @fig:010).

![Создаем копию файла клавишей F6](image/10.jpg){#fig:010 width=70%}

Проверяем созданный файл (рис. @fig:011).

![Проверяем скопировался ли файл](image/11.jpg){#fig:011 width=70%}

Открываем новый файл и заполняем его в соответствии с листингом (рис. @fig:012).

![Открываем и заполняем файл](image/12.jpg){#fig:012 width=70%}

Транслируем и запускаем новый файл (рис. @fig:013).

![Смотрим, как сработала программа](image/13.jpg){#fig:013 width=70%}

Снова открываем файл для редактирования и меняем sprintLF на sprint( рис. @fig:014).

![Редактируем файл](image/14.jpg){#fig:014 width=70%}

Транслируем и запускаем файл(рис. @fig:015).

![Смотрим, как сработал программа и сравниваем с прошлой ](image/15.jpg){#fig:015 width=70%}

Таким образом можем понять, что команда sprint выводит текст в той же строке, а sprintLF переносит на новую строку.

## Задание для самостоятельной работы

Создаем копию файла lab5-1.asm (рис. @fig:016).

![Создаем копию файла lab5-1.asm](image/16.jpg){#fig:016 width=70%}

Редактируем файл, чтобы введеный текст с клавиатуры выводился в консоль (рис. @fig:017).

![Редактируем файл](image/17.jpg){#fig:017 width=70%}

Транслируем файл и запускаем программу (рис. @fig:018).

![Проверяем правильность написания программы](image/18.jpg){#fig:018 width=70%}

Создаем копию файла lab5-2.asm (рис. @fig:019).

![Создаем копию файла lab5-2.asm](image/19.jpg){#fig:019 width=70%}

Редактируем файл, чтобы введеный текст с клавиатуры выводился в консоль (рис. @fig:020).

![Редактируем файл](image/20.jpg){#fig:020 width=70%}

Транслируем файл и запускаем программу (рис. @fig:021).

![Проверяем правильность написания программы](image/21.jpg){#fig:021 width=70%}






# Выводы

Мы преобрели навыки работы с Midnight Commander и освоили инстркции mov


