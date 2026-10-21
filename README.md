<div align="center">

# Hi, I'm Pranita 👋

**M.Tech CSE student building AI systems and backend services that solve real problems in India.**

Currently learning, shipping, and measuring.

[![Email](https://img.shields.io/badge/Email-pranitajeyan%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:pranitajeyan@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-pranitajeyan--cyber-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pranitajeyan-cyber)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-pranitajeyan--cyber-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/pranitajeyan-cyber)

</div>

---

## 🌱 What I'm working on

### Blood Donation Network — a predictive, escalating marketplace for blood

India collects ~11.9M units of blood a year and needs ~14.6M. That ~20% gap isn't random, and existing platforms (e-RaktKosh, Friends2Support) are *directories* — they react **after** a crisis.

So I built the two things a directory can't do:

- **Automatic escalation.** A request that finds no donor in 15 minutes expands its search radius (5 → 15 → 50 km). At 30 minutes it triggers a caregiver SMS blast. The engine is a pure function of elapsed time, so it's replayable and idempotent under retries.
- **Shortage forecasting.** Predicts units needed per blood group per district for the next 7 days — and publishes the accuracy number. A weekday-adjusted moving average scores **0.2211 mean WMAPE** against a seasonal-naive baseline's **0.7782**, both through the same backtest harness.

> I deliberately shipped an explainable baseline with a measured score rather than an unmeasured black box. The next model has to *beat 0.2211 on the same split* to ship.

### RAG Chat with Your Notes — retrieval-augmented Q&A over my own study material

Upload PDFs, TXT files, Markdown, a URL, or a YouTube link and ask questions — answers are generated **only** from my content, with every source cited. Runs fully local (Ollama + ChromaDB + `sentence-transformers`) or against free Gemini/Groq APIs.

---

## 🚀 Featured work

| Project | What it does | Stack | Highlights |
|---|---|---|---|
| **[Blood Donation Network](https://github.com/pranitajeyan-cyber/blood-donation-network)** | Predictive, escalating blood marketplace | FastAPI · SQLAlchemy · PostgreSQL · JWT | Donor matching engine, SLA escalation, backtested 7-day forecaster, barcode impact tracking · **72 tests, 82% coverage, CI on 3 Python versions** |
| **[RAG Chat with Your Notes](https://github.com/pranitajeyan-cyber/rag-chat-notes)** | Ask questions of your own study documents | Python · LangChain · ChromaDB · Streamlit | Overlapping smart chunking, local sentence embeddings, URL + YouTube ingestion, source citations, multi-provider LLM support |
| **[Mochi's AI Study Planner](https://github.com/pranitajeyan-cyber/study)** | AI-powered study planner with schedules, Pomodoro and progress tracking | Python · Streamlit · AI | Personalized study-plan generation, achievements and streaks, exam scheduling |
| **[M.Tech CSE — Learning Journey](https://github.com/pranitajeyan-cyber/mtech-cse)** | My coursework hub: projects, labs, research, tools, notes | Python · Markdown | Every lab cleaned up, every project given a real README — learning in public |
| **[Free Media Resources](https://github.com/pranitajeyan-cyber/Free-Media-Resources)** | Curated index of genuinely free media/design resources | Markdown | Photos, vectors, video, audio, fonts and mockups — all free, no hidden costs |

## 🛠️ Tech stack

<div align="center">

**Backend**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**AI / ML**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Chroma](https://img.shields.io/badge/ChromaDB-F3A13C?style=for-the-badge&logo=chroma&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-111111?style=for-the-badge&logo=ollama&logoColor=white)

**Frontend & Apps**
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=white)

**Tooling & Ops**
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

## 📊 GitHub stats

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=pranitajeyan-cyber&show_icons=true&include_all_commits=true&count_private=true&theme=radical)
&nbsp;&nbsp;
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs?username=pranitajeyan-cyber&layout=compact&theme=radical&langs_count=8)

</div>

<div align="center">

![Streak](https://github-readme-streak-stats.herokuapp.com?user=pranitajeyan-cyber&theme=radical&hide_border=true)

</div>

## 🧭 The journey

I'm an Integrated M.Tech CSE student (2025–2030 batch) at Sri Krishna College of Engineering and Technology, currently in my third semester.

I came in as a beginner. The plan I've been following:

| Phase | Focus | Outcome |
|---|---|---|
| **Sem 3** *(now)* | Foundations + exploration | DSA practice, taste-test each track, first real projects shipped |
| **Sem 4** | Pick a primary track | ~200 DSA problems, first full-stack + ML project |
| **Sem 5** | Depth + deployment | Cloud-deployed project, start freelancing |
| **Sem 6–7** | Specialisation + portfolio | Electives, third project, resume + mocks |
| **Sem 8–10** | Placement + venture | System design, internship, placement |

Three rules I keep coming back to:

1. **Consistency beats intensity.** Two hours every day beats fourteen on Sunday.
2. **Show work publicly.** GitHub, a blog, LinkedIn — employers hire evidence, not claims.
3. **Measure, don't assert.** Every number in my projects has a test behind it.

## 🏗️ How I work

- **Write it down first.** Design docs before code — Blood Donation Network shipped with a pitch, a technical framework and a build spec before a single line of Python.
- **Test the domain, not the framework.** The interesting logic lives in plain functions; the HTTP layer is a thin adapter over it.
- **Make CI do the policing.** Every push runs the suite and the linter across Python 3.11–3.13 on Ubuntu and Windows.
- **Write the trade-offs down.** My READMEs document what I *didn't* build and why, because that's the part a reviewer actually wants to talk about.
- **No half-baked code.** Every lab gets cleaned up. Every project gets a proper README.

## 🏆 Highlights

- 🥇 **Blood Donation Network** — 72 tests, 82% coverage, working escalation + forecasting engine, full demo script, CI green across 4 environments
- 🔍 **RAG Chat with Your Notes** — retrieval over PDFs, URLs and YouTube transcripts with local embeddings and source citations
- 📚 **M.Tech CSE Learning Journey** — a structured, public repo of coursework, labs and research notes
- 🔒 **DPDP Act–aligned design** — DigiLocker *attestation tokens* only, never identity numbers

## 📫 Let's connect

[![Email](https://img.shields.io/badge/Email-pranitajeyan%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:pranitajeyan@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-pranitajeyan--cyber-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pranitajeyan-cyber)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-pranitajeyan--cyber-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/pranitajeyan-cyber)

I'm open to internships, collaborative side projects, and conversations about RAG systems, ML forecasting, or anything with a hard constraint problem in it.

---

<div align="center">

![snake](https://github.com/platane/snk/raw/output/github-contribution-grid-snake-dark.svg)

*Python · FastAPI · LangChain · Streamlit · MIT & open source*

</div>
