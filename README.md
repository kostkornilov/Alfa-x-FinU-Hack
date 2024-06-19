# Alfa-x-FinU-Hack
Ноутбук с решением Yandex Contest соревнования, организованного Альфа-Банком совместно с Финансовым Университетом при Правительстве РФ.

Задача — построить модель CLTV, которая будет предсказывать продуктовый кластер клиента - Юридического лица на горизонте в 12 месяцев. Целевая метрика — взвешенный по значимости кластеров ROC-AUC.

Решение из этого ноутбука по итогам соревнования было оценено взвешенной ROC-AUC метрикой, равняющейся 0.902866.

Используемые алгоритмы и инструменты:

- CatBoost, алгоритм градиентного бустинга
- Seaborn, matplotlib, библиотеки для визуализации
- Numpy, pandas, инструменты для обработки данных
- Sklearn, библиотека для машинного обучения

Код решения и комментарии находятся в "notebook.ipynb". Для полного обучения моделей требуется GPU и набор данных, который нужно добавить в новую папку data. Если нет возможности ждать расчета решения, имеется возможность загрузки модели из папки models (в ноутбуке есть соответствующие ячейки для этого). Файл с решением на тестовой выборке сохраняется в текущую директорию под названием "submission_final.csv".

По итогам соревнования команда заняла третье место.
