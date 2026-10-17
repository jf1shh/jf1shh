<p align="center">
  <img src="assets/banner.svg" alt="Jared Fisher — 17 years on a live insurance claims desk, self-taught AI builder since March 2026, now building AI for insurance claims" width="100%">
</p>

I spent 17 years on a high-volume insurance claims desk — starting in the mailroom and working up through claims support, total loss adjusting, field appraisal, and senior auto appraisal — before I ever wrote a line of code. In March 2026, I started teaching myself to build with AI — no CS background, no bootcamp — because I kept seeing the gap between what frontline operational work actually needs and what most software assumes about it. My time on the desk ended in September 2026. Now I build claims AI full-time.

That combination is the whole thesis: **domain fluency in a regulated, high-volume operational environment, plus the ability to actually ship the tool the domain needs.**

### 🧾 Claims background

17 years, one company, four roles — claims support (starting in the mailroom) → senior total loss adjuster → field appraiser → senior auto appraiser. Day-to-day: total loss determinations, supplement review, fraud indicators, subrogation, complex shop disputes, OEM position statements — high-volume, regulated, zero patience for a tool that guesses.

### 🚀 Featured: ClaimsRAG

<a href="https://github.com/jf1shh/claims-rag">
  <img src="https://raw.githubusercontent.com/jf1shh/claims-rag/main/assets/demo.gif" alt="ClaimsRAG demo — a theft claim, an OEM parts rider audit, and a cited per-line-item answer from a local model" width="100%">
</a>

Local-first retrieval for auto claims, on synthetic data. Hybrid search and reranking, an agentic router that plans sub-queries across policy documents and the claim's own file, **cited answers, and a refusal instead of a guess when nothing relevant is found.** The test cases come from real desk judgment calls: exclusion stacking, regional labor-rate caps, endorsement math, subrogation eligibility. It is scored with dated quality and adversarial evaluations.

**[→ Repository](https://github.com/jf1shh/claims-rag)**

### 🛠️ Also: Agentic App Harness

<a href="https://jf1shh.github.io/agentic-app-harness/">
  <img src="https://raw.githubusercontent.com/jf1shh/agentic-app-harness/master/.github/screenshots/portfolio-hub.png" alt="Agentic App Harness — spec-driven monorepo dashboard" width="100%">
</a>

A spec-driven development harness that holds six real, deployed apps to one enforced quality bar — contract-first Zod schemas, BDD unit + E2E tests, accessibility gates, all **enforced in CI, not just documented.** It also closes its own improvement loop (Sense → Propose → Act → Verify → Learn) with **no embedded LLM and no API key** — the AI coding agent is a pluggable actuator, not a hardcoded dependency.

**[→ Live showcase](https://jf1shh.github.io/agentic-app-harness/) · [→ Repository](https://github.com/jf1shh/agentic-app-harness)**

<p align="center">
  <img src="https://img.shields.io/badge/guardrails-10%20self--tested-8b5cf6" alt="10 self-tested guardrails">
  <img src="https://img.shields.io/badge/learned%20lessons-58-6366f1" alt="58 learned lessons">
  <img src="https://img.shields.io/badge/apps-6%20live-14b8a6" alt="6 live apps">
</p>

### 🧰 What I build with

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/RAG-hybrid%20%2B%20rerank-0f766e?style=flat-square" alt="RAG: hybrid + rerank">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" alt="Zod">
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest">
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
</p>

### 🎯 What I'm building toward

AI product, solutions and implementation roles in **insurance and claims**: InsurTech and claims-software companies, carrier AI and claims-transformation teams, and insurance-domain AI evaluation. These are places where claims judgment decides whether an AI tool gets adopted. I'm most useful where the AI has to work inside real constraints: compliance, audit trails, high transaction volume, and users who have zero patience for a tool that guesses.
