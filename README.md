<h1 align="center">Awesome-Agent-Memory</h1>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![TMLR](https://img.shields.io/badge/TMLR-Accepted-d90429?style=flat&logo=openreview&logoColor=white)](https://openreview.net/forum?id=XycbogUAeJ)
[![Survey Certification Award](https://img.shields.io/badge/🏆%20Survey%20Certification%20Award-d90429?style=flat)](https://openreview.net/forum?id=XycbogUAeJ)
[![arXiv](https://img.shields.io/badge/arXiv-2602.06052-b31b1b.svg?style=flat&logo=arxiv)](https://arxiv.org/abs/2602.06052)
[![HuggingFace](https://img.shields.io/badge/🤗%20Hugging%20Face-Paper-FFD21E?style=flat)](https://huggingface.co/papers/2602.06052)
[![Last Commit](https://img.shields.io/github/last-commit/AgentMemoryWorld/Awesome-Agent-Memory?style=flat&color=blue)](https://github.com/AgentMemoryWorld/Awesome-Agent-Memory)
![Maintenance](https://img.shields.io/badge/Maintained-yes-green.svg?style=flat)
[![Google Scholar](https://img.shields.io/badge/Google-Scholar-4285F4?style=flat&logo=googlescholar&logoColor=white)](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C14&q=Rethinking+Memory+Mechanisms+of+Foundation+Agents+in+the+Second+Half%3A+A+Survey&btnG=)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat)](LICENSE)
<h3 align="center">Rethinking Memory Mechanisms of Foundation Agents in the Second Half: A Survey</h3>

<p align="center">
  <a href="https://openreview.net/forum?id=XycbogUAeJ">
    <img alt="Accepted to TMLR with Survey Certification Award" src="https://img.shields.io/badge/🏆%20Accepted%20to%20TMLR%20—%20Survey%20Certification%20Award-d90429?style=for-the-badge&labelColor=8b0000">
  </a>
</p>


<p align="center">
  <img src="img/road_map.png" width="800" />
  <br/>
  <span style="font-size: 16px;"><i>Figure 1: Roadmap of foundation agent memory (2023–2025)</i></span>
</p>


## 🗞️ News

- 🏆 **2026-07-23** — ![NEW](https://img.shields.io/badge/NEW-d90429?style=flat) Our survey has been **accepted to [TMLR](https://openreview.net/forum?id=XycbogUAeJ)**, and received the **Survey Certification Award**! Huge thanks to everyone who contributed and gave feedback.
- 📚 **2026-07-22** — Paper list expanded with **972 new papers** covering 2025-12-01 to 2026-07-21, each tagged along the survey taxonomy (substrate / subject / cognitive mechanism). The list now holds **1,224 papers**.
- 🎉 **2026-02-09** — Our paper is now available on arXiv! Check it out: [Rethinking Memory Mechanisms of Foundation Agents in the Second Half: A Survey](https://arxiv.org/abs/2602.06052).
- 🚀 **2026-01-14** — Repository initialized with paper list, taxonomy figures, and full contents.

## 📌 Introduction
As AI enters the **second half,** the core challenge shifts from chasing benchmark gains to delivering real utility in long-horizon, dynamic, and user-dependent environments—where agents face **context explosion** and must continuously accumulate, manage, and selectively reuse information across extended interactions.

This repository accompanies the survey *Rethinking Memory Mechanisms of Foundation Agents in the Second Half: A Survey*. The survey is based on a systematic literature collection and curates **218 key articles** published between **2023 Q1 and 2025 Q4**, and organizes foundation-agent memory via a unified taxonomy along three core design dimensions: **memory substrates**, **cognitive mechanisms**, and **memory subjects**. From a system perspective, it further analyzes memory operations in **single-agent and multi-agent** settings, highlights the growing role of **learning memory policies**, discusses **scaling** with context length and environment complexity, reviews **evaluation metrics and benchmarks**, and outlines six open challenges to guide next generation memory systems design.

> 💡 **We will continuously update this repository with newly released papers and resources. Contributions and open new issues are highly welcome.**


## 🗂️ Taxonomy

We categorize foundation agent memory along three orthogonal perspectives in Figure 2: **Memory Substrate**, **Memory Cognitive Mechanism**, and **Memory Subject**.

<p align="center">
  <img src="img/memory_main-compressed.png" width="800" />
  <br/>
  <span style="font-size: 16px;"><i>
    Figure 2: Taxonomy of Foundation Agent Memory — organized by (1) Memory Substrate (internal and external),
    (2) Memory Cognitive Mechanism (episodic, semantic, sensory, working, procedural), and
    (3) Memory Subject (user-centric and agent-centric).
  </i></span>
</p>

### 1) Memory Substrate (What Form is Represented)
- **External memory**: non-parametric stores (e.g., databases, vector stores, logs) that can be written/read by the agent.
- **Internal memory**: information internalized into model states or parameters.

### 2) Memory Cognitive Mechanism (How Memory Functions)
- **Sensory memory**: captures high-frequency, immediate or time-sensitive signals from recent inputs for rapid perception and filtering.
- **Working memory**: maintains short-term, task-relevant variables (goals, intermediate states, tool results) to support ongoing reasoning and action.
- **Episodic memory**: stores time-series interaction traces and experiences for later recall in similar situations.
- **Semantic memory**: abstracts stable facts and concepts from experiences/knowledge sources to enable generalization beyond specific episodes.
- **Procedural memory**: encodes reusable skills, routines, and action policies that improve how the agent acts over time.


### 3) Memory Subject (Who is Supported)
- **User-centric memory**: persistent user facts, preferences, and interaction history for personalization.
- **Agent-centric memory**: the agent’s own experience/trajectories/skills for task performance and self-improvement. 

For memory operations & management, learning policies, scalability, and evaluation, please refer to Sections 4–7 of our survey.

## 🧑‍💻 Applications

Foundation agent memory is a key component for **long-horizon performance and personalization** across a wide range of real-world domains, including **education**, **scientific research**, **gaming & simulation**, **robotics**, **dialog systems**, **healthcare**, **workflow automation**, **software engineering**, **online streaming & recommendation**, **information search**, **finance & accounting**, and **legal & consulting**. In practice, these settings often require agents to accumulate experiences, distill reusable skills, and maintain coherent histories over time. Please refer to application in out survey for more details.

<p align="center">
  <img src="img/application.png" width="800" />
  <br/>
  <span style="font-size: 16px;"><i>
    Figure 3: Applications of the Foundation Agent Memory System.
  </i></span>
</p>

## 📑 Paper List
We curate and organize representative papers on foundation agent memory using the taxonomy in the survey (Substrate, Cognitive Mechanism, and Subject). Below is a structured list to help you quickly navigate the design space.

### 📊 Statistics

<p align="center">
  <img alt="Total" src="https://img.shields.io/badge/Total-1%2C224_papers-1f6feb?style=for-the-badge&logo=bookstack&logoColor=white">
  <img alt="Span" src="https://img.shields.io/badge/Span-2021.07_→_2026.07-6e7681?style=for-the-badge">
  <img alt="Tagged" src="https://img.shields.io/badge/Tagged-1%2C205-2ea043?style=for-the-badge">
</p>

<details open>
<summary><b>📈 Papers per month</b> — the field&rsquo;s growth since 2025-08</summary>

| Month | Papers | |
|:--|--:|:--|
| `2025-08` | **6** | █ |
| `2025-09` | **7** | █ |
| `2025-10` | **32** | ████ |
| `2025-11` | **33** | █████ |
| `2025-12` | **96** | █████████████ |
| `2026-01` | **149** | █████████████████████ |
| `2026-02` | **118** | ████████████████ |
| `2026-03` | **126** | █████████████████ |
| `2026-04` | **111** | ███████████████ |
| `2026-05` | **153** | █████████████████████ |
| `2026-06` | **159** | ██████████████████████ |
| `2026-07`<sup>*</sup> | **95** | █████████████ |

<sub><sup>*</sup> 2026-07 is a partial month (through 2026-07-21).</sub>

</details>

<details open>
<summary><b>📅 Papers per year</b></summary>

| Year | Papers | |
|:--|--:|:--|
| `2021` | **1** | █ |
| `2023` | **39** | █ |
| `2024` | **57** | █ |
| `2025` | **216** | █████ |
| `2026`<sup>*</sup> | **911** | ██████████████████████ |

<sub><sup>*</sup> 2026 is partial (through July).</sub>

</details>

<details open>
<summary><b>🗂️ Papers per taxonomy</b> — shares over the 1,205 tagged papers</summary>

| Dimension | Tag | Papers | Share | |
|:--|:--|--:|--:|:--|
| **Substrate** | ![external](https://img.shields.io/badge/external-3b82f6?style=flat) | **1,108** | 92% | █████████████████ |
|  | ![internal](https://img.shields.io/badge/internal-f97316?style=flat) | **108** | 9% | ██ |
| **Subject** | ![agent](https://img.shields.io/badge/agent-10b981?style=flat) | **814** | 68% | ████████████ |
|  | ![user](https://img.shields.io/badge/user-a855f7?style=flat) | **391** | 32% | ██████ |
| **Mechanism** | ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) | **859** | 71% | █████████████ |
|  | ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat) | **797** | 66% | ████████████ |
|  | ![working](https://img.shields.io/badge/working-6366f1?style=flat) | **372** | 31% | ██████ |
|  | ![procedural](https://img.shields.io/badge/procedural-84cc16?style=flat) | **338** | 28% | █████ |
|  | ![sensory](https://img.shields.io/badge/sensory-06b6d4?style=flat) | **133** | 11% | ██ |

</details>

> **Reading the shares.** *Subject* is single-label, so its two shares sum to 100%. *Mechanism* is multi-label — a paper may exercise several, averaging **2.07** per paper, so its shares sum well above 100%. *Substrate* is normally single-label, but **11 hybrid papers** (MemGPT, Memory³, MemoRAG, Memento, …) carry both tags. The **19 untagged entries** are benchmarks, datasets and surveys, which are listed but propose no memory mechanism of their own.

### 📂 Browse the full list

The list is split by year so each file stays fast to load and search.

| Year | Papers | List |
|:--|--:|:--|
| **2026** | 911 | [`papers/2026.md`](papers/2026.md) |
| **2025** | 216 | [`papers/2025.md`](papers/2025.md) |
| **2024** | 57 | [`papers/2024.md`](papers/2024.md) |
| **2023 and earlier** | 40 | [`papers/2023-and-earlier.md`](papers/2023-and-earlier.md) |
| | **1224** | |

### 🆕 Latest 30 papers

- **2026-07-21** [arxiv 2026] [Supra Cognitive Modes: A Routed Architecture for Agent Memory](https://arxiv.org/abs/2607.19096) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![user](https://img.shields.io/badge/user-a855f7?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-21** [arxiv 2026] [Mi-Memory: A Lifecycle Memory Framework for Personal AI](https://arxiv.org/abs/2607.18975) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![user](https://img.shields.io/badge/user-a855f7?style=flat) ![sensory](https://img.shields.io/badge/sensory-06b6d4?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-21** [arxiv 2026] [WorldScape Policy 2.0: Empowering Steerable World Action Modeling with Reasoning-Augmented Memory](https://arxiv.org/abs/2607.18840) ![internal](https://img.shields.io/badge/internal-f97316?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![sensory](https://img.shields.io/badge/sensory-06b6d4?style=flat) ![working](https://img.shields.io/badge/working-6366f1?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat)

- **2026-07-21** [arxiv 2026] [SkillSight: Seeing Through Shared Descriptions for Accurate Skill Retrieval](https://arxiv.org/abs/2607.18785) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![procedural](https://img.shields.io/badge/procedural-84cc16?style=flat)

- **2026-07-20** [arxiv 2026] [RoboHarness: Memory-Driven Orchestration of Heterogeneous Robot Policies for Long-Horizon Planning](https://arxiv.org/abs/2607.18060) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat) ![procedural](https://img.shields.io/badge/procedural-84cc16?style=flat)

- **2026-07-20** [arxiv 2026] [Exploratory and Assimilating Reflection: Reflective Recall Cycle for Long-term Memory](https://arxiv.org/abs/2607.17879) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![user](https://img.shields.io/badge/user-a855f7?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-20** [arxiv 2026] [From Blind Search to Memory-Aware Evolution: Efficient DBMS Tuning via Collaborative Diagnosis and Utility-Aware Retrieval](https://arxiv.org/abs/2607.17841) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-20** [arxiv 2026] [VLN-AVP: Zero-Shot Vision-Language Navigation with Hybrid Long-Short-Term Memory for Autonomous Valet Parking](https://arxiv.org/abs/2607.17767) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![sensory](https://img.shields.io/badge/sensory-06b6d4?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat) ![procedural](https://img.shields.io/badge/procedural-84cc16?style=flat)

- **2026-07-20** [arxiv 2026] [Mechanistic Attention Guidance for Agent Memory Refinement](https://arxiv.org/abs/2607.17621) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-20** [arxiv 2026] [Insecure Coding Preferences in Long-Term Memory: Security Risks for LLM-based Code Generation](https://arxiv.org/abs/2607.17619) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![user](https://img.shields.io/badge/user-a855f7?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat) ![procedural](https://img.shields.io/badge/procedural-84cc16?style=flat)

- **2026-07-20** [arxiv 2026] [ZifaMem: Structured Memory for Persona, Preference, and Emotional Continuity in AI Companions](https://arxiv.org/abs/2607.17564) [![stars](https://img.shields.io/github/stars/zifacorp/zifamem?style=social)](https://github.com/zifacorp/zifamem) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![user](https://img.shields.io/badge/user-a855f7?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-20** [arxiv 2026] [Retain or Consolidate? Budget-Dependent Operator Selection for Language Agent Memory](https://arxiv.org/abs/2607.17545) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![user](https://img.shields.io/badge/user-a855f7?style=flat) ![working](https://img.shields.io/badge/working-6366f1?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-19** [arxiv 2026] [MechMem-RTL: Reusing Verified Mechanism Memories for LLM-Based RTL Repair](https://arxiv.org/abs/2607.17053) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat) ![procedural](https://img.shields.io/badge/procedural-84cc16?style=flat)

- **2026-07-18** [arxiv 2026] [AgentBrew: Lifelong Knowledge Brewing from Strong Teachers to Weak LLM Agents](https://arxiv.org/abs/2607.16851) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat) ![procedural](https://img.shields.io/badge/procedural-84cc16?style=flat)

- **2026-07-18** [arxiv 2026] [Beyond Memory Leaderboards: Evaluating Scientific Memory as Budgeted Context Restoration](https://arxiv.org/abs/2607.16848) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![working](https://img.shields.io/badge/working-6366f1?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-18** [arxiv 2026] [RECON: Benchmarking Agent Memory for Compositional Reasoning over Long Contexts](https://arxiv.org/abs/2607.16716) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-18** [arxiv 2026] [PhyAgentOS: A Self-Evolving Operating System for Embodied Agents with Decoupled Cognitive Planning and Physical Execution](https://arxiv.org/abs/2607.16636) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![working](https://img.shields.io/badge/working-6366f1?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-18** [arxiv 2026] [From Memory to Skills: Evidence-Grounded Co-Evolution Governance for Long-Horizon LLM Agents](https://arxiv.org/abs/2607.16621) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat) ![procedural](https://img.shields.io/badge/procedural-84cc16?style=flat)

- **2026-07-17** [arxiv 2026] [RECAP: Feedback-Driven Streaming Semantic User Profiles for Short-Video Recommendation](https://arxiv.org/abs/2607.15730) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![user](https://img.shields.io/badge/user-a855f7?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-17** [arxiv 2026] [Do Agents Dream of False Memories? Black-box Visual Attacks on Long-term Memory in Multimodal AI Agents](https://arxiv.org/abs/2607.15657) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![user](https://img.shields.io/badge/user-a855f7?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-16** [arxiv 2026] [SearchOS-V1: Towards Robust Open-Domain Information-Seeking Agent Collaboration](https://arxiv.org/abs/2607.15257) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![working](https://img.shields.io/badge/working-6366f1?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat) ![procedural](https://img.shields.io/badge/procedural-84cc16?style=flat)

- **2026-07-16** [arxiv 2026] [MemPoison: Uncovering Persistent Memory Threats and Structural Blind Spots in LLM Agents](https://arxiv.org/abs/2607.14651) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-16** [arxiv 2026] [Bad Memory: Evaluating Prompt Injection Risks from Memory in Agentic Systems](https://arxiv.org/abs/2607.14611) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat) ![procedural](https://img.shields.io/badge/procedural-84cc16?style=flat)

- **2026-07-16** [arxiv 2026] [Memory-Driven Self-Disclosure and Relational Turning Points: A Longitudinal Multimodal Study of Human-AI Interaction](https://arxiv.org/abs/2607.14593) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![user](https://img.shields.io/badge/user-a855f7?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-16** [arxiv 2026] [VTM-Nav: Hierarchical Visual-Topological Memory for Cross-Episode Object-Goal Navigation](https://arxiv.org/abs/2607.14514) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-16** [arxiv 2026] [RetroAgent: Harnessing LLMs to Search Over Structured Memory for Agentic Retrosynthesis Planning](https://arxiv.org/abs/2607.14512) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![working](https://img.shields.io/badge/working-6366f1?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-15** [arxiv 2026] [CatalogAgent: A Supervisor-mediated Self-Learning System Enabling Context Engineering for GenAI Models](https://arxiv.org/abs/2607.14396) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-15** [arxiv 2026] [Why Git Is the Memory Solution for the Agentic Development Lifecycle](https://arxiv.org/abs/2607.14390) [![stars](https://img.shields.io/github/stars/rekal-dev/rekal-cli?style=social)](https://github.com/rekal-dev/rekal-cli) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat)

- **2026-07-15** [arxiv 2026] [A Self-Evolving Agent for Longitudinal Personal Health Management](https://arxiv.org/abs/2607.13940) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![user](https://img.shields.io/badge/user-a855f7?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat) ![procedural](https://img.shields.io/badge/procedural-84cc16?style=flat)

- **2026-07-15** [arxiv 2026] [Experience Memory Graph: One-Shot Error Correction for Agents](https://arxiv.org/abs/2607.13884) ![external](https://img.shields.io/badge/external-3b82f6?style=flat) ![agent](https://img.shields.io/badge/agent-10b981?style=flat) ![episodic](https://img.shields.io/badge/episodic-ef4444?style=flat) ![semantic](https://img.shields.io/badge/semantic-f59e0b?style=flat) ![procedural](https://img.shields.io/badge/procedural-84cc16?style=flat)

> Showing the 30 most recent of **1224** papers — see the per-year lists above for the rest.

## ⭐ Star History
[![Star History Chart](https://api.star-history.com/svg?repos=AgentMemoryWorld/Awesome-Agent-Memory&type=Date)](https://star-history.com/#AgentMemoryWorld/Awesome-Agent-Memory&Date)

## 📚 Citation

If you find this survey or the paper list useful in your research, please consider citing:

```bibtex
@article{huang2026rethinking,
  title   = {Rethinking Memory Mechanisms of Foundation Agents in the Second Half: A Survey},
  author  = {Wei-Chieh Huang and Weizhi Zhang and Yueqing Liang and Yuanchen Bei and
             Yankai Chen and Tao Feng and Xinyu Pan and Zhen Tan and Yu Wang and
             Tianxin Wei and Shanglin Wu and Ruiyao Xu and Liangwei Yang and Rui Yang and
             Wooseong Yang and Chin-Yuan Yeh and Hanrong Zhang and Haozhen Zhang and
             Siqi Zhu and Henry Peng Zou and Wanjia Zhao and Song Wang and Wujiang Xu and
             Zixuan Ke and Zheng Hui and Dawei Li and Yaozu Wu and Langzhou He and
             Chen Wang and Xiongxiao Xu and Baixiang Huang and Juntao Tan and
             Shelby Heinecke and Huan Wang and Caiming Xiong and Ahmed A. Metwally and
             Jun Yan and Chen-Yu Lee and Hanqing Zeng and Yinglong Xia and Xiaokai Wei and
             Ali Payani and Yu Wang and Haitong Ma and Wenya Wang and Chenguang Wang and
             Yu Zhang and Xin Wang and Yongfeng Zhang and Jiaxuan You and Hanghang Tong and
             Xiao Luo and Xue Liu and Yizhou Sun and Wei Wang and Julian McAuley and
             James Zou and Jiawei Han and Philip S. Yu and Kai Shu},
  journal = {Transactions on Machine Learning Research},
  issn    = {2835-8856},
  year    = {2026},
  url     = {https://openreview.net/forum?id=XycbogUAeJ},
  note    = {Survey Certification Award}
}
```

<details>
<summary>arXiv preprint version</summary>

```bibtex
@article{huang2026rethinkingarxiv,
  title         = {Rethinking Memory Mechanisms of Foundation Agents in the Second Half: A Survey},
  author        = {Wei-Chieh Huang and Weizhi Zhang and Yueqing Liang and Yuanchen Bei and
                   Yankai Chen and Tao Feng and Xinyu Pan and Zhen Tan and Yu Wang and
                   Tianxin Wei and Shanglin Wu and Ruiyao Xu and Liangwei Yang and Rui Yang and
                   Wooseong Yang and Chin-Yuan Yeh and Hanrong Zhang and Haozhen Zhang and
                   Siqi Zhu and Henry Peng Zou and Wanjia Zhao and Song Wang and Wujiang Xu and
                   Zixuan Ke and Zheng Hui and Dawei Li and Yaozu Wu and Langzhou He and
                   Chen Wang and Xiongxiao Xu and Baixiang Huang and Juntao Tan and
                   Shelby Heinecke and Huan Wang and Caiming Xiong and Ahmed A. Metwally and
                   Jun Yan and Chen-Yu Lee and Hanqing Zeng and Yinglong Xia and Xiaokai Wei and
                   Ali Payani and Yu Wang and Haitong Ma and Wenya Wang and Chenguang Wang and
                   Yu Zhang and Xin Wang and Yongfeng Zhang and Jiaxuan You and Hanghang Tong and
                   Xiao Luo and Xue Liu and Yizhou Sun and Wei Wang and Julian McAuley and
                   James Zou and Jiawei Han and Philip S. Yu and Kai Shu},
  journal       = {arXiv preprint arXiv:2602.06052},
  year          = {2026},
  eprint        = {2602.06052},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CL},
  url           = {https://arxiv.org/abs/2602.06052}
}
```

</details>

You are also welcome to ⭐ star this repository and share it with others who work on foundation agent memory.
