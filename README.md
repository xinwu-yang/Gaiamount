# Gaiamount

### 运行环境
1. 见ServerJRE
2. 见Nginx

### 主要软件版本
1. SpringBoot 2.1.4.RELEASE
2. SpringCloud Greenwich.SR1
3. Hibernate 5.4.2.Final

### 项目包说明
1. api存放Controller
2. event是项目包含的事件
3. task是项目包含的异步任务
4. utils是包含这个模块使用的公共函数

### API文件名称结构
1. RestApi 能直接访问的API
2. PrivateRestApi为需要登录鉴权的API
3. ViewApi 能直接访问的View
4. PrivateViewApi为需要登录才能访问的View