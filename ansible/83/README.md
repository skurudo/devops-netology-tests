### Что делает playbook

- Плейбук разворачивает ClickHouse, Vector, Lighthouse

- upgrade_reboot.yml - отдельный плейбук для обновления приложений OS

### Какие у него есть параметры 

- IP в файле инвентаризации - prod.yml
- Отредактировать версии ПО - group_vars\clickhouse
- Данные по Lighthouse - group_vars\lighthouse
- clickhouse_user/password задается в group_vars\all
