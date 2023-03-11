---
## Front matter
title: "Лабораторная работа №5"
author: "Медведева Кристина Андреевна"

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
Построение графика зависимости количества жертв от количества хищников. 



# Выполнение лабораторной работы
1. Подключаем необходимые пакеты.
2. Создаем основную функцию отрисовки, в соответствии с 3 вариантом.
3. Отрисовка графика.
![Скрин 1](1.png){#fig:001 width=70%}
![Скрин 2](2.png){#fig:001 width=70%}
![Скрин 3](3.png){#fig:001 width=70%}
![Скрин 4](4.png){#fig:001 width=70%}
![Скрин 5](5.png){#fig:001 width=70%}
![Скрин 6](6.png){#fig:001 width=70%}
4. Находим стационарное состояние системы.
x0=c/d
y0=a/b
x0=-0.35/(-0.032)=10.9375
y0=-0.14/(-0.043)=3.2558

# Выводы

Проделав работу, мы построили график зависимости количества жертв от количества хищников, нашли стационарное состояние системы.

# Список литературы{.unnumbered}

::: {#refs}
:::
