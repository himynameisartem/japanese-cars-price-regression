# Japanese Cars Price Regression

- [RU](#ru)
- [EN](#en)

## RU

### Навигация

- [О проекте](#о-проекте)
- [Что внутри](#что-внутри)
- [Файлы](#файлы)
- [Результат](#результат)
- [Запуск](#запуск)
- [Примечания](#примечания)

### О проекте

Небольшой `notebook` разбор задачи регрессии: предсказание цен на подержанные японские автомобили по табличным данным.

### Что внутри

- базовая очистка данных и фильтрация выбросов
- feature engineering: `age`, логарифм пробега и объема двигателя
- one-hot encoding категориальных признаков
- разделение на train / validation / test
- полносвязная нейросеть на TensorFlow / Keras
- оценка качества по MAPE в исходной шкале цен

### Файлы

- `japanese-cars-price-regression.ipynb` — основной ноутбук
- `japan_cars_dataset.csv` — локальная копия датасета

### Результат

Итоговые метрики из ноутбука:

- Validation MAPE: `28.84%`
- Test MAPE: `29.02%`

Этот репозиторий оформлен как учебный / baseline notebook, а не как production-ready ML-проект.

### Запуск

Открой ноутбук и выполни ячейки по порядку.

Основные зависимости:

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `tensorflow`

### Примечания

- Репозиторий специально оставлен легковесным и без лишней проектной обвязки.
- Перед публичной публикацией проверь, можно ли распространять файл датасета.

## EN

### Navigation

- [About](#about)
- [Contents](#contents)
- [Files](#files-1)
- [Result](#result)
- [Run](#run)
- [Notes](#notes)

### About

A compact `notebook-first` regression walkthrough for predicting used Japanese car prices from tabular vehicle data.

### Contents

- basic data cleaning and outlier filtering
- feature engineering: `age`, log-scaled mileage, and engine capacity
- one-hot encoding for categorical features
- train / validation / test split
- feed-forward neural network built with TensorFlow / Keras
- evaluation with MAPE on the original price scale

### Files

- `japanese-cars-price-regression.ipynb` - main notebook
- `japan_cars_dataset.csv` - local copy of the dataset

### Result

Final metrics reported in the notebook:

- Validation MAPE: `28.84%`
- Test MAPE: `29.02%`

This repository is presented as a learning / baseline notebook rather than a production-ready ML project.

### Run

Open the notebook and run the cells in order.

Main dependencies:

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `tensorflow`

### Notes

- The repository is intentionally lightweight and avoids unnecessary project scaffolding.
- Before publishing publicly, make sure you are allowed to redistribute the dataset file.
