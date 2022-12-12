# 工具

## Android studio 插件分享

- https://juejin.cn/post/7169790724304633893?share_token=9b247f82-3fb7-4030-84b1-dc24c7d14743
- 分享人:CV战士
- 主要介绍Android studio的常用插件,实际操作性比较强,一些插件的下载不同主要墙或版本

## git实用技巧

- https://juejin.cn/post/7172209699998138405/
- �_南京_android 性能优化
- 对常用的git技巧做了详细的介绍

## 使用Breakpad捕获Android Native Crash
- https://juejin.cn/post/6935472686655078414?share_token=c1c0c1b5-fd84-473b-814c-7ed762d7d558
- Ray-成都-应用 
- 基于`Android开发高手课`,使用`breakpad`进行了实操,对整个过程做了详细的描述

## 通过ASM实现大图监控

- https://juejin.cn/post/6844904136266219534?share_token=57c23501-90c4-4751-b37a-d217ea8d5b92
- 周正一
- 文章讲述了通过hook的方式对应用中加载图片中的超标图片(大小,尺寸)进行检查提示.实际操作性非常高.

## 【Compose】Desktop Application 初尝试

- https://blog.csdn.net/lucky_tom/article/details/128036111?spm=1001.2014.3001.5501
- 苏老泉-西安-性能
- 文章主要分享了Jetpack中的Compose组件,可以轻松跨平台的方案,对于流程的配置介绍相对比较详细,深度不够,是个很不错的入门配置文章.


# frameworks

## Android 12 系统源码分析 | Native Binder 代码变迁

- https://blog.csdn.net/m0_62167422/article/details/122386024
- 疙瘩徐-深圳-图形
- 文章承前启后，分析了ServiceManager逻辑在版本迭代中的变迁，有助于加深对 Binder 机制和 AIDL 的理解

## Android ANR深入分析

- https://juejin.cn/post/7170975699593855012
- 李圳均-成都-wms/ams
- 文章分析了ANR的深层次原因,从日常工作的角度讲述了实际解决ANR问题的几个案例.

## Android智能指针初探——轻量级指针（Light Pointer）

- https://juejin.cn/post/7174003890889687076?share_token=dd9d761a-ac63-4df6-9692-3cf5251b65ea
- 一只蓝鲸-合肥-app
- 文章简单的介绍了常见的垃圾回收算法,然后用源码中`Light Pointer`的关键部分介绍了`sp`的实现过程.

# Android编译

## SeLinux & 自启动-实战

- https://juejin.cn/post/7169781842696994846?share_token=1baf206b-73bb-44ef-a856-7853e8b63816
- 分享人:谢+深圳+Android，Linux BSP
- 主要介绍SELinux的基础知识,对`SELinux`的编译,自定义,常见错误等做了分析.

## init.rc深入学习

- https://juejin.cn/post/7173951742118199309/
- 流年-深圳-android安全
- init.rc是Android开机用来初始化系统守护进程的配置文件，如果大家后面要自己写一个底层服务，可以参考这篇文章里的规则来编写rc配置文件

# 性能

## loadavg系统负载介绍

- https://juejin.cn/post/7169417417599401998
- 分享人:邢-杭州-framework&性能
- 基于kernel4.9.版本讲述loadavg的数据产生和输出过程.内含大量源代码


## 【性能优化】大厂OOM优化和监控方案

- https://juejin.cn/post/7074762489736478757?share_token=185c2f00-7e09-494c-bfa5-1eb239b58073
- Ray-成都-应用
- 属于集合类的一个文章,问中将常见的监控和优化方案都有大致的说明,非常好的方向性文章.

https://blog.csdn.net/lucky_tom/article/details/128036111?spm=1001.2014.3001.5501

