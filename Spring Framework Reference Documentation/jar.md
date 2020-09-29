<!--
 * @Descripttion: 
 * @Author: guox
 * @Date: 2020-09-28 15:27:54
 * @LastEditors: guox
-->
+ core
  + core 依赖注入IoC与DI的最基本实现
  + beans Bean工厂与bean的装配
  + context spring的context上下文即IoC容器
  + expression spring表达式语言
+ aop
  + apo 面向切面编程
   + aspects 集成AspectJ
  + instrument 提供一些类级的工具支持和ClassLoader级的实现，用于服务器
  + spring-instrument-tomcat 针对tomcat的instrument实现
+ data access
  + jdbc jdbc的支持
  + tx 事务控制 对象关系映射，集成orm框架
  + oxm 对象xml映射
  + jms java消息服务
+ web
  + web 基础web功能，如文件上传
  + webmvc mvc实现
  + spring-webmvc-portlet 基于portlet的mvc实现
  + websocket 为web应用提供的高效通信工具
+ test
  + test spring测试，提供junit与mock测试功能
  + context-support spring额外支持包，比如邮件服务、视图解析等
+ messaging
  用于构建基于消息的应用程序