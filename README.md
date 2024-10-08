## Описание проекта

Данный проект представляет собой анализ набора данных о продажах на основе заданий, предоставленных в тестовом задании. В рамках проекта выполняются три задания, каждое из которых включает в себя анализ данных, визуализацию и выводы.

### Содержимое проекта

1. **Файлы проекта**:
   - `test.py` — файл с кодом, в котором реализованы решения для всех заданий.
   - `train.csv` — таблица с данными о продажах, которые будут анализироваться.

2. **Задания**:
   - **Задание 1**: Анализ подгрупп товаров на основе частоты покупок.
     - a) Определить подгруппы товаров, наиболее часто покупаемые за всё время продаж (минимум 4 группы);
     - b) Определить подгруппы товаров, наиболее часто покупаемые за последние два года (минимум 4 группы);
     - c) Определить подгруппы товаров, наиболее часто покупаемые за последний год (минимум 4 группы);
   - **Задание 2**: Построить boxplot (ящик с усами) на основе данных о продажах, избавившись от аномалий.
   - **Задание 3**: Разбить все покупки на группы по величине продаж и определить основные тенденции и паттерны, а также выделить наиболее прибыльную группу.

## Анализ данных

### Задание 1

Для выполнения задания 1 были использованы следующие методы:
- Группировка данных по подкатегориям товаров (`Sub-Category`) и подсчет количества продаж.
- Фильтрация данных по временным рамкам: все время, последние два года, последний год.

### Задание 2

Для задания 2 был построен boxplot на основе данных о продажах (`Sales`). Применено правило трех сигм для определения аномалий.

### Задание 3

В третьем задании данные о продажах были разделены на несколько групп (например, маленькие, средние и высокие продажи) на основе значений `Sales`. Затем данные были сгруппированы по регионам и группам продаж. По результатам анализа определены основные тенденции и выделена прибыльная группа.