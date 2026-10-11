# Obsidian-Quartz-Notes

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Raisetsu41/Obsidian-Quartz-Notes)

> MES 工程師在職筆記 — 基於 Obsidian + Quartz 5 + Vercel 的個人知識庫。
>
> 線上筆記舊網址：[https://popjoker.github.io/obsidian-notes/](https://popjoker.github.io/obsidian-notes/)
>
> 線上筆記新網址：[https://mesengobsidiannote.vercel.app/](https://mesengobsidiannote.vercel.app/)

[中文](#中文) | [English](#english)

---

## 中文

### 關於這個筆記庫

這是我在擔任 **MES 工程師** 期間的個人筆記庫，用來記錄工作上遇到的技術細節、系統開發紀錄、專案規劃與學習心得。內容以製造執行系統（MES）相關的實務經驗為主，也涵蓋周邊的開發技術與工具。

前一個筆記網站：[Maverick's Online Note](https://popjoker.github.io/obsidian-notes/)

### 特性

- **Obsidian 原生寫作** — 所有筆記在 Obsidian 中編輯，享受雙向連結、圖譜、插件生態
- **Quartz 5 渲染** — 將 Markdown 筆記轉化為美觀的靜態網站
- **Vercel 一鍵部署** — 免費、自動 HTTPS、全球 CDN
- **自有域名支持** — 內建 CNAME 插件
- **雙模式配色** — 亮色/暗色模式，自動切換，配色和諧
- **LaTeX 公式** — KaTeX 渲染，學術筆記無壓力
- **關係圖譜** — 可視化筆記之間的連接
- **全文搜尋** — 快速定位內容
- **RSS / Sitemap** — SEO 友善
- **Obsidian Git 自動備份** — 筆記自動同步到 GitHub
- **豐富的測試內容** — 開箱即用的範例筆記，展示全部功能

### 快速開始

1. 點擊上方的 **Deploy with Vercel** 按鈕
2. 按提示創建你自己的 Git 倉庫
3. Vercel 自動構建並部署
4. 克隆倉庫到本地，用 Obsidian 打開 `blog/content` 資料夾（它就是 Obsidian 庫根目錄）
5. 安裝推薦插件，開始寫作！

詳細步驟請見 [SETUP.md](./SETUP.md)。

### 目錄結構

```
Obsidian-Quartz-Notes/
├── blog/                    # 🏗️ Quartz 5 引擎 + 你的筆記
│   ├── content/             # 📝 你的筆記（Obsidian 庫根目錄，直接編輯這裡）
│   │   ├── .obsidian/       #   Obsidian 配置（本地，不提交到 git）
│   │   ├── index.md         #   筆記首頁
│   │   ├── demo-showcase.md #   功能展示頁（全功能測試）
│   │   ├── demo-math.md     #   數學公式測試
│   │   ├── demo-i18n.md     #   多語言測試
│   │   ├── 01-Courses/      #   課程筆記（含示例）
│   │   ├── 03-Music/        #   音樂筆記（含示例）
│   │   ├── 04-Templates/    #   Templater 模板（不發布）
│   │   ├── 05-Languages/    #   語言學習
│   │   ├── 06-Katex/        #   數學公式測試頁
│   │   └── 07-Futures/      #   功能測試頁
│   ├── quartz.config.default.yaml  # 博客配置
│   ├── quartz/styles/custom.scss   # 自定義樣式
│   └── static/              #   靜態資源
├── vercel.json              # Vercel 部署配置
├── README.md                # 本文件
└── SETUP.md                 # 詳細設置指南
```

### 客製化

| 項目 | 修改位置 |
|------|----------|
| 博客標題 | `blog/quartz.config.default.yaml` → `pageTitle` |
| 域名 | `blog/quartz.config.default.yaml` → `baseUrl` |
| 配色 | `blog/quartz.config.default.yaml` → `colors` |
| 字體 | `blog/quartz.config.default.yaml` → `typography` |
| 背景圖 | 放 `album-cover.jpg` 到 `blog/static/`，取消 `custom.scss` 中的註釋 |
| 頁腳連結 | `blog/quartz.config.default.yaml` → footer 插件 |

### 技術棧

- [Obsidian](https://obsidian.md) — 知識庫 / 筆記編輯器
- [Quartz 5](https://quartz.jzhao.xyz) — Markdown 靜態站點生成器
- [Vercel](https://vercel.com) — 託管 & 自動部署
- [Templater](https://github.com/SilentVoid13/Templater) — Obsidian 模板引擎
- [Obsidian Git](https://github.com/Vinzent03/obsidian-git) — 自動 Git 備份

### 許可

MIT License — 自由使用、修改、分發。

---

## English

### About This Vault

This is my personal knowledge base kept during my time as an **MES Engineer**. It documents technical details, system development logs, project planning, and learning notes from work — primarily hands-on experience with Manufacturing Execution Systems (MES) and related development technologies.

Previous note site: [Maverick's Online Note](https://popjoker.github.io/obsidian-notes/)

### Features

- **Obsidian-Native Writing** — Edit all notes in Obsidian with backlinks, graph view, and plugin ecosystem
- **Quartz 5 Rendering** — Transform Markdown notes into a beautiful static website
- **One-Click Vercel Deploy** — Free, automatic HTTPS, global CDN
- **Custom Domain** — Built-in CNAME plugin
- **Dual-Mode Color Scheme** — Light/dark mode with harmonious palettes
- **LaTeX Math** — KaTeX rendering for academic notes
- **Knowledge Graph** — Visualize connections between notes
- **Full-Text Search** — Find content instantly
- **RSS / Sitemap** — SEO-friendly
- **Auto Git Backup** — Notes synced to GitHub automatically
- **Rich Demo Content** — Ready-to-use sample notes showcasing all features

### Quick Start

1. Click the **Deploy with Vercel** button above
2. Follow the prompts to create your own Git repository
3. Vercel builds and deploys automatically
4. Clone the repo locally and open `blog/content` as an Obsidian vault
5. Install recommended plugins, start writing!

For detailed instructions, see [SETUP.md](./SETUP.md).

### Customization

| Item | Where to Modify |
|------|-----------------|
| Blog Title | `blog/quartz.config.default.yaml` → `pageTitle` |
| Domain | `blog/quartz.config.default.yaml` → `baseUrl` |
| Colors | `blog/quartz.config.default.yaml` → `colors` |
| Fonts | `blog/quartz.config.default.yaml` → `typography` |
| Background | Place `album-cover.jpg` in `blog/static/`, uncomment in `custom.scss` |
| Footer Links | `blog/quartz.config.default.yaml` → footer plugin |

### Tech Stack

- [Obsidian](https://obsidian.md) — Knowledge base / note editor
- [Quartz 5](https://quartz.jzhao.xyz) — Markdown static site generator
- [Vercel](https://vercel.com) — Hosting & auto-deployment
- [Templater](https://github.com/SilentVoid13/Templater) — Obsidian template engine
- [Obsidian Git](https://github.com/Vinzent03/obsidian-git) — Automatic Git backup

### License

MIT License — Free to use, modify, and distribute.

---

> 靈感來自 [Quartz](https://quartz.jzhao.xyz) 和無數優秀的數字花園。
> Inspired by [Quartz](https://quartz.jzhao.xyz) and countless beautiful digital gardens.