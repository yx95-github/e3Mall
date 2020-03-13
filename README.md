# e3Mall
## 项目背景
    宜立方网上商城是一个综合性的B2C平台，类似京东商城、天猫商城。会员可以在商城浏览商品、下订单，以及参加各种活动。
    管理员、运营可以在平台后台管理系统中管理商品、订单、会员等。
    客服可以在后台管理系统中处理用户的询问以及投诉。
## 系统架构
    该项目是面向服务的架构(SOA:Service Oriented Architecture),也就是把工程拆分成服务层、表现层两个工程。
    服务层中包含业务逻辑，只需要对外提供服务即可。
    表现层只需要处理和页面的交互，业务逻辑都是调用服务层的服务来实现。
![系统架构](https://github.com/yx95-github/e3Mall/blob/master/%E7%B3%BB%E7%BB%9F%E6%9E%B6%E6%9E%84.png)
## 开发工具及环境
    Eclipse Mars2   Maven 3.3.9   Tomcat 7
    GDK 1.7         Mysql 5.7     Nginx 1.8
    Redis 3.0.0     Windows 10    Linux
## 技术选型
    1.Spring、SpringMVC、Mybatis、MyBatis 逆向工程
    2.JSP、JSTL、jQuery、EasyUI、KindEditor（富文本编辑器）
    3.Redis（缓存服务器）、Nginx（web 服务器）
    4.Solr（搜索）
    5.Dubbo（调用系统服务）
    6.Mysql、MyCat mysql 分库分表技术
## 数据库准备和逆向工程
    1.直接使用sql脚本。
    2.使用逆向工程生成mapper和pojo。
