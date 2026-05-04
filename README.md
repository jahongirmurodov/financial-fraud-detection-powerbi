# Financial Fraud Transaction Analysis (Power BI)

This project is an analytical dashboard built in Power BI focused on detecting and analyzing fraudulent financial transactions. It provides insights into transaction distribution, fraud impact, and key financial indicators across different transaction types.

## 📊 Overview

The dashboard is designed to monitor transaction activity and identify fraud patterns using aggregated metrics and visual analytics.

Key capabilities:
- Transaction analysis by type (Cash In, Cash Out, Debit, Payment, Transfer)
- Fraud detection metrics and KPIs
- Financial turnover and total amount analysis
- Transaction distribution insights

---

## 🗂 Data Model

The model is structured for efficient analytical queries:

### Main Dataset
Contains:
- Transaction Type
- Transaction Amount
- Fraud Flag (Fraud / Non-Fraud)
- Transaction ID

Additional calculated structures are used for aggregation and KPI computation.

---

## ⚙️ Data Processing (Power Query)

Data preparation steps include:
- Data cleaning and normalization
- Handling transaction types
- Creating flags for fraud detection
- Structuring data for aggregation and reporting

---

## 📐 DAX Measures

### Core Metrics
- Total Amount
- Total Turnover
- Total Transactions

### Fraud Metrics
- Total Fraud Amount
- Count Fraud Transactions
- Fraud Rate
- Fraud Amount Rate

### Analytical Metrics
- Transaction Type Share
- Distribution of transactions by type

---

## 📈 Dashboard Features

### KPI Cards
- Total Amount
- Total Transactions
- Total Turnover
- Fraud Amount
- Fraud Count
- Fraud Rate

### Transaction Type Analysis
- Bar chart comparing total amount and turnover by type

### Distribution Analysis
- Donut chart showing percentage share of each transaction type

### Filters
- Transaction type slicer (Cash In, Cash Out, Debit, Payment, Transfer)

---

## 🎯 Business Value

This dashboard helps to:
- Detect and monitor fraudulent activity
- Analyze financial exposure to fraud
- Understand transaction behavior across types
- Support risk management and decision-making

---

## 🛠 Tools & Technologies

- Power BI
- Power Query (ETL)
- DAX (Data Analysis Expressions)

---

## 📌 Notes

- Currency: USD ($)
- Designed for fraud analysis and BI portfolio demonstration

# Анализ мошеннических транзакций (Power BI)

Данный проект представляет собой аналитический дашборд в Power BI, направленный на выявление и анализ мошеннических финансовых операций.

## 📊 Обзор

Дашборд позволяет отслеживать транзакции, анализировать их структуру и выявлять аномалии, связанные с мошенничеством.

Основные возможности:
- Анализ транзакций по типам (Cash In, Cash Out, Debit, Payment, Transfer)
- Метрики мошенничества
- Анализ оборота и сумм
- Распределение транзакций

---

## 🗂 Модель данных

Основной набор данных включает:
- Тип транзакции
- Сумма
- Признак мошенничества
- ID транзакции

Используются вычисляемые меры для анализа и KPI.

---

## ⚙️ Обработка данных (Power Query)

Основные шаги:
- Очистка данных
- Нормализация типов транзакций
- Создание признаков мошенничества
- Подготовка данных для аналитики

---

## 📐 DAX-метрики

### Основные показатели
- Общая сумма
- Общий оборот
- Количество транзакций

### Метрики мошенничества
- Сумма мошеннических операций
- Количество мошеннических транзакций
- Уровень мошенничества
- Доля суммы мошенничества

### Аналитика
- Доля типов транзакций
- Распределение транзакций

---

## 📈 Визуализации

### KPI
- Общая сумма
- Количество транзакций
- Оборот
- Fraud показатели

### Анализ типов
- Столбчатая диаграмма по типам транзакций

### Распределение
- Кольцевая диаграмма долей

### Фильтры
- Срез по типам транзакций

---

## 🎯 Бизнес-ценность

Позволяет:
- Выявлять мошеннические операции
- Оценивать риски
- Анализировать поведение транзакций
- Поддерживать принятие решений в risk management

---

## 🛠 Технологии

- Power BI
- Power Query
- DAX

---

## 📌 Примечание

- Валюта: USD ($)
- Проект выполнен как демонстрация аналитики мошенничества
