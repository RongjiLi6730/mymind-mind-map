<div align="center">

# 🧠 MyMind - 多维思维导图

### 功能强大的思源笔记思维导图插件

[📅 更新日志](https://github.com/RongjiLi6730/mymind-mind-map/blob/main/CHANGELOG.md) &nbsp; | &nbsp; [💬 问题反馈](https://github.com/RongjiLi6730/mymind-mind-map/issues) &nbsp; | &nbsp; [⭐ GitHub 仓库](https://github.com/RongjiLi6730/mymind-mind-map)

</div>

---

### 🤝 项目信息

| 项目 | 说明 |
| :--- | :--- |
| **项目地址** | [GitHub Repository](https://github.com/RongjiLi6730/mymind-mind-map) |
| **维护者** | RongjiLi6730 |
| **开源协议** | MIT License - **永久免费开源** |

---

### 🚀 核心功能

* **🌳 文档树思维导图**
    * 以思维导图形式展示整个工作空间的文档目录结构。
    * **快捷键**：`Alt+Q`

* **📄 文档思维导图**
    * 自动识别当前文档的标题层级（H1-H6），生成大纲导图。
    * **快捷键**：`Alt+W`

* **🔖 插入思维导图块**
    * 在文档中直接插入可交互的思维导图块。
    * **快捷键**：`Alt+E`

* **🔗 智能关联线**
    * 自动检测并显示文档间的引用关系（关联线由出链指向入链）。

* **📦 强大的导出功能**
    * 支持导出为 **PNG, SVG, PDF, Markdown, XMind, JSON**。
    * 支持 **ZIP 打包导出**（一次性下载所有图片和附件）。

* **🎨 主题自适应**
    * 自动适配思源笔记的亮色/暗色主题。

---

### 📖 使用指南

<details>
<summary><strong>📦 安装插件</strong></summary>

1. 在思源笔记插件市场中搜索 "MyMind" 或 "多维思维导图"。
2. 点击安装。
3. 安装完成后，顶栏会出现思维导图图标。
</details>

<details>
<summary><strong>🌳 查看工作空间结构</strong></summary>

* **快捷键**：`Alt+Q`
* **功能**：展示工作空间 -> 笔记本 -> 文档的完整层级。点击节点可直接跳转。
</details>

<details>
<summary><strong>📄 查看文档大纲</strong></summary>

* **快捷键**：`Alt+W`
* **功能**：将当前文档内容转为思维导图，根节点为标题，子节点为各级标题。
</details>

<details>
<summary><strong>⚙️ 导出与配置</strong></summary>

* **导出**：点击导图界面右上角的导出按钮，选择需要的格式（推荐使用 ZIP 打包以免图片丢失）。
* **配置**：支持设置默认展开层级（默认为 3 级）。
</details>

---

### 🛠️ 技术特性

> 本项目基于 [Simple-Mind-Map](https://github.com/wanglin2/mind-map) 渲染引擎开发。

* ✅ **轻量高效**：优化的节点渲染与 SQL 查询。
* ✅ **智能解析**：精准识别 Markdown 语法结构。
* ✅ **资源整合**：集成 JSZip，解决导出时图片路径丢失痛点。

---

### 🚀 更新日志 (Latest)

**📅 v1.0.4**
* 🐛 修复 XMind 导出图片问题。
* ✨ 优化导入导出界面交互。

**📅 v1.0.3**
* 🐛 修复嵌入块重新加载的 Bug。
* 🚀 引入智能节流机制，提升性能。

*(完整日志请查看 [CHANGELOG.md](https://github.com/RongjiLi6730/mymind-mind-map/blob/main/CHANGELOG.md))*
