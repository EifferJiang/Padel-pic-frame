# Henkel Padel Tournament · 照片边框生成器
 
Photo frame maker for the 2026 Henkel Padel Tournament. Choose a template, add your photos, and save a finished image to share.
 
2026 Henkel Padel Tournament 参赛照片边框工具：选择模板、放入照片，一键生成可分享的图片。
 
**在线使用 / Live site:** https://eifferjiang.github.io/Padel-pic-frame/
 
---
 
## 功能 Features
 
- 5 套模板，其中既有单张照片，也有多窗口拼图（倾斜、圆形、网格）
- 支持一次选择多张照片，按顺序自动放入各个窗口
- 在画面中直接拖动照片调整位置；滚轮、双指或滑块缩放；方向键微调
- 输出高清图片（JPG 或 PNG，长边约 3000 像素）
- 电脑和手机浏览器均可使用，无需安装或注册
## 使用方法 How to use
 
1. 打开上面的网址，在顶部选择一套模板。
2. 点击 **选择照片**（多窗口模板可一次选多张），或直接点画面中的窗口放入照片。
3. 拖动照片调整位置，用滑块放大缩小；点击不同窗口可分别调整。
4. 点击 **生成图片**，电脑上点下载按钮，手机上长按图片保存到相册。
## 隐私 Privacy
 
所有照片只在你自己的浏览器中处理，不会上传到任何服务器。
Photos are processed entirely in your browser and are never uploaded.
 
## 项目结构 Structure
 
```
index.html      页面与全部交互逻辑（单文件，无外部依赖）
assets/         模板图片：背景层、前景层、各窗口蒙版、缩略图
```
 
这是一个纯静态网站，由 GitHub Pages 直接托管，没有构建步骤。
 
## 更新模板 Updating
 
替换 `assets/` 中的图片或 `index.html`，提交到 `main` 分支后，GitHub Pages 会在一两分钟内自动更新。
 
## 浏览器要求 Requirements
 
最新版 Chrome、Edge、Safari 或 Firefox。需要通过网址（https）访问，直接双击本地的 `index.html` 打开时，生成图片的功能无法使用。
 
## 联系 Contact
 
如有问题或建议，请在本仓库提交 Issue。
