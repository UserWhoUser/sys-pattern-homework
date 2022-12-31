#Домашнее задание к занятию "`Zabbix`" - `Demshin Anton`


---

### Задание 1

![alt text](https://github.com/UserWhoUser/img/blob/master/zabbix_server.png)

# wget https://repo.zabbix.com/zabbix/6.2/debian/pool/main/z/zabbix-release/zabbix-release_6.2-4%2Bdebian11_all.deb
# dpkg -i zabbix-release_6.2-4+debian11_all.deb
# apt update
# apt install zabbix-server-pgsql zabbix-frontend-php php7.4-pgsql zabbix-apache-conf zabbix-sql-scripts zabbix-agent
# sudo -u postgres createuser --pwprompt zabbix
# sudo -u postgres createdb -O zabbix zabbix
# zcat /usr/share/zabbix-sql-scripts/postgresql/server.sql.gz | sudo -u zabbix psql zabbix
# systemctl restart zabbix-server zabbix-agent apache2
# systemctl enable zabbix-server zabbix-agent apache2 
---

### Задание 2

![alt text](https://github.com/UserWhoUser/img/blob/master/config_hosts.png)

![alt text](https://github.com/UserWhoUser/img/blob/master/agent_log.png)

![alt text](https://github.com/UserWhoUser/img/blob/master/monit_LT_1.png)

![alt text](https://github.com/UserWhoUser/img/blob/master/monit_LT_2.png)

---

