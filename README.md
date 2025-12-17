<div align="center">

# 🧠 MyMind - Multi-dimensional Mind Map

### Powerful mind map plugin for SiYuan Note

[📅 Changelog](https://github.com/RongjiLi6730/mymind-mind-map/blob/main/CHANGELOG.md) &nbsp; | &nbsp; [💬 Feedback](https://github.com/RongjiLi6730/mymind-mind-map/issues) &nbsp; | &nbsp; [⭐ GitHub](https://github.com/RongjiLi6730/mymind-mind-map)

</div>

---

### 🤝 Project Information

| Item | Description |
| :--- | :--- |
| **Repository** | [GitHub Repository](https://github.com/RongjiLi6730/mymind-mind-map) |
| **Maintainer** | RongjiLi6730 |
| **License** | MIT License - **Permanently Free & Open Source** |

---

### 🚀 Core Features

* **🌳 Document Tree Mind Map**
    * Visualize the entire workspace document structure as a mind map.
    * Root: Workspace / Level 1: Notebooks / Level 2+: Documents.
    * **Shortcut**: `Alt+Q`

* **📄 Document Mind Map**
    * Display current document content structure (H1-H6) as a mind map.
    * **Shortcut**: `Alt+W`

* **🔖 Insert Mind Map Block**
    * Embed a mind map directly inside a document with real-time rendering.
    * **Shortcut**: `Alt+E`

* **🔗 Document Association Lines**
    * Automatically display reference lines between documents (from source to target).
    * Visibility can be toggled via the toolbar.

* **📦 Powerful Export Features**
    * Supports **JSON, PNG, SVG, PDF, Markdown, XMind, TXT**.
    * **ZIP Packaging**: Downloads all files and images at once (Recommended).
    * Option to remove HTML styles and keep plain text only.

* **🎨 Theme Adaptive**
    * Automatically adapts to SiYuan's light/dark theme.

---

### 📖 User Guide

<details>
<summary><strong>📦 Install Plugin</strong></summary>

1. Search for "MyMind" or "Multi-dimensional Mind Map" in the SiYuan plugin marketplace.
2. Click the install button.
3. After installation, the mind map icon will appear in the top bar.
</details>

<details>
<summary><strong>🌳 Use Document Tree Mind Map</strong></summary>

* **Trigger**: Press `Alt+Q` or click the top bar icon.
* **Feature**: View the entire workspace hierarchy. Click nodes to jump to documents.
</details>

<details>
<summary><strong>📄 Use Document Mind Map</strong></summary>

* **Trigger**: Open a document and press `Alt+W`.
* **Feature**: Quickly visualize the outline and structure of the current note.
</details>

<details>
<summary><strong>⚙️ Configuration & Export</strong></summary>

* **Config**: Set default expand levels (Default: 3).
* **Export**: Click the export button in the UI. **ZIP packaging** is recommended to ensure images are saved correctly.
</details>

---

### 🛠️ Technical Features

* **Lightweight Engine**: Built on [Simple-Mind-Map](https://github.com/wanglin2/mind-map).
* **High Performance**: Optimized node rendering and SQL queries.
* **Intelligent Parsing**: Automatically recognizes Markdown heading hierarchy.
* **Smart References**: Intelligent detection of block-level references.

---

### 🚀 Changelog (Latest)

**📅 v1.0.4**
* 🐛 Fixed XMind import image saving (supports base64 upload to assets).
* ✨ Optimized import/export option order.
* ✨ Removed Markdown import (users should use SiYuan's native import).

**📅 v1.0.3**
* 🐛 Fixed embedded mind map block reload issues.
* 🚀 Added intelligent throttling to prevent duplicate loading.

**📅 v1.0.2**
* ✨ Added "Enable Debug Log" option (default: off) for better performance.
* 🐛 Fixed memory leaks by removing excessive logging.

*(For the full history, please see [CHANGELOG.md](https://github.com/RongjiLi6730/mymind-mind-map/blob/main/CHANGELOG.md))*
