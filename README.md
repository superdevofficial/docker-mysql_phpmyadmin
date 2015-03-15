docker-mysql_phpmyadmin
============================

```
docker build -t {your-tag} .
```

Run with 22, 80 and 3306 ports opened:
```
docker run -d -p 22:22 -p 3306:3306 -p 80:80 {your-tag}
```

Open http://localhost:49161/phpmyadmin in your browser with following credential:
```
username: root
password:
```

Login by SSH
```
ssh root@localhost -p 22
password: admin
```
