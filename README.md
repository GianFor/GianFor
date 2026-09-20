<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
    <img src="assets/header-light.svg" alt="Gianrico Fornari — machine learning, research, video" width="100%">
  </picture>
</div>

<p align="center">
  <a href="https://gianrico.xyz"><img src="https://img.shields.io/badge/Portfolio-gianrico.xyz-24292f?style=flat-square" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/gianrico-fornari"><img src="https://img.shields.io/badge/LinkedIn-gianrico--fornari-24292f?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:gianrico.fornari@gmail.com"><img src="https://img.shields.io/badge/Email-gianrico.fornari-24292f?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Turin,%20Italy-24292f?style=flat-square&logo=googlemaps&logoColor=white" alt="Turin, Italy">
</p>

I like building things. Retrieval systems, data pipelines, agentic workflows, research
benchmarks, a traffic dataset that didn't exist until I started collecting it. I'd rather have a
rough working thing in front of me than a clean plan for one.

Then I want to know *why* it works. Something I can't explain isn't finished — I'll go back down
into the algorithm until it makes sense, and my projects tend to grow a measurement rig along the
way: something that tells me what's real and which part to cut.

Before any of this I spent six years as a videomaker. That's where I learned to finish.

## What I've built

**[univaq-doc-rag](https://github.com/GianFor/univaq-doc-rag)** — retrieval over 148 university
regulation PDFs. It cites the source article under every claim, and stays quiet when it isn't sure
instead of dressing up the nearest article it found. **0.875 Recall@5** on a 145-question eval set
I wrote first. Then the harness made the calls: a better embedding model, **+13.9 Recall@5**; the
cross-encoder reranker, **cut** — it lost recall at 24× the latency.

**Reverse Reconstruction** — BSc thesis, **110/110 with honours**. A benchmark that asks whether an
LLM's explanation of a graph counterfactual still contains the explanation. It usually doesn't: the
model knows what changed, then fails to say it. Three independent evaluators from three providers
agree at **r ≥ 0.977**. Now becoming a paper.

**Turin traffic** — a service on my VPS that has been swallowing the city's sensor feed every five
minutes at **93% coverage**, with a spatio-temporal GNN on top. Real data, streaming and dirty,
collected rather than downloaded.

**Agent infrastructure** — event-driven agentic workflows in production on a VPS since 2025:
stateful multi-step tasks, tool calling, webhook-triggered pipelines, all containerised. The
orchestration is written by hand, not assembled low-code.

**20,000+ users** — two years keeping the University of L'Aquila's web platforms alive and
redesigning **7 department portals** end to end: legacy PHP, production incidents, WCAG 2.1 AA.
The least glamorous thing on this list, and the one that taught me the most.

## Now

- **MSc in Data Science & Engineering**, Politecnico di Torino, 2026 → 2028.
- **Research assistant** at the University of L'Aquila — XAI for graph neural networks. Paper in preparation.
- **Open to Summer 2027 internships** — machine learning, research engineering, data engineering.

## Also true

- **Six years as a freelance videomaker and photographer.** I learned to ship on a deadline and talk to clients long before I learned to train a model.
- **gianrico.csv** — I explain AI and data science on TikTok and Instagram.
- **Elected student representative** for my degree course and for the DISIM department, Student Liaison for the EULiST alliance, and on the team that ran the EULiST Student Conference 2025 — students from 10 partner universities.

## Toolbox

<p align="center">
  <img src="https://img.shields.io/badge/Python-24292f?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-24292f?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/PyTorch%20Geometric-24292f?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch Geometric">
  <img src="https://img.shields.io/badge/pandas-24292f?style=flat-square&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/Hugging%20Face-24292f?style=flat-square&logo=huggingface&logoColor=white" alt="Hugging Face">
  <img src="https://img.shields.io/badge/FastAPI-24292f?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Docker-24292f?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Linux-24292f?style=flat-square&logo=linux&logoColor=white" alt="Linux">
  <img src="https://img.shields.io/badge/SQL-24292f?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Java-24292f?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/TypeScript-24292f?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-24292f?style=flat-square&logo=react&logoColor=white" alt="React">
  <img src="https://img.shields.io/badge/Node.js-24292f?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
</p>

<div align="center">
  <sub>Turin, Italy · <a href="mailto:gianrico.fornari@gmail.com">gianrico.fornari@gmail.com</a></sub>
</div>
