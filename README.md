# Hi, I'm Lyz1116-FOUND 👋

**Fudan University undergraduate · AI / Agents / Game AI / Optimization**

I like building AI systems that can be **run, tested, observed, and evaluated**, not just demonstrated in a notebook. My recent work focuses on coding agents, AI product engineering, game AI, reinforcement learning, and real-world combinatorial optimization.

> Current interests: **LLM Agents · AI Coding · Agent Harness · Game AI · Reinforcement Learning · AI Product Engineering**

## Featured work

| Project | What I built | Evidence |
|---|---|---|
| **[Agent Replay](https://github.com/Lyz1116-FOUND/agent-replay)** | A recorder, replay UI, evaluator, FastAPI service, and native ReAct coding-agent harness for Codex / Claude Code / OpenCode / Qoder / ZCode-style workflows. Includes tools, grader, retry, context compression, skills, MCP, reviewer, and multi-agent support. | Public beta; live demo; **130 live-model runs** across 13 variants × 10 tasks; context compression kept 10/10 completion while using about **47% of full-context total tokens**. |
| **[Beat Greedy](https://github.com/Lyz1116-FOUND/beat-greedy)** | A playable ToC algorithm game that turns 0/1 knapsack into a player-vs-greedy-boss experience. Built the product flow, interaction, scoring, visual system, audio, and deployment. | React 19 + TypeScript + Vite + Tailwind; **18 automated tests**; deployed online. |
| **[RealRoute-Bench](https://github.com/Lyz1116-FOUND/RealRoute-Bench)** | A real-city routing benchmark with unified problem definitions, data provenance, independent evaluation, exact/heuristic baselines, and dynamic-traffic acquisition. | **12 city worlds · 2,400 fixed road access points · N20/50/100/200 nested scales · 48 static duration/distance matrices**. |
| **[Computer Vision Colorization](https://github.com/Lyz1116-FOUND/Computer_Vision_Colorization)** | Course project on grayscale image colorization and conditional generation in Lab color space. | PyTorch / image generation workflow; paired with additional monocular-depth experiments on multi-GPU infrastructure. |

## Agent Replay

**Replay what a coding agent did — then verify whether it actually succeeded.**

- Record and replay real coding-agent sessions.
- Inspect edits, commands, tests, regressions, and recoveries on an interactive timeline.
- Compare multiple runs of the same task.
- Run a native Python ReAct harness with six built-in tools, independent grading, retries, context management, Skills, MCP, Reviewer, and Multi-Agent.
- Expose recording/evaluation through a FastAPI service.
- Evaluate system choices with measured experiments instead of relying on model self-reports.

**Live demo:** https://lyz1116-found.github.io/agent-replay/

## Beat Greedy

**Local optimum ≠ global optimum — turned into a small game.**

The player packs a bag while a greedy shopkeeper only looks at value/weight ratio. After submission, the game reveals the player's solution, the greedy baseline, and the true dynamic-programming optimum.

- Product idea → interaction → implementation → testing → deployment.
- Drag-and-drop gameplay, difficulty and timing, scoring, boss feedback, local persistence.
- Original SVG assets and WebAudio sound design.

**Play it:** https://beat-greedy-da-e676.vercel.app/

## Game AI & reinforcement learning

I have hands-on experience with game-agent development using **PPO / Actor-Critic / GAE / reward shaping / action masking**, including a KaiwuDRL-based real-time game environment. I also received a **National Third Prize in the Tencent Kaiwu Reinforcement Learning Competition**.

I am also an invited tester / real user of **TapTap GameBuddy**, and I am especially interested in AI products that combine visual understanding, domain knowledge, and real-time interaction inside games.

## Research & engineering

- **LLM / Agents:** ReAct, Function Calling, tool use, context management, evaluator/grader design, agent observability, prompt/agent experiments.
- **ML / DL:** PyTorch, Transformer, reinforcement learning, computer vision, conditional generation.
- **Optimization:** TSP/VRP-style combinatorial optimization, Gurobi, Concorde, LKH, OSRM-based routing pipelines.
- **Engineering:** Python, FastAPI, REST APIs, React, TypeScript, Vite, Tailwind CSS, Git, Docker, Linux.

## Selected recognition

- **National Third Prize**, Tencent Kaiwu Reinforcement Learning Competition
- **University Second-Class Scholarship**
- Academic performance: **top 20%** of cohort

## What I care about

I prefer projects where an AI system has to survive contact with reality: real tools, real state, real failures, real verification, and a user who needs to understand what happened.

For internships, I am particularly interested in **AI product engineering, coding agents, agent infrastructure/evaluation, game AI, and AI-native consumer products**.
