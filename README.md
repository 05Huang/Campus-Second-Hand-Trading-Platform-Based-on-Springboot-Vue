# Campus-Second-Hand-Trading-Platform-Based-on-Springboot-Vue
这是一个基于Spring Boot和Vue.js开发的校园二手交易平台，旨在为校园内的学生提供一个便捷、高效的二手物品交易环境。用户可以发布二手物品信息、浏览商品详情、进行在线交流和交易，同时平台还具备用户认证、商品分类管理等功能，确保交易的安全性和可靠性。This is a campus second-hand trading platform developed based on Spring Boot and Vue.js, aiming to provide a convenient and efficient second-hand goods trading environment for students on campus. 
# 校园二手交易平台

## 项目简介
这是一个基于 **Spring Boot** 和 **Vue.js** 开发的校园二手交易平台，旨在为校园内的学生提供一个便捷、高效的二手物品交易环境。用户可以发布二手物品信息、浏览商品详情、进行在线交流和交易，同时平台还具备用户认证、商品分类管理等功能，确保交易的安全性和可靠性。

## 项目架构
- **后端**：Spring Boot
- **前端**：Vue.js
- **数据库**：MySQL

## 功能模块
### 用户模块
- 用户注册与登录
- 用户信息管理（头像、昵称、联系方式等）
- 用户认证（邮箱验证、手机验证）

### 商品模块
- 商品发布（填写商品信息、上传图片、设置价格等）
- 商品分类（书籍、电子产品、生活用品等）
- 商品搜索与筛选
- 商品详情查看（图片、描述、价格、卖家信息等）
- 商品收藏与关注

### 交易模块
- 交易发起（私信卖家、在线沟通）
- 交易状态管理（待付款、待发货、已发货、已完成、已取消）
- 交易评价与反馈

### 管理模块
- 管理员登录
- 用户管理（查看用户信息、封禁/解封用户）
- 商品管理（审核商品、下架违规商品）
- 交易记录查询

## 环境依赖
- **Java**：1.8 及以上版本
- **Node.js**：14.x 及以上版本
- **MySQL**：5.7 及以上版本
- **Maven**：3.6 及以上版本
- **Docker**：用于容器化部署（可选）

## 项目启动
### 后端启动
1. **数据库初始化**
   - 在 MySQL 中创建相应数据库。
   - 执行 sql文件，完成表结构初始化。
2. **配置文件修改**
   - 修改 `src/main/resources/application.yml` 中的数据库连接信息，确保与你的 MySQL 数据库配置一致。
3. **项目构建**
   - 打开终端，进入项目根目录。
   - 执行 `mvn clean install` 命令，进行项目构建。
4. **启动项目**
   - 执行 `mvn spring-boot:run` 命令，启动 Spring Boot 应用。
   - 访问 `http://localhost:8080`，查看后端接口是否正常运行。

### 前端启动
1. **安装依赖**
   - 打开终端，进入 `frontend` 目录。
   - 执行 `npm install` 命令，安装项目依赖。
2. **启动项目**
   - 执行 `npm run serve` 命令，启动 Vue.js 开发服务器。
   - 访问 `http://localhost:8081`，查看前端页面是否正常运行。


## 数据库设计
- 数据库表结构设计详见sql 文件。


## 项目维护
- **代码规范**
  - 后端代码遵循 Java 代码规范，使用 Lombok 简化代码。
  - 前端代码遵循 Vue.js 代码规范，使用 ESLint 进行代码检查。
  - 
- **版本管理**
  - 使用 Git 进行版本管理，代码托管于 GitHub/GitLab 等平台。
  - 遵循 GitFlow 工作流进行分支管理。

## 贡献指南
欢迎为本项目贡献代码！提交 Pull Request 前，请确保您的代码已通过单元测试和代码检查，并在提交 PR 时详细描述您的变更内容和实现方式。

## 联系方式
- **项目负责人**：
- email:3441578327@qq.com
