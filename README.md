# Задание на классификацию временных рядов от VK
## Структура файлов проекта
```
├── data/
│   ├── raw/                      # необработанные исходные данные
│   │   ├── train.parquet
│   │   └── test.parquet
│   └── processed/                # обработанные данные с отобранными признаками
│        └── test
│            ├── test_116_features.parquet
│            └── test_141_features.parquet
├── models/                       # директория для хранения обученных моделей
│   ├── cb_no_tuned_141.pkl
│   ├── cb_tuned_116.pkl
│   ├── xgb_no_tuned_141.pkl
│   └── xgb_tuned_116.pkl
├── notebooks/
│   ├── eda.ipynb                       # анализ данных и визуализация
│   ├── feature_engineering.ipynb       # отбор признаков
│   ├── validation_and_learning.ipynb   # валидация и обучение моделей          
│   └── prediction.ipynb                # получение предсказания
├── src/                          # исходный код проекта
│   └── top_features.json         # файл со списками лучших признаков
├── submission.csv                # файл с предсказаниями для отправки
├── README.md                     # описание проекта
└── requirements.txt              # зависимости проекта
```
