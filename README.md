<div align="center">

<img src="assets/icon.png" width="120" height="120" alt="灵剪图标" />

# ✂️ 灵剪 ClipNote

**macOS 灵动岛剪贴板管理工具**

复制过的东西，再也不用找第二次

[![下载](https://img.shields.io/badge/下载-灵剪.dmg-blue?style=for-the-badge)](https://funbox.chat)
[![macOS](https://img.shields.io/badge/macOS-14+-000000?style=for-the-badge&logo=apple&logoColor=white)](https://funbox.chat)
[![版本](https://img.shields.io/badge/版本-1.1.0-green?style=for-the-badge)](https://github.com/hanhang-han/clipnote/releases/latest)
[![Homebrew](https://img.shields.io/badge/Homebrew-Available-orange?style=for-the-badge&logo=homebrew&logoColor=white)](https://github.com/hanhang-han/homebrew-tap)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

[功能](#-特性) · [下载](#-下载安装) · [价格](#-版本对比) · [FAQ](#-常见问题) · [English](#english)

</div>

---

## ✨ 特性

| 功能 | 描述 |
|------|------|
| 🏝️ 灵动岛交互 | 鼠标移到屏幕顶部自动展开，离开自动收起，不占桌面空间 |
| 📋 菜单栏快捷访问 | 点击菜单栏图标，查看最近 15 条记录，搜索 + 一键复制 |
| 🔍 极速搜索 | 3 秒找到 3 天前复制的那段话 |
| 🏷️ 智能分类 | 自动识别 7 种内容类型：文本、链接、代码、富文本、Markdown、图片 |
| 📌 置顶收藏 | 重要内容置顶、收藏，随时快速访问 |
| 📤 多格式导出 | 一键导出为 TXT、JSON、Markdown，资料永不丢失 |
| ⌨️ 全局快捷键 | `⌘⇧V` 快速唤出，效率拉满 |
| 🔄 自动更新 | Sparkle 后台自动检查，始终保持最新版本 |

## 🖥️ 截图

<div align="center">
<img src="assets/hero.png" width="700" alt="灵剪主界面" />

<img src="assets/demo.gif" width="700" alt="灵动岛交互演示" />

<img src="assets/features.png" width="700" alt="功能展示" />

<img src="assets/comparison.png" width="700" alt="版本对比" />
</div>

## 🚀 下载安装

### 方式一：官网下载（推荐）

前往 [funbox.chat](https://funbox.chat) 下载 `灵剪.dmg`

### 方式二：GitHub Releases

前往 [Releases 页面](https://github.com/hanhang-han/clipnote/releases/latest) 下载最新版本

### 方式三：Homebrew 安装

```bash
brew install --cask hanhang-han/tap/clipnote
```

### 安装步骤

1. 双击打开 DMG → 将「灵剪」拖入「Applications」文件夹
2. 打开「灵剪」，允许辅助功能权限
3. 开始使用！

> 已通过 Apple 公证，双击安装无警告

## 💰 版本对比

| 功能 | 免费版 | Pro 版 |
|------|--------|--------|
| 剪贴板历史 | 100 条 | 500 条 |
| 灵动岛交互 | ✅ | ✅ |
| 菜单栏快捷访问 | ✅ | ✅ |
| 置顶和收藏 | ✅ | ✅ |
| 时间分组 | ✅ | ✅ |
| 全文搜索 | ❌ | ✅ |
| 智能分类筛选 | ❌ | ✅ |
| 便签功能 | ❌ | ✅ |
| 图片剪贴板 | ❌ | ✅ |
| 多格式导出 | ❌ | ✅ |
| 富文本还原 | ❌ | ✅ |
| 价格 | 免费 | **¥18 买断** |

## 🎁 限时免费领取 Pro

关注以下任一账号，私信即可免费获取 Pro 兑换码（价值 ¥18）：

- 📕 小红书：**秃头也要做开发**
- 𝕏 Twitter：[@jch47643085](https://x.com/jch47643085)

## 🛠️ 技术栈

- **语言**：Swift + SwiftUI
- **数据**：SwiftData
- **架构**：NSPanel + Dynamic Island UI
- **自动更新**：Sparkle 2
- **分发**：DMG + Apple Notarization + Homebrew
- **最低版本**：macOS 14.0 (Sonoma)

## 🏗️ 源码构建

```bash
# 克隆仓库
git clone https://github.com/hanhang-han/clipnote.git
cd clipnote

# 安装 xcodegen
brew install xcodegen

# 生成项目
xcodegen generate

# 用 Xcode 打开并构建
open ClipNote.xcodeproj
```

## ❓ 常见问题

<details>
<summary><strong>灵剪安全吗？会不会上传我的数据？</strong></summary>

所有数据仅存储在你的本地 Mac 上，灵剪不会联网上传任何内容。剪贴板数据完全由你自己掌控。
</details>

<details>
<summary><strong>和 Mac 自带剪贴板有什么区别？</strong></summary>

Mac 系统剪贴板只能记住最近 1 条复制内容。灵剪可以记住最多 500 条，并且自动识别内容类型进行智能分类。
</details>

<details>
<summary><strong>¥18 是订阅吗？</strong></summary>

不是订阅，一次性买断，永久使用所有 Pro 功能。
</details>

<details>
<summary><strong>支持哪些 macOS 版本？</strong></summary>

支持 macOS 14 (Sonoma) 及以上版本。推荐 macOS 15 (Sequoia) 以获得最佳灵动岛体验。
</details>

<details>
<summary><strong>安装时提示"已损坏"怎么办？</strong></summary>

灵剪已通过 Apple 公证，正常情况下不会出现此提示。如遇到，请在终端执行：
`xattr -cr /Applications/灵剪.app`
</details>

<details>
<summary><strong>如何更新灵剪？</strong></summary>

灵剪内置 Sparkle 自动更新，有新版本时会自动提醒。你也可以手动从 [GitHub Releases](https://github.com/hanhang-han/clipnote/releases/latest) 下载最新版。
</details>

---

## 📝 更新日志

### v1.1.0 (2026-05-25)
- 新增菜单栏快捷访问（最近 15 条 + 搜索 + 一键复制）
- 新增 Sparkle 自动更新
- 新增 Homebrew 安装支持
- 修复 17 项核心 Bug

### v1.0.0 (2026-05-22)
- 初始发布版本
- 灵动岛三态交互
- 智能分类、搜索、便签、导出

---

<div align="center">

**如果觉得灵剪好用，给个 ⭐ Star 支持一下！**

[![Star](https://img.shields.io/badge/⭐_Star-感谢支持-yellow?style=for-the-badge)](https://github.com/hanhang-han/clipnote)

</div>

---

<a id="english"></a>

## English

ClipNote is a macOS clipboard manager with a Dynamic Island UI. It automatically records everything you copy and lets you find it instantly.

**Features:**
- **Dynamic Island UI** — hover to expand, leave to collapse, zero desktop footprint
- **Menu Bar Quick Access** — click the menu bar icon to browse recent clips, search, and copy in one click
- **Smart Categorization** — auto-detects text, links, code, images, rich text, Markdown
- **Instant Search** — find anything in milliseconds
- **Sticky Note Preview** — click to preview without switching windows
- **Multi-format Export** — TXT, JSON, Markdown
- **Global Shortcut** — `⌘⇧V`
- **Auto Update** — Sparkle-powered background updates
- **Homebrew Install** — `brew install --cask hanhang-han/tap/clipnote`

**Download:** [funbox.chat](https://funbox.chat) · [GitHub Releases](https://github.com/hanhang-han/clipnote/releases/latest)

**Pricing:** Free (100 items) · Pro ¥18 one-time (500 items + all features)

**Requirements:** macOS 14.0 (Sonoma) or later

**Build from source:**
```bash
git clone https://github.com/hanhang-han/clipnote.git
cd clipnote && brew install xcodegen && xcodegen generate
open ClipNote.xcodeproj
```

**License:** MIT
