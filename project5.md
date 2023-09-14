CLIENT-SERVER ARCHITECTURE WITH MYSQL
***

mysql-client installed on mysql client linux server
```
sudo apt install mysql-client

```
![screenshot](./images/mysqlclient.png)
***
Using mysql server's local (private) IP address to connect from mysql client. Recall; MySQL server uses TCP port 3306 by default, so you will have to open it by creating a new entry in ‘Inbound rules’ in ‘mysql server’ Security Groups.

mysqlserver server installed on mysqlserver instance

![screenshot](./images/mysqlserver.png)

```
sudo apt install mysql-server
```


