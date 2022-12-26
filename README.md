Сбор и анализ датасета из популярного онлайн-магазина с характеристиками ноутбуков и их влияния на цену и оценку пользователями.

Описание работы:
1. Данные собираются с сайта онлайн-магазина с помощью скрипта из файла datathone_22_dns_scraper.ipynb и складываются файл data/dns_laptop_dataset_raw.csv;
2. Русскоязычные названия колонок в csv-файле вручную переименовываются, после чего результат сохраняется в файл data/dns_laptop_dataset_raw_new_column_names.csv;
3. Csv-файл с новыми названиями колонок обрабатывается с помощью скрипта datathone_22_dns_cleaning.ipynb, после чего результат сохраняется в файл dns_laptop_dataset.csv;
4. С помощью скрипта datathone_22_dns_analysis.ipynb проводится анализ данных.