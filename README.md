# Импорт данных из Yandex Managed Service for MySQL в Yandex Data Processing с помощью Sqoop

Утилита [Sqoop](https://yandex.cloud/ru/docs/data-proc/operations/sqoop-usage) позволяет импортировать данные из [Managed Service for MySQL](https://yandex.cloud/ru/docs/managed-mysql) в кластер [Yandex Data Processing](https://yandex.cloud/ru/docs/data-proc). В зависимости от конфигурации кластера Yandex Data Processing вы можете выполнить импорт в одно из следующих хранилищ:

* бакет [Yandex Object Storage](https://yandex.cloud/ru/docs/storage);
* директорию HDFS;
* Apache Hive;
* Apache HBase.

Подготовка инфраструктуры для виртуальной машины, Object Storage, Yandex Data Processing и Managed Service for MySQL через Terraform описана в [практическом руководстве](https://yandex.cloud/ru/docs/tutorials/dataplatform/sqoop-mmy), необходимый для настройки конфигурационный файл [clusters-mysql-data-proc-and-vm.tf](clusters-mysql-data-proc-and-vm.tf) расположен в этом репозитории.
