<h1 align="center">Yash Bhavsar</h1>

<p align="center">
  <b>Forward Deployed Software Engineer.</b> Production fintech infrastructure by day, agentic systems by night.
</p>

<p align="center">
  🏢 <a href="https://finaptive.com">Finaptive</a> &nbsp;·&nbsp; 🎓 Electrical Engineering &nbsp;·&nbsp; 🌐 <a href="https://yashexe.github.io">yashexe.github.io</a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yash-bhav"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://yashexe.github.io"><img src="https://img.shields.io/badge/Portfolio-1f1f1f?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
</p>

---

### Start with Adam

**[Adam](https://github.com/yashexe/Adam)** is an agentic outreach pipeline: a fresh job posting goes in, a personalized cold email to the person who can act on it comes out, sitting in Gmail Drafts. By design, **no code path in the repo can send an email**. Two Claude agents do the research and the writing; deterministic code owns every consequence.

- **8 stages, 2 tool-calling agents.** Agents propose, typed and audited code decides: address verification, send gating, per-company dedup and touch caps.
- **Measured, not vibed.** The LLM judge's scores matched real interview outcomes **7 for 7** in a ground-truth eval, over **300+ live postings** with frozen anchor postings as drift alarms.
- **The design rule, vindicated.** The contact-research agent named a real decision-maker **5/5**, and its one *high-confidence* address was wrong. A cheap deterministic check caught it before any human could act on it, lifting deliverable contacts from 3/5 to 5/5.

The [README](https://github.com/yashexe/Adam#readme) leads with the evidence tables, then the architecture.

---

### Also built

- **[asterion](https://github.com/yashexe/asterion)** finds asteroids in real telescope imagery. 100% recovery at SNR ≳ 11, zero false positives on injection-recovery benchmarks.
- **[code-atlas](https://github.com/yashexe/code-atlas)** turns a repo's full history into an explorable knowledge graph with ownership and risk lenses.
- **[stride](https://github.com/yashexe/stride)** screens equities for the turn from selling exhaustion to early accumulation. Every threshold config-driven, fully reproducible.
- **[algorithm-machine](https://github.com/yashexe/algorithm-machine)** is an event-driven trading engine where a risk gate has the final say on every order.

---

### What I do

I work on the parts of a system that are expensive to get wrong: **multi-tenant data pipelines, event-driven runtimes, and secure handling of financial data.** At Finaptive I build and operate the cloud data-integration platform our client delivery runs on: connectors that move financial data from ERP and finance systems into planning and analytics destinations, with the scheduling, tenant isolation, and reliability work that keeps pipelines trustworthy.

---

### 🛠 Tech

**Languages** &nbsp;·&nbsp; Python · C++ · JavaScript/TypeScript · SQL · Bash

**Backend & Data** &nbsp;·&nbsp; Flask · FastAPI · Celery · PostgreSQL · Redis · SQLAlchemy · Pydantic · Pandas/NumPy

**Cloud & Infra** &nbsp;·&nbsp; Azure (Container Apps, ACR) · Docker · Kubernetes · GitHub Actions CI/CD

**AI / Applied** &nbsp;·&nbsp; Claude API · agent orchestration · LLM-as-judge evals · PyTorch

---

### What I care about as an engineer

- Most of my design effort goes into what happens when a credential is corrupted, a job overruns its lock, or an upstream API lies about its status code.
- Same inputs, same output — screeners, scorers, and pipelines that are reproducible and auditable rather than vibes-based.
- I document architecture, gotchas, and contracts so the next person (or me in the future) isn't reverse-engineering silent failures at 2am.
