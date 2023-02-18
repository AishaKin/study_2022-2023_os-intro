---
## Front matter
title: "Отчёт по лабораторной работе №1"
subtitle: "Установка ОС Linux"
author: "Киньябаева Аиша Иделевна"

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
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью данной работы является установка виртуальной машины, установка ОС Linux, настройка ОС.

# Задание

Установить виртуальную машину и ОС Linux

# Выполнение лабораторной работы

Установка виртуальной машины (установка виртуальной машины и ОС были произведены ранее, здесь приведено краткое описание основных действий) (рис. @fig:001), (рис. @fig:002]), (рис. @fig:003)

![Выбор ОС](image/18.png){#fig:001 width=70%}

![Назначение размера памяти](image/19.png){#fig:002 width=70%}

![Создание жесткого диска](image/20.png){#fig:003 width=70%}

Настройка операционной системы (рис. @fig:004 ), (рис. @fig:005 ), (рис. @fig:006 )

![Выбор носителя](image/21.png){#fig:004 width=70%}

![выбор языка](image/22.png){#fig:005 width=70%}

![Регистрация](image/23.png){#fig:006 width=70%}

Основные настройки ОС после установки. Обновление всех пакетов из суперпользователя и повышение комфорта работы с помощью установки tmux (рис. @fig:007 ), (рис. @fig:008 )

![Обновление пакетов](image/4.png){#fig:007 width=70%}

![Установка tmux](image/5.png){#fig:008 width=70%}

Установка драйверов для виртуальной машины (dkms) (рис. @fig:009 )

![Установка dkms](image/6.png){#fig:009 width=70%}

Подключение образа диска дополнений гостевой ОС (рис. @fig:010 ])

![Подключение образа диска](image/a.jpeg){#fig:010  width=70%}

Установка драйверов (рис. @fig:011 ])

![Установка драйверов](image/7.png){#fig:011  width=70%}

Пропущенные пункты хода выполнения работы считаются уже проделанными*

Далее устанавливаю программное обеспечение для создания документации (pandoc уже установлен) (рис. @fig:012 ])

![Установка TexLive](image/b.jpeg){#fig:012  width=70%}

ДОМАШНЕЕ ЗАДАНИЕ

Изучение работы команды dmesg и нахождение заданных пунктов (рис. @fig:013 ]), (рис. @fig:014 ]), (рис. @fig:015 ]), (рис. @fig:016 ]), (рис. @fig:017 ])

![Версия ядра Linux](image/c.jpeg){#fig:013  width=70%}

![Частота и модель процессора](image/d.jpeg){#fig:014  width=70%}

![Объем доступной оперативной памяти](image/e.jpeg){#fig:015  width=70%}

![Тип гипервизора и корневой ФС](image/f.jpeg){#fig:016  width=70%}

![Последовательность монтирования ФС](image/8.png){#fig:017  width=70%}

КОНТРОЛЬНЫЕ ВОПРОСЫ

1. Учетная запись пользователя содержит информацию, необходимую для опознания пользователя при подключении к системе (сведения для авторизации: логин и пароль)

2. - Для получения справки по команде используется help
   - Для перемещения по файловой системе используется cd
   - Для просмотра содержимого каталога используется ls
   - Для определения обьема каталога используется du
   - Для создания каталога - mkdir, для удаления - rm, для создания файла - touch, для удаления - rm
   - Для задания прав - chmod
   - Для просмотра истории команд - стрелки вверх/вниз

3. Файловая система - организация хранения данных в памяти. Примеры: XFS (64-битная, журналируемая), JFS (64-битная, журналируемая), Ext2

4. Подмонтированные файловые системы можно посмотреть с помощью команды dmesg | grep -i "mount", которая выводит загруженные данные по ключевому слову

5. Остановить запущенный процесс можно с помощью комбинации "ctrl+c" или же удалить процесс с помощью команды kill


# Выводы

В ходе данной лабораторной работы были установлены виртуальная машина и ОС Linux, проведены обновления и все необходимые загрузки, а также изучены команды для просмотра загрузок.
