# Emoji Maker

This repo contains a simple demo page for creating image or text memes.

## Features
- Upload a local image
- Add editable text
- Export the canvas as a PNG file

## Quick Start

Follow these steps to try the demo locally:

1. **Install prerequisites**
   - [Node.js](https://nodejs.org/) (version 16+ is fine)
   - [Git](https://git-scm.com/)

2. **Clone the repository** and open a terminal in the project folder:
   ```bash
   git clone https://github.com/your-account/emoji-maker.git
   cd emoji-maker
   ```

3. **Launch a simple server** so the page can load local files. Choose either method:
   ```bash
   # Using Node.js
   npx serve . -p 5173
   # or using Python
   python3 -m http.server 5173
   ```

   Windows 用户也可以直接双击 `index.html` 打开浏览器，但使用本地服务器可避免权限限制。

4. **Open the demo** at `http://localhost:5173` (or直接打开文件)。

5. **Use the editor**
   - 点击 “上传” 选择图片
   - 点击 “添加文字” 输入并拖动文本
   - 完成后点击 “导出 PNG” 保存

这样即可在本地快速体验表情包制作流程。

