<div align="center">

# Hassam Gani

### Teaching machines to learn from their own *mistakes.*

`reinforcement learning & NL2SQL research @ Columbia` · `founder of MorningsideMunch`

<a href="https://hassamgani.com"><img src="https://img.shields.io/badge/hassamgani.com-1a1a1a?style=for-the-badge&logo=safari&logoColor=white" /></a>
<a href="https://linkedin.com/in/hassamgani"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:gani.hassamabdul@gmail.com"><img src="https://img.shields.io/badge/Email-c0925e?style=for-the-badge&logo=maildotru&logoColor=white" /></a>

</div>

```
epoch 300 ······················· loss 0.012 ✓   trained on scroll
```

### `whoami`

I build reinforcement-learning and text-to-SQL agents at Columbia, then ship the
ones that make it out of the lab. Half of what I do is research; the other half is
keeping real software running, two papers in flight and one app a thousand students
open at lunch. I think in four languages and debug in all of them.

---

## 🔬 Research · Columbia DAPLab

**Reinforcement Learning Researcher** — self-improving reasoning · `Mar 2026 → now`

> Building a self-improvement framework (targeting **AAAI / ICLR**) that turns an
> LLM's own wrong answers into synthetic training data through a challenger–solver–critic
> **GRPO** self-play loop. Reproduced **R-Zero** across 4 base models and 7 math
> benchmarks, then showed its reported +6.49 gain shrinks to **+0.89** under a properly
> measured baseline. `+3.8 avg acc` on Qwen3-8B · `+9.1` on OlympiadBench · 30+ H100 runs.

**NL2SQL Researcher** — text-to-SQL · `May 2026 → now`

> Authoring an **ICLR submission** showing a **graph-based semantic layer** over raw
> table schemas makes LLM database agents more accurate on **BIRD** and **LiveSQLBench**,
> beating SQL-agent, Spider-Agent, and ReFoRCE. Wrote 9K+ lines of Python: auto-generated
> PuppyGraph schemas over **58 Postgres databases**, a Cypher ReAct agent with a matched
> SQL twin, and a GPT-5 eval harness over **1,350 tasks**. `8× graph-agent accuracy lift`.

<sub>Earlier: **ML Engineer & Researcher** @ Columbia Software Systems Lab, built cpyAnalyzer to catch malware hiding in pickle-based ML models (loaded 79.8% of benign models, rejected 100% of malicious).</sub>

---

## 🍽️ Ventures

**MorningsideMunch** — founder & CEO · [morningsidemunch.com](https://www.morningsidemunch.com/)

> The dining app for Columbia & Barnard. **1,000+ users** in under a month, over 30% of
> dining-plan holders, now in partnership talks to become Columbia's official dining app.
> Behind it: a Cloudflare-bypass scraping pipeline running headless Chromium in Vercel
> lambdas behind a Redis distributed lock, feeding a multi-tier cache and hand-rolled
> HTTP/2 APNs that cut per-refresh load from **20+ requests to 1** across **21 halls**.

---

## 🧪 Selected Projects

| Project | What it is | Stack |
|---|---|---|
| **[xPredict](https://github.com/HassamGani/xai)** · 🏆 xAI Hackathon Honorable Mention | Live prediction market pricing X posts in real time; 2 LightGBM models correcting engine prices in logit space | LightGBM · FastAPI · X API |
| **[FaceGuard](https://github.com/HassamGani/FaceGuard)** | FaceID for macOS that trains on your face in 6s without a GPU | OpenCV · numpy |
| **[SmartSnake](https://github.com/HassamGani/SmartSnake)** | A deep Q-learning agent that plays Snake; +733% by game 100 | PyTorch |
| **myHomer** | Campus-aware RAG advisor over a per-user ChromaDB index | RAG · ChromaDB · React |
| **[cpyAnalyzer](https://github.com/wunused/python-ast)** | ML code analyzer flagging malicious pickle transformations | Python · CPython |

---

## 🛠️ Toolkit

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![veRL](https://img.shields.io/badge/veRL-c0925e?style=flat-square)
![vLLM](https://img.shields.io/badge/vLLM-302f2c?style=flat-square)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

<div align="center">

<br>

*The rest of the training run lives at* **[hassamgani.com](https://hassamgani.com)** ↗

</div>
