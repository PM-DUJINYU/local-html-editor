<p align="center">
  <img src="assets/local-html-editor-logo.svg" width="96" height="96" alt="local-html-editor logo">
</p>

<h1 align="center">local-html-editor</h1>

<p align="center">
  For product, marketing, and brand teams: edit AI-generated local HTML visually without touching code.
</p>

<p align="center">
  <img alt="Chrome Extension" src="https://img.shields.io/badge/Chrome-Extension-0075DE?style=flat-square">
  <img alt="Local HTML" src="https://img.shields.io/badge/Local-HTML-F6F5F4?style=flat-square&labelColor=31302E">
  <img alt="Version 0.2.0" src="https://img.shields.io/badge/v-0.2.0-615D59?style=flat-square">
</p>

<p align="center">
  <a href="README.zh-CN.md">简体中文</a> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.ko.md">한국어</a> ·
  <a href="README.es.md">Español</a>
</p>

<p align="center">
  <img src="assets/local-html-editor-demo.gif" width="960" alt="local-html-editor visual editing demo">
</p>

---

## What It Does

`local-html-editor` helps non-technical teams edit generated HTML pages without opening a code editor. Open a local `.html` file in Chrome, enter edit mode, change copy, images, links, and layout directly on the rendered page, then export a clean HTML file or a ZIP package.

It is useful for AI-generated single-file HTML, landing pages, newsletters, campaign pages, resumes, product mockups, brand drafts, and internal documents.

## Why Use It

- Change page copy directly on the rendered HTML.
- Adjust underline, highlight, text color, background color, font size, line height, alignment, links, and images.
- Paste clipboard images into the cursor position.
- Keep existing remote image URLs unchanged.
- Export as one HTML file or as `index.html + assets/`.
- Keep autosaved drafts and up to 10 history snapshots per file.
- Work with a clean, focused editing toolbar.

## Highlights

| Area | Details |
| --- | --- |
| Editing | WYSIWYG editing for local `file://` HTML pages |
| Toolbar | Icon-only toolbar with hover tooltips |
| Typography | Font size dropdown with direct numeric entry from `4` to `128`, line height, rich text styles |
| Layout | Horizontal alignment dropdown and vertical alignment for tables, images, and blocks |
| Images | Insert, replace, resize, and paste images from the clipboard |
| Colors | Deep-to-light preset swatches plus RGB picker |
| Format painter | Paste all formatting, text style, colors, text color, highlight, or alignment |
| Autosave | Live draft saving with visible status |
| History | Save, close-page, day-change, and pre-restore snapshots |
| Theme | Automatic light/dark mode from browser theme |
| Languages | English, Chinese, Japanese, Korean, and Spanish UI |

## Download

[Download the extension ZIP](releases/local-html-editor-extension.zip).

## Install

1. Download the extension ZIP.
2. Unzip the downloaded file.
3. Open `chrome://extensions`.
4. Enable **Developer mode**.
5. Click **Load unpacked**.
6. Select the unzipped extension folder.
7. Open extension details and enable **Allow access to file URLs**.

## Use

1. Open a local `.html` file in Chrome.
2. Click the floating edit button on the right side of the page.
3. Use the top toolbar to edit text, formatting, colors, links, alignment, and images.
4. Paste an image from your clipboard at the cursor position when needed.
5. Click the save icon to export HTML, or the archive icon to export ZIP.
6. Open History to preview, export, or restore a previous version.

## Boundaries

- Local `file://` HTML only.
- No online webpage editing.
- No direct source-file overwrite; exports go through the browser save/download flow.
- No automatic folder creation next to the source HTML.
- No Git automation.
