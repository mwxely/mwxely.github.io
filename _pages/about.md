---
permalink: /
title: ""
excerpt: "I am a third-year Ph.D. candidate at NTU. My research interests include: video understanding, video reasoning, and video agents."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.paper-box {
  display: flex;
  align-items: flex-start;
  margin-bottom: 24px;
  border-radius: 12px;
  box-shadow: 0 4px 16px 0 rgba(0,0,0,0.08);
  background: #fff;
  padding: 16px;
  gap: 20px;
}
.paper-box-image {
  flex: 0 0 220px;
  position: relative;
}
.paper-box-image .badge {
  position: absolute;
  left: 0; top: 0;
  background: #337ab7;
  color: #fff;
  padding: 2px 12px;
  font-size: 14px;
  border-radius: 8px 0 8px 0;
  font-weight: 700;
  z-index: 2;
}
.paper-box-image img {
  width: 100%;
  border-radius: 8px;
  margin-top: 22px;
}
.paper-box-text {
  flex: 1;
  font-size: 0.98em;
  line-height: 1.45;
  color: #202124;
}
.paper-box-text a {
  color: #1684fc;
  font-weight: 600;
  font-size: 1em;
}
.paper-box-text i {
  color: #555;
  font-style: italic;
  font-size: 0.98em;
}
/* Dark mode styles */
[data-theme="dark"] .paper-box {
  background: #252525;
  box-shadow: 0 4px 16px 0 rgba(0,0,0,0.3);
}
[data-theme="dark"] .paper-box-text {
  color: #e0e0e0;
}
[data-theme="dark"] .paper-box-text a {
  color: #52adc8;
}
[data-theme="dark"] .paper-box-text i {
  color: #b0b0b0;
}
/* Publication carousel: VERTICAL-scroll cards inside a fixed-height window. */
.paper-carousel {
  position: relative;
  max-height: 720px;
  overflow-y: auto;
  overflow-x: hidden;
  scroll-snap-type: y proximity;
  margin-bottom: 24px;
  padding-right: 6px;
  scrollbar-width: thin;
  scrollbar-color: rgba(0,0,0,0.25) transparent;
  -webkit-overflow-scrolling: touch;
  /* Soft fade hint at the bottom so users see there's more to scroll */
  mask-image: linear-gradient(180deg, #000 0, #000 calc(100% - 32px), transparent 100%);
  -webkit-mask-image: linear-gradient(180deg, #000 0, #000 calc(100% - 32px), transparent 100%);
}
.paper-carousel::-webkit-scrollbar { width: 8px; }
.paper-carousel::-webkit-scrollbar-thumb {
  background: rgba(0,0,0,0.25);
  border-radius: 4px;
}
.paper-carousel-track {
  display: flex;
  flex-direction: column;
  gap: 16px;
}
.paper-carousel-track .paper-box {
  flex: 0 0 auto;
  scroll-snap-align: start;
  margin-bottom: 0;
}
[data-theme="dark"] .paper-carousel {
  scrollbar-color: rgba(255,255,255,0.25) transparent;
}
[data-theme="dark"] .paper-carousel::-webkit-scrollbar-thumb {
  background: rgba(255,255,255,0.25);
}

/* Mobile styles - only affects screens smaller than 768px */
@media (max-width: 768px) {
  .paper-carousel {
    max-height: 560px;
    padding-right: 4px;
  }
  .paper-box {
    position: relative;
    flex-direction: column;
    padding: 8px;
    padding-top: 28px; /* Space for badge at top */
    gap: 8px;
  }
  .paper-box-image {
    position: static; /* Remove relative so badge positions to paper-box */
    flex: none;
    width: 100%;
    display: flex;
    justify-content: center;
  }
  .paper-box-image .badge {
    /* Badge at paper-box top-left corner */
    position: absolute;
    left: 0;
    top: 0;
    border-radius: 12px 0 8px 0;
  }
  .paper-box-image img {
    width: 65%;
    max-width: 200px;
    margin-top: 0;
  }
  .paper-box-text {
    font-size: 0.85em;
    line-height: 1.35;
    overflow-wrap: break-word;
    word-wrap: break-word;
  }
  .paper-box-text a {
    font-size: 0.92em;
  }
}
</style>

I am a third-year Ph.D. candidate with [Visual Intelligence Lab](https://sg-vilab.github.io/) at Nanyang Technological University (NTU), supervised by [Prof. Shijian Lu](https://personal.ntu.edu.sg/shijian.lu/). Prior to joining NTU, I obtained my B.S. degree in Computing Science from University of Alberta. I am currently working on native multimodal foundation models at [Kimi (Moonshot AI)](https://www.moonshot.cn/), advised by [Dr. Haoning Wu](https://teowu.github.io/) and [Xinyu Zhou](https://scholar.google.com/citations?user=Jv4LCj8AAAAJ&hl=en). Previously, I worked closely with [Dr. Lidong Bing](https://lidongbing.github.io/) at [MiroMind](https://miromind.ai/) and [Dr. Song Bai](https://songbai.site/) at [ByteDance](https://www.bytedance.com/). I also enjoy vibe building with other researchers at [LMMs-Lab](https://www.lmms-lab.com/), a non-profit open-source organization led by [Dr. Bo Li](https://brianboli.com/) and [Prof. Ziwei Liu](https://liuziwei7.github.io/). My research centers on the long-standing quest for building video-centric multimodal intelligence, spanning temporal grounding, agentic reasoning, long-horizon tool use, and self-evolving multi-agent systems.

*I am open to any interesting ideas, questions, and future opportunities. Feel free to contact me via WeChat: 17310143309.*

Exciting News
---
{: #exciting-news }
* 2026.05 - [**ParaVT**](https://arxiv.org/abs/2605.20342), [**PRISM**](https://arxiv.org/abs/2604.28123), and [**WorldReasonBench**](https://arxiv.org/abs/2605.10434) were released. Other work regarding Audio-Visual Captioning, Multimodal Evaluation, and Database Agent will be released soon.
* 2026.03 - [**MiroThinker-1.7 & H1**](https://arxiv.org/abs/2603.15726) was released.
* 2026.02 - Four papers were accepted by **CVPR 2026**.
* 2025.10 - One paper was accepted by **SIGGRAPH Asia 2025**.
* 2025.08 - One paper was accepted by **EMNLP 2025**.
* 2025.06 - Two papers were accepted by **ICCV 2025**.
* 2025.05 - Two papers were accepted by **ACL 2025**.
* 2023.09 - One paper was accepted by **NeurIPS 2023**.


Selected Publications ([Full List](https://scholar.google.com/citations?user=TlBhP8EAAAAJ&hl=en&oi=ao))
---
{: #selected-publications }

<div class="paper-carousel"><div class="paper-carousel-track">

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">arXiv</span>
    <img src="images/ParaVT.png" alt="ParaVT" width="100%">
  </div>
  <div class="paper-box-text">
    <a href="https://arxiv.org/abs/2605.20342"><b>ParaVT: Taming the Tool Prior Paradox for Parallel Tool Use in Agentic Video Reinforcement Learning</b></a><br>
    <b>Zuhao Yang</b>, Kaichen Zhang, Sudong Wang, Keming Wu, Zhongyu Yang, Bo Li, Xiaojuan Qi, Shijian Lu, Xingxuan Li, Lidong Bing<br>
    arXiv 2026<br>
    <a href="https://arxiv.org/pdf/2605.20342">paper</a> / <a href="https://mwxely.github.io/bibtex/yang2026paravt.html">bibtex</a> / <a href="https://github.com/EvolvingLMMs-Lab/ParaVT">code</a>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">arXiv</span>
    <img src="images/VisGen.jpg" alt="Visual Generation Survey" width="100%">
  </div>
  <div class="paper-box-text">
    <b>Visual Generation in the New Era: An Evolution from Atomic Mapping to Agentic World Modeling</b><br>
    Keming Wu<sup>*†</sup>, <b>Zuhao Yang<sup>*†</sup></b>, and 20+ authors<br>
    arXiv 2026<br>
    <a href="#">paper</a> / <a href="https://mwxely.github.io/bibtex/wu2026visgen.html">bibtex</a> / <a href="https://github.com/EvolvingLMMs-Lab/Evolving-Visual-Generation">webpage</a><br>
    <i><sup>*</sup>Co-first authors. <sup>†</sup>Project organizer.</i>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">CVPR</span>
    <img src="images/LVT.png" alt="LVT" width="100%">
  </div>
  <div class="paper-box-text">
    <a href="https://arxiv.org/abs/2511.20785"><b>LongVT: Incentivizing "Thinking with Long Videos" via Native Tool Calling</b></a><br>
    <b>Zuhao Yang*</b>, Sudong Wang*, Kaichen Zhang*, Keming Wu, Sicong Leng, Yifan Zhang, Bo Li, Chengwei Qin, Shijian Lu, Xingxuan Li, Lidong Bing<br>
    CVPR 2026<br>
    <a href="https://arxiv.org/pdf/2511.20785">paper</a> / <a href="https://mwxely.github.io/bibtex/yang2025longvt.html">bibtex</a> / <a href="https://github.com/EvolvingLMMs-Lab/LongVT">code</a>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">CVPR</span>
    <img src="images/OMR.png" alt="OMR" width="100%">
  </div>
  <div class="paper-box-text">
    <a href="https://arxiv.org/abs/2511.16334"><b>OpenMMReasoner: Pushing the Frontiers for Multimodal Reasoning with an Open and General Recipe</b></a><br>
    Kaichen Zhang*, Keming Wu*, <b>Zuhao Yang</b>, Bo Li, Kairui Hu, Bin Wang, Ziwei Liu, Xingxuan Li, Lidong Bing<br>
    CVPR 2026<br>
    <a href="https://arxiv.org/pdf/2511.16334">paper</a> / <a href="https://mwxely.github.io/bibtex/zhang2025openmmreasoner.html">bibtex</a> / <a href="https://github.com/EvolvingLMMs-Lab/OpenMMReasoner">code</a>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">CVPR</span>
    <img src="images/SVAgent.png" alt="SVAgent" width="100%">
  </div>
  <div class="paper-box-text">
    <a href="https://arxiv.org/abs/2604.05079"><b>SVAgent: Storyline-guided Long Video Understanding via Cross-modal Multi-agent Collaboration</b></a><br>
    Zhongyu Yang, <b>Zuhao Yang</b>, Shuo Zhan, Tan Yue, Wei Pang, Yingfang Yuan<br>
    CVPR 2026<br>
    <a href="https://arxiv.org/pdf/2604.05079">paper</a> / <a href="https://mwxely.github.io/bibtex/yang2026svagent.html">bibtex</a>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">CVPR</span>
    <img src="images/dMLLM.png" alt="dMLLM" width="100%">
  </div>
  <div class="paper-box-text">
    <a href="https://arxiv.org/abs/2511.15098"><b>A Comprehensive Study on Visual Token Redundancy for Discrete Diffusion-based Multimodal Large Language Models</b></a><br>
    Duo Li*, <b>Zuhao Yang*</b>, Xiaoqin Zhang, Ling Shao, Shijian Lu<br>
    CVPR 2026<br>
    <a href="https://arxiv.org/pdf/2511.15098">paper</a> / <a href="https://mwxely.github.io/bibtex/li2025comprehensive.html">bibtex</a>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">ICCV</span>
    <img src="images/TE.png" alt="TimeExpert" width="100%">
  </div>
  <div class="paper-box-text">
    <a href="https://arxiv.org/abs/2508.01699"><b>TimeExpert: An Expert-Guided Video LLM for Video Temporal Grounding</b></a><br>
    <b>Zuhao Yang</b>, Yingchen Yu, Yunqing Zhao, Shijian Lu, Song Bai<br>
    ICCV 2025<br>
    <a href="https://arxiv.org/pdf/2508.01699">paper</a> / <a href="https://mwxely.github.io/bibtex/yang2025timeexpert.html">bibtex</a> / <a href="https://mwxely.github.io/projects/yang2025time/index">webpage</a>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">ICCV</span>
    <img src="images/VTG.png" alt="VTG" width="100%">
  </div>
  <div class="paper-box-text">
    <a href="https://arxiv.org/abs/2508.01698"><b>Versatile Transition Generation with Image-to-Video Diffusion</b></a><br>
    <b>Zuhao Yang</b>, Jiahui Zhang, Yingchen Yu, Shijian Lu, Song Bai<br>
    ICCV 2025<br>
    <a href="https://arxiv.org/pdf/2508.01698">paper</a> / <a href="https://mwxely.github.io/bibtex/yang2025versatile.html">bibtex</a> / <a href="https://mwxely.github.io/projects/yang2025vtg/index">webpage</a>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">ACL</span>
    <img src="images/QAEval.png" alt="QAEval" width="100%">
  </div>
  <div class="paper-box-text">
    <a href="https://aclanthology.org/2025.acl-long.716"><b>QAEval: Mixture of Evaluators for Question‑Answering Task Evaluation</b></a><br>
    Tan Yue, Rui Mao, Xuzhao Shi, Shuo Zhan, <b>Zuhao Yang</b>, Dongyan Zhao<br>
    ACL 2025<br>
    <a href="https://aclanthology.org/2025.acl-long.716.pdf">paper</a> / <a href="https://mwxely.github.io/bibtex/yue2025qaeval.html">bibtex</a> / <a href="https://github.com/yuetanbupt/QAEval">code</a>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">NeurIPS</span>
    <img src="images/FACE.png" alt="FACE" width="100%">
  </div>
  <div class="paper-box-text">
    <a href="https://arxiv.org/abs/2305.10307"><b>FACE: Evaluating Natural Language Generation with Fourier Analysis of Cross‑Entropy</b></a><br>
    <b>Zuhao Yang*</b>, Yingfang Yuan*, Yang Xu*, Shuo Zhan, Huajun Bai, Kefan Chen<br>
    NeurIPS 2023<br>
    <a href="https://arxiv.org/pdf/2305.10307">paper</a> / <a href="https://mwxely.github.io/bibtex/yang2023face.html">bibtex</a> / <a href="https://github.com/CLCS-SUSTech/FACE">code</a>
  </div>
</div>

</div></div>

Academic Services
---
{: #academic-services }

**Conference Reviewer**
* CVPR 24/25/26, ECCV 24/26, ACM MM 24/25/26, NeurIPS 24/25/26, ICLR 25, AISTATS 25/26, ICML 25, ICCV 25, BMVC 26

**Journal Reviewer**
* IEEE TPAMI, Pattern Recognition, Journal of Electronic Imaging  

**Workshop PC Member**
* [SyntaGen: Harnessing Generative Models for Synthetic Visual Datasets](https://syntagen25.github.io/) (CVPR 24/25)
* [Neural Rendering Intelligence](https://neural-rendering.com/) (CVPR 24)
* [Engineering Agentic Intelligence: A Pipeline from Efficient Reasoning to Multimodal Grounding to Agentic Collaboration](https://aaai.org/conference/aaai/aaai-26/interactive-industry-sessions/#ChenInstitute) (AAAI 26)

**Teaching Assistant**
* AI6121 - Computer Vision, NTU, Fall 2025 / Spring 2026

Invited Talks
---
{: #invited-talks }

* 2026.05 - At SenseTime, covering [Evolving Visual Generation](https://github.com/EvolvingLMMs-Lab/Evolving-Visual-Generation).
* 2026.05 - At Cantina, covering [TimeExpert](https://mwxely.github.io/projects/yang2025time/index), [LongVT](https://evolvinglmms-lab.github.io/LongVT/), [ParaVT](https://evolvinglmms-lab.github.io/ParaVT/), and [ToDRE](https://arxiv.org/abs/2505.18757).
* 2026.01 - At AAAI ([slides](https://docs.google.com/presentation/d/1Xm0tH28hdZKBLB7d5LCNrFJNJQtd6kasKPov15FH4FE/edit?usp=sharing)), covering [MiroMind-M1](https://github.com/MiroMindAI/MiroMind-M1), [First Try Matters](https://github.com/Olafyii/first-try-matters), [MATPO](https://github.com/mzf666/MATPO), [OpenMMReasoner](https://evolvinglmms-lab.github.io/OpenMMReasoner/), and [LongVT](https://evolvinglmms-lab.github.io/LongVT/).
* 2025.12 - At BAAI ([slides & recording](https://event.baai.ac.cn/activities/983)), covering [OpenMMReasoner](https://evolvinglmms-lab.github.io/OpenMMReasoner/) and [LongVT](https://evolvinglmms-lab.github.io/LongVT/).
* 2025.11 - At [Dr. Bosheng Ding](https://www.boshengding.com/)'s reading group, covering [LongVT](https://evolvinglmms-lab.github.io/LongVT/).

Technical Blogs
---
{: #technical-blogs }

**Chinese Blogs**
* [LLM Tool Calling & Reinforcement Learning](https://www.notion.so/LLM-Tool-Calling-Reinforcement-Learning-22282320208b80db9ccbde95f76577c5?source=copy_link) (by [Dr. Handuo Zhang](https://zhanghanduo.github.io/))
* [Thinking with Images & Agentic Tool Use](https://www.notion.so/Thinking-with-Images-Agentic-Tool-Use-22282320208b801fa6b4dcebc5b5da8d?source=copy_link) (by [Zuhao Yang](https://mwxely.github.io/))

**English Blogs**
* [OpenMMReasoner: Pushing the Frontiers for Multimodal Reasoning with an Open and General Recipe](https://www.lmms-lab.com/posts/openmmreasoner/) (by [Kaichen Zhang](https://kcz358.github.io/))
* [LongVT: Incentivizing "Thinking with Long Videos" via Native Tool Calling](https://www.lmms-lab.com/posts/longvt/) (by [Zuhao Yang](https://mwxely.github.io/))

Patent & Awards
---
{: #patent--awards }

* Method, Device, and Medium for Video Temporal Grounding with Mixture-of-Experts, US Patent, 2025
* Method, Device, and Medium for Generating Transition Videos with Diffusion Model, SG Patent, 2024
* [Method, Device, and Medium for Automatic Question-Answering](http://epub.cnipa.gov.cn/patent/CN113946669A), CN Patent, 2022
* Outstanding Graduate with Distinction, University of Alberta, 2021
* Dean's Honor Roll Award, University of Alberta, 2018 - 2020
* International Student Scholarship, University of Alberta, 2017 - 2019
