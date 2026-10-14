# goit-rdb-hw-03

ДЗ 3. Завантаження даних та основи SQL. DQL-команди.

- **Датасет:** UCI Adult (Census Income), https://archive.ics.uci.edu/dataset/2/adult
- **Отримання:** `ucimlrepo.fetch_ucirepo(id=2)` у notebook, повний набір (adult.data + adult.test) без семплювання.
- **Кількість рядків:** 48 842 (staging = clean).
- **Файли:** `hw_t3.ipynb` з output клітинок, `data/hw3_adult.csv`.

## Запуск

Відкрити `hw_t3.ipynb` у Google Colab і виконати Runtime → Restart and run all. PostgreSQL 16 запускається через `pgserver`, дані завантажуються через `COPY FROM STDIN`.
