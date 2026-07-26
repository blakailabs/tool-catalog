# 🛠️ Tool & Resource Catalog

A living catalog of every tool, product, open-source project, dataset, AI service, and platform that's been researched, discussed, or is actively used across projects.

---

## 🔥 Platforms & Infrastructure

### Cloud / Hosting
| Tool | Description | Status | For |
|------|-------------|--------|-----|
| **Netlify** | Static site hosting & serverless functions | ✅ Active | ProposalPal, AI Night School, AutoNetwork SaaS |
| **GoDaddy** | DNS & domain management | ✅ Active | All domains |
| **Vercel** | Next.js / JAMstack hosting platform | ⚡ Available | Optional |
| **Cloudflare** | CDN, DNS, DDoS protection, Workers | ⚡ Available | Optional |
| **Supabase** | Open-source Firebase alternative (Postgres DB, auth, storage) | 🔧 Needs Setup | Pending connection string |
| **Firebase** | Google's app development platform (auth, DB, hosting) | 🔧 Needs Setup | Optional |

### Communications / SMS
| Tool | Description | Status | For |
|------|-------------|--------|-----|
| **Twilio** | SMS, Voice, Phone API — core engine for Possum phone QA | 🔧 Needs API Key | Possum |
| **AgentMail** | Dedicated AI agent email inbox | ✅ Active | Communication |
| **Himalaya** | IMAP/SMTP email CLI | ✅ Active | Communication |

### Payments / Finance
| Tool | Description | Status | For |
|------|-------------|--------|-----|
| **Stripe** | Payment processing, subscriptions, invoicing | 🔧 Needs API Keys | ProposalPal, AI Night School |
| **Coinbase** | Crypto exchange & trading via CDP MCP | 🔧 Needs API Key | Crypto |

### Marketing / Email
| Tool | Description | Status | For |
|------|-------------|--------|-----|
| **ConvertKit** | Creator-friendly email marketing & automation | 🔧 Needs API Key | ProposalPal cold outreach |
| **Mailchimp** | Full-featured email marketing platform | 🔧 Needs API Key | Alternative to ConvertKit |

---

## 🧠 AI Models & Services

### Language Models (via Hermes)
| Model | Provider | Role |
|-------|----------|------|
| **DeepSeek V4 Flash** | Nous Research | 🎯 Primary model |
| **Gemini 2.0 Flash** | OpenRouter (free tier) | ⚡ Fallback 1 |
| **Kimi K3** | Nous Research | ⚡ Fallback 2 |

### Image Generation
| Service | Description | Status |
|---------|-------------|--------|
| **DALL-E 3** (OpenAI) | Text-to-image, via Nous subscription | ✅ Active |
| **FAL** | Image gen plugin (comfyui, stable diffusion) | ✅ Installed |

### Audio / Speech
| Service | Description | Status |
|---------|-------------|--------|
| **OpenAI TTS** | Text-to-speech via Nous subscription | ✅ Active |
| **OpenAI Whisper** | Speech-to-text via Nous subscription | ✅ Active |

### AI Agent / Coding Tools
| Tool | Description | Status |
|------|-------------|--------|
| **Claude Code** | Anthropic's CLI coding agent | ✅ Active |
| **OpenAI Codex** | OpenAI's CLI coding agent | ✅ Active |
| **Blackbox** | AI CLI coding agent | ✅ Active |
| **Grok Build** | xAI's CLI coding agent | ✅ Active |
| **OpenHands** | Model-agnostic coding agent (LiteLLM) | ✅ Active |
| **OpenCode** | CLI coding agent | ✅ Active |

---

## 📦 Awesome LLM Apps Repo

**Repo:** `Shubhamsaboo/awesome-llm-apps` — **128K ⭐** — **Apache-2.0** — [GitHub](https://github.com/Shubhamsaboo/awesome-llm-apps)

**Creator:** Shubham Saboo (Sr. AI PM @ Google, Unwind AI newsletter, 350K+ AI dev community)
**License:** Apache-2.0 → clone, ship, sell free
**Last commit:** Jul 23, 2026 (very active, weekly drops)
**Models:** Works with Claude, Gemini, GPT, DeepSeek, Llama, Qwen

### 🧩 Agent Skills (installable into Claude Code / Codex / Cursor)
| Skill | What It Does | Business Fit |
|-------|-------------|-------------|
| Project Graveyard | Autopsies your dead side projects, tells you why | TFG (debug why projects stall) |
| Scope Creep Detector | Checks if a diff grew beyond stated intent | ProposalPal (scope control) |
| Commit Archaeologist | Reconstructs why any code exists via git | Dev workflows |
| Advisor Orchestrator Worker | Meta loop: Claude Fable 5 → GPT → Gemini | AI Night School curriculum |
| Self-Improving Agent Skills | Skills that rewrite themselves against evals | All (teaches agents to improve) |

### 🌱 Starter AI Agents (single-file, 1 API key)
| Agent | What It Does | Business Fit |
|-------|-------------|-------------|
| Meme Generator | Makes memes by driving a real browser | TFG social content |
| Music Generator | Prompt → MP3 track out | TFG, content creation |
| Travel Agent | Day-by-day personalized itineraries | General |
| Gemini Multimodal Agent | Video analysis + web search in one | AI Night School demos |
| Mixture of Agents | Multiple LLMs answer, one aggregates best | ProposalPal research |
| xAI Finance Agent | Real-time stock analysis via Grok | Personal finance |
| OpenAI Research Agent | Multi-agent topic research | ProposalPal, myAdjusterPRO |
| Web Scraping AI Agent | Describe what to extract, agent scrapes it | ProposalPal grant data |
| Data Analysis Agent | Query CSV/Excel in plain English | ProposalPal analytics |
| Medical Imaging Agent | X-ray/scan diagnostics with Gemini | General |
| Breakup Recovery Agent | Agent team that talks you through it | Fun / content |
| Blog to Podcast Agent | Turn any blog URL into narrated podcast | TFG, AI Night School content |

### 🚀 Advanced AI Agents (production-style)
| Agent | What It Does | Business Fit |
|-------|-------------|-------------|
| AI Deep Research Agent | Comprehensive web research (OpenAI + Firecrawl) | ProposalPal (grant research) |
| AI VC Due Diligence Agent Team | Multi-agent startup investment analysis | myAdjusterPRO investor pitch |
| AI Research Planner & Executor | Multi-phase research + auto-infographics | ProposalPal |
| AI Consultant Agent | Market analysis + strategy with web research | All (strategic planning) |
| AI System Architect Agent | Architecture reviews (DeepSeek R1 + Claude) | Dev workflows |
| AI Fraud Investigation Agent | Cross-references public records | **myAdjusterPRO** 🎯 |
| AI Home Renovation Agent | Photo → renovation renders | Content / demo |
| DevPulse AI | Multi-agent signal intelligence digest | General monitoring |
| AI Product Launch Intelligence Agent | Competitor launch GTM intelligence | ProposalPal, myAdjusterPRO |
| AI Financial Coach Agent | Budget, debt, savings analysis | Personal finance |
| AI Investment Agent | Stock comparison (Yahoo Finance) | Personal finance |
| Earnings Call Analyst Agent | YouTube earnings → analyst workspace | myAdjusterPRO (public co claims) |
| AI Health & Fitness Agent | Diet + workout plans from goals | General |
| AI Journalist Agent | Researches, writes, edits articles | TFG content, AI Night School |
| AI Mental Wellbeing Agent | Coordinated support plans | General |
| AI Meeting Agent | Context, insights, strategy briefs pre-meeting | Sales / partnerships |
| AI Self-Evolving Agent | Rewrites its own workflows (EvoAgentX) | R&D |
| AI Sales Intelligence Agent Team | Competitive battle cards in real-time | ProposalPal, myAdjusterPRO |
| AI Social Media News & Podcast Agent | Curated briefs + generated podcasts | TFG content automation |
| Trust-Gated Multi-Agent Team | Hash-chained audit trail per action | Compliance (insurance) |

### 🤝 Multi-Agent Teams
| Team | What It Does | Business Fit |
|------|-------------|-------------|
| Competitor Intelligence Agent Team | Structured competitor teardowns | ProposalPal |
| Finance Agent Team | Analyst team in 20 lines of Python | Personal finance |
| Legal Agent Team | Research + contract analysis | myAdjusterPRO (claims disputes) |
| Real Estate Agent Team | Property search + market analysis | General |
| Recruitment Agent Team | Resume screening → interview scheduling | Hiring |
| Teaching Agent Team | Faculty of agents for learning paths | **AI Night School** 🎯 |
| Services Agency (CrewAI) | Digital agency that scopes software projects | ProposalPal dev |
| Game Design Agent Team | Full game concepts from design specialists | Content |
| Multimodal Coding Agent Team | Photo of bug → sandboxed solution | Dev workflows |
| Design Agent Team | Design critiques from Gemini panel | Brand |
| UI/UX Feedback Agent Team | Landing page feedback + auto-improved version | All products |
| Travel Planner Agent Team | Complete trip itinerary | General |

### 🗣️ Voice AI Agents
| Agent | What It Does | Business Fit |
|-------|-------------|-------------|
| Insurance Claim Live Agent Team | Real-time voice claim intake (Gemini Live) | **myAdjusterPRO** 🎯🎯 |
| Customer Support Voice Agent | Voice answers grounded in your docs | Possum, myAdjusterPRO |
| Voice RAG Agent (OpenAI SDK) | Ask PDFs questions, hear answers | All (document queries) |
| AI Audio Tour Agent | Self-guided audio tours | Content |

### ♾️ MCP AI Agents
| Agent | What It Does | Business Fit |
|-------|-------------|-------------|
| Browser MCP Agent | Drive a real browser via natural language | Web automation |
| GitHub MCP Agent | Explore/analyze repos in English | Dev workflows |
| Notion MCP Agent | Talk to Notion from terminal | Internal docs |
| Travel Planner MCP Agent | Itineraries on live Airbnb + Google Maps data | General |
| Multi-MCP Agent Router | Specialists, each wired to its own MCP server | **System architecture template** |

### 🖼️ Generative UI Agents (interactive UI, not just text)
| Agent | What It Does | Business Fit |
|-------|-------------|-------------|
| Generative UI Starter Project | Chat-driven kanban board | MVP prototyping |
| AI Dashboard Canvas Agent | Describe a dashboard → live canvas charts | ProposalPal analytics |
| AI MCP App Builder | Describe an MCP app → live sandboxed instance | Rapid prototyping |
| AI Shadcn Component Generator | Chat to production-ready shadcn components | All (UI dev) |
| AI Deep Research Agent (UI) | Research with live workspace cards | ProposalPal |

### 🎮 Game-Playing Agents
| Agent | What It Does |
|-------|-------------|
| AI 3D Pygame Agent | DeepSeek R1 writes PyGame code, runs live |
| AI Chess Agent | Agent White vs Agent Black |
| AI Tic-Tac-Toe Agent | Two LLMs battle move by move |

### 🛰️ Always-on Agents (scheduled background)
| Agent | What It Does | Business Fit |
|-------|-------------|-------------|
| HN Briefing Agent | Daily ranked brief to Slack/email | General monitoring |
| Release Radar Agent | Watches dependency releases for breaking/security | Dev ops |

### 📀 RAG Tutorials (20+ patterns)
| Tutorial | What It Covers | Business Fit |
|----------|---------------|-------------|
| Multimodal Agentic RAG | Gemini Embedding 2 + Google ADK | AI Night School curriculum |
| Deep Research RAG | Firecrawl + Gemini for comprehensive research | ProposalPal |
| Internet RAG | Multi-model internet-augmented generation | General |
| Enterprise RAG | Exa + Agno for business data | myAdjusterPRO |
| Voice RAG | Ask PDFs, hear answers (OpenAI SDK) | Possum |

### 🏆 Top Picks Per Business

| Business | Highest-Value Templates |
|----------|------------------------|
| **myAdjusterPRO** 🥇 | Insurance Claim Live Agent Team, Fraud Investigation Agent, Legal Agent Team, Earnings Call Analyst, Customer Support Voice, Sales Intelligence Team, Trust-Gated Agent Team |
| **ProposalPal** | Deep Research Agent, Consultant Agent, Competitor Intelligence Team, Web Scraping Agent, Sales Intelligence Team, Dashboard Canvas Agent, Data Analysis Agent |
| **AI Night School** | Teaching Agent Team, Medical Imaging Agent, Agent Skill tutorials, RAG tutorials, Self-Evolving Agent, System Architect Agent |
| **TFG / Content** | Blog to Podcast Agent, Journalist Agent, Music Generator, Meme Generator, Social Media News Agent, Audio Tour Agent |
| **Possum** | Customer Support Voice Agent, Voice RAG Agent, Always-on Agents |

> ⚠️ **Warning:** All templates use cloud LLM APIs (OpenAI, Gemini, Anthropic). None are optimized for local Jetson inference. But the architectures are reusable — swap the model provider for local models.

---

## 📋 Research & Web Tools

### Web Data
| Tool | Description | Status |
|------|-------------|--------|
| **Firecrawl** | Full-stack web scraping suite — search, scrape, map, crawl, extract, agent, monitor, interact, parse, feedback, research | ✅ Active |
| **Firecrawl SEO Audit** | SEO audit skill for site analysis | ✅ Active |

### Academic Research
| Tool | Description | Status |
|------|-------------|--------|
| **arXiv** | Academic paper search (AI/ML, math, physics) | ✅ Active |
| **BlogWatcher** | RSS/Atom blog monitoring | ✅ Active |

### Data Sources
| Dataset | Description | Stars | Link |
|---------|-------------|-------|------|
| **awesome-public-datasets** | 30+ categories of public datasets, 155+ contributors | ⭐ 77.6k | [GitHub](https://github.com/awesomedata/awesome-public-datasets) |

---

## 🗣️ Agents & Voice

| Tool | Description | Status | For |
|------|-------------|--------|-----|
| **LiveKit Agents** | Real-time voice/video AI agents for phone calls | 🔧 Needs Setup | Possum (Stress Test) |
| **Headroom** | AI token compression (evaluated but not adopted) | 🗄️ Archived | Was considered for Possum |

---

## 📱 Social Media & Content

### Scheduling & Publishing
| Tool | Description | Status | For |
|------|-------------|--------|-----|
| **Postiz** | AGPL self-hosted social media scheduler — 28+ platforms (Instagram, TikTok, YouTube, LinkedIn, X), AI content gen, approval workflows, analytics | ✅ Active | AutoNetwork SaaS |
| **Postiz Agent CLI** | CLI companion for Postiz — `posts:create`, `upload`, `analytics:platform` commands, AGPL 3.0 | ✅ Available | Automation |

### Platform-specific
| Platform | Method | Status | For |
|----------|--------|--------|-----|
| **X/Twitter** | xurl CLI (post, search, DM, media) | ✅ Active | Brand |
| **YouTube** | youtube-* skills (channel research, content analysis, branding) | ✅ Active | TFGtv, AI Night School |
| **Skool** | Community platform for BlakAI Labs / AI Night School | ✅ Active | AI Night School |
| **Instagram** | Via Postiz scheduling | ✅ Active | Brand |

---

## 🏗️ Development & Design

### Design / Creative
| Tool | Description | Status |
|------|-------------|--------|
| **Excalidraw** | Hand-drawn style diagrams | ✅ Active |
| **Claude Design** | HTML artifacts, landing pages, decks | ✅ Active |
| **Sketch** | Throwaway HTML mockups (2-3 variants) | ✅ Active |
| **Concept Diagrams** | Flat SVG diagrams (light/dark aware) | ✅ Active |
| **Architecture Diagram** | Dark-themed HTML architecture diagrams | ✅ Active |
| **p5.js** | Generative art, shaders, interactive, 3D | ✅ Active |
| **Meme Generation** | Real meme images by template | ✅ Active |
| **Popular Web Designs** | 54 design systems (Stripe, Linear, Vercel) as HTML/CSS | ✅ Active |
| **Hyperframes** | HTML video compositions, animated title cards | ✅ Active |
| **ComfyUI** | Image/video/audio generation | ✅ Active |

### Documents / Presentations
| Tool | Description | Status |
|------|-------------|--------|
| **PowerPoint** (python-pptx) | Create, read, edit .pptx decks | ✅ Active |
| **Excel** (openpyxl) | Build auditable Excel workbooks headless | ✅ Active |
| **NanoPDF** | Edit PDF text/typos/titles via NL prompts | ✅ Active |
| **OCR & Documents** | Extract text from PDFs/scans (pymupdf, marker-pdf) | ✅ Active |
| **MarkItDown** | PDF/DOCX/XLSX/PPTX → Markdown converter | ✅ Active |

### SaaS Builders / Platforms
| Tool | Description | Status | For |
|------|-------------|--------|-----|
| **Bubble** | No-code web app builder (MVP) | ✅ Active | MVP Development |
| **Make (Integromat)** | Automation workflows MCP | 🔧 Needs OAuth | Automation |
| **n8n** | Open-source workflow automation (self-host) | ⚡ Available | Alternative to Make |

### AI Avatar / Video Content
| Tool | Description | Status | For |
|------|-------------|--------|-----|
| **HeyGen** | AI avatar video generation — 20min production, proven at 2.5M followers | 🔧 Needs Account | TFG, AI Night School, myAdjusterPRO |
| **Synesthesia** | Alternative AI avatar + text-to-video platform | ⚡ Available | Content pipeline |

---

## 💼 Products & Businesses

### Active Products
| Product | Description | Revenue | Status |
|---------|-------------|---------|--------|
| **ProposalPal** | Grant drafting SaaS | $382 MRR (12 subs) | ✅ LIVE (v4) |
| **TFG / TheFuneralGuy** | Life insurance via Ethos partnership | Pre-revenue | ✅ Active |
| **AI Night School** | Adjuster AI training (community $1 + Accelerator $497/yr) | Active | ✅ LIVE |
| **AutoNetwork SaaS** | TV network content automation platform | Active | ✅ Deployed |

### In Development / Vision
| Product | Description | Status |
|---------|-------------|--------|
| **Possum** | AI simulation + Stress Test (B2B phone QA) | 🔧 In Development |
| **myAdjusterPRO** | Claims overflow marketplace — carrier-to-adjuster platform, 30-min SLA, 75/25 split | 🎯 Vision Stage |
| **BBIAI → BBANA** | Adjuster AI training platform (rebranding) | 🔧 In Development |
| **FlowShow** | Part of Ivey Engineering capstone suite | 🔧 In Development |

---

## 🔐 Security & Infrastructure

| Tool | Description | Status |
|------|-------------|--------|
| **1Password CLI** | Password/secret management | ✅ Active |
| **Sherlock** | OSINT username search (400+ platforms) | ✅ Active |
| **Unbroker** | Automated data broker removal | ✅ Active |
| **Web Pentest** | Authorized web penetration testing | ✅ Active |

---

## 🗄️ MCP Servers (Configured)

| Server | Type | Status | Tools Provided |
|--------|------|--------|---------------|
| **firecrawl-mcp** | npx command | ✅ Enabled | scrape, search, map, crawl, extract, agent, monitor, interact, parse, feedback, research_* |
| **coinbase** | CLI command | 🔧 Needs API Key | 21 tools (balance, orders, portfolios, convert, transfer, products) |
| **happyscribe** | HTTP OAuth | 🔧 Needs Auth | Transcription, subtitles, speaker management |
| **make** | HTTP OAuth (Make.com) | 🔧 Needs Auth | Automation workflow management |
| **unreal-engine** | HTTP (localhost:8000) | 🔧 Needs Server | Game engine tools |

---

## 🔧 Skills Ecosystem (Hermes)

### Software Development
- **plan** — Write actionable markdown plans
- **spike** — Throwaway experiments to validate ideas
- **systematic-debugging** — 4-phase root cause debugging
- **simplify-code** — Parallel 3-agent code cleanup
- **subagent-driven-development** — Execute plans via delegate_task subagents
- **test-driven-development** — RED-GREEN-REFACTOR workflow
- **code-wiki** — Generate wiki docs + Mermaid diagrams
- **codebase-inspection** — LOC, languages, ratios via pygount
- **requesting-code-review** — Pre-commit security scan + quality gates
- **node-inspect-debugger** — Chrome DevTools Protocol debugging
- **python-debugpy** — PDB REPL + remote DAP debugging
- **rest-graphql-debug** — API debugging (status codes, auth, schemas)

### GitHub (full suite)
- **github-auth** — HTTPS tokens, SSH keys, gh CLI
- **github-code-review** — PR diffs, inline comments
- **github-issues** — Create, triage, label, assign
- **github-pr-workflow** — Branch, commit, open, CI, merge
- **github-repo-management** — Clone/create/fork repos, releases

### DevOps
- **docker-management** — Container lifecycle management
- **inference-sh-cli** — 150+ AI apps via infsh CLI
- **watchers** — RSS/JSON API polling with watermark dedup
- **hermes-multi-instance-deployment** — Multi-process Hermes setup
- **omniroute-browser-use** — Free AI gateway + Browser-Use
- **pinggy-tunnel** — Zero-install SSH tunnels

### Company Building
- **company-builder** — Evidence-first company construction
- **one-three-one-rule** — Structured decision-making framework
- **brand-surface-deployment** — Brand audit + deploy across channels

### YouTube / Content
- **youtube-channel-research** — Competitor analysis, metrics, thumbnails
- **youtube-content** — Transcripts → summaries, threads, blogs
- **youtube-creator-branding** — Channel visual system critique/build

### Creative
- **ascii-art** — pyfiglet, cowsay, boxes, image-to-ascii
- **ascii-video** — Colored ASCII MP4/GIF from video/audio
- **manim-video** — 3Blue1Brown-style math/algo animations
- **songwriting-and-ai-music** — Songcraft + Suno AI prompts
- **humanizer** — Strip AI-isms, add real voice

### Productivity
- **google-workspace** — Gmail, Calendar, Drive, Docs, Sheets
- **notion** — Pages, databases, markdown via Notion API
- **obsidian** — Read, search, create, edit vault notes
- **airtable** — Spreadsheet-database REST API
- **shopify** — Admin & Storefront GraphQL APIs
- **memento-flashcards** — Spaced-repetition flashcard system
- **petdex** — Animated mascot selection for Hermes
- **siyuan** — SiYuan Note API for search/read/create

### Social Media / Communication
- **xurl** — X/Twitter v2 API (post, search, DM, media)
- **autonetwork-tfgtv-posting** — AutoNetwork content publishing
- **telegram-chat-organization** — DM vs Group rename/organize
- **yuanbao** — Group @mention, user info, member queries

### Note-Taking
- **qmd** — Search personal knowledge bases, notes, docs
- **obsidian** — Vault navigation and editing

### Finance
- **stocks** — Stock quotes, history, search, compare, crypto
- **3-statement-model** — Fully-integrated financial models in Excel
- **dcf-model** — DCF valuation models in Excel
- **comps-analysis** — Comparable company analysis in Excel
- **lbo-model** — LBO models in Excel
- **merger-model** — Accretion/dilution models in Excel
- **pptx-author** — Build PowerPoint decks headless
- **excel-author** — Build auditable Excel workbooks

### Research / OSINT
- **domain-intel** — Passive domain reconnaissance
- **osint-investigation** — SEC EDGAR, public records, entity search
- **polymarket** — Prediction market queries (markets, prices, orderbooks)
- **arxiv** — Academic paper discovery
- **blogwatcher** — RSS/Atom feed monitoring
- **gitnexus-explorer** — Codebase index + interactive KB
- **llm-wiki** — Build/query interlinked markdown KB

### Security
- **1password** — CLI auth and vault management
- **sherlock** — Social media username search
- **unbroker** — Automated data broker removal
- **web-pentest** — Authorized web pentesting
- **oss-forensics** — Supply chain investigation
- **godmode** — LLM jailbreak research

### Data Science / ML
- **chroma** — Embedding database
- **faiss** — Similarity search
- **pinecone** — Managed vector database
- **qdrant-vector-search** — Vector similarity search
- **whisper** — Speech recognition
- **stable-diffusion-image-generation** — Text-to-image
- **segment-anything-model** — Zero-shot image segmentation
- **audiocraft-audio-generation** — Text-to-music/sound
- **llama-cpp** — Local GGUF inference
- **outlines** — Structured JSON/regex/Pydantic generation
- **dspy** — Declarative LM programs
- **axolotl** — YAML LLM fine-tuning
- **unsloth** — 2-5x faster LoRA/QLoRA
- **huggingface-*** — Hub, accelerate, tokenizers
- **peft-fine-tuning** — LoRA/QLoRA for LLMs
- **evaluating-llms-harness** — lm-eval-harness (MMLU, GSM8K)
- **weights-and-biases** — Experiment tracking
- **serving-llms-vllm** — High-throughput LLM serving
- **modal-serverless-gpu** — Serverless GPU cloud
- **lambda-labs-gpu-cloud** — GPU cloud instances
- **nemo-curator** — GPU-accelerated data curation
- **tensorrt-llm** — NVIDIA inference optimization
- **instructor** — Structured data extraction via Pydantic
- **guidance** — Regex/grammar LLM output control
- **fine-tuning-with-trl** — SFT, DPO, PPO, GRPO
- **distributed-llm-pretraining-torchtitan** — PyTorch-native distributed pretraining
- **sparse-autoencoder-training** — SAE training
- **simpo-training** — Simple Preference Optimization
- **optimizing-attention-flash** — Flash Attention optimization
- **pytorch-fsdp** — Fully Sharded Data Parallel
- **pytorch-lightning** — High-level PyTorch
- **clip** — Vision-language model
- **llava** — Visual instruction following
- **obliteratus** — Abliterate LLM refusals

### Smart Home
- **openhue** — Philips Hue lights, scenes, rooms via OpenHue CLI

### Computer Use
- **computer-use** — Desktop automation (click, type, scroll, drag) via cua-driver

### Web Development
- **cloudflare-temporary-deploy** — Deploy Worker live, no account
- **page-agent** — Embed alibaba/page-agent into web applications

### MCP
- **fastmcp** — Build, test, inspect, install, deploy MCP servers
- **mcporter** — List, configure, auth, call MCP servers via CLI

### Migration
- **openclaw-migration** — Migrate OpenClaw customization footprint into Hermes

### Email
- **agentmail** — Dedicated AI agent email inbox via AgentMail
- **himalaya** — IMAP/SMTP email from terminal

### Telephony
- **telephony** — Phone capabilities via Hermes CLI

---

*Last updated: 2026-07-25*
