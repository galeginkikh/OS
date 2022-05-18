---
## Front matter
title: "Индивидуальный проект. Этап 4"
author: "Легиньких Галина Андреевна НФИбд-02-21"

## Generic otions
lang: ru-RU
toc-title: "Содержание"


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

- Добавить к сайту ссылки на сайты. 

- Написать пост по прошедшей неделе.

- Написать пост на тему по выбору.

# Выполнение лабораторной работы

**1.** По словам преподавателей регестрироваться на предложенных сайтах не нужно. Поэтому я добавила ссылки на свои социальные сети.

Список добавленных данных:

- ссылка vk;

- ссылка instagram;

- ссылка youtube;

- ссылка githab.

**2.**  Для того чтобы добавить ссылки, зашла в файл `content/authors/admin/_index.md` и изменила там необходимые данные. (рис. [-@fig:001])

![Ссылки](image/1.png){ #fig:001 width=70% }

**5.** Сделала пост по прошедшей неделе. 09.05.2022 - 15.05.2022 (рис. [-@fig:002])

![My week](image/2.png){ #fig:002 width=70% }

**6.** Сделала пост на тему "Язык разметки Markdown" (рис. [-@fig:003])

![Отчет в Markdown](image/3.png){ #fig:003 width=70% }

**7.** Обновила данные моего сайта на github pages, чтобы все что я сделала было не только на localhost.

# Вывод 

Я изенила данные на сайте обо мне. Выложила пост по прошедшей неделе. Выложила пост на тему "Оформление отчета в  Markdown".


