# Spot Read · 聚读 — test builds

Spot Read focuses one sentence at a time while you read (highlight, bold, enlarge, underline), with keyboard navigation, auto-advance, read-aloud, a built-in PDF reader and favorites.

This repository only hosts **test builds** for Chrome / Edge. It contains no source code.

[中文说明在下方](#中文说明)

## Install (Chrome / Edge)

1. Download the latest build: **[spot-read-v0.12.10.zip](https://github.com/n2ywzt8hegodfiob/spot-read-test/raw/main/downloads/spot-read-v0.12.10.zip)** (older builds are in the [downloads](downloads) folder).
2. Unzip it into a folder you will keep (do not delete it afterwards; the browser loads the extension from that folder).
3. Open `chrome://extensions` (Edge: `edge://extensions`).
4. Turn on **Developer mode** (top right; in Edge, on the left).
5. Click **Load unpacked** and choose the unzipped folder (the one that contains `manifest.json`).
6. Pin the Spot Read icon in the toolbar. Open any article and press **Space** or **→** to move to the next sentence.

**Update:** download the new zip, replace the files in the same folder, then click the reload button on the Spot Read card in `chrome://extensions`. Refresh tabs that were already open.

**PDF files on your computer:** on the Spot Read card, click **Details** and turn on **Allow access to file URLs**.

## What's new in v0.12.10

- PDF reader no longer crashes when switching between original and text layout.
- No more "Extension context invalidated" errors in tabs left open after an update.

Feedback: assist@getspotread.com

## 中文说明

聚读会在你阅读时一次只突出一句话（高亮、加粗、放大、下划线），支持键盘逐句翻页、自动翻句、朗读、内置 PDF 阅读器和收藏。

这个仓库只放 Chrome / Edge 的**测试版安装包**，不含源码。

### 安装步骤

1. 下载最新版：**[spot-read-v0.12.10.zip](https://github.com/n2ywzt8hegodfiob/spot-read-test/raw/main/downloads/spot-read-v0.12.10.zip)**（旧版本在 [downloads](downloads) 文件夹里）。
2. 把它解压到一个会长期保留的文件夹（之后不要删除，浏览器从这个文件夹加载插件）。
3. 在地址栏打开 `chrome://extensions`（Edge 打开 `edge://extensions`）。
4. 打开右上角的「**开发者模式**」（Edge 在左侧）。
5. 点「**加载已解压的扩展程序**」，选择解压后的文件夹（里面有 `manifest.json` 的那一层）。
6. 把聚读图标固定到工具栏。打开任意一篇文章，按 **空格** 或 **→** 就能逐句往下读。

**更新：** 下载新版 zip，覆盖同一个文件夹里的文件，然后在 `chrome://extensions` 里点聚读卡片上的刷新按钮。之前已经打开的网页需要刷新一下。

**读本地 PDF：** 在聚读卡片上点「详情」，打开「允许访问文件网址」。

### v0.12.10 更新

- PDF 阅读器在原版和文字模式之间切换不再崩溃。
- 插件更新后，之前打开的网页不再报 "Extension context invalidated"。

反馈：assist@getspotread.com
