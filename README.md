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
- **openhue** — Philips Hue lights, scenes, rooms

### Email
- **agentmail** — Dedicated agent email inbox
- **himalaya** — IMAP/SMTP terminal email

---

## 🧩 Skills Catalog (Quick Reference)

All Hermes skills organized by category:

| Category | Skills |
|----------|--------|
| **agent-reach** | agent-reach |
| **autonomous-ai-agents** | antigravity-cli, blackbox, claude-code, codex, grok, hermes-agent, honcho, opencode, openhands |
| **communication** | one-three-one-rule, telegram-chat-organization |
| **computer-use** | computer-use |
| **creative** | architecture-diagram, ascii-art, ascii-video, baoyu-infographic, brand-surface-deployment, claude-design, comfyui, concept-diagrams, creative-ideation, creator-ecosystem-brand-rollout, creator-funnel-copy-architecture, design-md, excalidraw, humanizer, hyperframes, manim-video, meme-generation, p5js, popular-web-designs, pretext, sketch, songwriting-and-ai-music, touchdesigner-mcp, youtube-creator-branding, youtube-personal-branding |
| **data-science** | jupyter-live-kernel |
| **devops** | docker-management, hermes-multi-instance-deployment, inference-sh-cli, local-llm-with-hermes, omniroute-browser-use, pinggy-tunnel, watchers |
| **dogfood** | adversarial-ux-test, dogfood |
| **email** | agentmail, himalaya |
| **finance** | 3-statement-model, coinpicks-trade-executor, comps-analysis, dcf-model, excel-author, lbo-model, merger-model, pptx-author, stocks |
| **firecrawl** | firecrawl (15+ sub-skills: scrape, search, map, crawl, extract, agent, monitor, etc.) |
| **github** | codebase-inspection, github-auth, github-code-review, github-issues, github-pr-workflow, github-repo-management |
| **hermes-skills-catalog** | hermes-skills-catalog |
| **make** | make-api-shell-connection-workflow, make-e2b-code-execution, make-mcp-reference, make-module-configuring, make-scenario-building |
| **mcp** | fastmcp, mcporter |
| **media** | gif-search, heartmula, songsee, youtube-channel-research, youtube-content |
| **migration** | openclaw-migration |
| **mlops** | chroma, clip, distributed-llm-pretraining-torchtitan, faiss, guidance, huggingface-accelerate, huggingface-hub, huggingface-tokenizers, instructor, lambda-labs-gpu-cloud, llava, modal-serverless-gpu, nemo-curator, obliteratus, optimizing-attention-flash, peft-fine-tuning, pinecone, pytorch-fsdp, pytorch-lightning, qdrant-vector-search, simpo-training, slime-rl-training, sparse-autoencoder-training, stable-diffusion-image-generation, tensorrt-llm, whisper |
| **mlops/evaluation** | evaluating-llms-harness, weights-and-biases |
| **mlops/inference** | llama-cpp, outlines, serving-llms-vllm |
| **mlops/models** | audiocraft-audio-generation, segment-anything-model |
| **mlops/research** | dspy |
| **mlops/training** | axolotl, fine-tuning-with-trl, unsloth |
| **note-taking** | obsidian |
| **payments** | mpp-agent, stripe-link-cli, stripe-projects |
| **productivity** | airtable, canvas, company-builder, google-workspace, here.now, insurance-adjuster-ai-digital-product-systems, maps, memento-flashcards, nano-pdf, notion, ocr-and-documents, petdex, powerpoint, shop, shopify, siyuan, teams-meeting-pipeline, telephony |
| **reference** | tool-catalog |
| **research** | arxiv, bioinformatics, blogwatcher, darwinian-evolver, domain-intel, gitnexus-explorer, llm-wiki, osint-investigation, parallel-cli, polymarket, qmd, scrapling, youtube-channel-analysis |
| **security** | 1password, godmode, oss-forensics, sherlock, unbroker, web-pentest |
| **smart-home** | openhue |
| **social-media** | autonetwork-tfgtv-posting, multi-platform-profile-deploy, xurl |
| **software-development** | code-wiki, hermes-agent-skill-authoring, node-inspect-debugger, plan, python-debugpy, requesting-code-review, rest-graphql-debug, simplify-code, spike, subagent-driven-development, systematic-debugging, test-driven-development |
| **web-development** | cloudflare-temporary-deploy, page-agent |
| **yuanbao** | yuanbao |

---

## 📋 Provisioning Queue

Items that need API keys, OAuth, or setup before they can be used:

| # | Resource | Type | For Biz | Priority |
|---|----------|------|---------|----------|
| 1 | **Email Marketing API** (ConvertKit/Mailchimp) | API Key | ProposalPal + AI Night School | 🔴 High |
| 2 | **Twilio** (SID + Auth Token) | API Key | Possum | 🔴 High |
| 3 | **Stripe** (Secret + Publishable keys) | API Key | ProposalPal + AI Night School | 🔴 High |
| 4 | **Coinbase CDP API Key** | API Key | Crypto | 🟡 Medium |
| 5 | **Airtable API Key** | API Key | All businesses | 🟡 Medium |
| 6 | **Make.com OAuth** | OAuth Auth | Automation | 🟠 Low |
| 7 | **Happyscribe OAuth** | OAuth Auth | Transcriptions | 🟠 Low |
| 8 | **LiveKit** | API Key | Possum | 🟡 Medium |

---

## 🗺️ Repo Map

```
blakailabs/tool-catalog/
├── README.md        ← This file (living catalog)
├── TOOL_CATALOG.md  ← Full catalog
└── ...
```

*Last updated: 2026-07-24*
