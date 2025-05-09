Project-python2 Оценка рисков невозврата кредита.

Описание проекта:
Цель проекта — выяснить, какие характеристики клиентов банка влияют на вероятность своевременного погашения кредита. На основе этих данных можно разработать систему кредитного скоринга — модель, оценивающую способность потенциального заёмщика погасить кредит.

В проекте использовался датасет credit_scoring_eng.csv, содержащий информацию о клиентах:
children — количество детей;
days_employed — стаж в днях;
dob_years — возраст клиента;
education — уровень образования;
family_status — семейное положение;
gender — пол;
income_type — тип занятости;
total_income — ежемесячный доход;
purpose — цель кредита;
debt — факт наличия просрочки по кредиту (целевой признак).

Этапы проекта:
Загрузка и изучение данных:
Анализ пропусков и дубликатов;
Исследование аномалий и выбросов.

Предобработка:
- Заполнение пропущенных значений
- Устранение дубликатов
- Приведение данных к единому виду

Анализ данных:
- Исследование зависимости между уровнем дохода, количеством детей, семейным положением и вероятностью невозврата кредита;
- Визуализация результатов с помощью matplotlib и seaborn.

Выводы:
- Определены факторы, повышающие риск невозврата кредита;
- Сформулированы рекомендации для банка.

Используемые библиотеки
pandas
matplotlib
seaborn
