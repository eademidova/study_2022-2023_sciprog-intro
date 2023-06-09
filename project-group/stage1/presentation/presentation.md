---
## Front matter
lang: ru-RU
title: Этап 1
subtitle: Научная проблема проекта "Хищник-жертва"
author:
  - Беличева Д. М.,
  - Демидова Е. А.,
  - Самигуллин Э. А.,
  - Смирнов-Мальцев Е. Д.
institute:
  - Российский университет дружбы народов, Москва, Россия

date: 04 мая 2023

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

## Состав исследовательской команды

Студенты группы НКНбд-01-21

- Беличева Дарья Михайловна
- Демидова Екатерина Алексеевна
- Самигуллин Эмиль Артурович
- Смирнов-Мальцев Егор Дмитриевич

# Вводная часть

## Актуальность

Математическая модель Лотки – Вольтерры применяется в разных сферах:

- экология
- биология
- медицина
- социальные исследования
- история 
- радиофизика.

## Объект и предмет исследования

- Математическая модель Лотки – Вольтерры

- Стационарные состояния системы, которая описывается моделью "Хищник-жертва".

- Графики зависимости изменения численности хищников от изменения численности жертв(фазовый портрет) и графики изменения численности хищников и жертв в зависимости от времени.

## Цели и задачи

**Цель работы**

Исследование модели Лотки-Вольтерра.

**Задачи**

- Описание модели "Хищник-жертва" и её аналитическое исследование.

- Построить график зависимости изменения численности хищников от изменения
численности жертв(фазовый портрет) и графики изменения численности хищников и жертв в зависимости от времени.

- Найти стационарное состояние системы, которая описывается моделью "Хищник-жертва".

# Описание задачи

## Теоретическое описание задачи

$$\begin{cases}
  &\dfrac{dx}{dt} = ax(t)-bx(t)y(t)\\
  &\dfrac{dy}{dt} = -cy(t)+dx(t)y(t)
\end{cases}$$

$x$ – число жертв, $y$ - число хищников
$a$, $d$ - коэффициенты прироста популяции, $b$, $c$ - коэффициенты смертностик.

## Аналитическое исследование модели

**Поиск стационарного состояния системы**

$$\begin{cases}
  &\dfrac{dx}{dt} = ax(t)-bx(t)y(t)\\
  &\dfrac{dy}{dt} = -cy(t)+dx(t)y(t)
\end{cases}$$

Стационарное состояние системы будет в точке $x_0 = c/d$, $y_0 = a/b$.

## Постановка задачи

$$\begin{cases}
  &\dfrac{dx}{dt} = ax(t)-bx(t)y(t)\\
  &\dfrac{dy}{dt} = -cy(t)+dx(t)y(t)
\end{cases}$$

$x$ – число жертв, $y$ - число хищников
$a$, $d$ - коэффициенты прироста популяции, $b$, $c$ - коэффициенты смертности.

1. Построить график зависимости $x$ от $y$ и графики функций $x(t)$, $y(t)$.
2. Найти стационарное состояние системы

# Заключение

## Выводы

Во время выполнения первого этапа группового проекта мы сделали теоретическое описание модели "Хищник-жертва", аналитически исследовали её и поставили задачу нашей работы.

## Список литературы

1. Вольтерра В. Математическая теория борьбы за существование. Наука, 1976. 354 с.
