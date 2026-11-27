<div align="center">

# eatingDream Antigravity Plugins

**Fast, local-first desktop & browser tools with live, zero-flicker panels for AI coding agents.**

[Suite Home](https://eatingdream.dev) · [AI Digest](https://ai.dreamsi.cc) · [GitHub Org](https://github.com/eatingDream-antigravity-plugins)

</div>

## Plugin Suite

| Plugin | Repository | What It Does | Links |
| :--- | :--- | :--- | :--- |
| **Context Radar** | [`context-radar`](https://github.com/eatingDream-antigravity-plugins/context-radar) | Spot why an Antigravity turn slowed down, inspect cache hit rates, and keep long chats lean before compacting | [Site](https://contextradar.eatingdream.dev) · [Releases](https://github.com/eatingDream-antigravity-plugins/context-radar/releases) |
| **Clam Guard** | [`clam-guard`](https://github.com/eatingDream-antigravity-plugins/clam-guard) | Keep MacBooks fast and cool with the lid closed, adjust built-in brightness safely, and verify screen locks | [Site](https://clamguard.eatingdream.dev) · [Releases](https://github.com/eatingDream-antigravity-plugins/clam-guard/releases) |
| **Remote Cast** | [`remote-cast`](https://github.com/eatingDream-antigravity-plugins/remote-cast) | Stream and control local browser tabs smoothly over weak networks with adaptive frame rates and standby keep-alive | [Site](https://remotecast.eatingdream.dev) · [Releases](https://github.com/eatingDream-antigravity-plugins/remote-cast/releases) |
| **Colab Deck** | [`colab-deck`](https://github.com/eatingDream-antigravity-plugins/colab-deck) | Monitor Google Colab GPU/TPU runtimes, compute units, and kernel runs from one live control panel | [Site](https://colabdeck.eatingdream.dev) · [Releases](https://github.com/eatingDream-antigravity-plugins/colab-deck/releases) |

## Shared Foundation & Companion Projects

- **[Panel Kit](https://github.com/eatingDream-antigravity-plugins/panel-kit)** (`agy-mcp-kit`) — Shared Rust MCP runtime, dark-first single-file panel kit, browserless CSP/i18n QA gates, and SHA-256 drift-free sync powering the entire suite.
- **[AI Digest](https://github.com/eatingDream/ai-digest)** (`eatingDream/ai-digest`) — Turns 150+ sources into a bilingual (EN / 简体中文) daily & weekly AI digest with verifiable citations—live at **[ai.dreamsi.cc](https://ai.dreamsi.cc)**.

## Built to Stay Fast & Private

- **Sub-millisecond local responses**: Standalone native Rust binaries (macOS & Linux, SHA-256 verified) with warm in-memory caching.
- **Zero white-flash UI**: Single-file dark-first panels (`< 43.5 KB`) with strict offline CSP, live EN / 中文 switching, and automated i18n parity checks.
- **Local-first privacy**: Zero telemetry, read-only access to external databases, loopback-only relays, and owner-only local state.
- **Ready for any AI agent**: Every repository ships `llms.txt`, `docs/ai-guide.md`, and an installable `SKILL.md` (`npx skills add eatingDream-antigravity-plugins/<repo>`).
