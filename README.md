<!--
  README STRUCTURE NOTES (for Vino, not for GitHub — strip before publishing if you want it clean):
  - Order: identity → current focus → projects (collapsible depth) → open source → skills → metrics → contact.
  - Interactivity here means two things GitHub actually renders: <details> collapsibles and dynamic
    generated images (typing SVG, contribution snake, live stats). No client-side JS is possible.
  - Collapsibles keep the top-level scan fast (recruiter) while letting engineers expand for depth.
  - The snake animation requires a one-time GitHub Actions setup — instructions at the bottom of this file.
  - Replace every [BRACKETED] placeholder before publishing.
-->

<div align="center">

# Vinothana Balakrishnan

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2F81F7&center=true&vCenter=true&width=600&lines=Software+Engineer+%7C+ML+Systems;Offline-first+RAG+%2F+Retrieval+Pipelines;Building+under+real+hardware+constraints" alt="Typing animation" />

[Portfolio](https://portfolio-vinothana.vercel.app/) · [LinkedIn](https://linkedin.com/in/vinothana-balakrishnan) · [Email](mailto:vinothanakrish05@gmail.com)

</div>

---

### Currently

Building **TaxMind**, an offline retrieval-augmented system over Indian tax law, and contributing to **EaseMotion CSS**, an open-source micro-interaction library. Based in Chennai, India.

---

### Featured Projects

**ClinIQ — Offline RAG System for Tamil Healthcare Q&A**
Built as ML Engineer for a 5-person team, TNSDC Naan Mudhalvan 2026 hackathon.

Hybrid BM25 + vector retrieval (Reciprocal Rank Fusion), ChromaDB + BioSentenceBERT embeddings, TinyLlama via Ollama for generation — running fully offline on CPU-only hardware.

<details>
<summary><b>Technical details</b></summary>
<br>

- **Problem:** Rural and Tamil-speaking users often lack reliable medical guidance without internet access.
- **Architecture:** Query → hybrid retrieval (BM25 + vector) → RRF re-ranking → confidence threshold check → TinyLlama generation.
- **Challenges:** Ran the full pipeline on CPU-only, low-spec hardware with no dedicated GPU; added confidence thresholding to reduce hallucinated medical answers; built a custom evaluation framework to validate retrieval quality.
- **Stack:** Python, ChromaDB, BioSentenceBERT, Ollama, BM25
- **Links:** [repo] · [demo]

</details>

**GrpStudy — Real-Time Collaborative Study Platform**

[One-line pitch — what does this solve for students?]

<details>
<summary><b>Technical details</b></summary>
<br>

- **Problem:** [fill in]
- **Architecture:** [core sync mechanism, data model]
- **Challenges:** Split Vercel/Render deployment; resolved SPA routing issues via `vercel.json` rewrites.
- **Stack:** [fill in]
- **Metrics:** [users / uptime / requests, if available — else delete this line]
- **Links:** [repo] · [live demo]

</details>

**EaseMotion CSS — Open Source Contributions**

Merged upstream: a pure-CSS wobble-focus tooltip component and a multi-mixin SCSS ripple-effect module for button micro-interactions.

<details>
<summary><b>Technical details</b></summary>
<br>

- **Wobble-focus tooltip:** Pure CSS, no JS dependency, checkbox-hack-free focus trigger.
- **Ripple mixin module:** SCSS mixins for reusable button micro-interactions across variants.
- **Links:** [merged PR #1] · [merged PR #2]

</details>

---

### Core Technical Skills

![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit--learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### GitHub Activity

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=VinothanaBalakrishnan05&show_icons=true&theme=dark&hide_border=true&count_private=true" height="150"/>

<img src="https://raw.githubusercontent.com/VinothanaBalakrishnan05/VinothanaBalakrishnan05/output/github-contribution-grid-snake.svg" alt="Contribution snake animation" />
</div>

---

<div align="center">
Open to SDE-1 / ML Engineer roles · <a href="mailto:vinothanakrish05@gmail.com">vinothanakrish05@gmail.com</a>
</div>

     this will look sparse -- worth adding once you have a few months of steady green squares.
-->
