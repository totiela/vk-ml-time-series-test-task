# Задание на классификацию временных рядов от VK
## Структура файлов
```
├── data/
│   ├── raw/                      # необработанные исходные данные
│   │   ├── train.parquet
│   │   └── test.parquet
│   ├── processed/                # обработанные данные с отобранными признаками
│   │   └── test
│           ├── test_116_features.parquet
│           └── test_141_features.parquet
├── models/                       # директория для хранения обученных моделей
│   ├── model_v1.pkl
│   ├── model_v2.pkl
│   ├── model_v3.pkl
│   └── model_v3.pll
├── notebooks/
│   ├── eda.ipynb                 # анализ данных и визуализация
│   └── experiments.ipynb         # эксперименты с моделями (при необходимости)
├── src/                          # исходный код проекта
│   └── top_features.json # файл со списками лучших признаков
├── submission.csv                # файл с предсказаниями для отправки
├── README.md                     # описание проекта
└── requirements.txt              # зависимости проекта
```
