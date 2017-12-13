# JHipster 应用代码生成器

## 简介

JHipster 可以创建 Spring Boot + AngularJS 的应用。

可以在实际开发中，可以分离前后端，分别生成前后端代码。

## JHipster 优势：

- 风头超劲，席卷欧美，最新全能Java Web开发程式产生器 (Java Web Generator)

- 由Java专家累积的开发经验，配上各类实用的框架技术，去繁取精的运用，全方位的配置，制成出完备的开发应用程式

- 完美Java体系架构，尤其适用于 MicroService

- 相对较低的学习成本

- 快速建立基本项目工作模版，更专注业务上

## 客户端技术栈

单页面 Web 应用：

- 响应式页面设计

- HTML5 Boilerplate

- Twitter Bootstrap

- AngularJS `[`JavaScript MVC 框架`]`

- IE9+ , etc..

- 基于 Angular Translate 支持

- 可选 Sass 用于 CSS 设计

- 可选 Spring WebSocket 实现 WebSocket

强大的 Yeoman`[`建立在 Bower 之上，workflow。生成前端模板，下载依赖，构建任务`]` 开发工作流：

- 使用 Bower`[`客户端管理器，搜索、安装、卸载 JS/HTML/CSS 等`]` 轻松安装 JS 类库

- 使用 Gulp.js 构建，优化项目，支持 Live Reload`[`前端自动化`]`

- 支持 Thymeleaf 模板引擎，用于服务端渲染页面

## 服务端技术栈

完整的 Spring 应用

- Spring Boot 用于简化应用配置

- Maven / Gradle 用于构建，测试 / 运行

- `development` 和 `production` 配置文件

- Spring Security `[`标准业内的授权和认证`]`

- Rest + Jackson `基于 Http 协议实现资源操作`

- 可选的 WebSocket 支持 -- 基于 Spring WebSocket `允许用户在浏览器中实现双向通信，实现数据的及时推送`

- Spring Data JPA + Bean 验证

- 使用 Liquibase`[`支持主流数据库重构、迁移`]` 实现数据库自动更新`数据库版本控制`

- 支持 `document-oriented` NoSQL，如：MongoDB

- 支持 `column-oriented` NoSQL，如：Cassandra

支持生产环境：

- Monitoring with Metrics 监控运行状态

- 支持 Ehcache`本地缓存` 或 Hazelcast'分布式缓存'

- 可选 Http Session 集群，基于 Hazelcast

- 优化静态资源（gzip filter,Http cache headers）

- 日志管理 Logback，可在运行时配置

- HikariCP 连接池，用于性能优化

- 可以将应用构建一个标准的 WAR 或可执行的 JAR


## JHipster 环境依赖

- Node.js

- Git

- NPM

- Yeoman

- Bower

- Grunt

- Yarn

- 最后安装 JHipster

- 具体安装，抽时间补齐

## JHipster 生产环境

- mkdir jhipster && cd jhipster

- yo jhipster

- 具体选项抽时间补齐。网上资料大多陈旧过时。

**注意:** 生产环境前，需要在相关数据库中的 `schema.sql`中填写在选项中曾经定义的 `项目名字` 

- 
