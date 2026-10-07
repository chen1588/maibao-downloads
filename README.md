# 迈宝 PPT 转视频工具 · 下载页

本仓库只放两样东西：

1. **下载页** —— `index.html`（纯静态，用 GitHub Pages 开）
2. **软件本体** —— `MBppt2video.exe` / `MBppt2video-gui.exe`（放在 Releases 里）

页面上的下载按钮指向本仓库的 `releases/latest`，所以**只要在 Releases 里发新版本，页面不用改**，
除了「当前版本」那行字和文件大小要顺手更新。

## 改哪里

| 要改的东西 | 在哪 |
|---|---|
| 下载地址里的仓库名 | `index.html` 里两处 `releases/latest/download/...` |
| 当前版本号 / 日期 | `index.html` 里 `class="verline"` 那行 |
| 文件大小 | `index.html` 下载表格里两处 |
| SHA256 | `index.html` 里折叠块 `<details>` 内 |

## 目录

```
index.html          下载页（单页，无外部依赖）
assets/             品牌 Logo、图标
screenshots/        界面截图
```

> 页面不依赖任何外部 CDN，离线也能看。
