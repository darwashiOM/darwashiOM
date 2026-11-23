<h1 align="center">Hi, I'm Anas Al Darwashi 👋</h1>

<p align="center">
  <b>Full-stack software engineer building AI products end to end: iOS, web, backend and cloud.</b><br/>
  Based in Muscat, Oman · Open to remote roles in any time zone · Full-time or contract
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/darwashi"><img src="https://img.shields.io/badge/LinkedIn-darwashi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:darwashi@udel.edu"><img src="https://img.shields.io/badge/Email-darwashi%40udel.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open%20to%20work-Remote-2ea44f?style=for-the-badge" alt="Open to work"/>
</p>

---

### 🚀 What I do

I take products from the first commit to something live. Most of my work has been at early-stage startups, where I owned the app, the API, the AI pipeline, the infrastructure and the security, usually all at once.

- **RIVR Health AI** ($500K raised): **Full-Stack Developer (iOS app, web and backend).** I'm the sole author of the iPhone/Android app and the web app, and wrote most of the Django backend.
- **Proxa Labs** ($300K raised): **Software Engineer.** I led engineering on an AI-first learning platform for biopharma and authored ~85% of the commits on its main product.

### 🛠️ Selected work

> These codebases are private, so here's what's inside them.

**RIVR Health AI: personal health records with AI**
- **iOS/Android app** (Expo / React Native + TypeScript): 35 screens, a native SwiftUI WidgetKit widget, an Apple HealthKit and Android Health Connect sync, and an offline-first API cache. Tokens are kept in the Keychain and there's a Face ID lock. 1,000+ tests.
- **Backend** (Python, Django REST Framework, Celery/Redis, PostgreSQL + pgvector): an async document pipeline (OCR → GPT-4o structured extraction → citations) and RAG Q&A with voice answers streamed over SSE. It also has field-level PII encryption, rate limiting and audit logs, backed by 1,272 pytest tests.
- **Web app** (Next.js 15, React 19): PIN-gated record sharing, upload portals with retries and idempotency keys, and QR phone↔computer pairing.
- I led the migration off Supabase to a self-hosted Django API and split the monorepo into three repos, each with its own CI and guarded deploys.

**Proxa Labs: AI training products for biopharma**
- **Forge** (FastAPI, SQLAlchemy, PostgreSQL row-level security, Redis workers): a multi-tenant AI content platform. It runs Claude on AWS Bedrock agents, uses RAG over per-tenant vector stores, and connects to 10 OAuth integrations (Microsoft 365, Slack, Salesforce, HubSpot, Veeva…). It has a workflow engine and exports to PDF, PPTX and SCORM.
- **Proxa Identity** (Node.js, Express, oidc-provider, PostgreSQL): a self-hosted OIDC SSO provider with SAML/OIDC federation, SCIM 2.0 and token exchange, backed by 466 tests.
- **Stage** (Node.js + React): an AI avatar roleplay trainer with Claude-based scoring and coaching, plus a partner REST API.
- **AWS infrastructure in Terraform**: ECS Fargate, Aurora PostgreSQL, ElastiCache, CloudFront and WAF, deployed through a gated CI/CD pipeline.

### 📦 Open-source projects

| Project | What it is | Stack |
|---|---|---|
| [**the-straight-path**](https://github.com/darwashiOM/the-straight-path) | An accessible, multilingual introduction to Islam ([live](https://the-straight-path-tsp.web.app)) | React · Vite · Firebase · TypeScript |
| [**meeting-copilot**](https://github.com/darwashiOM/meeting-copilot) | AI meeting copilot for the terminal: local transcription + suggestions | Python |
| [**realtime-context-tui**](https://github.com/darwashiOM/realtime-context-tui) | Live audio transcription + BM25 retrieval streamed into a TUI | Python · Textual |
| [**notebooklm-clone**](https://github.com/darwashiOM/notebooklm-clone) | Turns your sources into a two-host podcast | TypeScript · OpenAI · Kokoro TTS |

### 🧰 Tech stack

**Languages**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white"/>

**Frontend & mobile**<br/>
<img src="https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white"/>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>

**Backend & data**<br/>
<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white"/>

**AI**<br/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Claude%20on%20Bedrock-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG%20%2B%20pgvector-336791?style=flat-square"/>
<img src="https://img.shields.io/badge/AI%20agents-555555?style=flat-square"/>

**Cloud & DevOps**<br/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>

### 🎓 Education & certs

- **B.S. Cybersecurity Engineering, University of Delaware**: Cum Laude, minors in Computer Science and Computer Engineering
- CompTIA Security+ · Google Cybersecurity Certificate
- Arabic (native) · English (fluent) · 🏆 National chess champion (Oman)

---

<p align="center"><i>Hiring for a full-stack or AI engineer? <a href="https://www.linkedin.com/in/darwashi">Let's talk.</a></i></p>
