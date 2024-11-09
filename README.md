# ansible-vector

[Скачивает](https://yum.vector.dev/stable/vector-0/x86_64/), устанавливает *rpm* пакет и создает демонстрационный конфигурационный файл для интеграции c *ClickHouse*.

<br>
<br>

<a  name="vars"></a>

## Переменные

|  Название  |  Значение по умолчанию  |  Описание  |
|  :--:  |  :--:  |  :--:  |
| *vector_version*  |  0.42.0  |  Версия пакета  |
| *vector_ch_address*  |  127.0.0.1  |  Адрес подключения к *ClickHouse*  |
| *vector_ch_port*  |  8123  |  Порт подключения к *ClickHouse*  |
| *vector_ch_db_name*  |  db_example  |  Имя БД в *ClickHouse*  |
| *vector_ch_table_name*  |  table_example  |  Имя таблицы для записи логов в *ClickHouse*  |

<br>
<br>

## Теги

Поддерживает тег *vector* для возможности запустить только эту роль в playbook.
