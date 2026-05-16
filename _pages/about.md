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
  enabled: false # rendered manually in the body, above the research projects
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

Hi! I'm **Xi Chen (陈希)**, a first-year **M.S.E. student in Computer Science** at **Johns Hopkins University**, where I work in the [ARCADE Lab](https://arcade.cs.jhu.edu/) with Dr. Lalithkumar Seenivasan and collaborate with Prof. Laixi Shi and Prof. Jianyi Yang on robust reinforcement learning. Before JHU, I received my B.Eng. in Computer Science from **Nankai University**.

I am broadly interested in **decision-making and perception for embodied agents**, and I am **applying for a Ph.D.** to pursue this direction. My current research focuses on:

- **World Models for Reinforcement Learning** — generative trajectory models, long-horizon value estimation, and distributionally robust offline RL under dynamics shift.
- **Vision-Language-Action (VLA) & Visual Foundation Models** — low-latency point-tracking and representation models that can serve as perception backbones for embodied and surgical agents.

Earlier work spans time-series learning, generative modeling, and computer vision. I enjoy problems where robust decision-making meets real deployment constraints.

---

## news

{% include news.liquid limit=true %}

## selected research projects

**Adversarial Finetuning of Generative World Models for Distributionally Robust Offline RL** &nbsp; <span style="color: var(--global-text-color-light)">· Apr 2026 – Present</span>

_Johns Hopkins University — with Prof. Laixi Shi, Prof. Jianyi Yang, and Jiaqi Wen_

A robust offline-RL framework pairing **flow-matching trajectory generation** with **distributionally robust optimization (DRO)**: the generative module rolls out _H_-step futures for long-horizon target-Q estimation beyond one-step Bellman backups, while a DRO objective optimizes against worst-case trajectory distributions — yielding strong robustness under dynamics shift versus standard offline-RL baselines.
<span style="color: var(--global-text-color-light)">_In preparation — targeting ICLR 2027._</span>

**Point Tracking for Bronchoscopy via Adjacent-Frame Correlation** &nbsp; <span style="color: var(--global-text-color-light)">· Feb 2026 – Present</span>

_ARCADE Lab, Johns Hopkins University — with Dr. Lalithkumar Seenivasan_

An AllTracker-style tracker adapted to bronchoscopy, where textureless airway walls, illumination shifts, and specular reflections break long-range query-anchored matching. An **adjacent-frame correlation** module estimates and chains frame-to-frame optical flow for robust tracking, distilled (Transformer teacher → lightweight CNN student with D2-Net-style features) for real-time deployment at **< 30 ms latency**.
<span style="color: var(--global-text-color-light)">_Manuscript in preparation._</span>

**Backdoor Attacks on Multivariate Time-Series Forecasting** &nbsp; <span style="color: var(--global-text-color-light)">· Dec 2024 – May 2025</span>

_Undergraduate thesis, DBIS Lab, Nankai University — with Dr. Xiangrui Cai_

A stealthy backdoor-attack framework for multivariate forecasting under realistic missing-value scenarios: invisible triggers at missing-value positions plus a critical-time-step imputation strategy preserve stealth while cutting attack MAE by **43%** versus baselines.
