# Java 后端工程师学习指南 🚀

> 本指南涵盖 Java 后端核心技术和必要的前端知识，适合有一定基础、希望通过文档自学的开发者。

---

## 目录

- [学习路线](#学习路线)
- [文档学习资源](#文档学习资源)
- [学习方法与技巧](#学习方法与技巧)
- [学习顺序建议](#学习顺序建议)

---

## 学习路线

### 📚 第一阶段：编程基础（1-2个月）

#### 1. Java 基础
- **语法基础**：变量、数据类型、运算符、流程控制
- **面向对象**：类、对象、封装、继承、多态、抽象类、接口
- **核心 API**：String、集合框架（List、Set、Map）、异常处理
- **I/O 流**：文件读写、字节流、字符流
- **多线程**：Thread、Runnable、线程池、并发工具类
- **JDK 新特性**：Lambda 表达式、Stream API、Optional

#### 2. 开发工具
- **IDE**：IntelliJ IDEA（推荐）
- **版本控制**：Git + GitHub
- **构建工具**：Maven / Gradle

---

### 🔧 第二阶段：数据库（1个月）

#### 1. 关系型数据库
- **MySQL**：
  - SQL 语法（CRUD、JOIN、子查询）
  - 索引原理与优化
  - 事务与锁机制
  - 数据库设计与范式

#### 2. 非关系型数据库
- **Redis**：
  - 数据类型与应用场景
  - 缓存策略（穿透、击穿、雪崩）
  - 持久化（RDB、AOF）

---

### 🌐 第三阶段：Web 开发基础（1个月）

#### 1. 计算机网络
- HTTP/HTTPS 协议
- TCP/IP 基础
- RESTful API 设计

#### 2. Java Web 基础
- Servlet & JSP（了解即可）
- Tomcat 服务器
- Cookie & Session

---

### 🏗️ 第四阶段：主流框架（2-3个月）⭐重点

#### 1. Spring 全家桶
```
Spring Framework → Spring Boot → Spring MVC → Spring Security
```
- **Spring 核心**：IoC 容器、DI 依赖注入、AOP 面向切面
- **Spring Boot**：自动配置、Starter、Actuator
- **Spring MVC**：控制器、拦截器、参数绑定
- **Spring Security**：认证与授权、JWT

#### 2. 持久层框架
- **MyBatis**：SQL 映射、动态 SQL、缓存机制
- **MyBatis-Plus**：简化 CRUD 操作
- **JPA/Hibernate**（了解）

#### 3. 其他常用框架/工具
- **Lombok**：简化代码
- **Swagger/OpenAPI**：API 文档
- **Log4j2/Logback**：日志框架

---

### 🎨 第五阶段：前端基础（1-1. 5个月）

#### 1. 基础三件套
- **HTML5**：页面结构
- **CSS3**：样式布局（Flexbox、Grid）
- **JavaScript**：ES6+ 语法、DOM 操作、异步编程

#### 2. 前端框架（选一个深入）
- **Vue.js**（推荐，上手快）
  - Vue3 + Composition API
  - Vue Router + Pinia/Vuex
  - Element Plus UI 组件库
- 或 **React**（可选）

#### 3. 前后端交互
- Axios HTTP 请求
- 跨域问题处理（CORS）
- 前后端分离架构

---

### ☁️ 第六阶段：微服务与分布式（2个月）

#### 1. 微服务架构
- **Spring Cloud**：
  - 服务注册与发现（Nacos/Eureka）
  - 配置中心（Nacos Config）
  - 网关（Gateway）
  - 负载均衡（LoadBalancer）
  - 熔断降级（Sentinel）
  - 远程调用（OpenFeign）

#### 2. 消息队列
- **RabbitMQ** 或 **Kafka**
- 消息模型、可靠性保证

#### 3. 分布式技术
- 分布式事务（Seata）
- 分布式锁（Redis/Zookeeper）
- 分布式 ID 生成

---

### 🐳 第七阶段：DevOps 与部署（1个月）

#### 1. 容器化
- **Docker**：镜像、容器、Dockerfile、Docker Compose
- **Kubernetes**（K8s）：基础概念与部署

#### 2. CI/CD
- **GitHub Actions** / Jenkins
- 自动化构建与部署

#### 3. Linux 基础
- 常用命令
- Shell 脚本
- Nginx 配置

---

### 📈 第八阶段：进阶提升（持续学习）

#### 1. 性能优化
- JVM 调优、GC 原理
- SQL 优化、慢查询分析
- 缓存优化策略

#### 2. 设计模式
- 单例、工厂、代理、策略、观察者等

#### 3. 源码阅读
- Spring 源码
- MyBatis 源码

#### 4. 系统设计
- 高并发、高可用架构设计
- 秒杀系统、分布式限流

---

## 文档学习资源

### Java 基础

| 资源 | 链接 | 说明 |
|------|------|------|
| Oracle 官方文档 | [docs.oracle.com/javase](https://docs.oracle.com/en/java/) | 权威但略枯燥 |
| 廖雪峰 Java 教程 | [liaoxuefeng. com](https://www.liaoxuefeng.com/wiki/1252599548343744) | 中文友好，通俗易懂 ⭐推荐 |
| Java 全栈知识体系 | [pdai. tech](https://pdai.tech/) | 体系完整，进阶必备 ⭐推荐 |
| Baeldung | [baeldung. com](https://www.baeldung. com/) | 英文，Spring 生态最佳 |

### Spring 全家桶

| 资源 | 链接 | 说明 |
|------|------|------|
| Spring 官方文档 | [spring.io/guides](https://spring.io/guides) | 官方教程，有中文翻译 ⭐必看 |
| Spring Boot 文档 | [docs.spring.io/spring-boot](https://docs.spring.io/spring-boot/docs/current/reference/html/) | 官方参考手册 |
| Spring 中文网 | [springdoc.cn](https://springdoc.cn/) | 官方文档中文翻译 ⭐推荐 |

### 数据库

| 资源 | 链接 | 说明 |
|------|------|------|
| MySQL 官方文档 | [dev.mysql.com/doc](https://dev.mysql.com/doc/) | 权威参考 |
| Redis 官方文档 | [redis. io/docs](https://redis.io/docs/) | 清晰易读 |
| MyBatis 官方文档 | [mybatis.org](https://mybatis.org/mybatis-3/zh/index.html) | 有中文版 ⭐ |
| MyBatis-Plus | [baomidou.com](https://baomidou. com/) | 中文文档完善 |

### 微服务

| 资源 | 链接 | 说明 |
|------|------|------|
| Spring Cloud | [spring.io/projects/spring-cloud](https://spring.io/projects/spring-cloud) | 官方文档 |
| Spring Cloud Alibaba | [sca.aliyun.com](https://sca.aliyun.com/docs/) | 阿里微服务生态 ⭐推荐 |
| Nacos 文档 | [nacos.io](https://nacos.io/zh-cn/docs/quick-start.html) | 中文友好 |

### 前端部分

| 资源 | 链接 | 说明 |
|------|------|------|
| MDN Web Docs | [developer.mozilla. org](https://developer.mozilla.org/zh-CN/) | HTML/CSS/JS 权威 ⭐必备 |
| Vue3 官方文档 | [cn.vuejs. org](https://cn.vuejs.org/guide/introduction.html) | 中文官方，质量极高 ⭐ |
| ES6 入门教程 | [es6.ruanyifeng.com](https://es6.ruanyifeng.com/) | 阮一峰，经典教程 |

### DevOps

| 资源 | 链接 | 说明 |
|------|------|------|
| Docker 官方文档 | [docs. docker.com](https://docs.docker.com/) | 清晰完整 |
| Linux 命令大全 | [linuxcool.com](https://www.linuxcool.com/) | 快速查阅 |
| GitHub Docs | [docs.github.com](https://docs.github.com/zh) | Git/GitHub 官方 |

---

## 学习方法与技巧

### 视频学习 vs 文档学习

| 阶段 | 推荐方式 |
|------|----------|
| 入门阶段（0-6个月） | 视频为主（70%） + 文档辅助（30%） |
| 进阶阶段（6-12个月） | 文档为主（60%） + 视频辅助（40%） |
| 工作阶段（1年以后） | 文档/源码为主（80%） + 视频辅助（20%） |

### 高效文档阅读法

```
1. 先看目录 → 了解整体结构
2. 快速浏览 → Getting Started / Quick Start
3. 跟着敲 → 官方示例代码
4. 深入阅读 → 你需要用到的章节
5. 遇到问题 → 回来查阅细节
```

### ⚠️ 注意事项

- **不要从头到尾全部看完** → 边学边查，用到什么看什么
- **一定要动手写代码** → 看懂 ≠ 会写
- **善用搜索** → `Ctrl+F` 是你的好朋友
- **收藏常用页面** → 建立自己的知识书签库

### 黄金组合

| 学习内容 | 推荐方式 |
|----------|----------|
| Java 基础/框架入门 | 视频 + 跟练 |
| 新框架/新技术 | 官方文档 + 官方示例 |
| 遇到具体问题 | Google/Stack Overflow/GitHub Issues |
| 深入原理 | 书籍 + 源码阅读 |
| 算法练习 | LeetCode + 题解视频 |

---

## 学习顺序建议

```
廖雪峰 Java 教程（复习巩固）
        ↓
Spring 官方 Guides（入门 Spring Boot）
        ↓
MyBatis-Plus 文档（数据库操作）
        ↓
pdai. tech（体系化查漏补缺）
        ↓
Vue3 官方文档（前端部分）
        ↓
Spring Cloud Alibaba（微服务进阶）
```

---

## 📁 学习笔记仓库结构建议

在 GitHub 上创建一个学习笔记仓库，把学到的知识点整理成 Markdown 文档：

```
my-learning-notes/
├── README.md
├── java-basics/
│   ├── 01-syntax. md
│   ├── 02-oop.md
│   ├── 03-collections.md
│   └── 04-multithreading.md
├── spring-boot/
│   ├── 01-getting-started.md
│   ├── 02-configuration.md
│   └── 03-web-mvc.md
├── mysql/
│   ├── 01-sql-basics.md
│   ├── 02-index.md
│   └── 03-transaction.md
├── redis/
│   ├── 01-data-types.md
│   └── 02-cache-strategy.md
├── vue3/
│   ├── 01-basics.md
│   └── 02-composition-api.md
└── projects/
    ├── blog-system/
    └── admin-dashboard/
```

---

## 📖 推荐书籍

| 类别 | 书名 |
|------|------|
| Java 基础 | 《Java 核心技术》 |
| JVM | 《深入理解 Java 虚拟机》 |
| 并发 | 《Java 并发编程实战》 |
| MySQL | 《高性能 MySQL》 |
| Redis | 《Redis 设计与实现》 |
| 设计模式 | 《Head First 设计模式》 |

---

## 🎯 学习建议总结

1. **动手为主**：每学一个知识点，都要写代码练习
2. **项目驱动**：搭建完整项目（如：博客系统、电商系统、后台管理系统）
3. **GitHub 积累**：将学习项目上传 GitHub，养成版本管理习惯
4. **定期总结**：写技术博客，输出倒逼输入
5. **循序渐进**：按阶段学习，不要跳跃

---

**预计总学习时长**：8-12 个月（全职学习）

祝学习顺利，早日成为优秀的后端工程师！💪