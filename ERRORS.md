# ERRORS.md - 错误记录

记录每次翻车经历，避免重犯同类错误。

---

## 2026-03-17

### 错误1：PinchTab API 路由错误
- **问题**：使用 /api/navigate 返回 404
- **原因**：PinchTab 导航 API 路由不正确
- **解决方案**：需要查找正确的 API 文档

### 错误2：Gateway Token 配置问题
- **问题**：Chrome Relay 扩展连接失败
- **原因**：Token 不匹配、端口配置错误（25295 vs 18792）
- **解决方案**：生成新 Token 并重启 Gateway

---

*更新于 2026-03-17*
