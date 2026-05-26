# FlowForge Community Blocks

A curated registry of community-built blocks for [FlowForge](https://github.com/keylympi/flowforge) — the open-source visual automation tool for Linux, Windows, and macOS.

---

## What is this?

This repo is the official community block registry. Anyone can submit a block, and hand-picked blocks get featured here. Each block is a self-contained directory with a `block.json` manifest and an entry script in Python, JavaScript, or Shell.

Browse, install, and use blocks directly from FlowForge via the block registry panel, or clone this repo and drop blocks into your local `blocks/` folder manually.

---

## Installing a block

**From FlowForge (recommended)**
1. Open FlowForge
2. Click **Blocks → Browse Registry**
3. Search or browse, click **Install**

**Manually**
```bash
# Clone the registry
git clone https://github.com/keylympi/flowforge-blocks

# Copy the block you want into your FlowForge blocks directory
cp -r flowforge-blocks/tools/my-block ~/.flowforge/blocks/
```

---

## Featured Blocks

> Hand-picked by the FlowForge team for quality, usefulness, and polish.

### 🔧 Tools

Developer and power-user tooling — HTTP clients, file manipulation, data processing, scripting utilities.

| Block | Description | Language | Author |
|---|---|---|---|
| *More coming soon* | | | |

---

### 🖥 OS

Interact with the operating system — notifications, clipboard, file system, processes, system info.

| Block | Description | Language | Author |
|---|---|---|---|
| *More coming soon* | | | |

---

### 📦 App-Specific

Blocks built around specific apps — Slack, VS Code, Spotify, browsers, and more.

| Block | Description | Language | Author |
|---|---|---|---|
| *More coming soon* | | | |

---

### 🤖 AI

LLM calls, image generation, transcription, embeddings, and AI pipeline utilities.

| Block | Description | Language | Author |
|---|---|---|---|
| *More coming soon* | | | |

---

### 🌐 Web

Web scraping, DOM parsing, browser automation, RSS feeds, and webhook utilities.

| Block | Description | Language | Author |
|---|---|---|---|
| *More coming soon* | | | |

---

### 📊 Data

CSV, JSON, XML, databases, spreadsheets, and format conversion.

| Block | Description | Language | Author |
|---|---|---|---|
| *More coming soon* | | | |

---

### 🔔 Notifications

Discord webhooks, email, SMS, push notifications, Pushover, Ntfy, and more.

| Block | Description | Language | Author |
|---|---|---|---|
| *More coming soon* | | | |

---

### 🔒 Security

Password generation, hashing, encryption, secret scanning, and cert checks.

| Block | Description | Language | Author |
|---|---|---|---|
| *More coming soon* | | | |

---

### 🎬 Media

FFmpeg wrappers, image resizing, audio processing, and screenshot capture.

| Block | Description | Language | Author |
|---|---|---|---|
| *More coming soon* | | | |

---

### 👨‍💻 Developer

Git, Code Editing, Language Runtimes.

| Block | Description | Language | Author |
|---|---|---|---|
| *More coming soon* | | | |

---

### 💸 Finance

Crypto prices, stock tickers, exchange rates, and budget utilities.

| Block | Description | Language | Author |
|---|---|---|---|
| *More coming soon* | | | |

---

## Submitting a block

1. Fork this repo
2. Create a directory under the right category
3. Add your `block.json` manifest and entry script — see the [block authoring guide](https://github.com/keylympi/flowforge#writing-a-custom-block-python)
4. Open a pull request with a short description of what your block does

Blocks are reviewed for security and quality before merging. See [CONTRIBUTING.md](CONTRIBUTING.md) for the full guidelines.

---

## Directory structure

```
flowforge-blocks/
├── tools/           # Developer tools, HTTP, scripting utilities
├── os/              # Files, clipboard, notifications, processes
├── app-specific/    # Slack, Spotify, VS Code, browsers, etc.
├── ai/              # LLMs, image gen, transcription, embeddings
├── web/             # Scraping, browser automation, RSS, webhooks
├── data/            # CSV, JSON, XML, databases, format conversion
├── notifications/   # Discord, email, SMS, push notifications
├── security/        # Hashing, encryption, secret scanning
├── media/           # FFmpeg, image resizing, audio, screenshots
├── developer/       # Git, Code editing, language runtimes
└── finance/         # Crypto, stocks, exchange rates
```

---

## License

All blocks in this registry are MIT licensed unless otherwise stated in the block's own directory.
