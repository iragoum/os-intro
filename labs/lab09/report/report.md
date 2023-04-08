---
## Front matter
title: "Архитектура компьютеров и операционные системы | Операционные системы"
subtitle: "Лабораторная работа № 9. Текстовой редактор emacs"
author: "Мугари Абдеррахим - НКАбд-03-22"

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

- Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Выполнение лабораторной работы : 

- запуск emacs из терминала в серверном режиме (рис. @fig:001)

![запуск emacs](image/2.png){#fig:001 width=70%}

- Создание файла **lab07.sh** используя комбинацию Ctrl-x Ctrl-f (Cx Cf) и вставка кода в файл (рис. @fig:002)

![Создание файла **lab07.sh**](image/2.png){#fig:002 width=70%}

- Сохранение файла с помощью Ctrl-x Ctrl-s (C-x C-s) (рис. @fig:003)

![Сохранение файла **lab07.sh**](image/3.png){#fig:003 width=70%}

- Вырезание целой строки (с помощью -k) одной командой (рис. @fig:004)

![Вырезание целой строки](image/4.png){#fig:004 width=70%}

- Вставка этой строки в конец файла (C-y) (рис. @fig:005)

![Вставка строки в конец файла](image/5.png){#fig:005 width=70%}

- Выделение текстовой области (C-пробел) (рис. @fig:006)

![Выделение текстовой области ](image/6.png){#fig:006 width=70%}

- Копирование области в буфер обмена (M-w) и вставка этой области в конец файла (рис. @fig:007)

![Копирование области в буфер обмена и вставка этой области в конец файла](image/7.png){#fig:007 width=70%}

- область выделения и разрез (C-w) и отмена последнего действия (C-/) (рис. @fig:008)

![область выделения и разрез и отмена последнего действия](image/8.png){#fig:008 width=70%}

- Отображение списка активных буферов на экране (рис. @fig:009)

![Отображение списка активных буферов на экране](image/9.png){#fig:009 width=70%}

- Закрытие окна (C-x-0) (рис. @fig:010)

![Закрытие окна](image/11.png){#fig:010 width=70%}

- снова переключение между буферами, но без отображения их списка на экране (C-x b) (рис. @fig:011)

![переключение между буферами, без отображения их списка на экране ](image/12.png){#fig:011 width=70%}

- Разделение рамки на 4 части и отображение текста на них (рис. @fig:012)

![Разделение рамки на 4 части и отображение текста на них](image/13.png){#fig:012 width=70%}

- Переключение в режим поиска (C-s) и поиск нескольких слов, присутствующих в тексте (рис. @fig:013)

![Переключение в режим поиска и поиск нескольких слов](image/14.png){#fig:013 width=70%}

- Переключение в режим поиска и замены (M-%), ввод текста, который необходимо найти и заменить (рис. @fig:014)

![ереключение в режим поиска и замены](image/15.png){#fig:014 width=70%}

- нажав M-s, мы воспользовались другой системой поиска и замены (рис. @fig:015)

![использование другой системы поиска и замены](image/16.png){#fig:015 width=70%}




## Контрольные вопросы:





## выводы по результатам выполнения заданий:

- В этой лабораторной работе мы узнали, как использовать **emacs** и каких масштабов мы можем достичь с его помощью
  
# Выводы, согласованные с целью работы:

- Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.
