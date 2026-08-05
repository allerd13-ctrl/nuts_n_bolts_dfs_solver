# nuts_n_bolts_dfs_solver
Программа для поиска решения головоломок по типу перемещения гаек или переливанию цветных жидкостей в колбы/бутылочки. Python DFS solver for Nuts.
Bolts color sorting puzzle solver.
Создано под предводительством ChatGPT.
Create with ChatGPT.

Для ЗАПУСКА скопировать код в Python на ПК либо в CoLab (colab.research.google.com)
Время просчета в CoLab около 50 секунд, на ПК порядка 10 минут.
telegram @artiee95

Для работы: 1. Указываем максимальную высоту шпильки или колбы (MAX_HEIGHT=)
2. После строчки START Записываем цвета одной буквой в строчку с нижней гайки к верхней. Можно добавить или убрать, не забывая про запятую.


# Nuts & Bolts DFS Solver

Python solver for the Nuts & Bolts color sorting puzzle.

## Features

- Depth First Search algorithm
- Backtracking
- State caching
- Branch pruning
- Console progress monitoring

## Algorithm

The solver explores possible moves recursively.
When a branch reaches a dead end, it returns back and tries the next branch.

## Performance

Example:

- Checked states: 359597
- Search time: 56 seconds

## Requirements

Python 3.x

## Run

```bash
python nuts_bolts_dfs.py
