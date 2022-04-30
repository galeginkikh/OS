---
## Front matter
title: "Индивидуальный проект. Этап 1"
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

Размещение на Github pages заготовки для персонального сайта.

# Выполнение лабораторной работы

**1.** Скачала Hugo

**2.** Создала папку bin и копировала туда файл hugo(рис. [-@fig:001])

![Файл hugo](image/1.png){ #fig:001 width=70% }

**3.** Использовала данный репозиторий как шаблон и назвала blog(рис. [-@fig:002]) Клонировала(рис. [-@fig:003])

![Шаблон](image/2.png){ #fig:002 width=70% }

![Клонирование](image/3.png){ #fig:003 width=70% }

**4.** Использовала команду hugo server и перешла по ссылке(рис. [-@fig:004])

![Ссылка](image/4.png){ #fig:004 width=70% }

**5.** Удалила файл demo.md, чтобы убрать зелёный фон с сайта(рис. [-@fig:005])

![Файл demo.md](image/5.png){ #fig:005 width=70% }

**6.** Создала новый репозиторий с определённым именем и клонировала его(рис. [-@fig:006])

![Новый репозиторий](image/6.png){ #fig:006 width=70% }

**7.** Создала ветку main, создала файл и активировала репозиторий(рис. [-@fig:007])

![Ветка main](image/7.png){ #fig:007 width=70% }

**8.** Подключила новый репозиторий к папке public(рис. [-@fig:008])

![Папка public](image/8.png){ #fig:008 width=70% }

**9.** ~/bin/hugo(рис. [-@fig:009])

![Команда](image/9.png){ #fig:009 width=70% }

**10.** Скопировала ссылку на сайт(рис. [-@fig:010])

![Ссылка на сайт](image/10.png){ #fig:010 width=70% } 

# Вывод

Создала сайт и разместила его на githab.

