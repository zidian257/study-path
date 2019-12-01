# 前端架构知识图谱

## JavaScript 高级

1. call、apply、bind、new 等手写实现

2. 原型链和闭包深入

3. 执行上下文和作用域链

4. 深拷贝和浅拷贝

5. 防抖和节流

6. 词法分析和语法分析

7. 常量、解析、模板字符串、展开运算符、解构操作符、箭头函数、数组新方法、生成器和迭代器

8. Symbol 元编程、Set 和 Map 应用以及 WeakMap、Object.defineProperty 以及下一代 Proxy&Reflect、ESModule 实现、浏览器和 Node.js 中的 EventLoop

9. V8 内存管理、垃圾收集、引用记数、标记清除、标记整理和增量标记

10. 高阶函数、发布订阅和观察者模式、Promise 核心应用、generator 和实现 co 库、async+await 原理、实现完整的 PromiseA+类库，包含 reace、all、finally、try 等方法

## React 全家桶

### 核心篇

1. React 核心

2. 模块化和组件化

3. React 的属性、校验和参数传递

4. React 的状态和双向数据绑定

5. React 中的单向数据流

6. 受控组件和非受控组件

7. React 表单双向数据绑定

8. 新旧 Context 上下文环境

9. DOM 获取之 Ref

10. 新旧生命周期函数

11. children 属性的使用

### 进阶篇

1. create-react-app 原理分析

2. JSX 原理和虚拟 DOM 原理

3. setState 异步原理实现和事务实现

4. 使用 Immutablejs 和 PureComponent 优化性能

5. React 动画

6. ErrorBoundary、Suspense 和 Fragment

7. React Hooks+Redux 实战

8. React 性能分析

9. React 中的高阶组件和 render props

10. React 新一代的 Fiber 架构

11. 从零实现一款包含完整 dom-diff 算法的 React

### 路由篇

1. 路由配置

2. 路由懒加载

3. 路由重定向

4. 路由之权限管理

5. 受保护的路由

6. 手写一个完整的 React-router4 路由库

### redux 篇

1. redux 核心概念 action、reducer、store

2. 手写实现 redux、react-redux、connected-react-router 完整功能库

3. 手写 redux-logger、redux-promise、redux-thunk、redux-saga、redux-actions、reselect、redux-persist 完整类库

### React 服务器端渲染 SSR

1. 客户端渲染 VS 服务器端渲染

2. React 中的服务器端原理

3. 同构的原理和意义

4. SSR 中使用路由跳转和 redux

5. SEO 优化和预渲染

6. Koa2+next.js 服务器端渲染实战

### mobx 篇

1. observable、computed、autorun、when、reaction 实战

2. 手写一个 mobx 类库

### UI 类库实践

## node 高级

### node 核心模块

1. EventLoop 和事件队列

2. process 全局对象

3. commonjs 原理解析

4. 深入字符编码

5. Buffer 对象

6. fs 文件模块

7. 压缩与解压缩

8. 加密与签名算法

9. Stream 流的原理和应用

10. 多线程与集群

11. tcp 和 http 服务器

12. 多语言、防盗链、正向和反向代码服务器

### Express&Koa

1. 路由配置、参数处理、使用中间件、模板、静态文件中间件、重定向、cookie 和 session

2. 手写原版 express 框架、手写原版 koa2 框架、JWT 权限认证

3. 企业级开发框架 Egg.js

4. 项目架构、配置路由、静态文件服务、模板引擎、远程接口服务、计划任务

5. 集成 MYSQL、restful 接口、sequelize 持久化工具、国际化、扩展工具方法、中间件、运行环境、单元测试、服务器部署和运维

6. 自定义插件和框架

## 单元测试

### 测试用例和需求分析

### 单元测试框架 mocha

### Jest+Enzyme 实现 React 单元测试

## 服务器布署

### TCP

1. TCP/IP 协议族网络模型
2. IP 协议以及简单路由
3. TCP 连接的本质
4. TCP 三次握手和加次挥手
5. 路由和网关、滑动容器和 Nagle 算法
6. HTTPS
7. 网络命令
8. 网络调优
9. wireshark 抓包实战

### 域名、备案、服务器、环境配置、安全设置、远程部署、发布与更新

### 集群的负载均衡、PM2 实战

### Nginx

1. nginx 的安装和使用

2. 模块和基本配置

3. 正向反向代理等应用场景

4. CDN

5. 浏览器缓存

6. 跨域

7. 防盗链

### Docker

1. Docker 介绍和安装

2. Dockerfile

3. 存储和镜像仓库

4. Dock 实战

### jenkins

1. jenkins job

2. shell 集成

3. 集成 nginx 和 git

4. 持续集成和布署

5. travis gitlab ci

### MySQL

1. MYSQL 安装与使用

2. MYSQL 系统架构

3. 数据处理之增删改查

4. 数据类型和约束分页

5. 索引和慢查询性能分析

6. 数据库安全之防止 SQL 注入

7. 数据库设计 ER 图设计

8. 数据库事务、锁和日志隔离级别

9. 数据库设计之三大范式

10. 基于角色的权限访问控制（Role-Based Access Control）

### Mongodb

1. Mongodb 安装和使用

2. Mongodb 的系统架构

3. Mongodb 高级查询

4. Mongodb 索引

5. Mongodb 安全与权限

6. mongoose 模块之 Schema

7. mongoose 模块之 Model

8. mongoose 实战

### Redis

1. Redis 安装和使用

2. 5 种数据结构及使用场景

3. API 的理解和使用

4. Redis 客户端

5. 发布订阅

### 事务

7.备份和恢复

## 前端设计模式

### 创建型设计模式

1. 工厂模式

2. 建造者模式

3. 原型模式

4. 单例模式

### 结构型设计模式

1. 外观模式

2. 适配器模式

3. 代理模式

4. 装饰者模式

5. 组合模式

### 行为型设计模式

1. 观察者模式

2. 状态模式

3. 策略模式

4. 命令模式

5. 访问者模式

6. 中介者模式

7. 迭代器模式

## 算法&数据结构

### 算法的基础知识

1. 输入、输出和数据级

2. 计算能力的变革

3. CPU、寄存器和内存

4. 二分查找

5. 插入排序

6. 冒泡排序

### 算法的衡量和优化

1. 时间复杂度和空间复杂度

2. 复杂度的本质

3. 合并排序

4. 递归函数复杂度分析

5. 递归表达式分析法

6. 递归数学归纳法分析

### 排序算法

1. 排序算法介绍

2. 基于比较的排序算法

3. 合并排序优化

4. 快速排序

5. 快速排序复杂度和优化

6. 计数排序

7. 基数排序

8. 桶排序

9. 外部排序

### 递归

1. 递归的基本概念

2. 递归图形的绘制

3. 递归和穷举问题

4. 组合问题

5. 递归空间优化

6. 回溯算法

7. 重复子问题优化

8. 尾递归

9. 搜索问题(8 皇后)

10. 深度优先搜索和广度优先搜索

### 数据结构

1. 数组

2. 双向链表

3. 反转单向链表

4. 堆

5. 栈

6. 队列

7. 进阶算法

8. 动态规划的概念

9. LCS 问题的子结构

10. 填表法

11. 构造结果

## BAT 面试真题

### 反转二叉树

### 解析 query 字符串

### 取 N 个数字为 M

### 火车排序问题和队列

### 网格走法动态规划

### 两个栈实现一个队列
