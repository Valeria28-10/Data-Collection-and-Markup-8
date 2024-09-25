# ДЗ по "Сбор и разметка данных (семинары)"

## Семинар 8. Работа с данными


### Домашнее задание:

### 1. Скачайте датасет House Prices Kaggle со страницы конкурса (ссылка на Kaggle) и сохраните его в том же каталоге, что и ваш скрипт или блокнот Python.

### 2. Загрузите датасет в pandas DataFrame под названием df.

### 3. Выполните предварительную обработку данных, выполнив следующие шаги:

### - Определите и обработайте отсутствующие значения в датасете. Определите, в каких столбцах есть отсутствующие значения, и решите, как их обработать (например, заполнить средним, медианой или модой, или отбросить столбцы/строки с существенными отсутствующими значениями).

### - Проверьте и обработайте любые дублирующиеся строки в датасете.

### - Проанализируйте типы данных в каждом столбце и при необходимости преобразуйте их (например, из объектных в числовые типы).

### 4. Проведите разведочный анализ данных (EDA), ответив на следующие вопросы:

### - Каково распределение целевой переменной 'SalePrice'? Есть ли какие-либо выбросы?

### - Исследуйте взаимосвязи между целевой переменной и другими характеристиками. Есть ли сильные корреляции?

### - Исследуйте распределение и взаимосвязи других важных характеристик, таких как 'OverallQual', 'GrLivArea', 'GarageCars' и т.д.

### - Визуализируйте данные, используя соответствующие графики (например, гистограммы, диаграммы рассеяния, квадратные диаграммы), чтобы получить представление о датасете.

### 5. Выполните проектирование признаков путем реализации следующих преобразований:

### - Работайте с категориальными переменными, применяя one-hot encoding или label encoding, в зависимости от характера переменной.

### - При необходимости создайте новые характеристики, такие как общая площадь или возраст объекта недвижимости, путем объединения существующих характеристик.

### 6. Сохраните очищенный и преобразованный набор данных в новый CSV-файл под названием 'cleaned_house_prices.csv'