# ShareBookServer
【MySelf共享图书】一个基于SpringBoot的共享后端服务，实战教学版

项目介绍，这个一个`企业级的共享图书项目`，涉及部分Iot实践环节，整个项目主要以SpringBoot为后台提供API，前端小程序调用接口，
同时项目会涉及共享书柜硬件的通信环节，其中涉及`netty知识`，整个项目大致的技术栈应该会有小程序源码MVC开发模式、ES6基
础能力提升、共享书柜二维码生成、图书管理系统、图书业务知识、netty构建简易Iot通信，SpringBoot实现基本的业务功能。

业务具体介绍，本系统是一个`共享图书的小程序项目`，企业级，创业项目。类似共享自行车，投放自行车，本项目投放图书书柜（小型快递柜），书柜内部有24本图书，每个书柜会有定位，可以在小程序搜到距离你最近的书柜，并且每个书柜会有专属的二维码，因为每个书柜存放的图书不一样，你可以在A书柜扫码借书，之后在B书柜还书，前提是B书柜有空余格子。具体业务流程类似共享自行车，也有设计押金、月卡、季卡等等。

![Image](https://raw.githubusercontent.com/UncleCatMySelf/img-myself/master/img/%E5%85%B1%E4%BA%AB%E5%9B%BE%E4%B9%A6/%E5%85%B1%E4%BA%AB%E5%9B%BE%E4%B9%A6%E6%95%88%E6%9E%9C%E5%9B%BE.gif)

### 相关信息

swagger-ui查看路径：`http://localhost:8080/sharebook/swagger-ui.html`

#### 公众号：Java猫说

**学习交流群：728698035**

> 现架构设计（码农）兼创业技术顾问，不羁平庸，热爱开源，杂谈程序人生与不定期干货。

![Image Text](https://user-gold-cdn.xitu.io/2018/12/28/167f41f1a5729856?w=344&h=344&f=jpeg&s=8231)