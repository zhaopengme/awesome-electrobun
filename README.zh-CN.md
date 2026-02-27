# Awesome Electrobun（精选清单）

一个关于 **Electrobun** 的精选资源清单：工具链、模板、UI 组件、示例、以及基于 Electrobun 构建的应用。

- 欢迎 PR
- 每条尽量“一句话说明”
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
- [示例应用（开源）](#示例应用开源)
- [商业应用](#商业应用)
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

- *(正在收集：React/Vite/Solid/Vue + Tailwind 等模板，欢迎提交 PR！)*

## UI / 前端（Webview）

- *(UI kits、组件库、shadcn/ui 集成、设计系统、主题包等。)*

## 原生能力（系统集成）

- *(托盘/菜单、通知、文件对话框、deep link/协议处理、全局快捷键、剪贴板等。)*

## 主进程 ↔ Webview 通信

- *(RPC bridge、消息总线模式、类型安全 IPC、状态同步等。)*

## 自动更新与差分补丁

- **zig-bsdiff** — 基于 SIMD + zstd 的 bsdiff/bspatch；Electrobun 用于差分更新。https://blackboard.sh/blog/introducing-zig-bsdiff/

## 打包、签名与公证

- *(macOS 签名/公证、Windows 代码签名、Linux 打包等指南与工具。)*

## CI/CD 与发布自动化

- *(GitHub Actions 工作流、发布工具、签名自动化、更新渠道策略等。)*

## 调试、性能分析与优化

- *(Devtools、崩溃上报、profiling、包体积、启动速度、内存优化等。)*

## 测试

- *(桌面应用 E2E、单元测试模式、UI golden test、CI 建议等。)*

## 示例应用（开源）

- **Audio TTS** — Electrobun 仓库中列出的示例应用。https://github.com/blackboardsh/electrobun
- **Co(lab)** — Electrobun 仓库中列出的另一个应用。https://github.com/blackboardsh/electrobun

## 商业应用

- *(如果你使用 Electrobun 发布了商业应用且希望被收录，欢迎提 PR；可选：一句话简介 + 官网链接。)*

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
