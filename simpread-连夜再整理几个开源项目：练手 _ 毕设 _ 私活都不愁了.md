> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [mp.weixin.qq.com](https://mp.weixin.qq.com/s/jjugnXIr3G0u7i9krbmmqg)

一直以来，总有小伙伴问说：诶，有没有什么好的项目推荐啊，想参考使用。

一般用途无非如下几种情况：

*   自学练手：从书本和博客的理论学习，过渡到实践练手
    
*   吸收项目经验，找工作写简历时能参考：毕竟有时候确实没有实际项目经验可写，那研究开源项目的经验就非常宝贵了
    
*   毕业设计：想找点参考、找点选题、找点灵感
    
*   甚至还有想接私活参考的：想找一个脚手架快速开发
    

索性今天再整理几款开源项目吧，分为几大方面：

*   后台管理类项目
    
*   商城类项目
    
*   秒杀类项目
    
*   支付类项目
    
*   综合平台类项目
    

后台管理类项目
=======

**项目名称：** _**JeeSite**_

**项目介绍：**

这是个典型的`SSM`后台管理项目（不是有很多小伙伴让推荐 SSM 项目练手嘛），基于经典技术组合（`Spring MVC`、`Shiro`、`MyBatis`、`Bootstrap UI`等）开发，适合学习练手。

而且它作为一个典型的后台管理系统，要素基本都有，包括：组织机构、角色用户、权限授权、数据权限、内容管理、工作流等。

尤其要提的就是最后的**工作流模块**，它可以实现提工单、审核 / 审批等流程，这个在后台管理类项目里是必备的模块。

![](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzr2vicXVJpWialGDfVCHAooHk7nvOe4apnh6xdGq5ZVMVoAPYPgSbVicluFny94j1dp7ibb8kXuwr6XYw/640?wx_fmt=png)

**传送门：** 

https://gitee.com/thinkgem/jeesite

商城类项目
=====

**项目名称**：_**platform-wechat-mall**_

**项目介绍**：

该项目是一个开源的微信小程序商城，虽说其项目技术栈不算特别新，后端用的也是 SSM 框架，但是它作为一个商城项目，要素模块基本都包含了，比如：系统后台管理、商品后台管理、移动端商城的`API`接口、手机移动端商城、微信小程序商城等等。

而且主要功能也非常丰富，包括：会员管理、商城配置、商品管理、推广管理、订单和系统管理等等。

![](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzr2vicXVJpWialGDfVCHAooHkmch9yPsRohsiaY44JL37wKIAhQicAddaEoibgr5GBT3AbT4xvHkW2oMkw/640?wx_fmt=png)![](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzr2vicXVJpWialGDfVCHAooHkCCsjrfrjVt2rEGQAG5keTOQ2eZjve4uu8kjDM5JxzTeDwDjibs9aFHQ/640?wx_fmt=png)

**传送门**：

https://gitee.com/fuyang_lipengjun/platform

秒杀类项目
=====

**项目名称**：_**spring-boot-seckill**_

**项目介绍：**

秒杀类开源项目其实很难得，毕竟涉及高并发的一些问题嘛，这些在面试时都是能让面试官眼前一亮的东西。

这个项目与其说是一个开源项目，倒不如说是一些具体秒杀问题里面的案例集合。

![](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzr2vicXVJpWialGDfVCHAooHkCLJ5MN1tvBFTiaH6ym5P3WZR44GmF0W02Lia6nn8P0uoK5XhrZLs0FzA/640?wx_fmt=png)

秒杀系统基本设计思想无非也就是：**限流**、**缓存**、**异步**、**分摊**、**主备**，其实某一程度上来说就是开源 + 节流的思想。

![](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzr2vicXVJpWialGDfVCHAooHkQoG39StZ5j45fmQGJE4yavfujEQkjz3wAwIrecI5A6GOY9JM1PQyWA/640?wx_fmt=png)

所以通过它应该能学到一些比 CRUD 高级一些的技术，诸如：**线程池**、**锁**、**分布式锁**、**消息队列（kafka）**、**缓存（redis）** 等等。

**传送门**：

https://gitee.com/52itstyle/spring-boot-seckill

支付类项目
=====

**项目名称**：_**roncoo-pay**_

**项目介绍：**

支付系统嘛，集成了主流支付方式、支付平台等，除此之外它还有些额外的管理功能，比如对账、结算、交易订单的管理等等，所以也有后台管理的。

![](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzr2vicXVJpWialGDfVCHAooHkN7Ria25ElUTL9TkyMoyWSdB1GO2uxzL9gRd1qria5PMWlz9XGyXHVsqQ/640?wx_fmt=png)

该项目的技术栈也是后端的主流技术，包括：`Spring Boot`、`Shiro`、`MyBatis`、`Redis`等。

开源的支付类项目平时见得可能也不多，它也是一个偏业务类型的开源项目。毕竟开源项目很少有业务强相关的，开源出来的东西，业务一般都剥离出去了。该项目涉及了一些和支付相关的业务流程，包括：支付流程、对账流程、结算流程等等。

![](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzr2vicXVJpWialGDfVCHAooHkLCu43OoIXFsFldUvumYmouVxK6fDTSakSJhtRoUbs3b0renKrN6buA/640?wx_fmt=png)

**传送门**：

https://gitee.com/roncoocom/roncoo-pay

综合平台类项目
=======

项目一：_**Cloud-Platform**_
------------------------

**项目介绍**：

Cloud-Platform 是一个基于 Spring Cloud 技术栈实现的微服务化开发平台，包含了微服务架构的常见组件，比如：服务注册和发现、网关、服务调用、熔断 / 降级机制、认证 / 鉴权、监控中心等等。

![](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzr2vicXVJpWialGDfVCHAooHk8neKp2WsHy49uAHE9MVw3ticiahxBemdIPx3E07p9ACJv2so5IQyNjfg/640?wx_fmt=png)![](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzr2vicXVJpWialGDfVCHAooHkyKxCXug3JgQXRo3VOo4bPjIEHyPRpibVXWS3SvkohH2FXoc8ibw5pSuw/640?wx_fmt=png)

**传送门**：

https://gitee.com/geek_qi/cloud-platform

项目二：**_open-capacity-platform_**
--------------------------------

**项目介绍：**

同样和上面项目一样，`open-capacity-platform`也是一个学习 Spring Cloud 微服务技术栈的不错范例，其同样也包含了微服务架构里面的各种应用组件。

![](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzr2vicXVJpWialGDfVCHAooHkB4e5JNDs9uKiaOxqpHAaAsQpfOHp9ksK6KlWcibtJ1eySrx62QuLnGFg/640?wx_fmt=png)![](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzr2vicXVJpWialGDfVCHAooHkj67b1ib9AA4Xv1zCetiayO3xSgEnvyxhtyDh2JecHGJMgHfMibQ6bjfAA/640?wx_fmt=png)

**传送门**：

https://gitee.com/owenwangwen/open-capacity-platform

后 记
===

最后，小伙伴们如果有好的项目资源可以推荐的，赶快安利吧，一起交流进步。

> **另注：** 本文在开源项目：

> https://github.com/hansonwang99/JavaCollection

> 中已收录，包含自学编程、面试题和面经、及系列技术文章等，资源持续更新中...

每天进步一点点

慢一点才能更快

```
给个[在看]，是对程序羊最大的支持
```