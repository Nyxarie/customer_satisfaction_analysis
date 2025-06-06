# Анализ удовлетворенности клиентов
## Описание проекта
В данном проекте мы оценим удовлетворенность клиентов по различным характеристикам, включая уровень образования, возраст, пол и доход. Проанализируем влияние этих факторов на общий уровень удовлетворенности, а также исследуем сегменты клиентов в зависимости от их удовлетворенности.

## Цель проекта
Цель - анализ уровня удовлетворенности клиентов на основе данных опроса.

## Источник данных
Для работы с данным проектом используется база данных ACSI.db, содержащая преобразованный публичный набор данных The American Customer Satisfaction Index (ACSI), доступный по ссылке: [ACSI Dataset](https://data.mendeley.com/datasets/64xkbj2ry5/1). Hult, Tomas; Morgeson, Forrest (2023), “The American Customer Satisfaction Index (ACSI): A Sample Dataset and Description”, Mendeley Data, V1, doi: 10.17632/64xkbj2ry5.1

## Инструменты
- Python — основной язык программирования;
- pandas — для обработки и анализа данных;
- sqlite3 — для работы с базой данных SQLite и выполнения SQL-запросов;
- Jupyter Notebook — для выполнения анализа и документирования шагов;
- Power BI — для создания интерактивных дашбордов и анализа данных.

## Шаги
- Извлечение данных;
- Создание дашборда;
- Презентация с выводами.

## Структура проекта

```
customer_satisfaction_analysis/
	└── data/
		├── ACSI.db # База данных
		└── acsi_data.csv/ # Извлеченная таблица (создается после запуска первой тетрадки)
	├── notebooks/
		└── customer_satisfaction_analysis.ipynb # Извлекаем данные с помощью sql-запроса
	├── vizualization/
		├── dash.pbix # Визуализация в Power BI
		└── presentation.pdf/ # Презентация
	└── README.md
```

**Примечание**: Папка data/ изначально содержит только один файл - базу данных. После запуска customer_satisfaction_analysis.ipynb в эту папку также сохранится извлеченная таблица.

## Результаты
В результате проделанной работы был создан интерактивный [дашборд в Power BI](https://github.com/Nyxarie/customer_satisfaction_analysis/blob/main/vizualization/dash.pbix), позволяющий анализировать распределение клиентов по различным категориям и рассчитывать NPS. Также была подготовлена [презентация](https://github.com/Nyxarie/customer_satisfaction_analysis/blob/main/vizualization/presentation.pdf), содержащая основные выводы по анализу данных.

## Вывод
Все ключевые инсайты и выводы представлены в файле [presentation.pdf](https://github.com/Nyxarie/customer_satisfaction_analysis/blob/main/vizualization/presentation.pdf).
