```bash
docker run --name nifi  -p 8443:8443  -d  -e SINGLE_USER_CREDENTIALS_USERNAME=admin -e SINGLE_USER_CREDENTIALS_PASSWORD=ctsBtRBKHRAx69EqUghvvgEvjnaLjFEB -v $PWD:/mysql/drivers/mysql-connector apache/nifi:latest
```

[MySql JDBC Connector](https://dev.mysql.com/downloads/connector/j/)

```
jdbc:mysql://nifi_mysql/future_nations
```

```
com.mysql.jdbc.Driver
```

