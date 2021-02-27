---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №1
author: |
	Ilya V. Kim\inst{1}
	
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
date: 13 February, 2019 
## Formatting
mainfont: Times New Roman
romanfont: Times New Roman
sansfont: Times New Roman
monofont: Times New Roman
toc: false
slide_level: 2
theme: metropolis
header-includes:
- \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
- '\makeatletter'
- '\beamer@ignorenonframefalse'
- '\makeatother'
aspectratio: 43
section-titles: true
---



## Прагматика выполнения

Обучиться работать с системой управления версиями git и с языком разметки текстов markdown, а так же научиться написанию грамотных отчетов и созданию презентаций.

## Цель работы

Узнать и ознакомится с основными возможностями git и markdown. 


## Задание

Создать отчет в 3 форматах (pdf, docx и md) и презентацию по лабораторной работе в формате markdown.

Создать репозиторий на github с полученными результатами.


# Выполнение лабораторной работы

## Шаг 1

Создал отдельную папку для выполнения лабораторной работы. 

## Шаг 2

Скачал с туиса шаблоны для документов и распаковал их в эту папку. 

## Шаг 3

Настроил систему: установил Pandoc v.2.11.4, pandoc-crossref v.0.3.9.1, MikTex и GNU make, используя Chocolatey GUI. Pandoc-crossref установил отдельно, т.к версия из Chocolatey была несовместима.

## Шаг 4

Заменил код в файле presentation.md, в разделе "Formatting", т.к он не воспринимал символы. 

## Шаг 5

Изменил содержание отчета и презентации.

## Шаг 6

Использовал команду make для создания pdf и docx файлов. 

## Шаг 7

Создал репозиторий "lab01-KimIlya" на github.

## Шаг 8

Загрузил файлы на github.



## Выводы

Ознакомился с основными функциями и возможностями git и markdown.



## {.standout}

The end.
