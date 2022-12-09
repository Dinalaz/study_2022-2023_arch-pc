---
## Front matter
title: "Отчёт по лабораторной работе №5"
subtitle: "Архитектура вычислительных систем"
author: "Лазева Диана Анатольевна"

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

риобретение практических навыков работы в Midnight Commander. Освоение
инструкций языка ассемблера mov и int.

# Задание

1. Создайте копию файла lab6-1.asm. Внесите изменения в программу (без
использования внешнего файла in_out.asm), так чтобы она работала по
следующему алгоритму:
• вывести приглашение типа “Введите строку:”;
• ввести строку с клавиатуры;
• вывести введённую строку на экран

2. Получите исполняемый файл и проверьте его работу. На приглашение
ввести строку введите свою фамилию.

3. оздайте копию файла lab6-2.asm. Исправьте текст программы с исполь-
зование подпрограмм из внешнего файла in_out.asm, так чтобы она ра-
ботала по следующему алгоритму:
• вывести приглашение типа “Введите строку:”;
• ввести строку с клавиатуры;
• вывести введённую строку на экран.

4. Создайте исполняемый файл и проверьте его работу.

# Теоретическое введение

# Выполнение лабораторной работы

1. Я открыла mc, в каталог ~/work/arch-pc созданный при выполнении лабораторной работы No4, создала lab05

![создание lab05](image/1.png){ #fig:001 width=90% }

2. Пользуясь строкой ввода и командой touch создала файл lab5-1.asm

![создание lab5-1.asm](image/2.png){ #fig:002 width=90% }

3. Я открыла файл lab5-1.asm для редактирования во встроенном редакторе и проверила его

![Открытие lab5-1.asm](image/3.png){ #fig:003 width=90% }

4. Ввела текст программы из листинга 6.1, сохранила изменения и закрыла файл.

![Ввод текста](image/4.png){ #fig:004 width=90% }

5. Я Оттранслировала текст программы lab5-1.asm в объектный файл. Выполнила компоновку объектного файла и запустила получившийся исполняемый файл

![отранслирование текста](image/6.png){ #fig:005 width=90% }

6. Скачала и подключила in_out.asm

![Скачивание](image/7.png){ #fig:006 width=90% }

7. Создала копию файла lab6-1.asm с именем lab6-2.asm

![Создание копии](image/8.png){ #fig:007 width=90% }

8. Исправил текст программы в файле lab6-2.asm с использованием подпрограмм из внешнего файла in_out.asm

![Исправления текста программы](image/9.png){ #fig:008 width=90% }

9. В lab6-2.asm заменила подпрограмму sprintLF на sprint, создала исполняемый фаил и выявил разницу - она заключается в выводе текста (отступ для ввода либо пробелом, либо новой строчкой)

10. Я создала копию файла lab6-1.asm и внёс изменения в программу

![Запуск файла lab04.asm](image/s1.png){ #fig:009 width=90% }

11. Я получила исполняемый фаил и проверила его работу

![Проверка](image/s2.png){ #fig:010 width=90% }

12. Создала копию файла lab6-2.asm. Исправила текст программы с использование подпрограмм из внешнего файла in_out.asm и проверила его работу

![РЕЗУЛЬТАТ](image/s3.png){ #fig:011 width=90% }

# Выводы

Мы приобрели практические навыкови работы в Midnight Commander. И освоили иструкции языка ассемблера mov и int.

# Список литературы{.unnumbered}

::: {#refs}
:::
