# 青禾 AI 修图

Windows 上的 Photoshop AI 图片工作助手。本仓库用于发布安装包和更新说明。

[下载最新安装包](https://github.com/rumolukuriza-bot/qinghe-ai-releases/releases/latest)

## 安装

需要 Windows 10/11 x64、Photoshop 24.2 或更新版本，以及 Creative Cloud。

1. 等生成、保存、回贴任务完成，保存文档并退出 Photoshop，关闭旧版青禾悬浮条。
2. 从 Releases 下载名称以 `qinghe-ai-studio-` 开头、以 `-windows-x64.exe` 结尾的安装包并运行。
3. 等待 Adobe 插件安装结束，按提示确认，然后打开青禾。
4. 在 Photoshop 插件菜单打开青禾面板，连接独立悬浮条；首次使用填写自己的 API 平台设置。

运行环境已内置，不需要另装 Node.js。`Source code` 下载项是本发布仓库的说明文件，使用插件请下载 EXE 附件。

## 在线更新

从 1.4.1 开始，桌面启动器通过本仓库提供版本检查和下载更新。更新前保存并退出 Photoshop，程序不会替你强行关闭文档。下载包使用签名清单和 SHA-256 校验。

旧版用户（包括曾安装 1.4.0 候选版的用户）需手动安装一次 1.4.1 或更高版本，之后可使用软件内的更新入口。网络失败时仍可使用当前版本，稍后重试或从本页手动下载。

API 设置、图片和历史保存在用户自己的电脑上。不要分享自己的 API 密钥或运行数据目录。

## 反馈

反馈时请附版本号、Windows/Photoshop 版本和错误文字，不要提交 API 密钥、配对令牌或含个人信息的完整日志。
