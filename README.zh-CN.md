# Awesome Electrobun（精选清单）

[![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

一个关于 **Electrobun** 的精选资源清单：工具链、模板、UI 组件、示例、以及基于 Electrobun 构建的应用。

[English](./README.md) | 简体中文

- 欢迎 PR
- 每条尽量"一句话说明"
- 优先收录一手来源（官方文档/仓库）而非转载

## 目录

- [官方](#官方)
- [快速开始](#快速开始)
- [模板与脚手架](#模板与脚手架)
- [UI / 前端（Webview）](#ui--前端webview)
- [原生能力（系统集成）](#原生能力系统集成)
- [主进程 ↔ Webview 通信](#主进程--webview-通信)
- [自动更新与差分补丁](#自动更新与差分补丁)
- [打包、签名与公证](#打包签名与公证)
- [CI/CD 与发布自动化](#cicd-与发布自动化)
- [调试、性能分析与优化](#调试性能分析与优化)
- [测试](#测试)
- [AI / Claude Code 技能与插件](#ai--claude-code-技能与插件)
- [示例应用（开源）](#示例应用开源)
- [商业应用](#商业应用)
- [文章](#文章)
- [社区](#社区)
- [相关项目](#相关项目)
- [贡献指南](#贡献指南)
- [许可协议](#许可协议)

---

## 官方

- **Electrobun（GitHub）** — 核心项目仓库。https://github.com/blackboardsh/electrobun

## 快速开始

- **Quickstart** — 使用 `npx electrobun init` 初始化新应用。https://github.com/blackboardsh/electrobun

## 模板与脚手架

- **mattgi/electrobun-starter** — Bun + Vite + React + Tailwind + shadcn/ui 脚手架。https://github.com/mattgi/electrobun-starter
- **rajavijayach/catalyst-electrobun-boilerplate** — Monorepo 模板：Catalyst Web 应用 + Electrobun 桌面外壳（Bun），共享 RPC 类型和 CI 工作流。https://github.com/rajavijayach/catalyst-electrobun-boilerplate
- **context-assistant/electrobun-template** — Electrobun 模板仓库。https://github.com/context-assistant/electrobun-template
- **adam2am/sveltekit-electrobun** — Electrobun 最小化 SvelteKit 骨架：Svelte 5 (runes)、Vite HMR、adapter-static 预渲染。https://github.com/adam2am/sveltekit-electrobun
- **TB516/electrobun-svelte-template** — Svelte 5 模板，支持 Vite HMR 开发流程，用于 Electrobun 桌面应用。https://github.com/TB516/electrobun-svelte-template
- **jeffgca/electrobun-sveltekit-example** — 在 Electrobun 项目中运行 SvelteKit 的示例。https://github.com/jeffgca/electrobun-sveltekit-example
- **AlessandroSampaio/electrobun-solid-tailwind-template** — Electrobun 的 Solid + Tailwind 模板。https://github.com/AlessandroSampaio/electrobun-solid-tailwind-template
- **Ataraxy-Labs/electrobun-react-starter** — 功能完备的脚手架：React 19 + TanStack Router/Query + Tailwind CSS v4 + Vite 7，包含 Bun 后端和独立的 Shell RPC 与 Tab RPC 通道。https://github.com/Ataraxy-Labs/electrobun-react-starter
- **AugusDogus/create-electrobun-react** — Electrobun + React 脚手架模板（create-* 风格）。https://github.com/AugusDogus/create-electrobun-react
- **rmay1er/electrobun-counter-template** — 计数器模板。https://github.com/rmay1er/electrobun-counter-template
- **JakkeLab-AEC/electrobun-three-kit** — 3D 应用脚手架。https://github.com/JakkeLab-AEC/electrobun-three-kit

## UI / 前端（Webview）

- *(UI kits、组件库、shadcn/ui 集成、设计系统、主题包等。)*

## 原生能力（系统集成）

- **mayfer/electrobun-macos-native-blur** — macOS 毛玻璃效果（NSVisualEffectView）+ 红绿灯按钮对齐 + 阴影恢复，通过 Bun FFI 加载的轻量 Objective-C 桥接实现。https://github.com/mayfer/electrobun-macos-native-blur

- *(托盘/菜单、通知、文件对话框、deep link/协议处理、全局快捷键、剪贴板等。)*

## 主进程 ↔ Webview 通信

- **Ataraxy-Labs/agent-electrobun** — Electrobun 应用的 CDP 自动化 CLI，通过原生 WebSocket 连接（无自动导航），保留 shell/OOPIF 生命周期。https://github.com/Ataraxy-Labs/agent-electrobun

- *(RPC bridge、消息总线模式、类型安全 IPC、状态同步等。)*

## 自动更新与差分补丁

- **zig-bsdiff** — 基于 SIMD + zstd 的 bsdiff/bspatch；Electrobun 用于差分更新。https://blackboard.sh/blog/introducing-zig-bsdiff/

## 打包、签名与公证

- *(macOS 签名/公证、Windows 代码签名、Linux 打包等指南与工具。)*

## CI/CD 与发布自动化

- **wnix/nix-electrobun** — 用于开发和打包 Electrobun 应用的实验性 Nix flake。https://github.com/wnix/nix-electrobun

- *(GitHub Actions 工作流、发布工具、签名自动化、更新渠道策略等。)*

## 调试、性能分析与优化

- *(Devtools、崩溃上报、profiling、包体积、启动速度、内存优化等。)*

## 测试

- *(桌面应用 E2E、单元测试模式、UI golden test、CI 建议等。)*

## AI / Claude Code 技能与插件

- **recrsn/agent-skills** — 将 Electron 应用迁移到 Electrobun 的 Claude Code 插件。https://github.com/recrsn/agent-skills
- **rajavijayach/electrobun-skills** — 用于构建 Electrobun 桌面应用的专业技能。https://github.com/rajavijayach/electrobun-skills
- **marketcalls/electrobun-skill** — Electrobun 桌面应用的 Claude Code 技能（专注于算法交易）。https://github.com/marketcalls/electrobun-skill

## 示例应用（开源）

- **blackboardsh/electrobun-doom** — 在 Electrobun 上运行的经典 DOOM 游戏。https://github.com/blackboardsh/electrobun-doom
- **blackboardsh/audio-tts** — 文本转语音音频片段生成器（官方组织）。https://github.com/blackboardsh/audio-tts
- **blackboardsh/electrobun-dawn** — Electrobun 相关仓库（官方组织）。https://github.com/blackboardsh/electrobun-dawn
- **designxdevelop/electrobun-google-messages** — Google Messages Web 桌面包，支持持久化分区存储以保持登录状态。https://github.com/designxdevelop/electrobun-google-messages
- **ddv1982/suno-prompting** — Suno 桌面提示词构建工具：结构化字段（流派/BPM/情绪/乐器），支持通过 Ollama 的本地 LLM 模式和多种生成模式。https://github.com/ddv1982/suno-prompting
- **MinhOmega/git-account-switcher** — macOS 菜单栏应用，用于管理和切换多个 GitHub 账号。支持原子化更新 git 凭据、全局配置和 GitHub CLI 会话，并提供回滚功能。https://github.com/MinhOmega/git-account-switcher
- **radish-miyazaki/electrobun-simple-browser** — 简单浏览器示例应用。https://github.com/radish-miyazaki/electrobun-simple-browser
- **t1m0thyj/zowe-electrobun-sample** — Zowe SDK GUI 示例应用。https://github.com/t1m0thyj/zowe-electrobun-sample
- **DutchRican/electrobun-did-a-recruiter-look** — "did-a-recruiter-even-look" 想法的 Electrobun 重制版。https://github.com/DutchRican/electrobun-did-a-recruiter-look
- **lolrazh/clawrvis** — 始终在线的语音优先 AI 助手。https://github.com/lolrazh/clawrvis
- **kittechsix-blip/medkitt** — 离线优先的急诊医学工作流工具。https://github.com/kittechsix-blip/medkitt
- **khanhthanhdev/electrobun-rms** — Electrobun RMS（餐厅管理系统）应用。https://github.com/khanhthanhdev/electrobun-rms
- **lopadz/crate** — macOS 音频库浏览器，面向音乐制作人：即时播放 + 标签 + BPM/调性/LUFS 分析（SQLite）— 基于 Electrobun + React 构建。https://github.com/lopadz/crate
- **crander7/devlog** — 本地优先的生产力应用（会话/待办/笔记/习惯/番茄钟），支持托盘 + 可选 CLI；基于 Electrobun + React + SQLite (Drizzle) 构建。https://github.com/crander7/devlog
- **okikeSolutions/guerillaglass** — 开源创作者工作室（录制 → 编辑 → 交付），混合架构：Electrobun + React/Tailwind shell 和原生媒体引擎（macOS 上用 Swift；Windows/Linux 的 stub/原生实现进行中）。https://github.com/okikeSolutions/guerillaglass
- **openclaw-infra/clawflow-desk** — 基于 Electrobun 构建的超轻量级 AI CLI 配置管理器。https://github.com/openclaw-infra/clawflow-desk

## 商业应用

- *(如果你使用 Electrobun 发布了商业应用且希望被收录，欢迎提 PR；可选：一句话简介 + 官网链接。)*

## 文章

- **Electrobun Born, MCP Hits Chrome, Still Learning to Code** — 周刊 roundup，涵盖 Electrobun 发布内容。 https://dev.to/urbanisierung/electrobun-born-mcp-hits-chrome-still-learning-to-code-21b8 (2026年2月27日)
- **This Week In React #269** — React 周刊，推荐了 Electrobun。 https://dev.to/sebastienlorber/this-week-in-react-269-state-of-react-tanstack-nextjs-hermes-sparkling-yoga-interop-g7j (2026年2月20日)
- **JavaScript's Fragmentation Crisis: Innovation vs. Interoperability** — JavaScript 生态碎片化分析，包含 Electrobun。 https://dev.to/pratikmathur279/javascripts-fragmentation-crisis-innovation-vs-interoperability-4ak9 (2026年2月28日)

## 社区

- **Discord** — 社区讨论（主仓库 README 提供入口）。https://github.com/blackboardsh/electrobun
- **X（Twitter）** — @electrobun（主仓库 README 提供入口）。https://github.com/blackboardsh/electrobun

## 相关项目

- **Bun** — Electrobun 常用的 JavaScript runtime。https://bun.sh/
- **Zig** — Electrobun 生态中用于原生部分的系统语言。https://ziglang.org/

## 贡献指南

见 [CONTRIBUTING.md](./CONTRIBUTING.md)。

## 许可协议

在法律允许的范围内，本清单以 **CC0 1.0** 方式贡献至公有领域。见 [LICENSE](./LICENSE)。
