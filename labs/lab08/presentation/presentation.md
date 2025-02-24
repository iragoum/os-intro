---
## Front matter
lang: ru-RU
title: Операционные системы
subtitle: Лабораторная работа №8.  Текстовой редактор vi.
author:
  - Абдеррахим Мугари.
institute:
  - Российский университет дружбы народов, Москва, Россия
  
date: 18 марта 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
 
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Абдеррахим Мугари
  * Студент
  * Российский университет дружбы народов
  * [1032215692@pfur.ru](mailto:1032215692@pfur.ru)
  * <https://github.com/iragoum>

:::
::: {.column width="30%"}

![](./image/mougari.jpg)

:::
::::::::::::::


## Цель работы:

-  Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

## Материалы и методы

- Терминал Unix.
- Файловая система.
- Текстовой редактор vi .

## Ход работы:

# Задание 1. Создание нового файла с использованием vi

## создание и перемещение в каталог с именем ~/work/os/lab 06:

- я создал и переместился каталог с именем ~/work/os/lab06

![создание и перемещение в каталог с именем ~/work/os/lab 06.](image/1.png){width=70%}

## вызов vi и создание файла hello.sh:

- затем я вызвал vi и создал файл hello.sh

![вызов vi и создание файла hello.sh](image/2.png){width=50%}

## Ввод текста в файл **hello.sh**:

- после этого я нажал клавишу **i** и ввел текст.

![Ввод текста в файл **hello.sh**](image/3.png){width=50%}

## сохранение изменений в файле и закрытие его:

- затем я нажал **Esc**, чтобы переключиться в **командный режим**, и нажал клавишу **:** для переключения в режим последней строки, наконец, я ввел **w** для сохранения и **q** для выхода из **редактора vi** и нажал **Enter** 

![сохранение изменений в файле и закрытие его](image/4.png){#fig:004 width=45%}

## сделать файл **hello.sh ** исполняемыйм файлом :

- на этом шаге мы сделали **hello.sh** исполняемым файлом

![сделать файл **hello.sh ** исполняемыйм файлом](image/5.png){width=70%}

# Задание 2. Редактирование существующего файла

## вызов vi для редактирования файла **hello.sh**:

-  мы вызвали vi, чтобы отредактировать файл **hello.sh**.

![вызов vi для редактирования файла **hello.sh**](image/6.png){width=50%}

## Размещение курсора в конце слова **АД** второй строки:

- мы поместили курсор в конец слова **HELL** второй строки 

![Размещение курсора в конце слова **АД** второй строки.](image/7.png){width=50%}

## изменение слова **HELL** на **HELLO**:

- после этого мы переключились в **режим вставки** и заменили на **HELLO**, добавив букву **o**. затем мы нажали **Esc**, чтобы вернуться в **командный режим**

![изменение слова **HELL** на **HELLO**](image/7.1.png){width=50%}

## Удаление одного слова из буфера

- затем мы поместили курсор на четвертую строку и стерли слово **LOCAL** с помощью команды **dw**

![Удаление одного слова из буфера](image/8.png){width=50%}

## ввод нового слова на месте удаленного слова

- мы переключились в **режим вставки** и набрали следующий текст: **local**, затем нажали **Esc**, чтобы вернуться в **командный режим** 

![ввод нового слова на месте удаленного слова](image/9.png){width=50%}

## переход к последней строке файла:

- на этом шаге я поместил курсор на последнюю строку файла, нажав на клавишу **G**

![переход к последней строке файла](image/10.png){width=50%}

## вставка новой строки после последней строки файла:

- затем я вставил после него строку, содержащую следующий текст: **echo $HELLO**

![вставка новой строки после последней строки файла](image/11.png){width=50%}

## переход в командный режим :

- после этого мы нажали **ESC** для перехода в **командный режим**

![переход в командный режим](image/12.png){width=50%}

## удаление последней строки:

- затем я удалил последнюю строку, используя команду **dd**

![удаление последней строки](image/10.png){#fig:014 width=50%}

## Отмена последней команды:

- Затем я отменил последнюю команду, и это было сделано нажатием на клавишу **u**

![Отмена последней команды](image/11.png){width=50%}

## сохранение файла и выход из него

- наконец, я ввел символ **:**, чтобы переключиться в режим **последней строки**, затем я ввел **w**, чтобы сохранить изменения, и **q**, чтобы выйти из файла.

![сохранение файла и выход из него](image/11.png){width=50%}

## выводы по результатам выполнения заданий:

- Выполняя эти упражнения, мы получили практические навыки использования **vi editor** каковы его полезные сочетания клавиш
  
# Выводы, согласованные с целью работы:

- Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.
