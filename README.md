# 🍽️ 餐厅点餐系统

一个使用Vue.js和Spring Boot构建的现代餐厅点餐系统。

## 🚀 功能特性

- 🔐 用户认证与授权
- 🍕 菜品管理
- 🛒 订单处理
- 💬 顾客评价
- 📊 管理员仪表盘
- 🏪 餐厅管理

## 🛠️ 技术栈

### 前端技术:
- Vue.js 2.6.14
- Element UI 2.13.0
- SCSS
- Axios 0.21.1
- vue-router 3.1.5

### 后端技术:
- Spring Boot 2.2.2
- MySQL 5.7+
- MyBatis-Plus 2.3
- Shiro 1.3.2
- JDK 1.8

## 📋 环境要求

- Node.js (推荐使用v14.21.3，避免使用高版本可能产生的兼容性问题)
- JDK 1.8
- MySQL 5.7+
- Maven 3.6+

## 🔧 安装与设置

### 后端设置

1. 克隆仓库:
```bash
git clone https://github.com/MilesSG/food-ordering-system.git
cd food-ordering-system
```

2. 配置数据库:
   - 创建MySQL数据库
   - 在`application.yml`中更新数据库配置信息

3. 构建并运行后端:
```bash
cd springboot1mi5m
mvn clean install
mvn spring-boot:run
```

### 前端设置

1. 安装管理后台依赖:
```bash
cd admin
npm install
```

2. 启动开发服务器:
```bash
npm run serve
```

## 🌟 使用说明

1. 访问管理后台:
   - 网址: `http://localhost:8080/admin`
   - 默认管理员账号:
     - 用户名: admin
     - 密码: admin

2. 配置餐厅设置:
   - 添加菜品分类
   - 上传菜品信息
   - 设置价格和供应状态

3. 监控订单和管理顾客

## 🤝 参与贡献

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的修改 (`git commit -m '添加一些特性'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

## 📝 许可证

本项目基于 MIT 许可证开源 - 查看 [LICENSE](LICENSE) 文件了解更多细节

## 👥 作者

- Miles SG - 初始开发

## 🙏 致谢

- 感谢所有贡献者
- 灵感来自现代餐饮外卖平台
- 为餐厅经营者和顾客用心打造

## 📌 版本说明

### 前端依赖版本
- vue: 2.6.14
- element-ui: 2.13.0
- axios: 0.21.1
- vue-router: 3.1.5
- core-js: 3.4.4
- sass: 1.26.5
- sass-loader: 8.0.2

### 后端依赖版本
- spring-boot-starter-parent: 2.2.2.RELEASE
- mybatis-plus: 2.3
- mysql-connector-java: 最新版
- commons-lang3: 3.0
- hutool-all: 4.0.12
- lombok: 最新版

## ⚠️ 注意事项

1. Node.js版本要求：
   - 推荐使用v14.21.3
   - 不建议使用v22+等高版本，可能会产生兼容性问题

2. 数据库配置：
   - 需要MySQL 5.7或以上版本
   - 默认端口3306
   - 需要提前创建数据库

3. 开发工具建议：
   - IDE: IntelliJ IDEA 2020+
   - 前端编辑器: VSCode
   - 数据库工具: Navicat Premium

4. 运行环境：
   - 建议在Windows 10或Ubuntu 18.04+上运行
   - 需要配置好Java和Node.js环境变量 