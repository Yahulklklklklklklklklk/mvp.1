# 开源威胁情报智能分级搜索平台

这是一个面向毕业设计/课程设计场景的 MVP 项目，包含以下核心能力：

- 本地缓存优先检索
- 缓存失效后自动并行查询外部情报源
- 可插拔式情报源适配器
- 用户登录、角色控制、查询历史与审计日志
- Web 搜索页面与后台情报源管理
- 基于 MySQL 的数据持久化

## 默认账号

- 管理员：admin / admin123
- 分析员：analyst / analyst123

## 环境要求

- Python 3.10+
- MySQL 8.x

## 先创建数据库

```sql
CREATE DATABASE threat_intel_platform CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;