Задание в рамках курса "Машинное обучение для анализа научных данных" от университета ИТМО & AI Talent Hub

Бизнес-постановка задачи: разработать модель прогнозирования стоимости акций компании Apple (AAPL) на основе исторических данных

Постановка ML-задачи: прогнозирование временного ряда с использованием машинного обучения

Для решения поставленной задачи будет использоваться набор данных о стоимости акций Apple, который включает следующие столбцы:

Date: дата регистрации значения.
Open: цена открытия акций в этот день.
High: наивысшая цена акций за день.
Low: наименьшая цена акций за день.
Close: цена закрытия акций в этот день.
Adj Close: скорректированная цена закрытия акций с учетом дивидендов и сплитов.
Volume: объем торгов акциями.

Данные доступны:
https://drive.google.com/file/d/1pPDjRxO3AuQpazS9jXkvtoN2swxrsC-k/view?usp=sharing

https://www.kaggle.com/datasets/henryshan/apple-stock-price/data?select=AAPL.csv

Для установки зависимостей внутри проекта: pip install -r requirements.txt

// Может пригодиться poetry env use .myenv/bin/python3.12

или через poetry 

poetry install                  
poetry env use .venv/bin/python3.12
