<p align="center">
  <img src="assets/local-html-editor-logo.svg" width="96" height="96" alt="local-html-editor logo">
</p>

<h1 align="center">local-html-editor</h1>

<p align="center">面向产品、运营和品牌团队：不用写代码，直接可视化修改 AI 生成的本地 HTML 页面。</p>

<p align="center">
  <img alt="Chrome Extension" src="https://img.shields.io/badge/Chrome-Extension-0075DE?style=flat-square">
  <img alt="Local HTML" src="https://img.shields.io/badge/Local-HTML-F6F5F4?style=flat-square&labelColor=31302E">
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.ko.md">한국어</a> ·
  <a href="README.es.md">Español</a>
</p>

<p align="center">
  <img src="assets/local-html-editor-demo.gif" width="960" alt="local-html-editor 可视化编辑演示">
</p>

---

## 它解决什么问题

`local-html-editor` 让非技术用户不用打开代码编辑器，也能直接修改 AI 生成或本地 HTML 页面。用 Chrome 打开本地 `.html` 文件，进入编辑模式后，可以直接修改文案、图片、链接和排版，再导出干净的 HTML 或 ZIP。

它适合 AI 生成的单文件 HTML、活动页、落地页、Newsletter、简历、产品原型、品牌稿和内部文档。

## 用户能得到什么

- 直接在渲染后的 HTML 页面上改文案。
- 修改下划线、高亮、文字颜色、背景色、字号、行高、对齐、链接和图片。
- 把剪贴板图片粘贴到当前光标位置。
- 保持原有远程图片 URL 不变。
- 导出单 HTML，或导出 `index.html + assets/` ZIP。
- 自动保存草稿，同一文件最多保留 10 个历史版本。
- 使用清晰、克制的图标编辑栏。

## 功能概览

| 模块 | 内容 |
| --- | --- |
| 编辑 | 支持本地 `file://` HTML 可视化编辑 |
| 工具栏 | 图标按钮，hover 显示释义 |
| 文字 | 4-128 字号下拉并支持手输、行高、加粗、斜体、下划线、删除线 |
| 排版 | 水平对齐下拉框，表格/图片/区块垂直对齐 |
| 图片 | 插入、替换、缩放、剪贴板粘贴 |
| 颜色 | 深到浅预置色块 + RGB 取色 |
| 格式刷 | 全部格式、文字样式、颜色与高亮、仅文字颜色、仅高亮、仅对齐 |
| 自动保存 | 实时草稿保存，并显示保存状态 |
| 历史 | 保存、关页、跨天、恢复前生成快照 |
| 主题 | 自动跟随浏览器明暗模式 |
| 语言 | 根据浏览器语言切换英文、中文、日文、韩文、西班牙文 |

## 下载

[下载插件 ZIP](releases/local-html-editor-extension.zip)。

## 安装

1. 下载插件 ZIP。
2. 解压下载后的 ZIP 文件。
3. 打开 `chrome://extensions`。
4. 开启“开发者模式”。
5. 点击“加载已解压的扩展程序”。
6. 选择解压后的插件文件夹。
7. 在扩展详情页开启“允许访问文件网址”。

## 使用

1. 用 Chrome 打开本地 `.html` 文件。
2. 点击页面右侧悬浮编辑按钮。
3. 用顶部工具栏修改文字、颜色、链接、对齐和图片。
4. 需要加图时，直接从剪贴板粘贴到光标处。
5. 点击保存图标导出 HTML，点击归档图标导出 ZIP。
6. 在历史中预览、导出或恢复版本。
