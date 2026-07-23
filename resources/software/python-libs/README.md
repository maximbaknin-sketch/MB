# Python-библиотеки и программные средства

Инструментальная база практических заданий. Формат карточки: [resource-card-template.md](../../resource-card-template.md).

## Учебный код в репозитории

| Файл | Назначение |
|---|---|
| [lr3_record_matching_template.py](lr3_record_matching_template.py) | шаблон канонизации ФИО и сопоставления записей для ЛР-3; работает на `resources/datasets/crm_*.csv` |

Запуск:

```bash
python resources/software/python-libs/lr3_record_matching_template.py
```

## Рекомендуемый стек

| Средство | Назначение | Связь с КИМ |
|---|---|---|
| Python, Jupyter / VS Code | прототипы, ЛР-3 | ЛР-1—ЛР-4 |
| PostgreSQL | реляционные витрины | модули 3, 7–9, ЛР-1, ЛР-3 |
| Apache Spark / Airflow / dbt (по выбору) | обработка и оркестрация | модули 7, 9, ЛР-2 |
| Milvus / Qdrant / Weaviate | векторный поиск | модуль 6, ЛР-1 |
| Docker | локальный запуск сервисов | ЛР-1, ЛР-4 |
| draw.io / C4 / Camunda Modeler | архитектура и BPMN | ЛР-1, ЛР-3, ЛР-4 |
| Облачные PaaS (учебный грант) | Data Lake | модуль 10, ЛР-4 |
