---
## Front matter
title: "Лабораторная работа №2"
subtitle: " "
author: "Ромицына Анастасия Романовна"

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
Целью данной работы является изучение принципов технологий Ethernet и
Fast Ethernet и практическое освоение методик оценки работоспособности сети,
построенной на базе технологии Fast Ethernet.
# Выполнение лабораторной работы

Требуется оценить работоспособность 100-мегабитной сети Fast Ethernet в
соответствии с первой и второй моделями. Конфигурации сети приведены на
рис. 1.1. Топология сети представлена на рис. 1.2:
(рис. [-@fig:001]).

![Варианты заданий.](image/1.png){#fig:001 width=70%}

Требуется оценить работоспособность 100-мегабитной сети Fast Ethernet в
соответствии с первой и второй моделями. Конфигурации сети приведены на
рис. 1.1. Топология сети представлена на рис. 1.2:
(рис. [-@fig:002]).

![Топология сети.](image/2.png){#fig:002 width=70%}


Предельно допустимый диаметр домена коллизий в Fast Ethernet.(рис. [-@fig:003]).

![Предельно допустимый диаметр домена коллизий в Fast Ethernet.](image/3.png){#fig:003 width=70%}


Временные задержки компонентов сети Fast Ethernet(рис. [-@fig:004]).

![Временные задержки компонентов сети Fast Ethernet](image/4.png){#fig:004 width=70%}

Вариант 1:
Первая модель: 96+5+97=198 (198<205)
Вывод: удовлетворяет условию работоспособности сети по первой модели.
Первая модель: 96+5+97=198 (198<205)
Вывод: удовлетворяет условию работоспособности сети по первой модели.

Вариант 2:
Первая модель: 95+90+98=283 (283>205)
Вывод: не удовлетворяет условию работоспособности сети по первой модели.
Вторя модель: 100+92+92+(95+90+98)*1,112=598 (598>512)
Вывод: не удовлетворяет условию работоспособности сети по второй модели.

Вариант 3:
Первая модель: 60+5+100=165 (165<205)
Вывод: удовлетворяет условию работоспособности сети по первой модели.
Вторя модель: 100+92+92+(60+5+100)*1,112=467 (467<512)
Вывод: удовлетворяет условию работоспособности сети по второй модели.

Вариант 4:
Первая модель: 70+4+80=154 (154<205)
Вывод: удовлетворяет условию работоспособности сети по первой модели.
Вторя модель: 100+92+92+(70+4+80)*1,112=455 (455<512)
Вывод: удовлетворяет условию работоспособности сети по второй модели

Вариант 5:
Первая модель: 60+15+100=175 (175<205)
Вывод: удовлетворяет условию работоспособности сети по первой модели.
Вторя модель: 100+92+92+(60+15+100)*1,112=478 (478<512)
Вывод: удовлетворяет условию работоспособности сети по второй модели.

Вариант 6:
Первая модель: 70+9+100=179 (179<205)
Вывод: удовлетворяет условию работоспособности сети по первой модели.
Вторя модель: 100+92+92+(70+9+100)*1,112=483 (483<512)
Вывод: удовлетворяет условию работоспособности сети по второй модели.





# Выводы
В ходе выполнения лабораторной работы мы изучили принципы технологий
Ethernet и Fast Ethernet и практически освоили методики оценки
работоспособности сети, построенной на базе технологии Fast Ethernet.


# Список литературы{.unnumbered}

::: {#refs}
:::
