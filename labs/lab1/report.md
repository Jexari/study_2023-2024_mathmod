---
## Front matter
title: "Лабораторная работа №1"
subtitle: "Работа с git"
author: "Долганов Ян Львович"

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

Научиться полному взаимодействию с git и разобрать основные его особенности.

# Выполнение лабораторной работы
# Отчет по изучению Git

## Введение
В рамках курса по информационным технологиям мне было предложено изучить систему управления версиями Git. В данном отчете я хочу поделиться своим опытом и описать шаги, которые я предпринял для освоения этой темы.

## Шаги выполнения

### Шаг 1: Ознакомление с основами Git
Для начала изучения Git я прочитал руководство на официальном сайте Git и сделал заметки по основным понятиям: репозиторий, коммит, ветка и т.д.

### Шаг 2: Установка Git
bash
# Установка Git на компьютер
git --version

### Шаг 3: Создание и клонирование репозитория
bash
# Создание нового репозитория
git init

# Добавление файлов в индекс
git add .

# Коммит изменений
git commit -m "Initial commit"

# Создание удаленного репозитория на GitHub
git remote add origin <URL>

# Клонирование репозитория
git clone <URL>

### Шаг 4: Работа с ветками
bash
# Создание новой ветки
git checkout -b newbranch

# Переключение на другую ветку
git checkout main

# Слияние веток
git merge newbranch

### Шаг 5: Загрузка изменений на GitHub
bash
# Загрузка изменений на удаленный репозиторий
git push origin main

# Отчет по изучению Git

## Введение
В рамках курса по информационным технологиям мне было предложено изучить систему управления версиями Git. В данном отчете я хочу поделиться своим опытом и описать шаги, которые я предпринял для освоения этой темы.

## Шаги выполнения

### Шаг 1: Ознакомление с основами Git
Для начала изучения Git я прочитал руководство на официальном сайте Git и сделал заметки по основным понятиям: репозиторий, коммит, ветка и т.д.

### Шаг 2: Установка Git
bash
# Установка Git на компьютер
git --version

### Шаг 3: Создание и клонирование репозитория
bash
# Создание нового репозитория
git init

# Добавление файлов в индекс
git add .

# Коммит изменений
git commit -m "Initial commit"

# Создание удаленного репозитория на GitHub
git remote add origin <URL>

# Клонирование репозитория
git clone <URL>

### Шаг 4: Работа с ветками
bash
# Создание новой ветки
git checkout -b newbranch

# Переключение на другую ветку
git checkout main

# Слияние веток
git merge newbranch

### Шаг 5: Загрузка изменений на GitHub
bash
# Загрузка изменений на удаленный репозиторий
git push origin main

## Заключение
Изучение Git было увлекательным и полезным опытом. Я освоил основные функции системы управления версиями и теперь понимаю, как ее использовать для удобной и эффективной работы над проектами. Работа с Git стала неотъемлемой частью моего процесса разработки и я надеюсь продолжать совершенствовать свои навыки в этой области.

## Заключение
Изучение Git было увлекательным и полезным опытом. Я освоил основные функции системы управления версиями и теперь понимаю, как ее использовать для удобной и эффективной работы над проектами. Работа с Git стала неотъемлемой частью моего процесса разработки и я надеюсь продолжать совершенствовать свои навыки в этой области.