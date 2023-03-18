---
## Front matter
title: "Архитектура компьютеров и операционные системы. Раздел | Операционные системы"
subtitle: "Индивидуальный проект | Этап 2"
author: "Мугари Абдеррахим | НКАбд-03-22"

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

- Целью второго раздела индивидуального проекта является добавление данных о себе на сайт.

# Задание

* Разместить фотографию владельца сайта.
* Разместить краткое описание владельца сайта (Biography).
* Добавить информацию об интересах (Interests).
* Добавить информацию от образовании (Education).
* Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору:
* Управление версиями Git.

# Выполнение работы :

1. Размещение фотографии владельца сайта:

- На этом шаге я опубликовал свою фотографию на сайте, и это было сделано путем перемещения моей фотографии в файл */portfolio/content/authors/admin* (рис. @fig:001)

![Рисунок 1](image/1.png){#fig:001 width=70%}

2. После этого я опубликовал краткое описание о владельце сайта (рис. @fig:002)

![Рисунок 2](image/2.png){#fig:002 width=90%}

- И вот предварительный просмотр двух модификаций, которые я сделал на сайте (рис. @fig:003)

![Рисунок 3](image/1.1.png){#fig:003 width=70%}

3. На этом шаге я добавил информацию об интересах владельца (рис. @fig:004)

![Рисунок 4](image/3.png){#fig:004 width=70%}

4. После этого я добавил информацию об образовании владельца сайта (рис. @fig:005)

![Рисунок 5](image/4.png){#fig:005 width=70%}

5. Я создал пост о том, что я сделал на прошлой неделе (рис. @fig:006)

![Рисунок 6](image/5.png){#fig:006 width=100%}

6. затем я опубликовал пост о **Github** (рис. @fig:007)

![Рисунок 7](image/6.png){#fig:007 width=100%}

7. наконец, я сгенерировал сайт, используя **Hugo** (рис. @fig:008)

![Рисунок 8](image/7.png){#fig:008 width=70%}



# Выводы второго этапа индивидуального проэкта:

- В этом втором разделе индивидуального проекта мы узнали, как вносить изменения на сайт, как изменять личную информацию и как размещать статьи
