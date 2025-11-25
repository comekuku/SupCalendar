# SupCalendar
a calendar design by Gemini 3

# 📅 Super Calendar (超级日历)

一个极简主义、本地优先 (Local-First) 的个人时间管理工具。
**单文件架构，无后端，无数据库，数据完全隐私。**

[👉 点击在线使用](https://comekuku.github.io/SupCalendar/) 
*(请将上面的链接替换为你第四步生成的那个网址)*

## ✨ 核心功能

- **🎯 绝对居中视图**：打破传统日历限制，以“今天”为中心的时间流视图 (3周/2周/1周)。
- **⚡ 快捷任务指令**：一键生成未来 90 天的周期性任务（隔天/每周/工作日）。
- **🛡️ 重要任务顺延**：未完成的重要任务会自动“顺延”到第二天，直到完成为止。
- **🔒 数据绝对安全**：基于 LocalStorage，数据只保存在你的浏览器中。
- **📂 备份与恢复**：支持一键导出 JSON 备份，随时迁移数据。
- **🎨 电子手账体验**：支持上传封面图、插入图片/文件、自定义配色。

## 🚀 如何部署

### 方法一：直接使用
下载本仓库的 `index.html`，用 Chrome/Edge 浏览器打开即可。

### 方法二：Docker 部署 (NAS/软路由)
```bash
docker run -d --name calendar -p 8888:80 -v $(pwd)/index.html:/usr/share/nginx/html/index.html nginx:alpine

## Made with ❤️ by [comekuku]
