# GoLure 钓鱼 - 专业垂钓社区 App

<p align="center">
  <strong>一款专业的垂钓社区应用，分享钓点、交流技巧、记录渔获</strong>
</p>

---

## 📱 应用简介

**GoLure（鱼道）** 是一款面向钓鱼爱好者的综合型移动应用，提供钓点发现与分享、渔获记录、装备管理、钓鱼活动组织、社区交流等核心功能，帮助钓友更好地探索钓点、提升技巧、结识同好。

### 核心功能

- **钓点发现**：浏览附近钓点，查看详细位置、鱼种、水域类型、路况等信息
- **钓点分享**：发布私有/公开钓点，支持金币解锁优质钓点
- **渔获记录**：记录每次出钓的鱼种、重量、照片，形成个人钓鱼档案
- **装备管理**：管理钓竿、鱼饵等装备，记录使用情况
- **社区动态**：发布帖子、分享渔获、点赞评论、关注钓友
- **钓鱼活动**：创建/参与线下钓鱼活动，组队出钓
- **私信聊天**：与钓友私信交流，分享钓点与帖子
- **AI 助手**：智能钓鱼建议与技巧问答

### 技术特点

- **跨平台**：基于 React Native + Expo，支持 iOS、Android
- **高德地图**：集成高德/百度地图导航，一键到达钓点
- **实时通信**：WebSocket 即时消息与活动群聊

---

## 🛠️ 技术栈

| 模块 | 技术 |
|------|------|
| 前端 | React Native、Expo、TypeScript |
| 后端 | Go、Gin、PostgreSQL、Redis、Elasticsearch |
| 地图 | 高德地图、百度地图 |
| 存储 | MinIO 对象存储 |

---

## 📂 项目结构

```
goLure0128/
├── fishway-front/     # 移动端前端 (React Native + Expo)
├── fishway-backend/   # 后端服务 (Go + Gin)
└── README.md
```

---

## 🚀 快速开始

### 环境要求

- Node.js 18+
- Go 1.23+
- PostgreSQL
- Redis

### 前端运行

```bash
cd fishway-front
npm install
npm start
# 或
npm run ios     # iOS 模拟器
npm run android # Android 模拟器
```

### 后端运行

```bash
cd fishway-backend
# 配置 config/config.yaml 后
go run main.go
# 或使用 Makefile
make run
```

---

## 📥 下载

应用正在持续开发与优化中，即将上架 App Store 及各大应用市场，敬请期待。

---

## 📄 许可证

本项目为私有项目，版权所有。

---

## 📞 联系我们

如有问题或合作意向，欢迎通过 GitHub Issues 反馈。
