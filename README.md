# Claude Studio 增强版

Claude Studio 是基于 Claude Code CLI 的 Windows 桌面客户端。此仓库提供便携版程序包；它不是 Anthropic 官方客户端，也不隶属于 Anthropic。

## 下载与运行

从仓库文件列表下载 `Claude-Studio-增强版-便携包.zip` 并解压，然后运行 `claude-studio.exe`。电脑需要安装 Node.js 和 Claude Code CLI，并通过 Claude Code 登录你的 Claude 账号。程序不会把账号凭据或聊天记录打入压缩包。

如果电脑已运行旧版，请先从托盘菜单退出旧版，再启动解压目录中的 EXE。保留旧版文件夹作为备份；新版本会在当前 Windows 账户的本地 Studio 数据目录中读取会话与配置。

## 包含功能

- 使用官方 Claude Code 登录与额度，并展示官方五小时和每周使用情况。
- Projects、Artifacts、Scheduled、Customize、Skills/MCP 与 Chrome 集成入口。
- 官方对话导入：支持 Claude 导出的 ZIP 或 `conversations.json`；也支持扫描本机 Claude Code 历史。
- 对话搜索、查看和以近期消息为上下文续开会话。

官方聊天导出是本机导入的历史快照；继续对话会创建新的 Claude Code 会话，不会把记录写回 Claude 官方聊天列表。导出方法见 [Claude 官方说明](https://support.claude.com/en/articles/9450526-export-your-claude-data)。

## 系统要求

- Windows 10/11
- Node.js
- Claude Code CLI
- Claude 账号登录

完整操作请查看 `RELEASE_NOTES.md` 与随包说明。