Backup zabbix mysql database

```
shell# chmod 700 /usr/sbin/zabbix_mysqldump.sh
shell# crontab -e 
0 3 * * *  /usr/sbin/zabbix_mysqldump.sh mysqldump
```
