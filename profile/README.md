<div align="center">

# eatingDream Antigravity Plugins

**Small, focused plugins for Antigravity.**

[Suite Home](https://eatingdream.dev) · [AI Digest](https://ai.dreamsi.cc) · [GitHub](https://github.com/eatingDream-antigravity-plugins)

</div>

Each plugin is a single Rust binary with a compact sidebar panel. Together they handle the small things that slow down long agent sessions on a Mac: a filling context window, a hot laptop with the lid closed, a browser you can't see, and GPU bills you forgot about.

## Plugins

| Plugin | Repo | What it does | Links |
| :--- | :--- | :--- | :--- |
| **Context Radar** | [`context-radar`](https://github.com/eatingDream-antigravity-plugins/context-radar) | Shows token use, cache hits, and cost for every session and subagent, and helps you decide when to `/compact` or open a new chat. | [Site](https://contextradar.eatingdream.dev) · [Releases](https://github.com/eatingDream-antigravity-plugins/context-radar/releases) |
| **Clam Guard** | [`clam-guard`](https://github.com/eatingDream-antigravity-plugins/clam-guard) | Keeps a MacBook awake with the screen dark when you close the lid, and eases off heavy work as it heats up without touching fan control. | [Site](https://clamguard.eatingdream.dev) · [Releases](https://github.com/eatingDream-antigravity-plugins/clam-guard/releases) |
| **Remote Cast** | [`remote-cast`](https://github.com/eatingDream-antigravity-plugins/remote-cast) | Streams a Chrome tab into the Antigravity sidebar so you can watch and steer what an agent is doing — click, type, and switch tabs. | [Site](https://remotecast.eatingdream.dev) · [Releases](https://github.com/eatingDream-antigravity-plugins/remote-cast/releases) |
| **Colab Deck** | [`colab-deck`](https://github.com/eatingDream-antigravity-plugins/colab-deck) | Starts, watches, and stops Google Colab sessions, forwards ports, and deploys GGUF models with auto-stop and spending limits. | [Site](https://colabdeck.eatingdream.dev) · [Releases](https://github.com/eatingDream-antigravity-plugins/colab-deck/releases) |

## Shared Toolkit & Companion

- **[Panel Kit](https://github.com/eatingDream-antigravity-plugins/panel-kit)** (`panel-kit`) — The small bridge, Lucid Indigo dark-first theme, and build setup these plugins use to ship sidebar panels under 64 KiB.
- **[AI Digest](https://github.com/eatingDream/ai-digest)** — Turns ~155 open AI sources into a bilingual (EN / 简体中文) daily and weekly briefing at **[ai.dreamsi.cc](https://ai.dreamsi.cc)**.

## How They're Built

- **Single native binaries**: Compiled Rust tools for macOS and Linux with no runtime interpreter dependencies.
- **Compact dark-first panels**: Single-file Lucid Indigo UIs under 64 KiB with strict offline CSP and live EN / 简体中文 switching.
- **Local-first by default**: No telemetry, read-only access to local state, loopback-only relays, and owner-only config files.
- **Built for agents too**: Every repo ships `llms.txt`, `docs/ai-guide.md`, and an installable skill (`npx skills add eatingDream-antigravity-plugins/<repo>`).
