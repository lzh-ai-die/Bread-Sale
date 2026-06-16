<img width="375" height="370" alt="image" src="https://github.com/user-attachments/assets/f430d06f-1bef-4f21-9e42-926a9fcdb20b" /># 面包售卖管理系统

基于 SpringBoot + Vue 开发的 B/S 架构烘焙门店数字化管理系统，覆盖商品管理、库存管控、销售收银、会员营销、经营分析全流程，解决中小型面包店手工记账效率低、库存损耗高、数据难追溯等痛点。

## 📌 项目简介
针对校园及社区中小型烘焙门店运营痛点，设计并实现了一套集进销存、收银、会员、数据分析于一体的管理系统。系统分为**后台管理端**与**用户购买端**，支持多角色权限控制、实时库存预警、智能促销计算、多维度数据报表等功能，助力门店实现降本增效与数字化运营。

## 🛠 技术栈
### 后端
- 核心框架：SpringBoot 2.x
- 持久层：MyBatis / MyBatis-Plus
- 数据库：MySQL 8.0
- 权限控制：基于 RBAC 模型 + JWT Token
- 接口规范：RESTful API
- 构建工具：Maven

### 前端
- 核心框架：Vue 2.x / Vue 3.x
- UI 组件库：Element UI / Element Plus
- 路由管理：Vue Router
- 状态管理：Vuex / Pinia
- HTTP 封装：Axios
- 构建工具：Vue CLI

## 🧩 核心功能模块
### 后台管理端
1. **商品与品类管理**
   - 商品信息全生命周期管理（增删改查、图片上传、条码绑定）
   - 多级品类树状结构管理，支持商品批量导入导出
   
2. **库存管理**
   - 采购入库、生产入库、报损出库、退货出库全流程记录
   - 实时库存查询、低库存自动预警、临期商品预警
   - 库存盘点与差异分析，支持盘点单审核流程

3. **销售收银管理**
   - 扫码/搜索快速收银，购物车实时金额计算
   - 支持会员价、单品折扣、整单折扣、满减、买赠等多种促销规则
   - 多支付方式（现金、微信、支付宝、会员余额）及混合支付
   - 订单挂单/取单、退货退款、小票打印

4. **会员与营销管理**
   - 会员信息、等级、积分、余额管理
   - 自定义促销活动规则，结算时自动匹配计算

5. **系统与权限管理**
   - 基于 RBAC 的角色权限分配（管理员、店长、收银员）
   - 操作日志记录、数据自动备份、系统参数配置

6. **经营数据分析**
   - 销售趋势、商品销量排行、营收统计报表
   - 支持按日/周/月维度可视化展示

### 用户购买端
- 商品浏览与搜索、购物车管理
- 订单提交、在线支付、订单状态跟踪
- 个人信息维护、收货地址管理

## 🏗 系统架构
采用前后端分离的 B/S 架构：
- 表现层：Vue 前端页面，通过 Axios 发起 HTTP 请求
- 接口层：SpringBoot 提供 RESTful API，统一响应格式
- 业务层：封装核心业务逻辑，包含促销规则引擎、库存计算
- 数据层：MyBatis 操作 MySQL 数据库

## 🗄 数据库设计
核心数据表：
<img width="375" height="370" alt="image" src="https://github.com/user-attachments/assets/3d0a5a5a-4083-4302-829e-b78dabcba9e6" />

## 🚀 本地运行
### 环境要求
- JDK 1.8+
- Node.js 14+
- MySQL 8.0+
- Maven 3.6+

## 📸 项目截图
<img width="1181" height="573" alt="注册页面设计" src="https://github.com/user-attachments/assets/efb1cd19-6d87-49b2-a2bc-271636d900b8" />
<img width="1210" height="621" alt="首页设计" src="https://github.com/user-attachments/assets/2036d389-938a-4f6f-916c-709eecaaee41" />
<img width="1135" height="494" alt="商品详细页面设计" src="https://github.com/user-attachments/assets/0df1226e-e918-447a-8bb6-f9a375934818" />
<img width="659" height="456" alt="我的订单页面设计" src="https://github.com/user-attachments/assets/fc426f96-01d9-41c3-bbf9-b385f221c3de" />
<img width="1091" height="436" alt="支付页面设计" src="https://github.com/user-attachments/assets/226bd98a-d8fa-403e-bfd1-11603df68f77" />
<img width="659" height="323" alt="购物车设计" src="https://github.com/user-attachments/assets/6d3d7d7e-83c4-4f39-a7f0-16b96b2c80b2" />
<img width="938" height="596" alt="销量排行" src="https://github.com/user-attachments/assets/32dab24a-bf83-4082-aa23-b9f5a645a9a0" />


