# cc-connect-screenshot

Fork of [cc-connect](https://github.com/chenhg5/cc-connect) with `/screenshot` command support.

Bridge AI coding agents (Claude Code, Cursor, Gemini CLI, Codex) to messaging platforms (Feishu/Lark, DingTalk, Slack, Telegram, Discord, LINE, WeChat Work).

## Install

```bash
npm install -g cc-connect-screenshot
```

## Usage

```bash
# Check version
cc-connect-screenshot --version

# Create config, then run
cc-connect-screenshot
```

## Extra Commands

| Command | Description |
|---------|-------------|
| `/screenshot` `/shot` `/screen` `/capture` | Capture current screen and send image |

Windows: uses PowerShell + .NET (zero dependencies)
Linux/macOS: requires scrot, gnome-screenshot, or ImageMagick

## Documentation

See full documentation at: https://github.com/Againstthewindtofly/cc-connect
