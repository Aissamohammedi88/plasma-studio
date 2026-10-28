# plasma-studio
⚡ The Sovereign Local-First Markdown Editor. Built with Rust, C++, Java &amp; Python (9k LOC). Zero telemetry, 90+ tools, auto-README generation.
<div align="center">
  <h1>⚡ PLASMA STUDIO</h1>
  <p><strong>The Sovereign Local-First Markdown & README Editor.</strong></p>
  
  [![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](#)
  [![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)](#)
  [![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](#)
  [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
  [![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](#)
</div>

---

## 🧬 The Philosophy

GitHub's web editor is heavy, cloud-dependent, and lacks professional tooling. **Plasma Studio** is the antidote.

Built from scratch with a **9,000-line multi-language architecture**, Plasma Studio is a blazing-fast, 100% local-first Markdown editor designed for systems architects and senior developers. It runs entirely on your machine (`127.0.0.1:2009`). No telemetry. No cloud lock-in. Just pure, sovereign code generation.

**"Stop writing READMEs in a browser. Start building them in a studio."**

---

## ⚙️ Architecture (The 4-Language Engine)

Plasma Studio is an engineering feat, utilizing the best of four languages to achieve maximum performance:

| Language | Role | Why? |
| :--- | :--- | :--- |
| 🦀 **Rust** | Core Server & I/O | Asynchronous, lightning-fast HTTP server (Port 2009) with zero memory leaks. |
| ⚡ **C++** | Markdown Parser & Lexer | Native parsing engine ensuring sub-millisecond syntax highlighting. |
| ☕ **Java** | Extensions & Plugins | Robust JVM backend for managing the 90+ tool options and integrations. |
| 🐍 **Python** | AI Integration & Scripting | Seamless local LLM connection (Vortex/GLM) for auto-README generation. |

---

## 🚀 Features

- **Split-View Live Preview:** Write Markdown on the left, see the rendered HTML instantly on the right.
- **Auto-README Generator:** Connect your local AI (Ollama/Vortex) and generate professional READMEs from a simple 3-word prompt.
- **90+ Pro Tools:** Mermaid diagram rendering, LaTeX math support, table formatting, and advanced syntax highlighting.
- **Cyberpunk/VIM UI:** A gorgeous, dark-themed interface built for terminal lovers.
- **Zero Telemetry:** 100% offline. Your data never leaves your `localhost`.
- **Ultra-Lightweight:** The entire studio binary is smaller and faster than a single GitHub web page load.

---

## 🛠️ Installation & Usage

*(Coming soon in the v3.0 Release)*

```bash
# 1. Clone the repository
git clone https://github.com/Aissamohammedi88/plasma-studio.git
cd plasma-studio

# 2. Compile the multi-language engine
./build.sh

# 3. Launch the Studio
./plasma-studio
