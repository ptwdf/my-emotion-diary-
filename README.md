# 🌱 情绪树洞 (Emotion Diary)

一个极简、治愈、且绝对安全的情绪记录本。

> 💡 **无需登录，无需服务器，你的数据只保存在你自己的设备里。**

<p align="center">
  <img alt="纯前端" src="https://img.shields.io/badge/纯前端-HTML%20%2F%20CSS%20%2F%20JS-C9B39F?style=flat-square" />
  <img alt="本地存储" src="https://img.shields.io/badge/数据存储-LocalStorage-B89B83?style=flat-square" />
  <img alt="PWA" src="https://img.shields.io/badge/PWA-可添加到主屏幕-9A93A0?style=flat-square" />
</p>

## ✨ 核心功能

- **18 种默认情绪 + 无限自定义**：涵盖开心、平静、满足、焦虑、悲伤等，支持新增、编辑、删除专属情绪。
- **一次记录可多选情绪**：更贴近真实复杂的心理状态，情绪太多时可“展开更多”。
- **纯本地存储 (localStorage)**：断网也能用，数据不上传服务器，绝对隐私。
- **原生 SVG 图表**：自动生成情绪占比环形图与次数明细柱状图，支持周统计 / 月统计。
- **情绪设置面板**：默认情绪可改图标（解决部分安卓机型表情显示异常）；自定义情绪可增删改，并支持“撤回”操作。
- **数据备份与恢复**：支持复制备份内容、导出 `.json` 文件、选择文件导入；导出后会保留文件列表，方便重复下载。
- **原生般体验**：支持添加到手机主屏幕（PWA），附带常见问题 FAQ 与隐私提示。

## 📸 界面预览

<p align="center">
  <img src="./screenshots/01-home.png" width="260" alt="情绪树洞主界面" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./screenshots/02-record.png" width="260" alt="记录此刻" />
</p>
<p align="center">
  <sub><b>极简治愈的主界面</b> · 每一天的情绪都有迹可循</sub>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <sub><b>记录此刻</b> · 支持多选情绪与快捷自定义</sub>
</p>

<br />

<p align="center">
  <img src="./screenshots/03-stats.png" width="260" alt="数据统计" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./screenshots/05-backup.png" width="260" alt="备份与恢复" />
</p>
<p align="center">
  <sub><b>原生 SVG 数据统计</b> · 情绪占比与明细一目了然</sub>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <sub><b>本地备份与恢复</b> · 数据安全掌握在自己手中</sub>
</p>

<br />

<p align="center">
  <img src="./screenshots/04-settings.png" width="260" alt="情绪设置" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./screenshots/06-custom.png" width="260" alt="新增自定义情绪" />
</p>
<p align="center">
  <sub><b>专属情绪设置面板</b> · 默认图标可换，支持撤回</sub>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <sub><b>无限扩展自定义情绪</b> · 命名与 Emoji 随心搭配</sub>
</p>

## 🚀 如何使用？

非常简单，不需要下载任何文件：

1. 在手机或电脑浏览器中打开：[点此访问情绪树洞](https://ptwdf.github.io/my-emotion-diary-/)
2. **iPhone 用户**：点击底部分享按钮 ⬆️ -> 选择“添加到主屏幕”。
3. **安卓用户**：点击右上角菜单 ⋮ -> 选择“添加到主屏幕”或“安装应用”。

## ⚠️ 数据安全提示

由于数据保存在浏览器本地（LocalStorage），**清理浏览器缓存、使用无痕模式或更换设备会导致数据丢失**。

建议定期使用页面右上角的 `☁️` 备份按钮导出数据：

- 备份文件中已包含你的**记录数据**与**自定义情绪设置**。
- 导入恢复是“全量覆盖”，导入前会弹出确认提示。
- 微信 / QQ 等内置浏览器可能拦截文件下载，建议使用 Safari / Chrome 打开本页，或使用弹窗中的“复制”按钮作为兜底方案。

## 🧩 技术栈

- 原生 HTML + CSS + JavaScript，无任何外部框架与 CDN 依赖。
- LocalStorage 本地持久化。
- 原生 SVG 绘制动态图表。
- PWA Manifest + Apple Touch Icon。

## 📬 联系与反馈

仍有问题或建议？欢迎联系：**2639805728@qq.com**

---
*Made with ❤️ and AI.*
