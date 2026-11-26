<div align="center">

# eatingDream Antigravity Plugins

**Native Rust MCP servers & Editorial-Warm SEP-1865 live panels for Google Antigravity.**

[Homepage](https://eatingdream.dev) · [Plugins](https://github.com/eatingDream-antigravity-plugins) · [AIDigest](https://github.com/eatingDream/ai-digest)

</div>

## Plugin Suite

| Brand | Repository | Focus | Links |
| :--- | :--- | :--- | :--- |
| **ContextRadar** | [`context-radar-mcp`](https://github.com/eatingDream-antigravity-plugins/context-radar-mcp) | Context telemetry, 3-way cold-cache attribution, prefix-safe `scratch/` distillation & gated `/compact` / fresh-chat handoffs | [Site](https://contextradar.eatingdream.dev) · [Releases](https://github.com/eatingDream-antigravity-plugins/context-radar-mcp/releases) |
| **ClamGuard** | [`mac-clamshell-mcp`](https://github.com/eatingDream-antigravity-plugins/mac-clamshell-mcp) | macOS closed-lid performance throttling, external-display-safe display guard, read-only AppleSMC fan telemetry, brightness & verified screen lock | [Site](https://clamguard.eatingdream.dev) · [Releases](https://github.com/eatingDream-antigravity-plugins/mac-clamshell-mcp/releases) |
| **RemoteCast** | [`chrome-stream-mcp`](https://github.com/eatingDream-antigravity-plugins/chrome-stream-mcp) | Weak-network local Google Chrome CDP screencast relay, standby keep-alive, isolated Remote Chrome & interactive tab controller | [Site](https://remotecast.eatingdream.dev) · [Releases](https://github.com/eatingDream-antigravity-plugins/chrome-stream-mcp/releases) |
| **ColabDeck** | [`colab-mcp`](https://github.com/eatingDream-antigravity-plugins/colab-mcp) | Google Colab GPU/TPU runtime dashboard, kernel execution, compute-unit telemetry & zero-flicker MCP App panel | [Site](https://colabdeck.eatingdream.dev) · [Releases](https://github.com/eatingDream-antigravity-plugins/colab-mcp/releases) |

## Shared Foundation & Companion Projects

- **[PanelKit](https://github.com/eatingDream-antigravity-plugins/agy-mcp-kit)** (`agy-mcp-kit`) — Shared zero-bloat Rust MCP/SWR runtime primitives, 16-token Editorial-Warm panel design kit, and SHA-256 zero-drift vendor sync powering the entire suite.
- **[AIDigest](https://github.com/eatingDream/ai-digest)** (`eatingDream/ai-digest`) — Agent-driven bilingual (EN / 简体中文) daily & weekly AI digest pipeline published as an encrypted static site.

## Engineering Standards

- **Native Rust, zero bloat**: Prebuilt SHA-256 verified release binaries for macOS & Linux with `< 1 ms` warm SWR responses.
- **Dark-first zero-flicker UI**: Self-contained `< 43.5 KB` single-file SEP-1865 panels with strict `default-src 'none'` CSP, zero external assets, and live EN / 中文 localization.
- **Local-first privacy**: Zero telemetry, read-only external DB access, loopback-only relays, and owner-only (`0700`/`0600`) local state.
- **Portable for any AI agent**: Every plugin ships `llms.txt`, `docs/ai-guide.md`, and an `agentskills.io`-compatible `SKILL.md` (`npx skills add eatingDream-antigravity-plugins/<repo>`).
