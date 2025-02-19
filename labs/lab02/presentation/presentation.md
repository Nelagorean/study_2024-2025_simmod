---
## Front matter
lang: ru-RU
title: Лабораторная работа 2
subtitle: Исследование протокола TCP и алгоритма управления очередью RED
author:
  - Горяйнова АА
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
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Горяйнова Алёна Андреевна
  * студентка
  * Российский университет дружбы народов

:::
::: {.column width="25%"}


:::
::::::::::::::

## Цель работы

Исследовать протокол TCP и алгоритм управления очередью RED..

## Задание

1. Выполнить пример с дисциплиной RED;
2. Изменить в модели на узле s1 тип протокола TCP с Reno на NewReno, затем на
Vegas. Сравнить и пояснить результаты;
3. Внести изменения при отображении окон с графиками (изменить цвет фона,
цвет траекторий, подписи к осям, подпись траектории в легенде).

# Выполнение лабораторной работы

## Изменение в модели на узле s1 тип протокола TCP с Reno на NewReno

![ NewReno](image/1.png){#fig:001 width=70%}

## Измените в модели на узле s1 тип протокола TCP с Reno на Vegas и изменение цвета фона, линий и текста

![ Vegas](image/2.png){#fig:002 width=70%}

## Сравнение всех трёх моделей

![ все 3 варианта](image/3.png){#fig:003 width=70%}

## Выводы

В процессе выполнения данной лабораторной работы я исследовала протокол TCP и алгоритм управления очередью RED.
