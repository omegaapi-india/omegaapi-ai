<h1 align="center">🤖 OmegaAPI AI — Offline AI Coding Agent for VS Code</h1>

<p align="center">
  <strong>The most powerful fully offline AI coding assistant.</strong><br>
  6 Specialized AI Agents · Self-Learning Memory · Autonomous Code Generation · 50+ Languages<br>
  No API keys. No cloud. No data collection. 100% private. Works with Ollama, LM Studio & any local AI.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.1.1-blue" alt="Version">
  <img src="https://img.shields.io/badge/license-Proprietary-red" alt="License">
  <img src="https://img.shields.io/badge/VS%20Code-%5E1.85.0-purple" alt="VS Code">
  <img src="https://img.shields.io/badge/offline-100%25-green" alt="Offline">
  <img src="https://img.shields.io/badge/agents-6-orange" alt="Agents">
  <img src="https://img.shields.io/badge/languages-50%2B-yellow" alt="50+ Languages">
</p>

---

## 🌐 What is OmegaAPI AI?

**OmegaAPI AI** is a professional-grade VS Code extension that brings the power of AI coding agents to your local machine — completely offline, completely private. It doesn't just suggest code — it **builds entire projects**, creates files, edits code, runs terminal commands, and learns from your workflow.

Built with a **multi-agent architecture**, **self-learning memory**, **persistent work context**, and **deep workspace analysis**, it's your AI-powered full-stack development team inside VS Code.

- 🔗 **Website:** [https://omegaapi.com](https://omegaapi.com)
- 👨‍💻 **Developer:** Krishna Prakash Ojha
- 🏢 **Publisher:** OmegaAPI

---

## ✨ Key Features

### 🤖 6 Specialized AI Agents

| Agent | Icon | Specialization |
|-------|------|----------------|
| **Full-Stack Developer** | 👨‍💻 | Web apps, REST APIs, databases, frontend + backend |
| **Blockchain & Crypto Expert** | ⛓ | Smart contracts, DeFi, NFTs, Web3, Solidity |
| **Backend & Database Expert** | 🗄 | Server-side, APIs, microservices, SQL/NoSQL |
| **Mobile & App Developer** | 📱 | React Native, Flutter, iOS, Android apps |
| **DevOps & Testing Agent** | 🛠 | CI/CD, Docker, testing, debugging, deployment |
| **Auto (Smart Select)** | 🧠 | Automatically picks the best agent for your task |

### ⚡ Autonomous Agent Mode

The AI doesn't just chat — it **builds**:
- Creates complete project files and folder structures
- Edits existing files with precise modifications
- Runs terminal commands (npm install, tests, builds)
- Smart fallback — extracts code from any AI response format

> **Example:** Ask *"Build a React dashboard with Express API and MongoDB"* and the agent creates the complete project, installs dependencies, and sets up everything.

### 🧠 Self-Learning AI + Persistent Work Context

- **Pattern Memory** — Remembers successful solutions and reuses them
- **Project Analysis** — Auto-detects your tech stack, frameworks, and patterns
- **Correction Learning** — Learns from your corrections, never repeats mistakes
- **Persistent Work Context** — Remembers files created, edited, commands run, and current task — even when you switch agents
- **Session Memory** — Chat history survives VS Code restarts

### 🌐 Web Search (No API Key Needed)

- Built-in DuckDuckGo search — no API key required
- Auto-detects when web results are needed
- Search in English, Hindi, or any language
- Results injected into AI context for accurate, up-to-date answers

### 🔌 Universal Local AI Support

Works with **any** local AI backend:

| Backend | Default Port | Status |
|---------|-------------|--------|
| **Ollama** | 11434 | Full streaming support |
| **LM Studio** | 1234 | Full streaming support |
| **llama-cpp-python** | 8000 | OpenAI-compatible |
| **koboldcpp** | 5001 | OpenAI-compatible |
| **LocalAI** | 8080 | OpenAI-compatible |
| **vLLM** | 8000 | OpenAI-compatible |
| **text-generation-webui** | 5000 | OpenAI-compatible |
| **Jan** | 1337 | OpenAI-compatible |
| **GPT4All** | 4891 | OpenAI-compatible |
| **Any OpenAI-compatible** | Custom | Add via settings |

**Auto-Discovery:** On startup, OmegaAPI scans all common ports and auto-detects running AI backends.

### 📦 35+ AI Models (One-Click Download)

| Category | Models |
|----------|--------|
| **Coding** | `qwen2.5-coder:1.5b/7b/14b/32b`, `deepseek-coder-v2`, `codellama:7b/13b/34b`, `starcoder2:3b/7b/15b`, `codegemma:7b` |
| **General** | `llama3.1:8b/70b`, `llama3.2:1b/3b`, `mistral:7b`, `mixtral:8x7b`, `gemma2:9b/27b`, `phi3:mini/medium` |
| **Advanced** | `deepseek-r1:7b/14b/32b`, `qwen2.5:7b/14b/32b/72b`, `command-r:35b`, `wizardlm2:7b` |
| **Small/Fast** | `tinyllama:1.1b`, `phi3:mini`, `llama3.2:1b`, `qwen2.5-coder:1.5b` |

### 🛑 Instant Stop Generation

- Red stop button during AI generation
- Immediately cancels the request — no waiting
- Full control over AI responses

---

## 🌍 50+ Supported Programming Languages

OmegaAPI AI can understand, generate, debug, refactor, and explain code in all major programming languages:

### Web & Frontend
| Language | Extensions |
|----------|-----------|
| HTML5 | `.html`, `.htm` |
| CSS3 / SCSS / SASS / Less | `.css`, `.scss`, `.sass`, `.less` |
| JavaScript (ES6+) | `.js`, `.mjs`, `.cjs` |
| TypeScript | `.ts`, `.tsx` |
| React / JSX / TSX | `.jsx`, `.tsx` |
| Vue.js | `.vue` |
| Angular | `.ts`, `.component.ts` |
| Svelte | `.svelte` |
| Next.js / Nuxt.js | `.js`, `.ts`, `.tsx` |
| Tailwind CSS | `.css`, `.html` |
| WebAssembly | `.wasm`, `.wat` |

### Backend & Server
| Language | Extensions |
|----------|-----------|
| Node.js / Express | `.js`, `.ts` |
| Python | `.py`, `.pyw` |
| PHP | `.php` |
| Java | `.java` |
| C# / .NET | `.cs` |
| Go (Golang) | `.go` |
| Ruby | `.rb` |
| Rust | `.rs` |
| C / C++ | `.c`, `.cpp`, `.h`, `.hpp` |
| Perl | `.pl`, `.pm` |
| Scala | `.scala` |
| Elixir | `.ex`, `.exs` |
| Haskell | `.hs` |
| Lua | `.lua` |
| R | `.r`, `.R` |

### Mobile Development
| Language | Extensions |
|----------|-----------|
| React Native | `.jsx`, `.tsx` |
| Flutter / Dart | `.dart` |
| Swift (iOS) | `.swift` |
| Kotlin (Android) | `.kt`, `.kts` |
| Objective-C | `.m`, `.mm` |
| Java (Android) | `.java` |

### Blockchain & Web3
| Language | Extensions |
|----------|-----------|
| Solidity | `.sol` |
| Vyper | `.vy` |
| Rust (Solana) | `.rs` |
| Move (Aptos/Sui) | `.move` |
| Cairo (StarkNet) | `.cairo` |

### Data & ML
| Language | Extensions |
|----------|-----------|
| Python (NumPy, Pandas, TensorFlow, PyTorch) | `.py` |
| R | `.r`, `.R` |
| Julia | `.jl` |
| SQL | `.sql` |
| MATLAB | `.m` |

### DevOps & Infrastructure
| Language | Extensions |
|----------|-----------|
| Shell / Bash | `.sh`, `.bash` |
| PowerShell | `.ps1`, `.psm1` |
| Dockerfile | `Dockerfile` |
| Docker Compose | `docker-compose.yml` |
| Kubernetes YAML | `.yaml`, `.yml` |
| Terraform (HCL) | `.tf` |
| Ansible | `.yml` |
| Nginx Config | `nginx.conf` |
| GitHub Actions | `.yml` |

### Database & Query
| Language | Extensions |
|----------|-----------|
| SQL (MySQL, PostgreSQL, SQLite) | `.sql` |
| MongoDB Queries | `.js` |
| Redis Commands | — |
| GraphQL | `.graphql`, `.gql` |
| Prisma | `.prisma` |

### Config & Markup
| Language | Extensions |
|----------|-----------|
| JSON | `.json` |
| YAML | `.yml`, `.yaml` |
| TOML | `.toml` |
| XML | `.xml` |
| Markdown | `.md` |
| LaTeX | `.tex` |
| Protocol Buffers | `.proto` |

---

## 🗣️ Multilingual Chat Support / बहुभाषी सपोर्ट

OmegaAPI AI understands natural language commands in multiple languages:

### 🇮🇳 Hindi / हिन्दी
| Command | Action |
|---------|--------|
| *"ek website banao"* | पूरी वेबसाइट बनाता है |
| *"is code ko fix karo"* | कोड में बग ढूंढ कर ठीक करता है |
| *"samjhao ye kya hai"* | कोड समझाता है |
| *"test likho"* | टेस्ट फाइल बनाता है |
| *"mere code mein error hai"* | एरर ढूंढ कर ठीक करता है |
| *"khojo"* / *"dhundho"* | वेब सर्च करता है |
| *"chalao"* / *"run karo"* | प्रोजेक्ट रन करता है |
| *"deploy karo"* | प्रोजेक्ट deploy करता है |
| *"React app banao"* | React प्रोजेक्ट बनाता है |
| *"database setup karo"* | डेटाबेस सेटअप करता है |

### 🇬🇧 English
| Command | Action |
|---------|--------|
| *"Build a REST API with Express"* | Creates full API project |
| *"Fix the errors in my code"* | Finds and fixes bugs |
| *"Explain this function"* | Explains code logic |
| *"Write unit tests"* | Generates test files |
| *"Create a React dashboard"* | Builds complete React app |
| *"Deploy my project"* | Auto-deploys project |

### 🇺🇸 Hinglish (Hindi + English Mix)
| Command | Action |
|---------|--------|
| *"ek todo app bana do React me"* | React todo app बनाता है |
| *"ye function optimize karo"* | Function optimize करता है |
| *"MongoDB connection setup kar do"* | Database connection बनाता है |
| *"API se data fetch karne ka code do"* | API integration code देता है |

---

## 📋 All 23 Commands

Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`) and type **"Omega"**:

| Command | Description |
|---------|-------------|
| `Omega: New Chat` | Start a fresh chat session |
| `Omega: Select Model` | Choose from installed AI models |
| `Omega: Select Agent` | Pick a specialized AI agent |
| `Omega: Download Model` | Download a new AI model (35+ options) |
| `Omega: Delete Model` | Remove a downloaded model |
| `Omega: Explain Selected Code` | AI explains highlighted code |
| `Omega: Fix Selected Code` | AI fixes bugs in highlighted code |
| `Omega: Refactor Selected Code` | AI improves highlighted code |
| `Omega: Generate Code from Comment` | Generate code from description |
| `Omega: Web Search` | Search the web via DuckDuckGo |
| `Omega: Run Tests` | Auto-detect and run project tests |
| `Omega: Run Lint Check` | ESLint across your project |
| `Omega: Deploy / Run Project` | Auto-detect and launch project |
| `Omega: Setup Python AI` | Setup offline Python AI environment |
| `Omega: Add Custom AI Endpoint` | Add OpenAI-compatible endpoint |
| `Omega: Manage AI Endpoints` | View/remove custom endpoints |
| `Omega: Scan for Local AI Backends` | Auto-discover running AI servers |
| `Omega: Clear Chat Memory` | Wipe chat history and patterns |
| `Omega: Restore Checkpoint (Undo AI Changes)` | Undo AI changes or restore any earlier point, with before/after diff |
| `Omega: System Info (RAM / VRAM / Best Models)` | Your hardware and which models fit it |
| `Omega: Free RAM/VRAM (Unload Models)` | Unload models from memory right now |
| `Omega: Activate License` | Enter a license key |
| `Omega: License Info` | View current license status |

### Right-Click Context Menu

Select code → right-click:
- **Omega: Explain Selected Code**
- **Omega: Fix Selected Code**
- **Omega: Refactor Selected Code**

---

## 📋 System Requirements

| Requirement | Details |
|-------------|---------|
| **VS Code** | v1.85.0 or higher |
| **AI Backend** | Ollama, LM Studio, or any OpenAI-compatible server |
| **RAM** | 8GB minimum (16GB+ recommended for 7B models) |
| **Disk** | 2-50 GB depending on model size |
| **OS** | Windows 10/11, macOS 10.15+, Linux (Ubuntu 20.04+) |

---

## 🚀 Quick Start (2 Minutes)

### Step 1: Install an AI Backend

**Option A — Ollama (Recommended):**
```bash
# Windows: Download from https://ollama.com
# macOS: brew install ollama
# Linux: curl -fsSL https://ollama.com/install.sh | sh
```

**Option B — LM Studio:**
Download from [lmstudio.ai](https://lmstudio.ai) → Load a model → Start server

**Option C — Any OpenAI-compatible server:**
Use the command `Omega: Add Custom AI Endpoint` to add your server URL.

### Step 2: Pull a Model (Ollama)

```bash
ollama pull qwen2.5-coder:7b
```

Or use the built-in: **`Omega: Download Model`** command.

### Step 3: Start Building!

1. Click the **Omega AI** icon in the Activity Bar (sidebar)
2. Type your request:
   - *"Build a React todo app with Express backend"*
   - *"ek e-commerce website banao"*
   - *"Create a Solidity NFT smart contract"*
   - *"Fix the errors in my project"*
3. Watch the agent create files, write code, and run commands automatically!

---

## ⚙️ Configuration

Open VS Code Settings (`Ctrl+,`) → Search "Omega":

| Setting | Default | Description |
|---------|---------|-------------|
| `omega.ollamaUrl` | `http://localhost:11434` | Ollama API server URL |
| `omega.lmStudioUrl` | `http://localhost:1234` | LM Studio API server URL |
| `omega.defaultModel` | `qwen2.5-coder:7b` | Default model for chat |
| `omega.maxTokens` | `4096` | Maximum tokens per response |
| `omega.temperature` | `0.7` | Creativity (0 = precise, 1 = creative) |
| `omega.pythonPath` | *(auto-detect)* | Custom Python executable path |
| `omega.customEndpoints` | `[]` | Custom OpenAI-compatible endpoints |
| `omega.liveFileWriting` | `true` | Write files live in the editor while the AI generates them |
| `omega.autoMemoryManagement` | `true` | Auto-manage RAM/VRAM: unload unused models, size context to free memory |
| `omega.modelKeepAlive` | `10m` | How long Ollama keeps a model loaded after the last request (`0` = unload immediately) |
| `omega.contextWindow` | `0` | Context window in tokens for Ollama (`0` = automatic from your RAM/VRAM) |
| `omega.autoRunCommands` | `false` | Let the AI run terminal commands without asking each time |

---

## 💰 Pricing

**One plan. One payment. No monthly bills.**

| Plan | Price | What you get |
|------|-------|--------------|
| **Omega AI Pro** | **$251 one-time setup fee** (₹21,999 + GST in India) | **3 years of updates & new releases**, all features, unlimited usage, remote setup & device configuration by our team |

### Included:
- ✅ All 6 specialized AI agents (Full-Stack, Blockchain, Backend, Mobile, DevOps, Auto)
- ✅ Unlimited AI usage — no daily limits, no per-token cost
- ✅ **Real-time file generation** — watch code being written live in your editor
- ✅ **Checkpoints** — undo any AI change in one click, or restore the project to any earlier point
- ✅ **Secret leak protection** — API keys, passwords and `.env` files never reach the AI
- ✅ **Auto RAM / VRAM management** — detects your GPU & memory, recommends models that fit, sizes context automatically
- ✅ Self-learning memory & persistent work context
- ✅ Web search, terminal automation (with confirmation), file creation/editing
- ✅ 50+ programming language support
- ✅ Every update and new release for 3 years
- ✅ Remote setup & device configuration (our team helps you set up)
- ✅ 1 device, 1 seat per license key (machine-bound)

> **Buy / renew:** [omegaapi.in/product/omega-ai](https://omegaapi.in/product/omega-ai) — license key delivered instantly after payment.
>
> **Contact:** info@sonuojha.in | [https://omegaapi.com](https://omegaapi.com)

---

## 🔒 Privacy & Security

| Feature | Details |
|---------|---------|
| **AI runs on your machine** | Your prompts and code go only to the local AI server you choose (Ollama, LM Studio, etc.). Only when you use Web Search is the search text sent to DuckDuckGo |
| **No Telemetry** | Zero analytics, zero tracking |
| **No API Keys / No Cloud AI** | Uses local models — no cloud subscriptions, no per-token billing |
| **Secret Leak Protection** | API keys, passwords, tokens and `.env` files are hidden from the AI |
| **Checkpoints** | Every AI change can be undone in one click |
| **License check only** | The only thing that contacts our server (omegaapi.in) is the license check: your license key and a one-way hash of your machine ID — never your code |
| **Machine-Bound License** | 1 license = 1 computer |

> **Your code is YOUR code. Always.**

---

## 🔧 Troubleshooting

### AI not connecting?
```bash
# Check Ollama:
curl http://localhost:11434/api/tags

# Not running? Start it:
ollama serve
```

### Model too slow?
- Use smaller models: `qwen2.5-coder:1.5b` or `tinyllama:1.1b`
- Close heavy applications
- Recommended: 16GB+ RAM for 7B models

### Windows Firewall blocking?
- OmegaAPI auto-uses `127.0.0.1` instead of `localhost` to bypass Windows security
- If still blocked: Allow Ollama/LM Studio in Windows Firewall settings

### Extension not visible?
- Reload VS Code: `Ctrl+Shift+P` → *"Developer: Reload Window"*
- Check Extensions panel → search "OmegaAPI"

---

## 📄 Changelog

### v1.1.0 (November 2026)
- ✍️ **Real-time file generation** — watch code being written live in the editor while the AI streams it (like Cline / OpenCode); cancel mid-file and the original is restored
- ↩️ **Checkpoints / one-click undo** — the original of every file the AI touches is saved first; undo a turn, review the before/after diff, or restore the project to any earlier point (`Omega: Restore Checkpoint`)
- 🔒 **Secret leak protection** — API keys, passwords, tokens and `.env` files are hidden from the AI; real values are restored when it writes a file back
- 🧮 **Auto RAM / VRAM management** — detects your CPU, RAM and GPU (NVIDIA / AMD / Apple Silicon), shows which models fit, picks the best one, sizes the context window to free memory and unloads unused models (`Omega: System Info`, `Omega: Free RAM/VRAM`)
- ✅ **Command confirmation** — the AI asks before running any terminal command (`omega.autoRunCommands` to allow all)
- 💳 **New pricing** — single **Pro** plan: $251 one-time setup fee with 3 years of updates & new releases (buy/renew at [omegaapi.in](https://omegaapi.in/product/omega-ai)); existing keys keep working
- 🐛 **Bug fixes** — commands no longer run twice; the AI can no longer overwrite existing files from a snippet or write outside the workspace; clearer errors when the model server is unreachable; `temperature: 0` honoured; concurrent messages no longer mix; corrections learned against the right answer

### v1.0.0 (February 2026)
- 🤖 **6 AI Agents** — Full-Stack, Blockchain, Backend, Mobile, DevOps, Auto
- 🧠 **Self-Learning** — Pattern memory, project analysis, correction learning
- 🔄 **Persistent Work Context** — AI remembers work across agent switches
- ⚡ **Agent Mode** — Autonomous file creation, editing, command execution
- 🔌 **Universal AI Support** — Ollama, LM Studio, and any OpenAI-compatible backend
- 🔍 **Auto-Discovery** — Scans common ports for running AI backends
- 🌐 **Web Search** — DuckDuckGo (no API key)
- 📦 **35+ Models** — One-click download via Ollama
- 🛑 **Stop Generation** — Cancel AI response instantly
- 🗣️ **Hindi/Hinglish/English** — Multilingual chat support
- 🐍 **Python AI Setup** — Offline PyTorch/Transformers environment
- 🚀 **Auto Deploy** — Detect and launch any project type
- 🔑 **License System** — Pro: $251 one-time setup fee, 3 years of updates & new releases
- 🎨 **Dark Theme UI** — Agent cards, toolbar, streaming responses

---

## 👨‍💻 Developer

**Krishna Prakash Ojha**
- 🔗 Website: [https://omegaapi.com](https://omegaapi.com)
- 🏢 Publisher: OmegaAPI
- 📧 Support: [https://omegaapi.com](https://omegaapi.com)

---

<p align="center">
  <strong>Built with ❤️ by OmegaAPI</strong><br>
  <em>Your AI. Your Machine. Your Privacy. आपकी AI. आपकी मशीन. आपकी प्राइवेसी.</em>
</p>
