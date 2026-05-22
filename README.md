# 💫 About Me

嗨，我是 Charles，一名來自台灣的軟體開發者，現經營 [YuDefine 域定資訊工作室](https://github.com/YuDefine)，主要經營中小企業客製化數位轉型專案開發。以 **Nuxt 生態系 + Supabase + Cloudflare** 為主軸，搭配 **VoidZero 生態系**（Vite / Vitest / Rolldown / OXC）的 Rust-based 工具鏈，從前端延伸到後端（Supabase、Go）、邊緣部署、自建基礎設施（Proxmox），以及 AI 協作開發工作流的設計。曾為 Google Developer Groups (GDG) on Campus NYUST 2023–2024 核心成員，積極參與開源社群活動。

Hi, I'm Charles — a software developer from Taiwan running [YuDefine](https://github.com/YuDefine), a studio focused on customized digital transformation projects for small and medium businesses. I build primarily on the **Nuxt ecosystem + Supabase + Cloudflare**, powered by the **VoidZero ecosystem** (Vite / Vitest / Rolldown / OXC) Rust-based toolchain — extending into backend (Supabase, Go), edge deployment, self-hosted infrastructure (Proxmox), and AI-assisted development workflow design. Former core member of Google Developer Groups (GDG) on Campus NYUST 2023–2024, and an active contributor to open-source communities.

- 🏢 經營 **[YuDefine 域定資訊工作室](https://github.com/YuDefine)** — 中小企業客製化數位轉型專案
- ✍️ 在 **[blog.charlestw.dev](https://blog.charlestw.dev)** 記錄 Nuxt / Vue / AI 協作開發實踐
- 🤖 **Claude Code** 重度使用者 — 自建跨專案共用 AI 配置中央倉模板 [`clade-template`](https://github.com/YuDefine/clade-template)，含自訂 commands / agents / hooks / skills
- 📐 所有專案採 **Spec-Driven Development (SDD) + TDD** 工作流

---

# 🧠 How I Build

- **AI 協作為主軸** — 與 Claude Code 全流程協作，從 spec → tests → impl → review；自建中央倉模板 [clade-template](https://github.com/YuDefine/clade-template) 散播配置到 N 個 consumer 專案
- **Spec-Driven Development** — 先寫規格、可驗證的 acceptance criteria，再下手寫程式
- **Test-Driven Development** — Vitest unit + Playwright E2E
- **文件至上** — 每個 repo 都有詳盡 README、ADR 與 onboarding guide
- **VoidZero 生態系** — 已從 webpack / ESLint / Prettier 全面遷移到 Vite、Vitest、Rolldown、OXLint、OXFmt 等 Rust-based 工具鏈，持續追蹤 vite-plus、rolldown-vite 等下一代方案

---

# 💻 Tech Stack

### 🎯 Core Stack
> Nuxt 生態系 + Supabase + Cloudflare — 所有專案的預設組合

<img src="https://skills-icons.vercel.app/api/icons?i=nuxtjs,vuejs,tailwind,supabase,postgres,cloudflare" alt="nuxt, vue, tailwind, supabase, postgres, cloudflare" />

### 🔤 Languages
<img src="https://skills-icons.vercel.app/api/icons?i=ts,js,go,python,cpp,bash" alt="ts, js, go, python, cpp, bash" />

### 🎨 Frontend
<img src="https://skills-icons.vercel.app/api/icons?i=vuejs,nuxtjs,tailwind,vitepress" alt="vue, nuxt, tailwind, vitepress" />

### ⚙️ Backend & Database
<img src="https://skills-icons.vercel.app/api/icons?i=nodejs,go,supabase,postgres,drizzle" alt="node, go, supabase, postgres, drizzle" />

### ☁️ Edge / Cloud
<img src="https://skills-icons.vercel.app/api/icons?i=cloudflare,gcloud,aws,azure" alt="cloudflare, gcloud, aws, azure" />

### 🧰 Tooling
> **VoidZero ecosystem** · 套件管理 · CI/CD

<img src="https://skills-icons.vercel.app/api/icons?i=vite,vitest,pnpm,bun,docker,githubactions" alt="vite, vitest, pnpm, bun, docker, github actions" />

![Rolldown](https://img.shields.io/badge/Rolldown-FF3E00?style=flat-square&logo=rolldown&logoColor=white)
![OXC](https://img.shields.io/badge/OXC-A78BFA?style=flat-square&logo=rust&logoColor=white)
![OXLint](https://img.shields.io/badge/OXLint-A78BFA?style=flat-square&logo=rust&logoColor=white)
![OXFmt](https://img.shields.io/badge/OXFmt-A78BFA?style=flat-square&logo=rust&logoColor=white)

### 🧪 Testing
<img src="https://skills-icons.vercel.app/api/icons?i=vitest,playwright" alt="vitest, playwright" />

### 🖥️ Infrastructure
<img src="https://skills-icons.vercel.app/api/icons?i=proxmox,docker,linux" alt="proxmox, docker, linux" />

### 💾 OS
<img src="https://skills-icons.vercel.app/api/icons?i=windows,macos,linux" alt="windows, macos, linux" />

---

# 🚀 Featured Projects

### YuDefine 域定資訊工作室

| Project | Stack | Description |
| --- | --- | --- |
| 🌱 [**nuxt-supabase-starter**](https://github.com/YuDefine/nuxt-supabase-starter) | Nuxt 4 · Supabase · Claude Code | Nuxt + Supabase 快速開發範本，含 AI 輔助工作流（SDD + TDD） |
| 🔌 [**web-nfc-bridge**](https://github.com/YuDefine/web-nfc-bridge) | Go · Nuxt 4 · PC/SC | 瀏覽器 NFC 讀寫橋接器，跨平台安裝包 (.pkg/.msi/.deb) |
| 🧠 [**clade-template**](https://github.com/YuDefine/clade-template) | Claude Code · Template | 自建多專案 AI 配置中央倉模板（rules / plugins / hooks / skills），含投影層治理與 sanitization layer |
| 🛡️ [**mac-mem-guard**](https://github.com/YuDefine/mac-mem-guard) | Shell | Mac Mini M4 16GB 全局記憶體保護套件，針對 Claude Code SSH 開發環境 |
| 🤖 [**nuxt-edge-agentic-rag**](https://github.com/YuDefine/nuxt-edge-agentic-rag) | Nuxt · Cloudflare | Nuxt edge-native agentic RAG |
| 🎬 [**swc-movie-box-office-analysis**](https://github.com/YuDefine/swc-movie-box-office-analysis) | Nuxt 4 · Python | 陽光女子合唱團台灣票房分析儀表板 |

### 個人專案

- 📝 [**blog**](https://github.com/Charles5277/blog) — VitePress + Tailwind 技術部落格
- 🎙️ [**AIinterviewer**](https://github.com/Charles5277/AIinterviewer) — Nuxt + Gemini + TensorFlow.js AI 面試官
- 📑 [**VitePress-Theme-API-Docs**](https://github.com/Charles5277/VitePress-Theme-API-Docs) — VitePress + OpenAPI 文件主題

---

# 📊 GitHub Stats

<p>
  <img height="180" src="https://github-readme-streak-stats.herokuapp.com/?user=Charles5277&theme=midnight-purple&hide_border=false" />
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=Charles5277&theme=midnight-purple&hide_border=false&show_icons=true&count_private=true" />
</p>

---

# 📫 Contact

- 📧 [charles@yudefine.com.tw](mailto:charles@yudefine.com.tw)
- 🌐 [blog.charlestw.dev](https://blog.charlestw.dev)
- 🏢 [YuDefine 域定資訊工作室](https://github.com/YuDefine)
