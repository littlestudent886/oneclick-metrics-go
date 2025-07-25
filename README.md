# OneClick Metrics Exporter (Go)

## 📌 项目简介

OneClick Metrics Exporter 是一个使用 Go 编写的服务，用于从 PostgreSQL 数据库中定时采集 Pull Request（PR）相关指标，并通过 Prometheus 暴露 `/metrics` 接口，供监控系统使用。

## 🚀 功能说明

- 定时从数据库中采集 PR 状态、报告覆盖率等指标
- 使用 Prometheus 客户端注册并暴露指标
- 支持标签化指标（如 project、pr_state、report 等）
- 可配置采集间隔、数据库连接信息、日志等级等
