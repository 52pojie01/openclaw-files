# 📁 OpenClaw Files

连接 OpenClaw Gateway 的 Web 文件管理器。

## 功能

- 📂 目录浏览和导航
- 🔍 文件搜索和过滤
- 📄 文件内容预览（代码、文本、配置文件）
- ✏️ 新建文件和目录
- 📋 文件信息显示
- ⚡ 快捷访问常用目录
- 🖼️ 网格/列表双视图模式
- 📊 目录大小计算
- 💾 磁盘空间查看

## 使用

1. 浏览器打开 `index.html`
2. 默认连接 `http://192.168.1.5:18789`
3. 通过左侧快捷访问或顶部路径栏导航

## 快捷目录

| 图标 | 目录 |
|------|------|
| 🦞 | OpenClaw 配置目录 |
| 💼 | Workspace 工作目录 |
| 🧠 | Memory 记忆目录 |
| 🎯 | Skills 技能目录 |
| 📀 | Samba 共享文件 |
| 🗂️ | /tmp 临时文件 |

## 支持预览的文件类型

- 代码：Python, JavaScript, HTML, CSS, Shell
- 配置：JSON, YAML, ENV, CONF
- 文档：Markdown, TXT, LOG
- 其他：SVG

## 技术栈

- 纯前端 HTML/CSS/JS
- Gateway dir_list / file_fetch / file_write API
- Gateway exec API
- 响应式布局
