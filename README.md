# ByteCheck

> *注：本文档由 AI 辅助生成*

- ByteCheck 是一个基于 Golang + React 开发的多人每日打卡管理系统。
- 采用前后端分离架构
- 后端使用 Golang 提供高性能的 API 服务
- 前端使用 React + Vite 构建现代化的用户界面
- 管理员可以发布打卡任务，用户参与打卡并查看排行榜

## 功能特点

### 管理员功能
- 管理员登录
- 创建和管理打卡任务
- 设置打卡任务规则（每日打卡次数要求）
- 查看所有用户的打卡情况
- 数据统计和导出

### 用户功能
- 用户注册和登录
- 查看当前可参与的打卡任务
- 进行每日打卡
- 查看个人打卡历史
- 查看打卡排行榜
- 响应式设计，支持移动端和桌面端

## 技术栈

### 后端
- Golang
- Gin (Web 框架)
- GORM (ORM 框架)
- JWT (身份认证)
- MySQL (数据库)
- Redis (缓存)

### 前端
- React 18
- Vite
- TailwindCSS
- React Router
- React Query
- Axios

## 开发环境设置

1. 克隆项目