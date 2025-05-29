# ✨ Eyes on Me

**AI insight from your own words.**

> *"Did you ever know that I had mine on you?"*

---

## What is this?

**Eyes on Me** is an AI-powered self-reflection engine. It watches your daily memos, processes them with LLMs, and delivers daily, weekly, and monthly reports that offer a new perspective on your thoughts, actions, and habits.

Not just note-taking. Awareness.

## Key Features

* 🧠 LLM-based log analysis
* 📊 Daily / Weekly / Monthly digest generation
* 🔁 Automated scheduling via Celery + Redis + Flower + Beat
* 🗃️ Clean separation of original data (memos.sqlite) and analysis results (analysis.sqlite)
* ☁️ Optional cloud sync to Cloudflare D1 for easy web access

## Philosophy

This is not about writing notes.
It's about building an evolving, self-aware knowledge system that reflects you — with the help of a tireless AI.

Your logs speak. This tool listens.

## Tech Stack

* Python
* SQLite (memos.sqlite + analysis.sqlite)
* Celery + Redis + Flower + Beat (task orchestration)
* No ORM. Raw SQL only.
* CLI-first architecture
* Optional: Cloudflare D1 for dashboard sync

## Folder Structure (WIP)

```
eyes-on-me/
├── extractor/
├── llm_analysis/
├── db_writer/
├── digest_generator/
├── reporter/
├── run_log_manager/
└── analysis.sqlite
```

## License

MIT – because insight should be free.

---

> *"How I loved your peaceful eyes on me."*
