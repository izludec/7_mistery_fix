# Quadratic Equations Solver

Модуль высчитывает корни уравнения по коэффициентам.

# Как запустить

Модуль подключается к программе с помощью импорта:

```#!powershell

from quadratic_equation import get_roots

```
И вызывается в программе с помощью функции:


```#!bash

get_roots(a, b, c)

```
Где a, b , c - числа, коэффициенты квадратного уравнения.

На выходе функция выдает два числовых значения корней.

Файл tests.py служит для Unit-теста модуля. Запускается с помощью команды:


```#!bash

$ python3 tests.py

```

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
