# Pake App Collection

一个使用 [Pake](https://github.com/tw93/Pake) 框架构建的跨平台应用集合，将常用的网页应用打包成原生桌面应用。

## 📦 项目介绍

Pake 是一个基于 Tauri 的框架，可以轻松地将任何网页应用转换为原生桌面应用。本项目利用 Pake 构建了多个实用的应用程序。

## 🎯 包含的应用

查看[构建命令](./构建命令.md)了解每个应用的具体构建方式。
该项目包含以下应用程序：

| 应用          | 说明                      | 官方网站                  | 下载                                                                                            |
| ------------- | ------------------------- | ------------------------- | ----------------------------------------------------------------------------------------------- |
| Bilibili      | B站客户端                 | https://www.bilibili.com  | [下载 DMG](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/Bilibili.dmg)        |
| ChatGPT       | ChatGPT 网页版应用        | https://chatgpt.com       | [下载 DMG](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/ChatGPT.dmg)         |
| DevDocs       | DevDocs 开发文档浏览器    | https://devdocs.io        | [下载 DMG](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/DevDocs.dmg)         |
| Diagrams      | Diagrams.net 在线绘图工具 | https://www.diagrams.net  | [下载 DMG](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/Diagrams.dmg)        |
| Douyin        | 抖音客户端                | https://www.douyin.com    | [下载 DMG](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/Douyin.dmg)          |
| Excalidraw    | Excalidraw 白板绘图工具   | https://excalidraw.com    | [下载 DMG](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/Excalidraw.dmg)      |
| Gemini        | Google Gemini AI 应用     | https://gemini.google.com | [下载 DMG](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/Gemini.dmg)          |
| GitHub        | GitHub 网页版应用         | https://github.com        | [下载 DMG](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/GitHub.dmg)          |
| Google Docs   | Google 文档               | https://docs.google.com   | [下载 DMG](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/Google%20Docs.dmg)   |
| Google Keep   | Google Keep 笔记应用      | https://keep.google.com   | [下载 DMG](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/Google%20Keep.dmg)   |
| Google Sheets | Google 表格               | https://sheets.google.com | [下载 DMG](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/Google%20Sheets.dmg) |
| Google Slides | Google 幻灯片             | https://slides.google.com | [下载 DMG](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/Google%20Slides.dmg) |
| Notion        | Notion 笔记工具           | https://notion.so         | [下载 ZIP](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/Notion.app.zip)      |
| TikTok        | TikTok 客户端             | https://www.tiktok.com    | [下载 ZIP](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/TikTok.app.zip)      |
| 腾讯视频      | 腾讯视频客户端            | https://v.qq.com          | [下载 ZIP](https://github.com/genwilliam/Pake-app/releases/download/v1.0.0/tengxun.app.zip)     |

## 🛠 技术栈

- **Pake** - 基于 Tauri 的跨平台应用框架
- **Node.js** - v22（见 mise.toml）
- **Tauri** - Rust 和 Web 技术的完美结合

## 📋 前置要求

- macOS 10.13+ / Windows 7+ / Linux
- Node.js v22 或更高版本
- Rust（如果需要从源代码构建）

## 📂 项目结构

```
Pake-app/
├── README.md           # 项目文档
├── .gitignore         # Git 忽略文件
├── mise.toml          # mise 配置文件
├── *.dmg              # macOS 安装包
├── *.app.zip          # 应用程序压缩包
└── ...                # 其他应用文件
```

## 📄 关于 DMG 和 APP 文件

- **DMG 文件**：macOS 磁盘镜像格式，可直接在 macOS 上使用
- **APP.ZIP 文件**：应用程序压缩包，需要解压后使用

## 🔧 配置 Pake

详情请参考 [Pake 官方文档](https://github.com/tw93/Pake)。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📝 许可证

本项目遵循 MIT 许可证。

## 🔗 相关资源

- [Pake 官方仓库](https://github.com/tw93/Pake)
- [Tauri 文档](https://tauri.app/)
- [mise 项目](https://mise.jdx.dev/)

## 💡 常见问题

### Q: 如何打开已构建的应用？

A:

- macOS: 双击 .dmg 文件，或解压 .app.zip 后在应用程序中打开
- Windows: 运行对应的 .exe 文件
- Linux: 运行对应的可执行文件

### Q: 需要网络连接吗？

A: 是的，这些应用都需要网络连接以访问对应的网页服务。

---

**最后更新**: 2026年2月1日
