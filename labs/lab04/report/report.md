---
## Front matter
title: "Лабораторная работа №4"
subtitle: "Операционные системы"
author: "Кокшаров Никите Сергеевич"

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
lot: false # List of tables
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

Здесь приводится формулировка цели лабораторной работы. Формулировки
цели для каждой лабораторной работы приведены в методических
указаниях.

Цель данной лабораторной работы --- получить навыки правильной работы с репозиториями git.

# Задание

1. Выполнить работу для тестового репозитория
2. Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.

# Выполнение лабораторной работы

## Установка git-flow

Устанавливаю git-flow (рис. [-@fig:001]).

![Установка git-flow](image/1.png){#fig:001 width=70%}

Устанавливаю Node.js (рис. [-@fig:002]).

![Установка Node.js](image/2.png){#fig:002 width=70%}

Устанавливаю pnpm (рис. [-@fig:003]).

![Установка pnpm](image/3.png){#fig:003 width=70%}

Настраиваю Node.js согласно инструкции (рис. [-@fig:004]).

![Настройка Node.js](image/4.png){#fig:004 width=70%}

Создаю репозиторий git-extended на GitHub (рис. [-@fig:005]).

![Создание git-extended](image/5.png){#fig:005 width=70%}

Делаю первый коммит и выкладываю файл на GitHub (рис. [-@fig:006]).

![Выгрузка файла на GitHub](image/6.png){#fig:006 width=70%}

Добавляю в файл package.json команду для формирования коммитов (рис. [-@fig:007]).

![Изменение package.json](image/7.png){#fig:007 width=70%}

Добавляю новые файлы, выполняю коммит и отправляю файл на GitHub (рис. [-@fig:008]).

![Выгрузка файла на GitHub(1)](image/8.png){#fig:008 width=70%}

Инициализирую git-flow (рис. [-@fig:009]).

![Инициализация git-flow](image/9.png){#fig:009 width=70%}

После ряда манипуляций создаю релиз на github (рис. [-@fig:010]).

![Релиз на github](image/10.png){#fig:010 width=70%}

Создаю ветку для новой функциональности (рис. [-@fig:011]).

![Создание новой ветки](image/11.png){#fig:011 width=70%}

Создаю релиз с версией 1.2.3 (рис. [-@fig:012]).

![Создание релиза 1.2.3](image/12.png){#fig:012 width=70%}

Создаю журнал изменений и добавляю его в индекс (рис. [-@fig:013]).

![Добавление журнала изменений в индекс](image/13.png){#fig:013 width=70%}

Заливаю релизную ветку в основную и отправляю данные на GitHub (рис. [-@fig:014]).

![Загрузка релизной ветки в основную](image/14.png){#fig:014 width=70%}

# Выводы

По результатам проделанной работы я получил навыки правильного обращения с репозиториями git.
