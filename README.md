<p align="center">
  <img src="./assets/profile-hero-v3.svg" alt="Rishii Kumar Singh, AI/ML researcher and full-stack builder. Co-Head and Research Intern at AIMS-DTU, formerly AI/ML Intern at WESEE." width="100%" />
</p>

<p align="center">
  <a href="https://portfolio-rishii.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-101B33?style=for-the-badge&logo=firefox&logoColor=2DE2E6" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/rishiikumarsingh/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:rishiikumarsingh2201@gmail.com"><img src="https://img.shields.io/badge/Email-B4235A?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://huggingface.co/LogicPalette"><img src="https://img.shields.io/badge/Hugging%20Face-FF9D00?style=for-the-badge&logo=huggingface&logoColor=111111" alt="Hugging Face" /></a>
  <a href="https://x.com/RishiiSingh2201"><img src="https://img.shields.io/badge/X-111827?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
</p>


## About

B.Tech Environmental Engineering at **Delhi Technological University** (2025 to 2029). Research Intern and Co-Head at **AIMS-DTU**, the university's AI/ML research community. Previously AI/ML Intern at **WESEE, Ministry of Defence**.

Most of my work sits on one problem: a model that sounds right is not the same as a model that is right. So I build retrieval systems that carry citations, evaluation harnesses that survive a second look, and vision pipelines that run on the machine in front of you instead of someone else's API.

**Currently:** knowledge-graph completion and source-faithfulness evaluation, working toward a first-author manuscript.


## Featured work

| Project | What it is | Notable |
| --- | --- | --- |
| **[Sherpa](https://github.com/RishiiGamer2201/sherpa)** | Terminal assistant that explains command output and errors using a local GGUF model. | Published to PyPI as [`sherpa-dev`](https://pypi.org/project/sherpa-dev/). No API key, no network after model download. `pip install sherpa-dev` |
| **[Nyaya Navigator](https://github.com/RishiiGamer2201/Gemma_Hack)** | Offline English/Hindi/Hinglish legal-information navigator. | 6,845 chunks from 30 official law PDFs. BM25 + EmbeddingGemma fused by reciprocal rank, with citation gates and refusal on unsupported claims. |
| **[PolyAgent CI](https://github.com/RishiiGamer2201/polyagent-ci)** | Orchestrates four coding agents across isolated Git worktrees. | Dependency-aware DAG with cycle detection, topological scheduling, contract review and test-gated merges. |
| **[Apna Saathi](https://github.com/RishiiGamer2201/apna-saathi)** | Offline Hindi household-assistance assistant for a constrained Jetson board, built on the Suno Sutra retrieval base. | SQLite FTS5 lexical retrieval with a local Qwen model over Ollama. Measured on the target board: 2.70 s median, 3.64 s at p90. |
| **[Jarvis](https://github.com/RishiiGamer2201/gesture-desktop-control)** | Gesture and voice desktop control for cursor, click, scroll and volume. | MediaPipe hand landmarks into a KNN classifier, with a Flask/Socket.IO dashboard. [Demo](https://www.youtube.com/watch?v=thcPBI7ImGQ) |

The rest, including hackathon work and smaller tools, is on [my portfolio](https://portfolio-rishii.vercel.app/#projects).


## Open source

I spend most of my open-source time in other people's repositories, which is where the review is real.

**35 merged pull requests across 15 repositories. 16 of those were merged by maintainers of projects I do not own.**

| Project | Contribution |
| --- | --- |
| [scikit-bio](https://github.com/scikit-bio/scikit-bio/pull/2556) | Replaced deprecated NumPy `assert_warns` across the test suite. |
| [scikit-verify](https://github.com/aadya940/scikit-verify/pull/32) | Differential coverage tests for binary ufuncs. |
| [Heliox-OS](https://github.com/VyomKulshrestha/Heliox-OS/pulls?q=is%3Apr+author%3ARishiiGamer2201) | 10 merged PRs: WebSocket token streaming, action parallelization with dependency analysis, agent capability auto-discovery, rolling context compression for ReAct loops, daemon auto-restart. |
| [AegisAI](https://github.com/SdSarthak/AegisAI/pulls?q=is%3Apr+author%3ARishiiGamer2201) | Bulk CSV import for AI system records, plus unit tests for the LLM client. |
| [SahiDawa](https://github.com/RatLoopz/sahidawa-india/pull/88) | Winston structured logging for the API. |

In **GSSoC 2026** I placed **1,662 of 47,951** (top 3.5%), with 2,507 points and 13 merged PRs across three projects.


## Research

At AIMS-DTU, under Prof. Dinesh K. Vishwakarma:

- **Knowledge-graph completion.** Reproducing TransE and RotatE baselines on FB15k-237 and WN18RR, and reading the evaluation protocol carefully enough to know what the numbers do not say.
- **Source-conditioned faithfulness.** A per-triple gate that asks whether the source document actually supports a triple an LLM extracted from it. A DeBERTa-v3 cross-encoder, with synthetic corruption controls and source-blind ablations, evaluated across WebNLG, DocRED, REBEL and SciERC. The distinction that matters here is faithfulness to a source, not truth in general.
- **Multilingual inductive entity retrieval.** BGE-M3 with LoRA, reciprocal queries and concept-disjoint splits, built to keep answer exposure out of the evaluation.

Manuscripts in preparation. Nothing submitted or accepted yet. I will update this line when that changes.


## Stack

**Languages:** Python, C++, TypeScript, JavaScript, SQL

**ML:** PyTorch, TensorFlow, scikit-learn, Hugging Face Transformers, OpenCV, MediaPipe, ONNX

**Retrieval and local inference:** FAISS, ChromaDB, BM25, SQLite FTS5, llama.cpp, GGUF, Ollama

**Services and data:** FastAPI, Flask, React, PostgreSQL, SQLite, Docker, pandas, QGIS


## Selected achievements

- **First place, Green Tag track at BITS APOGEE 2026.** Five-person team.
- **GSSoC 2026**, top 3.5% of 47,951 contributors.
- **Deep Learning Specialization** and **Machine Learning Specialization**, DeepLearning.AI. [[1]](https://coursera.org/verify/specialization/WQ6EOXR8U51L) [[2]](https://www.coursera.org/account/accomplishments/specialization/8JFNCYJQ96M7)
- **Data Science and AI**, IIT Madras. [[Certificate]](https://drive.google.com/file/d/1VwFnCool9CxFYaS2EHMN1GT0KXpJ7vlO/view)


<!--
  Contribution card. Hosted service, verified responding 17 Sep 2026.
  Do not swap this for github-readme-stats.vercel.app or
  github-readme-activity-graph.vercel.app: both are offline as of today
  (DEPLOYMENT_PAUSED and DEPLOYMENT_DISABLED respectively).

  To stop depending on a hosted service at all, add the workflow in
  .github/workflows/profile-summary-cards.yml, run it once from the Actions
  tab, then replace the block below with:

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile-summary-card-output/github_dark/0-profile-details.svg">
    <img alt="Summary of my GitHub contributions, languages and activity" src="./profile-summary-card-output/default/0-profile-details.svg" width="100%">
  </picture>
-->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=RishiiGamer2201&theme=github_dark">
  <img alt="Summary of my GitHub contributions, languages and activity" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=RishiiGamer2201&theme=default" width="100%">
</picture>

<p align="center"><em>Build things that matter. Ship things that work.</em></p>
