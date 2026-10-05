# Tectonic Business Agents

A native macOS app for browsing and installing AI agents (built on [agency-agents-app](https://github.com/msitarzewski/agency-agents-app), MIT licensed).

## Download

**[Agency-Agents-macOS-arm64.dmg](Agency-Agents-macOS-arm64.dmg)** — click it, then press the **Download** button.

Requires macOS 13+ on an Apple Silicon Mac (M1/M2/M3/M4).

## Install

1. Open the `.dmg` and drag **Agency Agents** into **Applications**.
2. The app isn't notarized by Apple, so the first launch is blocked. Either right-click the app → **Open** → **Open**, or run:
   ```
   xattr -dr com.apple.quarantine "/Applications/Agency Agents.app"
   ```

## Using the agents

The app is free and open source. The agents run inside your own AI tools (Claude Code, Codex, Cursor, etc.), so you need to be signed in to your own subscription there.
