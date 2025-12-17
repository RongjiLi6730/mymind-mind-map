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
    * 根节点：工作空间名称 / 一级节点：笔记本 / 二级：文档。
    * **快捷键**：`Alt+Q`

* **📄 文档思维导图**
    * 自动识别当前文档的标题层级（H1-H6），生成大纲导图。
    * **快捷键**：`Alt+W`

* **🔖 插入思维导图块**
    * 在文档中直接插入嵌入式思维导图，实时渲染。
    * **快捷键**：`Alt+E`

* **🔗 智能关联线**
    * 自动检测并显示文档间的引用关系（关联线由出链指向入链）。
    * 工具栏可随时切换显示/隐藏。

* **📦 强大的导出功能**
    * 支持 **JSON, PNG, SVG, PDF, Markdown, XMind, TXT**。
    * **ZIP 打包**：一次性下载所有文件和图片（推荐）。
    * 支持去除 HTML 样式只保留纯文本。

* **🎨 主题自适应**
    * 自动适配思源笔记的亮色/暗色主题。

---

### 📖 使用指南

<details>
<summary><strong>📦 安装插件</strong></summary>

1. 在思源笔记插件市场中搜索 "MyMind" 或 "多维思维导图"。
2. 点击安装按钮完成插件安装。
3. 安装完成后，顶栏会出现思维导图图标。
</details>

<details>
<summary><strong>🌳 使用文档树思维导图</strong></summary>

* **触发方式**：`Alt+Q` 或点击顶栏图标。
* **功能**：展示整个工作空间的文档层级结构。点击节点可跳转到对应文档。
</details>

<details>
<summary><strong>📄 使用文档思维导图</strong></summary>

* **触发方式**：打开文档后按 `Alt+W`。
* **功能**：将当前文档内容以思维导图形式展示，帮助快速了解大纲。
</details>

<details>
<summary><strong>⚙️ 配置与导出</strong></summary>

* **配置**：设置默认展开层级（默认为 3）。
* **导出**：点击右上角导出按钮。推荐使用 ZIP 打包，解决图片路径问题。
</details>

---

### 🛠️ 技术特性

* **轻量级引擎**：使用 [Simple-Mind-Map](https://github.com/wanglin2/mind-map) 渲染引擎。
* **高性能**：优化的节点渲染和 SQL 查询。
* **智能解析**：自动识别 Markdown 标题层级结构。
* **关联线功能**：基于 AssociativeLine 插件逻辑。

---

### 🚀 更新日志

**📅 v1.0.4**
* 🐛 修复 XMind 导入后保存图片的问题，支持 base64 图片自动上传。
* ✨ 优化导入导出选项顺序。
* ✨ 移除 Markdown 导入功能（建议使用官方导入）。

**📅 v1.0.3**
* 🐛 修复嵌入思维导图块重新加载的问题。
* 🚀 增加智能节流机制，防止重复加载。

**📅 v1.0.2**
* ✨ 新增"启用调试日志"选项（默认关闭），提升性能。
* 🐛 修复内存泄漏问题。

*(详细日志请查看 [CHANGELOG.md](https://github.com/RongjiLi6730/mymind-mind-map/blob/main/CHANGELOG.md))*
