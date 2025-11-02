# 前言

欢迎来到基于SSM（Spring、SpringMVC、MyBatis）的珠宝交易系统项目。本项目致力于打造一个功能完善、易于使用的珠宝交易平台，为广大用户提供便捷的珠宝购买和销售体验。在这里，您可以轻松实现珠宝商品的浏览、搜索、购买和支付等操作。

# 内容介绍

本项目主要分为以下几个模块：

1. 用户模块：负责处理用户的注册、登录、个人信息管理等功能。
2. 商品模块：负责展示珠宝商品的详细信息，并提供搜索、分类浏览等功能。
3. 购物车模块：为用户提供添加、删除、修改购物车内商品的功能。
4. 订单模块：实现订单的创建、支付、取消等操作。
5. 后台管理模块：方便管理员进行商品、订单、用户等管理。

# 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下是项目中的一段核心代码，实现了用户登录的功能：

```java
@Service
public class UserServiceImpl implements UserService {

    @Autowired
    private UserMapper userMapper;

    @Override
    public User login(String username, String password) {
        // 查询用户信息
        User user = userMapper.findByUsername(username);
        // 校验密码
        if (user != null && user.getPassword().equals(password)) {
            return user;
        }
        return null;
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/336884/22/1887/198273/68ad4c1fFa846218e/6200d793f97a0a4c.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/338275/26/1750/47831/68ad4bfcFc1e9cbbc/378677b4a7b4bf8c.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/328669/10/11143/157358/68ad4bfdFb01cca50/9096a421172d503b.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/291825/21/23055/41523/68ad4bfeFa1412354/a7346b8dc22bf110.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/332946/18/4379/71669/68ad4bfeF5e7b9689/4f4374595c24b353.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/325893/35/11162/62293/68ad4bffF52ae3240/e725a99c30dcd64a.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/333210/14/4359/63409/68ad4bffF53d09c23/0e41ce3f7155cec4.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/339187/18/1769/52022/68ad4c00Fae3ab2c3/481ceba26b1d0b2d.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/287072/30/18542/39690/68ad4c00Fee85f446/a309be4896c8e0dd.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/325180/36/11158/46270/68ad4c01F737f04eb/6a351deb09271915.jpg)

