﻿# 组件介绍 #


iUAP平台采用iuap-jdbc作为数据持久化中间件，实现对对业务数据的持久化服务。

本组件对jdbc做了轻量封装，采用基于注解的ORM映射机制，简化代码配置。
使用简单，面向对象的方式编程，直接操作POJO，少量代码完成持久化操作。
组件能够自动识别数据源，提供不同数据库的基本语法转换的能力，做到一套语法，多种数据库兼容执行，目前支持MySQL，Oracle,PostgreSQL。

# 版本及更新 #

## iuap-jdbc-2.0.1-RELEASE.jar ##

1. 扩展数据库语法转换，支持MySQL，Oracle，PostgreSQL的基础语法

2. 提供主子表的级联保存，更新，删除操作。

## iuap-jdbc-3.1.0-RELEASE.jar ##

1. 适配weblogic和websphere JNDI数据源；
