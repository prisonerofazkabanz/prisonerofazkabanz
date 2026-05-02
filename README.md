## prisonerofazkabanz

Builder of autonomous intelligence systems — pipelines that ingest live data, run it through frontier AI, and publish structured analysis without human intervention.

---

### 📡 Active Projects

#### [fusion-tracker](https://github.com/prisonerofazkabanz/fusion-tracker)
Two fully autonomous AI pipelines running on a single repo, different cadences, shared architecture.

**Fusion Watch** — weekly fusion energy monitor  
Tracks KSTAR, Commonwealth Fusion, Helion, TAE/TMTG, ITER, and China's EAST program.  
Claude ingests RSS feeds across 6 companies every Monday, updates `data.json`, and the dashboard re-renders client-side automatically.  
→ [Live dashboard](https://prisonerofazkabanz.github.io/fusion-tracker/index.html)

**Grand Strategy Tracker** — monthly geopolitical intelligence briefing  
Monitors 6 active story threads: Iran, Qatar LNG, Russia, Venezuela, global chokepoints, US energy dominance.  
Claude produces structured HTML analysis, injects it into the live page via comment markers, and delivers a full formatted briefing by email on the 1st of every month.  
→ [Live dashboard](https://prisonerofazkabanz.github.io/fusion-tracker/grand-strategy.html)

---

### ⚙️ How the pipelines work


Both pipelines share a single `requirements.txt` and one `ANTHROPIC_API_KEY` secret.  
Neither requires a database, server, or any paid hosting beyond the Anthropic API.

---

### 🛠 Stack

![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-Opus%204-8A2BE2)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?logo=github-actions&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-deployed-222?logo=github)
![HTML](https://img.shields.io/badge/HTML%2FJS-vanilla-E34F26?logo=html5&logoColor=white)

---

*All analysis is AI-generated from public RSS sources. Updated automatically.*
