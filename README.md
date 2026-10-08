# Vant Agent Releases

Vant Agent Windows x64 安装包与版本说明的公开发布仓库。源码在独立私有仓库中维护，此处不包含源码历史。

[查看最新版本与下载安装包](https://github.com/kevlns/VantAgent-Releases/releases/latest)

## 检查更新

公开发布源不需要 GitHub Token。若旧版 Vant 检查更新显示 404，在桌面用户数据目录的 `update-feed.json` 中设置：

```json
{
  "provider": "github",
  "owner": "kevlns",
  "repo": "VantAgent-Releases"
}
```

Windows 当前默认位置为 `%APPDATA%\@vant\desktop\update-feed.json`。保存后重新点击“检查并更新”。也可以从 Release 下载安装包，退出 Vant 后按安装向导升级。

本仓的版本标签用于标识安装包版本，不对应私有源码仓库的提交历史。
