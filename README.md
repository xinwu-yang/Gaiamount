# Gaiamount
> Gaiamount是一个聚合专业影视制作人的作品与技术交流分享社区,通过真正意义上的高清晰,高画质以及在线4K/8K等强大功能来完美呈现原创者们拍摄制作的优秀作品.

### 运行环境
1. docker swarm
2. serverjre 11.0.3

### 主要软件版本
1. SpringBoot 2.1.4.RELEASE
2. SpringCloud Greenwich.SR1
3. Hibernate 5.4.2.Final

### web模块
1. api zuul网关
2. gateway reactor-netty网关
3. account 账号系统
4. upload 上传系统
5. works 作品系统
6. order 订单系统
7. personal 个人中心系统
8. gaia48 gaia48活动系统
9. admin 后台CMS管理系统

##### 1. 项目包说明
1. api存放Controller
2. event是项目包含的事件
3. task是项目包含的异步任务
4. utils是包含这个模块使用的公共函数

##### 2. API文件名称结构
1. RestApi 能直接访问的API
2. PrivateRestApi为需要登录鉴权的API
3. ViewApi 能直接访问的View
4. PrivateViewApi为需要登录才能访问的View

### 其他模块
1. autoconfigure 定制Gaiamount的通用配置
2. commons 公共复用组件
3. domain 应用到的实体类
4. nginx 负载均衡器
5. serverjre web模块的运行环境