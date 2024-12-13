


# 项目介绍

互联网发展至今，无论是其理论还是技术都已经成熟，而且它广泛参与在社会中的方方面面。它让信息都可以通过网络传播，搭配信息管理工具可以很好地为人们提供服务。针对学生宿舍信息管理混乱，出错率高，信息安全性差，劳动强度大，费时费力等问题，采用学生宿舍管理系统可以有效管理，使信息管理能够更加科学和规范。

学生宿舍管理系统在Eclipse环境中，使用Java语言进行编码，使用Mysql创建数据表保存本系统产生的数据。系统可以提供信息显示和相应服务，其管理员管理宿管员，管理学生，修改密码，维护个人信息。宿管员管理公寓资产，缴费信息，公共场所清理信息，日常事务信息，审核学生床位安排信息。学生查看公共场所清理信息，日常事务，缴费信息，在线申请床位，查看床位安排。

总之，学生宿舍管理系统集中管理信息，有着保密性强，效率高，存储空间大，成本低等诸多优点。它可以降低信息管理成本，实现信息管理计算机化。


**关键词**： 学生宿舍管理系统；Java语言；Mysql；  Spring Boot 框架；Java；MySQL数据库;  VUE;  前后端分离，毕业设计

**技术栈:**

* 后端:  SpringBoot +Mybatis
* 数据库 : MySQL 8
* 前端:  VUE + ElementUI

**开发环境依赖：**
* MySQL 8 数据库
* JDK 18+
* Maven 3
* IDEA
* Node 16

## 一 系统介绍
![ITSource_2024121703.png](https://itguang.oss-cn-beijing.aliyuncs.com/202412131217697.png)


![ITSource_2024121418.png](https://itguang.oss-cn-beijing.aliyuncs.com/202412131215061.png)
![ITSource_2024121526.png](https://itguang.oss-cn-beijing.aliyuncs.com/202412131215319.png)
![ITSource_2024121546.png](https://itguang.oss-cn-beijing.aliyuncs.com/202412131215271.png)
![ITSource_2024121559.png](https://itguang.oss-cn-beijing.aliyuncs.com/202412131216031.png)

![ITSource_2024121626.png](https://itguang.oss-cn-beijing.aliyuncs.com/202412131216941.png)
![ITSource_2024121635.png](https://itguang.oss-cn-beijing.aliyuncs.com/202412131216635.png)
![ITSource_2024121642.png](https://itguang.oss-cn-beijing.aliyuncs.com/202412131216553.png)

* 数据库
  ![ITSource_2024121940.png](https://itguang.oss-cn-beijing.aliyuncs.com/202412131219750.png)




## 二 技术介绍
### 1.技术栈

* 后端:  SpringBoot + Mybatis
* 数据库 : MySQL 8
* 前端:  VUE + ElementUI

**开发环境依赖：**
* MySQL 8 数据库
* JDK 18+
* Maven 3
* IDEA
* Node 16

### 2.代码介绍
> ![code.png](https://itguang.oss-cn-beijing.aliyuncs.com/202410261434141.png)



### 三 Quick Start

### 1. 环境准备
* MYSQL 8
* JDK 18+
* Maven 3
* IDEA
* Node 16 （如果不需要对配置后台二次开发,不需要安装)

> 以上环境需要准备好, 在自己的本地搭建好,方可进行下面步骤
### 2. 下载源码

---
**文章末尾获取下载方式。**
---


### 3. 后端部署

> 注意需要先本地安装 Redis ，端口 6379，不需要密码

- Step1: 下载源码
- Step2: IDEA 打开项目
- Step3: 安装 Maven 依赖
- Step4: 配置检查
> 数据库配置: 找到配置文件 `src/main/resources/application.yml` 修改为你本地的数据库配置。如
```yml
spring.datasource.url=jdbc:mysql://localhost:3306/itsource34??useUnicode=true&characterEncoding=utf8&autoReconnect=true&useSSL=false&serverTimezone=UTC&createDatabaseIfNotExist=true  
spring.datasource.username=root  
spring.datasource.password=root
```

注意：**不需要手动创建数据库和初始化表结构，直接运行项目，会自动创建数据库，初始化SQL语句**
- Step4: 启动后端项目
  【截图】运行按钮
> Idea 运行后端项目,看到以下信息,表示运行成功
> ![ITSource_2024122543.png](https://itguang.oss-cn-beijing.aliyuncs.com/202412131226504.png)




### 4. 前端部署
项目默认已经构建好了前端静态文件,如果不二次开发的话,不需要单独启动前端项目.

### 注意事项

如果部署失败请参考项目说明环境，版本是否一致。


## 下载源码

---
---

关注微信公众号: **ITSource 每日分享**,回复 `0035` 获取源码

> 可付费二次开发,  定制, 一对一讲解, 有意可微信联系:  **itguangit**

---
---

**关注微信公众号 【ITSource每日分享】,免费获取一万个IT资源：项目源码，软件工具，面试面经，学习视频 应有尽有！！！!**

![关注 微信公众号 ! 获取更多学习资源呀](https://itguang.oss-cn-beijing.aliyuncs.com/订阅号.jpeg)

**更多资源推荐:**
- [ITSource 分享 第1期【问卷调查系统】springboot+vue](https://mp.weixin.qq.com/s/KE7jOCpvbLVddVnu81fg9A)
- [ITSource 分享 第2期【在线考试系统】springboot+vue](https://mp.weixin.qq.com/s/So2Nb20hotB3S0aQtqf1mQ)
- [ITSource 分享 第4期【简洁的问卷调查系统】springboot+vue](https://mp.weixin.qq.com/s/HeSGWxxU-bGoeONjyR6qsw)
- [ITSource 分享 第5期【校园信息墙系统】springboot+vue](https://mp.weixin.qq.com/s/oA0Mbz3c4q1ziQbHvr72dg)
- [ITSource 分享 第6期【网址云收藏系统】】](https://mp.weixin.qq.com/s/NddwJn9h2f5n6dY-spCFhQ)
- [ITSource 分享 第7期【小程序记账软件系统】springboot+小程序](https://mp.weixin.qq.com/s/kRigevtP_EjpOS_Bw2UdZQ)
- [ITSource 分享 第8期【班级学生管理系统】](https://mp.weixin.qq.com/s/oJ-PEahVwQkwRwE8sINyZg)
- [ITSource 分享 第9期【学知识在线考试系统】springboot+vue](https://mp.weixin.qq.com/s/euvjxBX3bVG71IF8yV_zJQ)
- [ITSource 分享 第10期【个人博客系统】](https://mp.weixin.qq.com/s/j5O3oi0Yc28v8ROomyR9_g)
- [ITSource 分享 第11期【简单的教务管理系统】](https://mp.weixin.qq.com/s/5AEgWPW1v0Y5Z77LGoMm1Q)
- [ITSource分享第12期【驾校理论课考试系统】springboot+vue](https://mp.weixin.qq.com/s/YpJXaGC5338ydeLCMBiLtg)
- [ITSource分享第13期【班级信息管理系统】](https://mp.weixin.qq.com/s/7FYxlXoKrb5r-nckcPlAWw)
- [ITSource分享第14期【电影院售票管理系统】springboot+vue](https://mp.weixin.qq.com/s/oRU1VtvB68Z1qJbuGIGrGw)
- [ITSource分享第15期【图书管理系统】](https://mp.weixin.qq.com/s/rgixOXuJyJyZlL8Ny0AE8A)
- [ITSource分享第16期【连锁门店管理系统】springboot+vue](https://mp.weixin.qq.com/s/5aOJ9EHIqcVqtYWdKn3ONw)
- [ITSource分享第17期【宠物管理系统(带论文)springboot+vue】](https://mp.weixin.qq.com/s/S_mDclr4BKOzGZHG6etnoA)
- [ITSource分享第18期【二手交易(电商,商城)系统(带论文和PPT)springboot+vue】](https://mp.weixin.qq.com/s/_LlrbVBq_6nhGp3BY7F38A)
- [ITSource分享第19期【学生选课管理系统springboot+vue】](https://mp.weixin.qq.com/s/b8qTt-XT9SZNzQTKOJQqSw)
- [ITSource分享第20期-Java SpringBoot 微信点餐系统视频](https://mp.weixin.qq.com/s/xqmR6R96yFSZeQOmkCQcmQ)
- [ITSource分享第21期【房屋租赁管理系统】springboot+vue](https://mp.weixin.qq.com/s/7F7EhKv_CG81LEDS1XEJHw)
- [# ITSource分享第22期【景区旅游管理系统】springboot](https://mp.weixin.qq.com/s/ygvHpQeg_frDWD2f1F-R_A)
- [ ITSource分享第23期【图书管理系统】springboot+layui前后端分离](https://mp.weixin.qq.com/s/b1-prJSZdQcEBy0M6JOnDg)
- [第24期【在线拍卖系统】springboot+vue前后端分离+论文+PPT](https://mp.weixin.qq.com/s/VGKHG_ZPER3VA5rTdbXFiQ)
- [第25期【汽车票网上预定系统】springboot+vue前后端分离+论文](https://mp.weixin.qq.com/s/CB6xxXJkvK1GAhAVFUgHZw)
- [# 第26期【在线旅游购买网站系统】springboot+vue前后端分离+论文+PPT](https://mp.weixin.qq.com/s/BfUtXw77GQzXgPQfGyubmg)
- [# 第27期【校园网上租赁交易系统设计与实现】springboot+vue前后端分离+论文+部署文档](https://mp.weixin.qq.com/s/FvWVPlmOkuULLQ9seQHcpQ)
- [# ITSource分享第28期【网上宠物用品交易系统设计与实现】springboot+vue前后端分离+论文+部署文档](https://mp.weixin.qq.com/s/dMLwreWgZFsY56VrQv_dzw)
- [# ITSource分享第29期【在线文档管理系统的设计与实现】springboot+vue前后端分离+论文+PPT+部署文档](https://mp.weixin.qq.com/s/K1ON3lHfR_1K3iKgC2yhMw)
- [# ITSource分享第30期【在线考试管理系统的设计与实现】springboot+vue前后端分离+论文](https://mp.weixin.qq.com/s/s3rYbnRFRgcGYkFzWVlJyw)
- [# ITSource分享第31期【在线视频网站系统的设计与实现】springboot+vue前后端分离+论文](https://mp.weixin.qq.com/s/AdpMAAPM5PGz3scaYh9Hsg)
- [ITSource分享第32期【在线问卷调查网站系统的设计与实现】springboot+vue前后端分离](https://mp.weixin.qq.com/s/SXKUMVhMsKqKbeso2yWKdg)
- [ITSource分享第33期【在线小说阅读系统】](https://mp.weixin.qq.com/s/NAjSRu-dX9hJ4uftcOsvHA)

---


---

## 下载地址:

```
> 百度云源码 :链接：
 https://pan.baidu.com/s/1Cc2WelN3vI3lrFq_NPqz_A?pwd=s8ju 提取码: s8ju 

常用开发软件:
链接：https://pan.baidu.com/s/1KSLqE3eCi51FSfftkmLfGw?pwd=mc8v 
提取码：mc8v

```