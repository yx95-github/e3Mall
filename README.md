# e3Mall
## 项目背景
    宜立方网上商城是一个综合性的B2C平台，类似京东商城、天猫商城。会员可以在商城浏览商品、下订单，以及参加各种活动。
    管理员、运营可以在平台后台管理系统中管理商品、订单、会员等。
    客服可以在后台管理系统中处理用户的询问以及投诉。
## 系统架构
    该项目是面向服务的架构(SOA:Service Oriented Architecture),也就是把工程拆分成服务层、表现层两个工程。
    服务层中包含业务逻辑，只需要对外提供服务即可。
    表现层只需要处理和页面的交互，业务逻辑都是调用服务层的服务来实现。
