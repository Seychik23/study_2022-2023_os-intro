---
## Front matter
title: "Лабораторная работа №1"
author: "Мухин Тимофей Владимирович"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Выполнение лабораторной работы

1. Устанавливаем VirtualBox.

![](image/13.png){ #fig:001 width=70% }


2. Загружаем iso-образ дистрибутива Fedora Workstation с сайта getfedora.org

![](image/14.png){ #fig:001 width=70% }


3. Cоздаем новую виртуальную машину в virtualbox. 

![](image/2.png){ #fig:001 width=70% }


4. Указываем имя виртуальной машины (логин в дисплейном классе), тип операционной системы — Linux, Fedora.

![](image/3.png){ #fig:001 width=70% }


5. Указываем  размер основной памяти виртуальной машины — от 2048 МБ. Задаем конфигурацию жёсткого диска — загрузочный, VDI (VirtualBox Disk Image), динамический виртуальный диск.


![](image/4.png){ #fig:001 width=70% }


6. Добавляем новый привод оптических дисков и выбираем образ Fedora.

![](image/5.png){ #fig:001 width=70% }


7. Запускаем виртуальную машину и устанавливаем ОС

![](image/6.png){ #fig:001 width=70% }

![](image/7.png){ #fig:001 width=70% }

![](image/8.png){ #fig:001 width=70% }


8. Запускаем установленную ОС, извлекаем iso-образ, если  это не произошло автоматически

![](image/9.png){ #fig:001 width=70% }


9. Выполняем основные настройки. Создаем пользователя, задаем пароль

![](image/01.png){ #fig:001 width=70% }


![](image/02.png){ #fig:001 width=70% }


10. В окне терминала проанализируем последовательность загрузки системы, выполнив команду dmesg. Просматриваем вывод команды. Получите следующую информацию:  Версия ядра Linux, частота процессора, модель процессор, объём доступной оперативной памяти 


![](image/03.png){ #fig:001 width=70% }


# Выводы

Я приобрел практические навыки установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

