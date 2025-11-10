# 【Java计算机毕业设计分享】音乐翻唱与分享平台

## 前言

本项目是一个基于Java语言的音乐翻唱与分享平台，是计算机毕业设计的实战项目。在这个项目中，我们使用了Spring Boot框架、JavaScript、Vue、CSS3等技术，以及MySQL数据库进行数据存储。以下是本项目的详细介绍。

## 内容介绍

音乐翻唱与分享平台致力于为广大音乐爱好者提供一个展示才华、分享音乐作品的平台。用户可以在平台上发布自己的翻唱作品，与其他用户互动、评论、点赞，共同感受音乐的魅力。平台功能包括：用户注册、登录、发布作品、浏览作品、评论、点赞等。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是项目中的部分核心代码：

```java
// 用户点赞功能
@PostMapping("/like")
public ResponseEntity<Void> like(@RequestParam("workId") Integer workId, HttpSession session) {
    User user = (User) session.getAttribute("user");
    if (user == null) {
        return new ResponseEntity<>(HttpStatus.UNAUTHORIZED);
    }
    workService.like(workId, user.getId());
    return new ResponseEntity<>(HttpStatus.OK);
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/308244/33/26565/113842/689f005eF7b7a633f/a1f8ca97719feb41.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/299788/5/13090/19255/689f0036F6055f225/399d800e21ab1340.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/312108/1/27034/48748/689f0036Ffa9c8c60/2da817fad89970f8.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/308904/7/26728/20249/689f0037F2934485d/a6a8b28bc4735f96.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/312714/30/27012/30933/689f0037F3500a1da/b75a0afdd018db17.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/323590/37/5013/3368/689f0038F15d26ed2/c30e45662db36b7c.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/317781/2/24355/30407/689f0038Fcf757adf/3b9bd949131c9bd1.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/295810/16/22965/53385/689f0039Fced77259/544aef2f4f54394f.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/324873/31/5041/87604/689f003aF27e39b0a/a0e533bd8d4f5bae.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327090/33/4853/40004/689f003aFc9bab797/10cdc5a77cbba101.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
