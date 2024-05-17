# Шардирование таблиц Yandex Managed Service for ClickHouse®

Вы можете шардировать таблицы [Managed Service for ClickHouse®](https://yandex.cloud/ru/docs/managed-clickhouse), используя один из способов:

* Классический, когда распределенная таблица использует все шарды кластера.
* С группами шардов, когда часть шардов объединена в группу.
* Продвинутый с группами шардов, когда шарды разделены на две группы: в одной находится распределенная таблица, в другой — нижележащие таблицы.

Подготовка инфраструктуры для Managed Service for ClickHouse® через Terraform для указанных способов описана в [практическом руководстве](https://yandex.cloud/ru/docs/tutorials/dataplatform/clickhouse-sharding), необходимые для настройки конфигурационные файлы [simple-sharding.tf](simple-sharding.tf), [sharding-with-group.tf](sharding-with-group.tf) и [advanced-sharding-with-groups.tf](advanced-sharding-with-groups.tf) расположены в этом репозитории.
