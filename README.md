# Awesome Electrobun

[![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome **Electrobun** resources, tooling, templates, UI kits, examples, and apps.

English | [简体中文](./README.zh-CN.md)

- PRs welcome
- Keep descriptions short (one line)
- Prefer primary sources (official docs/repos) over reposts

## Contents

- [Official](#official)
- [Getting Started](#getting-started)
- [Templates & Starter Kits](#templates--starter-kits)
- [UI / Frontend (Webview)](#ui--frontend-webview)
- [Native Capabilities (OS Integration)](#native-capabilities-os-integration)
- [Main ↔ Webview Communication](#main--webview-communication)
- [Auto Update & Differential Patching](#auto-update--differential-patching)
- [Packaging, Signing & Notarization](#packaging-signing--notarization)
- [CI/CD & Release Automation](#cicd--release-automation)
- [Debugging, Profiling & Performance](#debugging-profiling--performance)
- [Testing](#testing)
- [AI / Claude Code Skills & Plugins](#ai--claude-code-skills--plugins)
- [Example Apps (Open Source)](#example-apps-open-source)
- [Commercial Apps](#commercial-apps)
- [Community](#community)
- [Related Projects](#related-projects)
- [Contributing](#contributing)
- [License](#license)

---

## Official

- **Electrobun (GitHub)** — Core project repository. https://github.com/blackboardsh/electrobun

## Getting Started

- **Quickstart** — Initialize a new app with `npx electrobun init`. https://github.com/blackboardsh/electrobun

## Templates & Starter Kits

- **mattgi/electrobun-starter** — Bun + Vite + React + Tailwind + shadcn/ui starter. https://github.com/mattgi/electrobun-starter
- **rajavijayach/catalyst-electrobun-boilerplate** — Monorepo template: Catalyst web app + Electrobun desktop shell (Bun) with shared RPC types and CI workflow. https://github.com/rajavijayach/catalyst-electrobun-boilerplate
- **context-assistant/electrobun-template** — Electrobun template repository. https://github.com/context-assistant/electrobun-template
- **adam2am/sveltekit-electrobun** — SvelteKit starter for Electrobun. https://github.com/adam2am/sveltekit-electrobun
- **TB516/electrobun-svelte-template** — Svelte template for Electrobun. https://github.com/TB516/electrobun-svelte-template
- **jeffgca/electrobun-sveltekit-example** — Example of running SvelteKit inside an Electrobun project. https://github.com/jeffgca/electrobun-sveltekit-example
- **AlessandroSampaio/electrobun-solid-tailwind-template** — Solid + Tailwind template for Electrobun. https://github.com/AlessandroSampaio/electrobun-solid-tailwind-template
- **Ataraxy-Labs/electrobun-react-starter** — Batteries-included starter: React 19 + TanStack Router/Query + Tailwind CSS v4 + Vite 7, with a Bun backend and separate Shell RPC vs Tab RPC channels. https://github.com/Ataraxy-Labs/electrobun-react-starter
- **AugusDogus/create-electrobun-react** — Starter template for Electrobun + React (create-* style). https://github.com/AugusDogus/create-electrobun-react
- **rmay1er/electrobun-counter-template** — Counter template. https://github.com/rmay1er/electrobun-counter-template
- **JakkeLab-AEC/electrobun-three-kit** — Boilerplate for 3D apps. https://github.com/JakkeLab-AEC/electrobun-three-kit

## UI / Frontend (Webview)

- *(UI kits, component libraries, shadcn/ui integrations, design systems, theme packs.)*

## Native Capabilities (OS Integration)

- **mayfer/electrobun-macos-native-blur** — macOS vibrancy (NSVisualEffectView) + traffic-light alignment + shadow restoration via a tiny Objective-C bridge loaded through Bun FFI. https://github.com/mayfer/electrobun-macos-native-blur

- *(Tray/menu, notifications, file dialogs, deep links/protocol handlers, global shortcuts, clipboard, etc.)*

## Main ↔ Webview Communication

- **Ataraxy-Labs/agent-electrobun** — CDP automation CLI for Electrobun apps that attaches via raw WebSocket (no auto-navigation), preserving the shell/OOPIF lifecycle. https://github.com/Ataraxy-Labs/agent-electrobun

- *(RPC bridges, message bus patterns, type-safe IPC, state sync.)*

## Auto Update & Differential Patching

- **zig-bsdiff** — SIMD + zstd powered bsdiff/bspatch; used by Electrobun for differential updates. https://blackboard.sh/blog/introducing-zig-bsdiff/

## Packaging, Signing & Notarization

- *(Guides and tooling for macOS signing/notarization, Windows code signing, Linux packaging.)*

## CI/CD & Release Automation

- *(GitHub Actions workflows, release tooling, signing automation, update channel strategies.)*

## Debugging, Profiling & Performance

- *(Devtools, crash reporting, profiling, bundle size, startup time, memory tuning.)*

## Testing

- *(E2E testing for desktop apps, unit testing patterns, golden UI tests, CI tips.)*

## AI / Claude Code Skills & Plugins

- **recrsn/claude-plugins** — Claude Code plugin to migrate Electron apps to Electrobun. https://github.com/recrsn/claude-plugins
- **rajavijayach/electrobun-skills** — Specialized skills for building desktop apps with Electrobun. https://github.com/rajavijayach/electrobun-skills
- **marketcalls/electrobun-skill** — Claude Code skill for Electrobun desktop apps (algo-trading focused). https://github.com/marketcalls/electrobun-skill

## Example Apps (Open Source)

- **blackboardsh/audio-tts** — Text-to-speech audio clip generator (official org). https://github.com/blackboardsh/audio-tts
- **blackboardsh/electrobun-dawn** — Electrobun-related repo (official org). https://github.com/blackboardsh/electrobun-dawn
- **designxdevelop/electrobun-google-messages** — Google Messages desktop wrapper. https://github.com/designxdevelop/electrobun-google-messages
- **ddv1982/suno-prompting** — Suno prompting desktop app (AI prompts). https://github.com/ddv1982/suno-prompting
- **radish-miyazaki/electrobun-simple-browser** — Simple browser example app. https://github.com/radish-miyazaki/electrobun-simple-browser
- **t1m0thyj/zowe-electrobun-sample** — Zowe SDK GUI sample app. https://github.com/t1m0thyj/zowe-electrobun-sample
- **DutchRican/electrobun-did-a-recruiter-look** — Electrobun remake of the "did-a-recruiter-even-look" idea. https://github.com/DutchRican/electrobun-did-a-recruiter-look
- **lolrazh/clawrvis** — Always-on voice-first AI assistant. https://github.com/lolrazh/clawrvis
- **kittechsix-blip/medkitt** — Offline-first Emergency Medicine workflow tool. https://github.com/kittechsix-blip/medkitt
- **lopadz/crate** — Desktop audio sample browser/analyzer. https://github.com/lopadz/crate
- **crander7/devlog** — Local/private productivity app (React + SQLite). https://github.com/crander7/devlog
- **okikeSolutions/guerillaglass** — Open-source creator studio workflow app (record → edit → deliver). https://github.com/okikeSolutions/guerillaglass
- **openclaw-infra/clawflow-desk** — Ultra-lightweight AI CLI configuration manager built with Electrobun. https://github.com/openclaw-infra/clawflow-desk

## Commercial Apps

- *(If you ship a commercial app with Electrobun and want it listed, open a PR — optional: include a short description and website link.)*

## Community

- **Discord** — Community chat (linked from the main repo). https://github.com/blackboardsh/electrobun
- **X (Twitter)** — @electrobun (linked from the main repo). https://github.com/blackboardsh/electrobun

## Related Projects

- **Bun** — JavaScript runtime often used with Electrobun. https://bun.sh/
- **Zig** — Systems language used for native parts in the Electrobun ecosystem. https://ziglang.org/

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).

## License

To the extent possible under law, this list is dedicated to the public domain under the **CC0 1.0** license. See [LICENSE](./LICENSE).
