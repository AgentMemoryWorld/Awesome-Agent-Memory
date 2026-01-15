<h1 align="center">Awesome-Agent-Memory</h2>



![](https://img.shields.io/badge/Status-Actively%20Maintained-1f6feb?style=for-the-badge)
[![](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/XXXX.XXXXX)
[![](https://img.shields.io/badge/Hugging%20Face-Profile-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/AgentMemoryWorld)
![](https://img.shields.io/github/last-commit/AgentMemoryWorld/Awesome-Agent-Memory?style=for-the-badge)


<h3 align="center">Rethinking Memory Mechanisms of Foundation Agents in the Second Half</h3>


<p align="center">
  <img src="img/road_map.png" width="800" />
  <br/>
  <span style="font-size: 16px;"><i>Figure 1: Roadmap of foundation agent memory (2023–2025)</i></span>
</p>


## 🗞️ News
- ✨ **2026-01-14** — Initialized Repository; added contents and figures.

## 📌 Introduction
As AI enters the **second half,** the core challenge shifts from chasing benchmark gains to delivering real utility in long-horizon, dynamic, and user-dependent environments—where agents face **context explosion** and must continuously accumulate, manage, and selectively reuse information across extended interactions.

This repository accompanies the survey *Rethinking Memory Mechanisms of Foundation Agents in the Second Half: A Survey*. The survey is based on a systematic literature collection and curates **218 key articles** published between **2023 Q1 and 2025 Q4**, and organizes foundation-agent memory via a unified taxonomy along three core design dimensions: **memory substrates**, **cognitive mechanisms**, and **memory subjects**. From a system perspective, it further analyzes memory operations in **single-agent and multi-agent** settings, highlights the growing role of **learning memory policies**, discusses **scaling** with context length and environment complexity, reviews **evaluation metrics and benchmarks**, and outlines six open challenges to guide next generation memory systems design.

<p style="color:#2ea44f;">
  <b>We will continuously update this repository with newly released papers and resources. Contributions and open new issues are highly welcome.</b>
</p>


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
- **Sensory memory**: captures high-frequency, immediate or time-sensative signals from recent inputs for rapid perception and filtering.
- **Working memory**: maintains short-term, task-relevant variables (goals, intermediate states, tool results) to support ongoing reasoning and action.
- **Episodic memory**: stores time-series interaction traces and experiences for later recall in similar situations.
- **Semantic memory**: abstracts stable facts and concepts from experiences/knowledge sources to enable generalization beyond specific episodes.
- **Procedural memory**: encodes reusable skills, routines, and action policies that improve how the agent acts over time.


### 3) Memory Subject (Who is Supported)
- **User-centric memory**: persistent user facts, preferences, and interaction history for personalization.
- **Agent-centric memory**: the agent’s own experience/trajectories/skills for task performance and self-improvement. 

Mememory operation and management, learning policy, scalability, evaluation please refer to Section 4~7 in our survey.

## 🧑‍💻 Applications

Foundation agent memory is a key component for **long-horizon performance and personalization** across a wide range of real-world domains, including **education**, **scientific research**, **gaming & simulation**, **robotics**, **dialog systems**, **healthcare**, **workflow automation**, **software engineering**, **online streaming & recommendation**, **information search**, **finance & accounting**, and **legal & consulting**. In practice, these settings often require agents to accumulate experiences, distill reusable skills, and maintain coherent histories over time. Please refer to Application in out survey for more details.

<p align="center">
  <img src="img/application.png" width="800" />
  <br/>
  <span style="font-size: 16px;"><i>
    Figure 3: Applications of the Foundation Agent Memory System.
  </i></span>
</p>

## 📑 Paper List
We curate and organize representative papers on foundation-agent memory using the taxonomy in the survey (Substrate, Cognitive Mechanism, and Subject). Below is a structured list to help you quickly navigate the design space.

**[The paper will be updated here soon]**

## ⭐ Star History
[![Star History Chart](https://api.star-history.com/svg?repos=AgentMemoryWorld/Awesome-Agent-Memory&type=Date)](https://star-history.com/#AgentMemoryWorld/Awesome-Agent-Memory&Date)

