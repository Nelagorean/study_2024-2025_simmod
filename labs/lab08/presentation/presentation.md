---
## Front matter
lang: ru-RU
title: Лабораторная работа №8
subtitle: Модель TCP/AQM
author:
  - Горяйнова Алёна
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

# Цель работы

Реализовать модель TCP/AQM в xcos и OpenModelica.

# Задание

1. Построить модель TCP/AQM в xcos;
2. Построить графики динамики изменения размера TCP окна $W(t)$ и размера очереди $Q(t)$;
3. Построить модель TCP/AQM в OpenModelica;

# Выполнение лабораторной работы

## Реализация в xcos

Построим схему xcos, моделирующую нашу систему, с начальными значениями параметров $N = 1, R = 1, K = 5.3, C = 1, W(0) = 0.1, Q(0) = 1$.
Для этого сначала зададим переменные окружения.

![Установка контекста](image/1.png){#fig:001 width=70%}

## Затем реализуем модель TCP/AQM, разместив блоки интегрирования, суммирования, произведения, констант, а также регистрирующие устройства (рис. [-@fig:002]):

![Модель TCP/AQM в xcos](image/2.png){#fig:002 width=70%}

В результате должны были получить динамику изменения размера TCP окна W(t)  и размера очереди Q(t) , а также фазовый портрет, но скилаб вылетел и ничего не сработало

## Реализация модели в OpenModelica

![Динамика изменения размера TCP окна W (t) и размера очереди Q(t). OpenModelica](image/3.png){#fig:003 width=70%}

![Фазовый портрет (W, Q). OpenModelica](image/4.png){#fig:004 width=70%}

## Выводы

В процессе выполнения данной лабораторной работы я реализовала модель TCP/AQM в xcos и OpenModelica.
