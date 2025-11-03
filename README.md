# 前言

此项目为基于HTML5的民谣网站设计与实现，是使用Java语言及Spring Boot框架开发而成的计算机毕业设计。它涵盖了前端展示与后端管理的完整实现过程，并采用MySQL数据库进行数据存储。以下将详细介绍项目的相关内容。

# 内容介绍

本项目致力于为民谣音乐爱好者提供一个展示和交流的平台。网站主要包括歌手介绍、专辑展示、音乐播放、用户评论等模块。前端界面利用HTML5技术实现响应式设计，以适应各种设备访问。后端采用Java语言结合Spring Boot框架，保证了系统的高效稳定运行。

# 技术介绍

## 语言：Java

## 使用框架：Spring Boot

## 前端技术：JS、Vue、CSS3

## 开发工具：IDEA/Eclipse

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpstudy/Navicat

## JDK版本：jdk1.8

## Maven：apache-maven 3.8.1-bin

## 前端环境：Node.Js 12\14\16

# 核心代码

以下为项目中一个简单的Java接口示例：

```java
@RestController
@RequestMapping("/api/singer")
public class SingerController {

    @Autowired
    private SingerService singerService;

    @GetMapping("/getSingerById/{id}")
    public Response getSingerById(@PathVariable("id") int id) {
        Singer singer = singerService.getSingerById(id);
        if (singer != null) {
            return new Response().success().setData(singer);
        } else {
            return new Response().error("查询不到该歌手信息");
        }
    }
}
```

# 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/304663/32/26750/126641/689dfd25F9955b50a/ed4cbb2e6b962482.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/295994/6/8009/57255/689dfd02F3a41a34c/3d66484e148d2b07.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326965/7/4598/53736/689dfd02F9d86e566/d96e5cbb3f3cdc42.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/303459/31/26203/53506/689dfd03F8b5c00b0/39e3c5588de7f1c8.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/300865/29/26055/35896/689dfd03F56c4498a/b71fd5d41c3cc88c.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/318238/18/24680/49797/689dfd04Fed243b91/beb7e9ef93793d7c.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/308406/9/26404/43966/689dfd04F20866067/211a3b83c98672fa.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/322452/16/8727/37539/689dfd05F9e37e25f/1cfeb39927097c5c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/311651/40/26211/30488/689dfd05Fb5eda051/f86cfd4803e19275.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/312641/14/26094/62885/689dfd06F564b56f4/bcca2f997bc3830a.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
