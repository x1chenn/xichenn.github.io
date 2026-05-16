---
layout: about
title: about
permalink: /
subtitle: M.S.E. in Computer Science @ <a href='https://www.jhu.edu/'>Johns Hopkins University</a> · Machine Learning & Reinforcement Learning

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Department of Computer Science</p>
    <p>Johns Hopkins University</p>
    <p>Baltimore, MD, USA</p>

selected_papers: false # I have no publications yet — research projects are listed in the body instead
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

Hi! 👋 I'm **Xi Chen (陈希)**, a first-year **M.S.E. student in Computer Science** at **🏫 Johns Hopkins University**, where I work in the [ARCADE Lab](https://arcade.cs.jhu.edu/) with Dr. Lalithkumar Seenivasan and collaborate with Prof. Laixi Shi and Prof. Jianyi Yang on robust reinforcement learning. Before JHU, I received my B.Eng. in Computer Science from **Nankai University**.

I am broadly interested in **decision-making and perception for embodied agents**, and I am **applying for a Ph.D.** to pursue this direction. My current research focuses on:

- **World Models for Reinforcement Learning** — generative trajectory models, long-horizon value estimation, and distributionally robust offline RL under dynamics shift.
- **Vision-Language-Action (VLA) & Visual Foundation Models** — low-latency point-tracking and representation models that can serve as perception backbones for embodied and surgical agents.

Earlier work spans time-series learning, generative modeling, and computer vision. I enjoy problems where robust decision-making meets real deployment constraints.

---

## Selected Research Projects

**Track-Any-Point Foundation Model for Endoscopic Scenes** &nbsp; <span style="color: var(--global-text-color-light)">· Feb 2026 – Present</span>
*ARCADE Lab, Johns Hopkins University — with Dr. Lalithkumar Seenivasan*
A low-latency point-tracking foundation model for endoscopic surgery, tackling domain-specific challenges such as illumination shifts, specular reflections, occlusions, and textureless homogeneous regions. I designed a **knowledge-distillation** framework in which a Transformer teacher generates pseudo-trajectories to supervise a lightweight **CNN student** (D2-Net-inspired feature layers), targeting real-time deployment at **< 30 ms latency** while retaining Transformer-level tracking accuracy.
<span style="color: var(--global-text-color-light)">*Manuscript in preparation.*</span>

**Adversarial Finetuning of Generative World Models for Distributionally Robust Offline RL** &nbsp; <span style="color: var(--global-text-color-light)">· Apr 2026 – Present</span>
*Johns Hopkins University — with Prof. Laixi Shi, Prof. Jianyi Yang, and Jiaqi Wen*
A robust offline RL framework combining **flow-matching trajectory generation** with **distributionally robust optimization (DRO)**. The generative module synthesizes *H*-step future trajectories, enabling target-Q estimation beyond one-step Bellman backups and emphasizing long-horizon returns; a DRO objective identifies worst-case trajectory distributions within an uncertainty set, yielding strong empirical robustness under dynamics-shift settings versus standard offline RL baselines.
<span style="color: var(--global-text-color-light)">*Manuscript in preparation.*</span>

<span style="color: var(--global-text-color-light)">A fuller list of projects, including time-series and computer-vision work, is on the [projects](/projects/) page.</span>
