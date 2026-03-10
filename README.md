## 前言

本项目是一款基于微信平台的原创音乐小程序，致力于为广大音乐爱好者提供一个发现和分享优秀原创音乐的场所。通过本小程序，用户可以轻松浏览、搜索和收听各类原创音乐作品，还可以与志同道合的朋友互动交流。以下是关于本项目的详细介绍。

## 内容介绍

本项目采用Java语言进行开发，结合Spring、Spring MVC、MyBatis等主流框架，以及微信小程序、Uniapp等前端技术，实现了一套功能完善、用户体验优良的原创音乐小程序。主要功能包括：音乐搜索、音乐播放、音乐收藏、评论互动等。

## 技术介绍

- **语言：** Java
- **使用框架：** Spring、Spring MVC、MyBatis、微信小程序
- **前端技术：** JS、Vue、CSS3、Uniapp
- **开发工具：** IDEA/Eclipse、Uniapp
- **数据库：** MySQL 5.7/8.0
- **数据库管理工具：** phpstudy/Navicat
- **JDK版本：** jdk1.8
- **Maven：** apache-maven 3.8.1-bin
- **前端环境：** Node.Js 12\14\16

## 核心代码

以下是本项目中的一个核心代码示例，展示了如何使用MyBatis实现音乐列表的查询：

```java
// MusicMapper.xml
<select id="selectMusicList" resultType="Music">
    SELECT id, title, artist, album, url
    FROM music
    WHERE status = 1
    ORDER BY create_time DESC
    LIMIT #{start}, #{size}
</select>

// MusicService.java
public List<Music> getMusicList(int start, int size) {
    return musicMapper.selectMusicList(start, size);
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

## 项目截图
![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/350415/29/2792/88783/68c4d3c6F87e533ad/f3490e3af32e3952.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/326868/22/19409/10227/68c4d39dF7f52327b/78b2396f5018d920.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/344407/22/2877/19887/68c4d39dF09e1cc49/d003bf6417effa05.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/328591/4/19283/11945/68c4d39eF3b8c2168/64631badb4246848.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/340571/37/10135/37006/68c4d39eFdc05edfa/bba912a363a52d7b.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/325468/30/19384/17607/68c4d39eFa568c507/5f550ce101ffc37d.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/339052/30/10299/13527/68c4d39eF94264872/4a77cc70262f8a40.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/328024/33/19527/20712/68c4d39eF4cb838ce/e2eeecc506568b02.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/325659/23/19476/28976/68c4d39eFbf2af565/2a1382987b004c52.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/345724/11/2809/24862/68c4d39eFb49f9d91/2320a968a7207011.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
