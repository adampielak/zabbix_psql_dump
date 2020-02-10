# zabbix_psql_dump
---
выгружает и удаляет данные из таблиц 'history', 'history_uint', 'history_str', 'history_text', 'history_log', 'trends_uint', 'trends'
---
для использования опишите подключение в conn (в самом скрипте) и выполнить pip3 install psycopg2
---
запуск ./dump_date гггг-мм-дд гггг-мм-дд
---
пример ./dump_date 2019-12-01 2019-12-31
---