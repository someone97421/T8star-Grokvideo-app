# Grok 视频生成器 (Grok Video Generator)

一个现代化的 Web 前端界面，专为视频生成模型（如 Grok 或类似 API）设计。支持文生视频、图生视频，并具备高度交互性的图片管理与提示词编辑功能。

A modern web interface designed for video generation models (like Grok or similar APIs). It supports Text-to-Video and Image-to-Video generation with highly interactive image management and prompt editing features.

## 🌟 主要特性 (Key Features)

* **双模式支持**：自动检测文生视频 (Text-to-Video) 和图生视频 (Image-to-Video) 模式。
* **智能提示词编辑器**：支持通过 `@` 符号快速引用已上传的图片（Mention 机制），并以 Chip 标签形式展示。
* **多图槽管理**：提供多个图片槽位，支持点击上传、拖拽上传以及剪贴板粘贴 (`Ctrl+V`)。
* **双主题系统**：内置精心设计的“深色夜间模式”和“白绿日间模式”，支持跟随系统自动切换。
* **配置管理**：支持 API 密钥、端点地址的本地保存、导入与导出。
* **历史记录与预览**：自动记录生成历史，支持视频/图片的点击放大预览。

---

## 🚀 核心功能展示 (Core Functionalities)

### 1. 自动模式检测 (Automatic Mode Detection)

系统会根据提示词中是否包含图片引用（Chips）自动判断生成模式。
The system automatically detects the generation mode based on whether image references (Chips) are included in the prompt.

### 2. 交互式提示词 (Interactive Prompts)

* **@ 引用**：在编辑器中输入 `@` 即可弹出图片选择面板。
* **可视化标签**：引用的图片会转化为可点击的标签，增强提示词的可读性。

### 3. 便捷的图片处理 (Convenient Image Handling)

* **粘贴支持**：直接从网页或软件截图并粘贴到槽位。
* **拖拽支持**：支持将本地文件直接拖入指定槽位。

---

## 🛠️ 技术栈 (Technology Stack)

* **HTML5 & CSS3**：采用现代 CSS 变量实现动态主题。
* **Tailwind CSS**：用于快速构建响应式布局和优雅的 UI。
* **Native JavaScript**：纯原生 JS 处理逻辑，无重型框架负担，响应迅速。
* **Lucide/SVG Icons**：高精度的矢量图标。

---

## 📥 快速开始 (Quick Start)

1. **打开项目**：直接在浏览器中打开 `index.html` 即可运行。
**Open Project**: Simply open `index.html` in your browser to run the application.
2. **配置 API**：
* 点击“设置与配置”展开抽屉。
* 输入您的 API 地址 (Endpoint) 和 API Key。
* 点击“保存配置”。
**Configure API**:
* Click "Settings & Configuration" to expand the drawer.
* Enter your API Endpoint and API Key.
* Click "Save Configuration".


3. **开始生成**：上传图片、编写提示词，点击“立即生成”即可开启视频创作。
**Start Generating**: Upload images, write prompts, and click "Generate Now" to start your video creation.

---

## 📄 许可证 (License)

本项目仅供个人学习与研究使用。
This project is for personal learning and research purposes only.
