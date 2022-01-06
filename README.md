# docker部署goweb应用模板
## Dockerfile使用
### 构建镜像
```
docker build . -t goweb_app
```
### 运行镜像
```
docker run -p 8888:8888 -d goweb_app
```
### 访问
```
http://127.0.0.1:8888
```

## Docker-compose使用
## 构建+运行镜像
```
docker-compose up -d
```
### 访问
```
http://127.0.0.1:8888
```