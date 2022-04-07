
![1649331119410.png](./images/1649331119410.png)


![1649331097905.png](./images/1649331097905.png)

## 环境编译


在路径`YoyoMooc.StuManagement`

```
docker build . -t yoyomooc.azurecr.io/blazorexampleapp -f .\YoyoMooc.StuManagement.Web\Dockerfile
```

## 编译命令

```bash
dotnet publish --framework netcoreapp3.1 --configuration Release --output dist

dotnet run 

```

```docker
docker build . -t yoyomooc.azurecr.io/blazorexampleapp -f Dockerfile

docker push yoyomooc.azurecr.io/exampleapp

```

```bash

docker run -p 3001:80 --name blazorexampleApp3001 yoyomooc.azurecr.io/blazorexampleapp


docker run -p 80:80 --name exampleApp yoyomooc.azurecr.io/exampleapp
```
