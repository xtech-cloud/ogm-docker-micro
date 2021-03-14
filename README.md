# 开始使用

- web
```
docker run --restart=always --name=micro-web -d xtechcloud/ogm-micro:v2.9.3.a web
```

浏览127.0.0.1:8082

- api
```
docker run --restart=always --name=micro-api -d xtechcloud/ogm-micro:v2.9.3.a api
```
默认使用8080端口

设置namespace
```
docker run --restart=always --name=micro-api -d xtechcloud/omo-micro:v2.9.3.a api --namespace=my.namespace
```

设置端口
```
docker run --restart=always --name=micro-api -d xtechcloud/omo-micro:v2.9.3.a api --address=0.0.0.0:8088
```

