---
# Front matter
lang: ru-RU
title: "Отчет по лабораторной работе №4"
subtitle: "Группа - НФИбд-02-18"
author: "Илья Владиславович Ким"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Научиться строить фазовый портрет гармонического осциллятора и решать уравнения гармонического осциллятора 


# Задание

![Задание](image/01.PNG){ #fig:001 width=70% }


# Выполнение лабораторной работы

1. Создал отдельную папку для выполнения лабораторной работы. 

2. Вводим нужные библиотеки. (рис. -@fig:002)

![Библиотеки](image/02.PNG){ #fig:002 width=70% }

3. Создаем переменную t (рис. -@fig:003)

![Переменная t](image/03.PNG){ #fig:003 width=70% }

4. Создаем функции для расчета значения после равно и второй производной (рис. -@fig:004)

![Функции](image/04.PNG){ #fig:004 width=70% }

5. Задаем вектор начальных значений и пишем функцию для вычисления дифференциального уравнения(рис. -@fig:005)

![Вектор начальных значений и расчет дифф уравнения](image/05.PNG){ #fig:005 width=70% }

6. Команды вывода на экран. (рис. -@fig:006)

![Вывод на экран](image/06.PNG){ #fig:006 width=70% }

7. Полученная фигура №1(рис. -@fig:007)

![Фигру №1](image/07.PNG){ #fig:007 width=70% }

8. Полученная фигура №2(рис. -@fig:008)

![Фигру №2](image/08.PNG){ #fig:008 width=70% }

9. Полученная фигура №3(рис. -@fig:009)

![Фигру №2](image/09.PNG){ #fig:009 width=70% }


# Выводы

Научились строить фазовый портрет гармонического осциллятора и решать уравнения гармонического осциллятора 
