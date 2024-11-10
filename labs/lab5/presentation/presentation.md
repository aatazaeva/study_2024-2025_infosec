---
## Front matter
lang: ru-RU
title: Лабораторная работа №5
subtitle: Дискреционное разграничение прав в Linux. Исследование влияния дополнительных атрибутов
author:
  - Тазаева А.А.
institute:
  - Российский университет дружбы народов, Москва, Россия

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
---

# Цели и задачи работы


Изучение механизмов изменения идентификаторов, применения SetUID- и Sticky-битов. Получение практических навыков работы в консоли с дополнительными атрибутами. Рассмотрение работы механизма смены идентификатора процессов пользователей, а также влияние бита Sticky на запись и удаление файлов.

## Результаты

![Создание и запуск simpleid.c](image/2.png){ #fig:001 width=70% height=70% }

## Результаты

![Создание и запуск simpleid.c](image/4.png){ #fig:002 width=70% height=70% }
## Результаты

![Создание и запуск simpleid2.c](image/7.png){ #fig:002 width=70% height=70% }

## Результаты

![Смена владельца и изменение прав на файл simpleid2.c](image/8.png){ #fig:003 width=70% height=70% }

## Результаты

![Запуск simpleid2 после смены владельца и прав](image/11.png){ #fig:004 width=70% height=70% }

## Результаты

![Смена прав относительно SetGID-бита](image/12_1.png){ #fig:004 width=70% height=70% }

## Результаты

![Повторение команд](image/12_2.png){ #fig:005 width=70% height=70% }

## Результаты

![Выполнение команд для readfile](image/15_19.png){ #fig:006 width=70% height=70% }

## Результаты

![Выполнение команд](image/17.png){ #fig:007 width=70% height=70% }

## Результаты

![Выполнение команд](image/18.png){ #fig:008 width=70% height=70% }

# Выводы по проделанной работе

Я изучила механизмы изменения идентификаторов, применения SetUID- и Sticky-битов, получила практические навыки работы в консоли с дополнительными атрибутами. 
