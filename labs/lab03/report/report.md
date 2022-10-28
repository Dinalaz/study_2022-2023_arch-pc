---
## Front matter
title: "Отчёт по лаболаторной работе номер 3"
subtitle: "Архитектура программирования"
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

Изучить идеологию и применение средств контроля версий. Приобрести практические навыки по работе с системой git

# Задание

1. Создайте отчет по выполнению лабораторной работы в соответствующем
каталоге рабочего пространства (labs>lab03>report).
2. Скопируйте отчеты по выполнению предыдущих лабораторных работ в
соответствующие каталоги созданного рабочего пространства.
3. Загрузите файлы на github.

# Выполнение лабораторной работы

1. Я открыла терминал: [-@fig:001]

![терминал](image/1.png){ #fig:001 width=90% }

2. Я перешла в каталог курса сформированный при выполнении лабораторной работы No3 и обновила локальный репозиторий, скачав изменения из удаленного репозитория с помощью команды git pull (рис. [-@fig:002])

![терминал](image/2.png){ #fig:002 width=90% }


3.  (рис. [-@fig:003])

![терминал](image/3.png){ #fig:003 width=90% }

4. Я провела компиляцию шаблона с использованием Makefile. Для этого ввела команду make и проверила файлы (рис. [-@fig:004])

![терминал](image/4.png){ #fig:004 width=90% }

5. Я удалила полученный файил с использованием Makefile, введя команду make clean 

6. Я открыла report.md с помощью gedit [-@fig:005]

![терминал](image/5.png){ #fig:005 width=90% }

7. Я заполнила и скомпилировала отчёт

8. Я загрузила файлы на хитхаб. [-@fig:006]

![терминал](image/6.png){ #fig:006 width=90% }

# Выводы

Я изучил идеологию и применение средств контроля версий и приобрел практические навыки по работе с системой git

# Список литературы{.unnumbered}

::: {#refs}
:::
