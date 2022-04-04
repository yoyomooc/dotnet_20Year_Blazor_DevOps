
<!-- ![.NET Core](https://github.com/yoyomooc/dotnet_20Year_Blazor_DevOps/workflows/.NET%20Core/badge.svg) 
![Docker Image CI](https://github.com/yoyomooc/dotnet_20Year_Blazor_DevOps/workflows/Docker%20Image%20CI/badge.svg) -->

# YoyoMooc.BlazorDemo 

更多信息与课程欢迎访问： 

- [https://www.52abp.com/](https://www.52abp.com/)

- [https://www.yoyomooc.com/](https://www.yoyomooc.com/)
  
网站Demo采用Blazor 开发完成,整个网站没有包含一行javascript和ts文件

- Blazor 解决了 Angular、Vue、React 的SEO问题，
- Blazor解决了 前端项目编译Angular、Vue、React慢的问题，
- 传统MVC、RazorPage在Ajax上需要通过js进行Dom操作的问题，被Blazor解决了双向绑定问题解决了，


源代码地址，每日自动同步更新

## 源代码下载

主仓库地址：[http://code.52abp.com/yoyomooc/blazordemo](http://code.52abp.com/yoyomooc/blazordemo)

镜像仓库地址以下：

- github：[https://github.com/yoyomooc/dotnet_20Year_Blazor_DevOps](https://github.com/yoyomooc/dotnet_20Year_Blazor_DevOps)
- gitee:[https://gitee.com/yoyomooc/blazor-demo](https://gitee.com/yoyomooc/blazor-demo)


  ### 总结一下，优秀

 
运行在Docker容器中，没有错。都在Docker中。


数据库：SqlServer 2019


## 本地调试


```docker

docker build .  --file ./YoyoMooc.StuManagement.Api/Dockerfile dotnet_20Year_Blazorwebapi


```


```
docker-compose -f 
```


## 快速运行

已经内置了docker-compose 脚本， 启动

```bash

docker-compose pull

docker-compose up -d

docker-compose -down 


``` 
搞定。。
> ps: 前提是你会docker。。。
