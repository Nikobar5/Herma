# Herma

**AI That Protects Your Data**


---

## Overview

Herma is a privacy-focused AI assistant that gives you complete control
over your data through intelligent, automatic routing. Define your privacy
 boundaries once—Herma enforces them forever.

### The Problem

Every time you use cloud AI, you make an invisible trade: your
confidential information for convenience. Sensitive documents, private
thoughts, and proprietary data flow to distant servers where they may be
used for training, logging, or analysis beyond your control.

The alternative? Slow, limited local tools that can't match cloud AI's
capabilities.

**You shouldn't have to choose between power and privacy.**

### The Solution

Herma introduces **Data Governor Mode**—an intelligent routing system that
 automatically decides where your AI queries are processed based on rules
*you* define.

- **Sensitive query?** Processed 100% locally on your device. Zero
internet required.
- **General query?** Routed to powerful cloud models for maximum speed and
 quality.
- **You decide the rules.** Herma enforces them. Automatically. Every
time.

---

## Three Modes, Infinite Control

### 🏰 Local Mode
**Maximum Privacy. Zero Compromises.**

- All processing happens on your device
- Works completely offline
- Perfect for confidential work: legal documents, medical records,
financial data, competitive strategy
- Powered by Ollama with state-of-the-art local language models

### 🛡️ Governor Mode *(The Herma Difference)*
**Intelligence That Respects Your Boundaries.**

- Define your privacy constitution once (e.g., "Medical records and legal
docs = local only")
- Herma automatically routes each query to the appropriate processing
location
- Sensitive data stays local, general queries leverage cloud speed
- Best of both worlds with zero friction
- *(Experimental - always verify critical routing decisions)*

### 🚀 Cloud Mode
**Maximum Performance. Maximum Speed.**

- Direct access to cutting-edge cloud models via OpenRouter
- Fastest responses, highest quality output
- Perfect for creative work, research, brainstorming, and general queries
- No local privacy protection—use when speed matters more than privacy

---

## Core Features

### 📄 Document Intelligence (RAG)
- Upload and analyze PDF, DOCX, PPTX, Excel, and more
- Powered by ChromaDB vector database for semantic search
- Documents are embedded and processed according to your privacy settings
- Context-aware responses grounded in your uploaded materials

### 🔐 Privacy Constitution
- Define custom rules for what stays local vs. what can use cloud
processing
- Simple, natural language configuration
- Automatically applied to every query—no manual toggling required
- Update anytime; changes apply instantly

### 🎯 Smart File Management
- Upload files in Local, Governor, or Cloud mode
- Each file remembers its privacy classification
- Visual indicators show which processing mode applies
- Free tier: 5 files | Pro tier: Unlimited files

### 🔄 Seamless Mode Switching
- Toggle between Local, Governor, and Cloud modes instantly
- No restart required, no context lost
- Your privacy constitution travels with you

### 🌐 Works Anywhere
- Fully offline capable in Local mode
- Cross-platform desktop application (Windows, macOS, Linux)
- Secure, sandboxed architecture

---

## Technology Stack

**Built with privacy and performance in mind:**

- **Frontend:** React, TypeScript, TailwindCSS
- **Desktop Framework:** Electron for cross-platform compatibility
- **Backend:** Python with LangChain for AI orchestration
- **Local AI:** Ollama integration for on-device language models
- **Cloud AI:** OpenRouter for access to GPT-4, Claude, and other frontier
 models
- **Vector Database:** ChromaDB for document embeddings and semantic
search
- **Authentication:** Firebase Auth (email/password and Google OAuth)
- **Cloud Storage:** Firestore for user preferences and settings
- **Document Processing:** Support for PDF, DOCX, PPTX, Excel, CSV, TXT,
Markdown, and more

**Security & Privacy:**
- Code obfuscation for production builds
- Sandboxed renderer processes
- Context isolation enabled
- No telemetry or tracking in Local mode
- End-to-end encryption for cloud-synced settings

---

## Use Cases

### For Professionals Who Can't Compromise

**Legal:** Draft client documents locally, research case law in the cloud
**Healthcare:** Analyze patient records on-device, summarize public
research with cloud speed
**Finance:** Model proprietary strategies locally, research market trends
via cloud
**Consulting:** Keep client work confidential, leverage AI for general
business tasks
**Engineering:** Protect intellectual property while accessing powerful
coding assistance
**Research:** Analyze sensitive datasets locally, synthesize public
literature in the cloud

---

## Business Model

### HΞRMΛ Free
- Full access to all three modes (Local, Governor, Cloud)
- Up to 5 uploaded files
- Community support
- Perfect for individual users exploring privacy-first AI

### HΞRMΛ Pro
- Unlimited file uploads
- Priority support
- Early access to new features
- Support the development of privacy-respecting AI tools

[Get Started Free](https://hermahq.com)

---

## Why Herma?

### You Own Your AI Interactions
Just like you own your devices, you should own your AI conversations.
Herma puts you in control of where your data goes and how it's processed.

### No More False Choices
Stop choosing between powerful AI and your privacy. Stop managing two
different tools. Stop second-guessing every query.

### Intelligence You Can Trust
Governor mode doesn't just blindly route traffic—it applies *your* rules
with precision. Set your boundaries once. Work with confidence forever.

### Privacy Without Paranoia
We're not anti-cloud. We're anti-*forced*-cloud. Sometimes speed matters
more than privacy. Sometimes privacy is non-negotiable. You decide. Every
time.

---

## The Herma Philosophy

**Autonomy Through Intelligence**

We believe AI should amplify your agency, not exploit your ignorance.
Every feature, every design decision, every line of code serves one
principle: **you are in control**.

- **Transparent by design:** You know exactly where your data goes
- **Local-first architecture:** Privacy is the default, not an
afterthought
- **No dark patterns:** Clear choices, honest trade-offs, respectful
design
- **Open about limitations:** Governor mode is experimental—we tell you
that upfront

**This is AI that answers to you.**

---

## Getting Started

### Installation & Download

Visit [hermahq.com](https://hermahq.com) to download Herma for your
platform (Windows, macOS, Linux).

### Quick Start

1. **Download & Install:** Get Herma from our landing page
2. **Choose Your Mode:** Start with Governor mode to experience
intelligent routing
3. **Set Your Constitution:** Define what stays local (e.g.,
"confidential", "medical", "legal")
4. **Start Working:** Type naturally—Herma handles the routing
automatically

### First-Time Setup

- Herma will automatically download required local AI models on first run
(Local/Governor modes)
- Internet connection required for initial setup and Cloud/Governor modes
- No internet needed for pure Local mode operation

---

## Roadmap

**Coming Soon:**
- Mobile companion app (view-only mode for on-the-go access)
- Team collaboration features with shared privacy constitutions
- Advanced constitution rules (regex patterns, custom classifications)
- Integration with enterprise SSO providers
- API access for developers
- Self-hosted cloud model option for organizations

---

## Community & Support

- **Documentation:** [docs.hermahq.com](#)
- **Discord Community:** [discord.gg/herma](#)
- **Email Support:** support@hermahq.com
- **Feature Requests:** [github.com/hermahq/herma/issues](#)
- **Twitter/X:** [@HermaHQ](#)

---

## FAQ

**Q: Does Herma store my data?**
A: In Local mode, nothing ever leaves your device. In Governor/Cloud
modes, only queries you explicitly route to the cloud are sent to AI
providers. We never store or log your query content—only metadata like
mode preferences.

**Q: What AI models does Herma use?**
A: Local mode uses Ollama (LLaMA 3, Mistral, etc.). Cloud mode uses
OpenRouter (GPT-4, Claude 3.5, Gemini Pro, etc.). You control which
provider handles your data.

**Q: How accurate is Governor mode routing?**
A: Governor mode applies your constitution rules with precision, but it's
currently experimental. We recommend reviewing critical routing decisions
until you're confident in your rule set.

**Q: Can I use Herma completely offline?**
A: Yes! Local mode works 100% offline after initial model downloads.

**Q: Is my privacy constitution shared with anyone?**
A: No. Your constitution is stored locally on your device and optionally
synced to your private Firestore account (encrypted). We never see or
access it.

**Q: What happens if I switch from Cloud to Local mode?**
A: Context and conversation history remain available. Only the processing
location changes.

---

## License

Herma is proprietary software. See [LICENSE](#) for details.

---

## Contact

**Website:** [hermahq.com](https://hermahq.com)
**Email:** hello@hermahq.com
**Support:** support@hermahq.com

---

<p align="center">
  <strong>HΞRMΛ</strong><br>
  Your Rules. Your Data. Your AI.
</p>

<p align="center">
  <a href="https://hermahq.com">Download Now</a> •
  <a href="#">Documentation</a> •
  <a href="#">Join Discord</a>
</p>

