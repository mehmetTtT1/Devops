### docker  login
```
docker login  --username mehmetarslan22 --password Root22..
```

### nginx
```
docker run -it --name my-nginx -p 9991:80  -d nginx
```


### postrgres
```
docker run --name my-postgres -p 9999:5432 -e POSTGRES_PASSWORD=123 -d postgres
```


### postrgres
```
docker run --name my-mysql -p 9990:3036 -e MYSQL_ROOT_PASSSWORD=123 -d mysql
```