<h1 align="left">Hi, I'm Jonatas Silveira 👋</h1>

<p align="left">
  <b>Senior Software Engineer · AI Engineering · Integrations</b><br/>
  Calgary, Alberta, Canada · Software Developer at <a href="https://fusionmediayyc.com/">Fusion Media YYC</a>
</p>

<p align="left">
  <a href="https://www.linkedin.com/in/jonatas-riciano-silveira"><img src="https://img.shields.io/badge/LinkedIn-Jonatas%20Silveira-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:jonatasricianotj@gmail.com"><img src="https://img.shields.io/badge/Email-jonatasricianotj%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://fusionmediayyc.com/"><img src="https://img.shields.io/badge/Web-fusionmediayyc.com-111111?style=flat&logo=googlechrome&logoColor=white" alt="Fusion Media YYC"/></a>
</p>

I build **AI products that run in production**: retrieval-augmented search, voice agents, computer-vision pipelines and the platforms and integrations around them.

19+ years in software, most of them on the backend (PHP, Node.js, Python, SQL): microservices, cloud migrations and legacy modernization. Today I put that experience to work on LLMs, embeddings, vision models and agentic workflows, shipped on a multi-tenant platform that serves a dozen live client websites.

---

## 🧠 What I'm building now

### Multi-tenant AI content platform
A headless CMS and admin platform that powers **12+ production websites** (ecommerce, home services, events and photo archives).
- Next.js 16 · TypeScript · Prisma · PostgreSQL + **pgvector** · Supabase · Docker · Render · Cloudflare
- RBAC, multi-tenant data model, catalog and commerce, SEO, analytics, SMS/email campaigns, scoped API keys
- AI built in: rich-text-aware **translation**, **SEO generation**, **LLM spam classification**, **AI SMS copy**, blog review generation
- **AI commerce feeds** for ChatGPT shopping (OpenAI product feed spec) and Google Merchant Center, with GTIN validation and category resolution

### RAG site search with cited answers
"Ask the website" search over hundreds of CMS pages.
- **Hybrid retrieval**: pgvector semantic search + PostgreSQL full-text, fused with **Reciprocal Rank Fusion**, then **LLM re-ranking**
- **Streamed, cited answers** over a single SSE endpoint; Gemini embeddings; query-embedding cache and precomputed popular answers
- Evaluated with an offline test set: **hit@5 100 %, MRR 0.96**; results in **~250 ms** (≈45 ms cached)
- Usage-ranked homepage cards that combine search behaviour with editor pins

### AI room visualizer (computer vision)
Upload a photo of a room or house, pick a surface, see a stone product applied realistically.
- Surface segmentation with **Mask2Former**, **SAM 2 / SAM 3**, **Grounding DINO** and **CLIP**: walls, fireplaces, floors, columns and more, as polygons with holes
- **Server-side photoreal rendering** with physical product scale; product swap in **~0.15 s**
- Benchmarked state-of-the-art segmentation models (OneFormer, DINOv3, open-vocabulary, Gemini) before choosing the pipeline
- PyTorch · FastAPI · Django · Vue · Hugging Face · Apple MPS / GPU

### Conversational voice agents
- **ElevenLabs** voice agents embedded on client sites through a secure HTTP/WebSocket proxy
- **Agent tools** that call the platform's own APIs (live catalogue and pricing lookups)
- Conversation sync, transcripts, audio and analytics inside the admin panel; Twilio SMS on the same platform

### Permit intelligence RAG
Turns a city's open building-permit data into business intelligence through natural-language conversation.
- Natural-language questions answered as tables, charts and CSV
- pgvector semantic search, Gemini and OpenAI providers, scheduled ingestion, contact discovery and outreach campaigns
- TypeScript · Express · PostgreSQL · Zod · Puppeteer

### Business integrations
- **Zoho CRM / CPQ → QuickBooks** bridge: scheduled exports, invoice/payment worksheets, email delivery
- Square, UPS, Google Analytics 4, Google Search Console, Google Shopping Content API, Twilio, Short.io, Supabase Storage
- Price-list extraction from PDFs and spreadsheets into normalized catalogues (Python, pandas, pdfplumber)

### AI-assisted engineering
I work with coding agents every day (**Claude Code**, multi-agent workflows, custom **MCP servers**) for code reviews, migrations across a dozen repositories and R&D, backed by Playwright E2E tests, Vitest, Docker and CI.

---

## 🛠️ Tech stack

**AI & ML**

<p align="left">
  <img src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude"/>
  <img src="https://img.shields.io/badge/ElevenLabs-000000?style=for-the-badge&logo=elevenlabs&logoColor=white" alt="ElevenLabs"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="Model Context Protocol"/>
  <img src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="pgvector"/>
</p>

RAG · embeddings · hybrid search · re-ranking · LLM evaluation · voice agents · tool calling · segmentation (SAM, Mask2Former, Grounding DINO, CLIP) · Whisper

**Languages, frameworks, data and cloud**

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,nodejs,python,php,nextjs,react,vue,tailwind,express,django,fastapi,laravel,postgres,prisma,supabase,mongodb,redis,docker,cloudflare,aws,githubactions,linux&perline=11" alt="Tech stack"/>
</p>

**Integrations**

<p align="left">
  <img src="https://img.shields.io/badge/Zoho-E42527?style=flat&logo=zoho&logoColor=white" alt="Zoho"/>
  <img src="https://img.shields.io/badge/QuickBooks-2CA01C?style=flat&logo=quickbooks&logoColor=white" alt="QuickBooks"/>
  <img src="https://img.shields.io/badge/Twilio-F22F46?style=flat" alt="Twilio"/>
  <img src="https://img.shields.io/badge/Square-3E4348?style=flat&logo=square&logoColor=white" alt="Square"/>
  <img src="https://img.shields.io/badge/UPS-150400?style=flat&logo=ups&logoColor=FFB500" alt="UPS"/>
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white" alt="Google Cloud"/>
  <img src="https://img.shields.io/badge/Render-000000?style=flat&logo=render&logoColor=white" alt="Render"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white" alt="Supabase"/>
</p>

---

## 💼 Experience

**Fusion Media YYC** · Software Developer · *Calgary, Canada · Feb 2025 – Present*
- Architected the multi-tenant CMS and the Next.js sites it powers; designed a monorepo and shared site kit to cut cross-site maintenance
- Shipped RAG search, voice agents, AI commerce feeds and the AI visualizer described above
- Built and maintain the CRM, accounting, payments, shipping and analytics integrations for clients

**Dura Software** · Senior Software Developer · *Remote, USA · Dec 2023 – Aug 2024*
- Led the move from a monolith to Docker + RabbitMQ microservices
- Migrated infrastructure to AWS, cutting monthly operating costs by ~30 %
- Refactored Classic ASP services to PHP/Laravel; built iOS and Android apps with Cordova and React Native

**PROMAD** · Senior Software Developer · *Remote, Brazil · Sep 2016 – Dec 2023*
- Led the Oracle → PostgreSQL migration
- Built data-capturing robots with Node.js and PostgreSQL; drove modernization with Scrum and Kanban

**GRUPO API** · Full Stack Developer · *Brazil · May 2012 – Sep 2016*
- Extended legacy systems with PHP, Classic ASP, jQuery and Yii2; optimized services with Nginx and Elasticsearch

**WBI On Life, DBServer, BriviaDez** · Software Developer · *2007 – 2012*

---

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=jonatasriciano&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views"/>
</p>
