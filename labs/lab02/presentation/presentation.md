---
## Front matter
lang: ru-RU
title: Презентация по лабораторной №2
subtitle: Установка Git
author:
  - Киньябаева А.И.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 18 февраля 2023

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

# Введение

## Цели и задачи

- Изучение системы контроля версий
- Устанвока Git

## Материалы и методы

- Репозиторий

# Выполнение лабораторной работы

## Установка виртуальной машины

Основными этапами в ходе установки виртуальной машины являются:

 - Выбор ОС и назначение имени(Ubuntu)
 - Обозначение объема выделенной памяти
 - Создание жесткого диска и указание его типа

![Рис. 1. Назначение размера памяти](image/19.png)

## Настройка ОС

Настройка ОС заключается в определении параметров по типу языка, раскладки клавиатуры, установка часового пояса и регистрации пользователя

![Рис. 2. Регистрация](image/23.png)

## Загрузка дополнительных параметров

После установки ОС требуется обновление пакетов и установка необходимого программного обеспечения, в данном случае TexLive

![Рис. 3. Установка TexLive](image/b.jpeg)

# Результаты

## Полученные сведения

Результат всех загрузок и нужная информация об определенных из них находится с помощью команды dmesg. К примеру, последовательность монтирования файловой системы

![Рис. 4. Монтирование](image/8.png)

## Итоги

В ходе работы приобретены навыки по установке виртуальной машины и операционной системы на нее. Изучен необходимый минимум команд для настройки операционной системы на дальнейшую работу.