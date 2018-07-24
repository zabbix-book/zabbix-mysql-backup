Backup zabbix mysql database

```
shell# chmod 700 ${PATH}/zabbix_mysqldump.sh
shell# crontab -e 
0 3 * * * ${PATH}/zabbix_mysqldump.sh
```