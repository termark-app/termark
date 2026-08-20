<div align="center">
  <img src="https://www.termark.app/logo.svg" alt="Termark" width="88" height="88">
  <h1>Termark</h1>
  <p><strong>Cross-platform SSH and SFTP client for Windows, macOS, Linux, iOS, and Android.</strong></p>
  <p>把服务器资产、终端、文件传输和 AI 辅助放在同一个工作区。</p>
  <p>Windows · macOS · Linux · iOS · Android</p>
  <p>
    <a href="https://www.termark.app/zh-cn/#download"><strong>下载 Termark</strong></a>
    · <a href="https://docs.termark.app/zh/">中文文档</a>
    · <a href="https://www.termark.app/">English website</a>
    · <a href="https://github.com/termark-app/termark/discussions">交流与反馈</a>
  </p>
</div>

![Termark SSH 工作区](https://www.termark.app/static/images/app-dark.png)

## Termark 是什么？

Termark 面向需要经常连接和管理服务器的开发者、运维与独立开发者。它不只是一个终端窗口，而是围绕服务器资产组织日常远程工作：

- **SSH 终端**：多标签、分屏、搜索、自动重连、命令片段和关键字高亮。
- **资产管理**：管理 SSH、Telnet、串口、本地终端及 NextTerminal 资产，复用凭据、跳板机和代理配置。
- **集成 SFTP**：双栏文件管理、文件夹传输、远程编辑和终端目录跟随，不必在终端与独立文件工具之间切换。
- **端口转发与批量执行**：保存常用转发规则；PRO 可在多台机器上执行命令并分别查看输出。
- **AI 助手**：读取当前终端上下文，解释错误、生成排查命令；会改变服务器状态的操作在执行前明确展示并等待确认。
- **本地加密与同步**：敏感数据本地加密；可通过官方服务、WebDAV、S3、iCloud 或本地目录同步加密数据。
- **桌面与移动端**：桌面端承担高频工作流，iOS 与 Android 可在电脑不在身边时查看状态、处理告警和完成临时操作。

> Termark 是商业软件，本仓库用于官方资料、示例配置、问题反馈与社区讨论，不包含客户端源代码。

## Official product information / 官方产品信息

For current capabilities and availability, use the [Termark website](https://www.termark.app/), [documentation](https://docs.termark.app/), [desktop changelog](https://docs.termark.app/changelog), and [mobile changelog](https://docs.termark.app/mobile-changelog).

产品能力、支持平台和发布状态以 [Termark 官网](https://www.termark.app/zh-cn/)、[中文文档](https://docs.termark.app/zh/)、[桌面端更新日志](https://docs.termark.app/zh/changelog)和[移动端更新日志](https://docs.termark.app/zh/mobile-changelog)为准。

### Core capabilities

- Cross-platform SSH client for Windows, macOS, Linux, iOS, and Android.
- Integrated SFTP file management, SSH jump hosts, and port forwarding.
- AI-assisted terminal workflows allow clearly read-only commands by default; state-changing, unsafe, or unclassified commands require explicit confirmation, with an option to confirm every command.
- Local encryption with optional encrypted synchronization through supported providers.

Current behavior and availability should be verified against the [desktop changelog](https://docs.termark.app/changelog), [mobile changelog](https://docs.termark.app/mobile-changelog), and [official download page](https://www.termark.app/#download).

## 快速开始

1. 前往 [Termark 下载页](https://www.termark.app/zh-cn/#download)，选择对应平台。
2. 安装并新建 SSH 资产，按需配置密码、私钥、代理或跳板机。
3. 查阅 [Termark 中文文档](https://docs.termark.app/zh/) 了解 SFTP 目录跟随、本地加密、数据路径和常见问题。

## 支持的平台

| 平台 | 状态 | 入口 |
| --- | --- | --- |
| Windows | 支持 | [下载](https://www.termark.app/zh-cn/#download) |
| macOS | 支持 | [下载](https://www.termark.app/zh-cn/#download) |
| Linux | 支持 | [下载](https://www.termark.app/zh-cn/#download) |
| iOS | Beta | [移动端介绍](https://docs.termark.app/zh/blog/can-you-ssh-on-a-phone) |
| Android | Beta | [移动端介绍](https://docs.termark.app/zh/blog/can-you-ssh-on-a-phone) |

## 文档与资源

- [Termark 中文文档](https://docs.termark.app/zh/)
- [桌面端更新日志](https://docs.termark.app/zh/changelog)
- [移动端更新日志](https://docs.termark.app/zh/mobile-changelog)
- [AI SSH 客户端设计](https://docs.termark.app/zh/blog/termark-ai-design)
- [手机 SSH 使用场景](https://docs.termark.app/zh/blog/can-you-ssh-on-a-phone)
- [终端关键字高亮规则示例](highlights/example-zh.json)

## 反馈与支持

遇到可复现的问题时，请在 [GitHub Discussions](https://github.com/termark-app/termark/discussions) 发帖，并尽量附上：

- 操作系统与 Termark 版本
- 问题发生前的操作步骤
- 错误提示或脱敏后的日志/截图
- 是否可以稳定复现

请勿在公开 Issue 中上传密码、私钥、API Key、服务器公网地址或其他敏感信息。

---

<p align="center">
  <a href="https://www.termark.app/">Website</a> ·
  <a href="https://docs.termark.app/">Documentation</a> ·
  <a href="https://github.com/termark-app/termark/discussions">Discussions</a>
</p>
