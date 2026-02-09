# ServerPlayerDataBase

Mindustry 客户端模组，用于本地采集与查询玩家数据库。

## 功能

- 采集玩家 PID / UID / IP / 名称 / 服务器历史
- 可选记录聊天并按 UID 查询
- 支持数据库完整性元数据校验（sha256-spdb-v1）
- 支持 UID 工具：按 UID 合并、手动填充空 UID、手动合并两个 UID
- 提供 OverlayUI 轻量查询窗口与独立设置查询窗口

## 下载

请在 Release 页面下载 `.jar` 产物：

- `ServerPlayerDataBase-<version>.jar`
- `ServerPlayerDataBase-<version>-android.jar`

## 说明

- 本仓库用于发布构建产物与 Release 配置。
- 发布时会自动生成带更新日志的 GitHub Release。
