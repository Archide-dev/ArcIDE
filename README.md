<div align="center">

<img src="https://www.arcide.xyz/logo.png" alt="ArcIDE Logo" width="80" />

# ArcIDE

### The Unlimited AI-Native Desktop IDE

**Run DeepSeek, Llama 3, and any Ollama model — 100% free, 100% local, 100% private.**

[![Website](https://img.shields.io/badge/Website-arcide.xyz-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.arcide.xyz)
[![Download](https://img.shields.io/badge/Download-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.arcide.xyz)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](LICENSE)

<br />

<img src="https://www.arcide.xyz/og-image.png" alt="ArcIDE Screenshot" width="800" style="border-radius: 12px;" />

<br />

**ArcIDE** is a next-generation desktop IDE built for developers who want AI-powered coding **without subscriptions, without cloud dependency, and without sacrificing privacy.**

[Website](https://www.arcide.xyz) · [Blog](https://www.arcide.xyz/blog) · [Report Bug](https://github.com/ArcIDE/arcide/issues)

</div>

---

## ⚡ Why ArcIDE?

| Feature | ArcIDE | Cursor | GitHub Copilot |
|---|---|---|---|
| 💰 Price | **Free** | $20/mo | $19/mo |
| 🏠 Local AI (Ollama) | ✅ | ❌ | ❌ |
| 🔒 Privacy | ✅ Air-gapped | ❌ Cloud-only | ❌ Cloud-only |
| 🤖 Autonomous Agents | ✅ | ✅ | ❌ |
| 📁 Multi-file Editing | ✅ | ✅ | Limited |
| 🧠 Open Source Models | ✅ | ❌ | ❌ |

## 🚀 Features

- **🤖 Autonomous AI Agents** — Agents that read your workspace, plan changes, and execute multi-file edits.
- **🏠 Local-First AI** — Run DeepSeek Coder V2, Llama 3, Mistral, CodeLlama, and any Ollama model directly on your machine.
- **🔒 Total Privacy** — Your code never leaves your laptop. Air-gapped compatible.
- **☁️ Cloud Models Too** — Optionally connect Claude, Gemini, or GPT-5 using your own API keys.
- **⚡ Blazing Fast** — Built with Tauri + React. Uses a fraction of the RAM compared to Electron-based editors.
- **🎨 Beautiful UI** — Modern dark theme designed for long coding sessions.

## 📦 Installation

### Windows
1. Download the latest installer from [arcide.xyz](https://www.arcide.xyz)
2. Run the `.exe` installer
3. Launch ArcIDE

### Setup Local AI (Optional but Recommended)
```bash
# Install Ollama
# Download from https://ollama.com

# Pull your favorite model
ollama pull deepseek-coder-v2:16b

# Or a lighter model for laptops
ollama pull llama3:8b
```

Then in ArcIDE: **Settings** → **AI Providers** → Enable **Ollama** → Select your model.

## 🖥️ Supported AI Models

| Model | Size | Best For |
|---|---|---|
| DeepSeek Coder V2 | 16B | Full-stack development, complex refactoring |
| Llama 3 | 8B | Fast prototyping, quick edits |
| CodeLlama | 34B | Large codebases, system programming |
| Mistral | 7B | Lightweight environments, laptops |
| Qwen 2.5 Coder | 7B | Multilingual projects |

You can also connect **Claude 4.6 Sonnet**, **Gemini Pro**, or **GPT-5** via API keys.

## 🔧 Tech Stack

- **Frontend:** React + TypeScript
- **Desktop Runtime:** Tauri (Rust-based, ultra-lightweight)
- **AI Engine:** Ollama integration + Direct API support
- **Design:** Custom dark theme with glassmorphism

## 🗺️ Roadmap

- [x] Local AI via Ollama
- [x] Autonomous agent system
- [x] Multi-file editing
- [x] Cloud model support (Claude, Gemini, GPT-4)
- [ ] Plugin system
- [ ] Vim keybindings
- [ ] Collaborative editing
- [ ] Linux & macOS builds

## 🤝 Contributing

We welcome contributions! If you'd like to help improve ArcIDE:

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

ArcIDE is proprietary software. See [LICENSE](LICENSE) for details.

## 🌐 Links

- **Website:** [arcide.xyz](https://www.arcide.xyz)
- **Blog:** [arcide.xyz/blog](https://www.arcide.xyz/blog)
- **YouTube:** [ArcIDE Channel](https://youtube.com)

---

<div align="center">

**Built with ❤️ for developers who value freedom, privacy, and unlimited AI.**

[Download ArcIDE](https://www.arcide.xyz) · [Read the Blog](https://www.arcide.xyz/blog)

</div>
