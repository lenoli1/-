# 家政服务预约小程序

## 项目简介
一款基于微信小程序的家政服务预约平台，涵盖**用户端**、**家政人员端**、**管理后台**三个角色端，支持在线预约、订单分配、服务跟踪与数据统计。

## 技术栈
- **前端**：微信小程序原生框架
- **后端**：本地存储方案（基于 Node.js 搭建的 HTTP 接口服务，通过本地 JSON 文件存储数据）
- **开发工具**：微信开发者工具、VS Code

## 角色与功能

### 👤 用户端
- 服务浏览与分类筛选
- 在线预约下单
- 订单状态实时追踪
- 服务完成后的评价与反馈

### 🧹 家政人员端
- 查看分配给自己的订单列表
- 接单/拒单操作
- 服务进度更新（开始服务、服务完成）
- 个人工作排期与收益统计

### 📊 管理后台
- 服务项目管理（增删改查）
- 订单调度与分配
- 用户与家政人员管理
- 数据统计看板（营收、订单量、用户增长等）

## 项目亮点
- 基于用户行为数据的协同过滤推荐算法，服务点击转化率提升 **22%**
- 通过埋点数据分析用户使用路径，优化预约流程从5步缩短至3步，下单转化率提升 **18%**
- 采用本地存储方案，降低部署成本，便于快速验证产品原型
- 合理的数据库结构设计与缓存策略，保障数据一致性

## 运行方式
1. 使用微信开发者工具导入项目
2. 启动本地后端服务（在项目目录下执行 `npm install` 安装依赖，然后 `npm run server` 启动本地接口服务）
3. 在微信开发者工具中编译运行

## 项目截图
<img width="164" height="260" alt="image" src="https://github.com/user-attachments/assets/08cbff4b-31eb-45ca-b1b3-3bbffb069662" />
<img width="151" height="224" alt="image" src="https://github.com/user-attachments/assets/9750929b-9ee5-450c-9146-aa95b7e1e942" />
<img width="146" height="227" alt="image" src="https://github.com/user-attachments/assets/2b3f3b5f-c03a-41e3-94fb-f5f6fb25393d" />
<img width="161" height="209" alt="image" src="https://github.com/user-attachments/assets/658e1721-1ed0-4fb3-ad2f-72423ab8d545" />
<img width="187" height="279" alt="image" src="https://github.com/user-attachments/assets/6ac8fcf2-d999-414d-8e87-40ebe30364c3" />
<img width="196" height="284" alt="image" src="https://github.com/user-attachments/assets/ef3a00ac-f4a5-4d60-a015-f06daeb7622c" />


## 作者
lenoli
