# EDA: доходы, страхование и поведение пользователей в e-commerce

## О проекте

Этот репозиторий объединяет несколько задач по исследовательскому анализу данных и показывает, как с помощью статистического мышления и визуализации можно изучать распределения, сравнивать группы и получать понятные выводы.

В анализ входят три датасета:

1. **Доходы в Краснодаре** — сравнение общего распределения доходов с распределением доходов IT-специалистов.
2. **Страхование** — исследование связи между курением, BMI и страховыми расходами.
3. **E-commerce** — сравнение пользовательских сегментов по сумме покупки и типу устройства.

## Используемые файлы

- Ноутбук: `eda_income_insurance_ecommerce.ipynb`
- Данные:
  - `data/krasnodar_income.csv`
  - `data/insurance.csv`
  - `data/ecommerce_user_behavior.csv`

## Структура папки

```text
eda-income-insurance-ecommerce/
├── README.md
├── README_images.md
├── eda_income_insurance_ecommerce.ipynb
├── data/
│   ├── krasnodar_income.csv
│   ├── insurance.csv
│   └── ecommerce_user_behavior.csv
└── images/
    ├── income_distribution.png
    ├── income_it_vs_all.png
    ├── insurance_smoker_charges.png
    ├── insurance_bmi_vs_charges.png
    └── ecommerce_purchase_by_device.png
```

## Что сделано

- исследованы распределения и различия между группами;
- построены гистограммы и сравнительные визуализации;
- проанализированы факторы, связанные со стоимостью страховки;
- рассмотрены пользовательские сегменты в e-commerce.

## Какие навыки показывает проект

- EDA;
- сегментация;
- анализ распределений;
- визуализация данных;
- формулирование и проверка аналитических гипотез.

## Визуализации

![Распределение доходов](images/income_distribution.png)

![Сравнение доходов IT и общей выборки](images/income_it_vs_all.png)

![Средняя стоимость страховки по признаку курения](images/insurance_smoker_charges.png)

![BMI и стоимость страховки](images/insurance_bmi_vs_charges.png)

![Сумма покупки по типу устройства](images/ecommerce_purchase_by_device.png)
