# 🐳 OrcaEdit

**Create, refine, and transform presentations with the power of AI.**  
Website: https://orcaecho.ai • LinkedIn: (add yours) • Contact: jeffrey.luo@orcaecho.ai

---

## What we’re building
OrcaEdit is an AI-native presentation platform. Our focus:
- **AI Engine** for PPTX ↔ JSON round-trip (true edit, not images)
- **Interactive Rendering** for precise, real-time editing in the browser
- **Chatbot** for rewrite/summarize/structure and workflow automation

---

## Repositories (private, in active development)

- **OrcaEdit-Engine** — Core PPTX ↔ JSON conversion, layout extraction, export to PPTX.  
- **OrcaEdit-Renderer** — Interactive previews (Canvas/SVG), selection, drag/resize, undo/redo.  
- **OrcaEdit-Chatbot** — Agentic workflows and content generation; orchestration for slide tasks.  
- **OrcaEdit-API** — Public gateway: verifies Firebase tokens, enforces auth/quotas/billing; routes to core services.  
- **OrcaEdit-Web** — Next.js app: uploads, editing UI, chat, projects, auth.  
- **OrcaEdit-Infra** — IaC & deployments (Cloud Run, networking, observability), CI/CD templates.

> We keep core repos private while we iterate quickly. Public SDKs/docs will arrive as we open up integration paths.

---

## Architecture (at a glance)

