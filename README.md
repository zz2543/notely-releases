# Notely

Notely 是一款本地 Markdown 桌面笔记应用，提供笔记编辑、搜索、专注模式、助手和空间。

**[下载最新版本](https://github.com/zz2543/notely-releases/releases/latest)** · [所有版本](https://github.com/zz2543/notely-releases/releases)

目前提供 macOS Apple Silicon（M 系列芯片）安装包。Windows 与 Intel Mac 安装包尚未发布。

## 安装

下载 Release 中的 `Notely-<版本>-arm64.dmg`，打开后将 Notely 拖到 Applications。当前版本未经过 Apple 公证；首次启动可在 Finder 右键选择“打开”，或前往“系统设置 → 隐私与安全性”允许。

## 校验下载

每个 Release 提供 `SHA256SUMS.txt`。将安装包与该文件放在同一目录，在终端运行：

```bash
shasum -a 256 -c SHA256SUMS.txt
```

## 关于本仓库

本仓库只用于分发 Notely 安装包和发布说明。Notely 源码未开源，不在本仓库中发布；页面上的 Source code 压缩包只包含下载说明，请下载安装包。第三方组件遵守各自的许可，相关许可随应用分发。

Notely © 2026 zhangzuhao. All rights reserved.
