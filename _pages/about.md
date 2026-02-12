---
permalink: /
title: About Me
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 全局版式：强化文字感与学术感 */
  .about-container {
    font-family: 'Times New Roman', Times, "serif", "PingFang SC", "Microsoft YaHei";
    color: #333;
    line-height: 1.6;
    max-width: 900px;
    margin: 0 auto;
  }
  
  .about-container h2 {
    border-bottom: 1px solid #ddd;
    padding-bottom: 8px;
    margin-top: 35px;
    font-variant: small-caps;
    color: #2c3e50;
    letter-spacing: 1px;
    display: block;
    width: 100%;
  }

  /* 个人简介联系方式 */
  .contact-bar {
    text-align: center;
    margin: 25px 0;
    font-size: 0.95em;
    border-top: 1px solid #f0f0f0;
    border-bottom: 1px solid #f0f0f0;
    padding: 10px 0;
  }
  .contact-bar a {
    margin: 0 12px;
    text-decoration: none;
    color: #1a5a96;
    font-weight: 500;
    transition: color 0.3s;
  }
  .contact-bar a:hover { color: #e74c3c; }

  /* News 滚动区域设置 */
  .news-scroll-container {
    height: 220px;
    overflow-y: auto;
    padding-right: 15px;
    margin: 15px 0;
    border-left: 3px solid #eee;
    background-color: #fcfcfc;
  }
  
  .news-scroll-container::-webkit-scrollbar { width: 5px; }
  .news-scroll-container::-webkit-scrollbar-track { background: #f1f1f1; }
  .news-scroll-container::-webkit-scrollbar-thumb { background: #ccc; border-radius: 10px; }
  .news-scroll-container::-webkit-scrollbar-thumb:hover { background: #999; }

  .news-list {
    list-style: none;
    padding-left: 15px;
    margin: 0;
    font-size: 0.92em;
  }
  .news-list li { margin-bottom: 10px; line-height: 1.4; }
  .news-date {
    font-weight: 600;
    color: #c0392b;
    margin-right: 8px;
    font-family: "Consolas", "Monaco", monospace;
  }

  /* 列表项布局 */
  .item-row {
    display: flex;
    align-items: flex-start;
    margin-bottom: 25px;
    gap: 25px;
  }
  .item-logo {
    flex-shrink: 0;
    width: 140px;
    display: flex;
    justify-content: center;
  }
  .item-logo img {
    max-width: 100%;
    height: auto;
    filter: grayscale(10%) contrast(105%);
  }
  .item-content { flex-grow: 1; }
  .item-content h3 { margin: 0 0 6px 0; font-size: 1.1em; color: #111; }
  .item-content p { margin: 3px 0; font-size: 0.92em; }
  .date-text { color: #7f8c8d; font-style: italic; font-size: 0.88em !important; }
  
  .highlight-topic { color: #e74c3c; font-weight: bold; }
  .conf-tag { font-weight: bold; color: #2980b9; }

  .project-item {
    padding: 15px 20px;
    margin-bottom: 20px;
    border-left: 3px solid #3498db;
    background-color: #f9f9f9;
    transition: all 0.3s ease;
    border-radius: 0 4px 4px 0;
  }
  .project-item:hover {
    background-color: #f0f7ff;
    border-left-color: #e74c3c;
    transform: translateX(5px);
  }
  .project-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 10px;
    margin-bottom: 8px;
  }
  .project-title {
    font-family: "Palatino", serif;
    font-size: 1.1em;
    font-weight: bold;
    color: #2c3e50;
    margin: 0;
  }

  .badge-container { margin-top: 10px; display: flex; flex-wrap: wrap; gap: 5px; }
  .badge-container img { height: 18px; }

  hr { border: 0; border-top: 1px solid #f0f0f0; margin: 20px 0; }
</style>

<div class="about-container" markdown="1">

My name is **Zhenhua Yang (杨振华, Yeung Chenwa)**. 

I am a Full-time Algorithm Engineer in Taobao & Tmall Group of [Alibaba](https://www.alibaba.com/) (2025). 
I received my Master's and Bachelor's degree from [SCUT-DLVCLab](https://github.com/HCIILAB) [supervised by [Prof. Lianwen Jin](http://www.dlvc-lab.net/lianwen/Index.html)] in South China University of Technology.

Fortunately, I have interned at the [Kling Team](https://klingai.com/global/) (advised by [Xin Tao](https://www.xtao.website/)) and [IDEA, Shenzhen](https://www.idea.edu.cn/) (advised by [Lei Zhang](https://www.leizhang.org/) and [Hao Zhang](https://haozhang534.github.io/)).

My research interests are focused on:
- **Post-Training for Multi-modal Generation and Editing**
- **Unifying Understanding and Generation for Next Generation Model**
- **Visual Text Generation and Editting**

<div class="contact-bar" markdown="1">
[GitHub](https://github.com/yeungchenwa) | [Google Scholar](https://scholar.google.com/citations?hl=zh-CN&user=2ITs6lUAAAAJ) | [Email](mailto:eezhyang@gmail.com) | [Zhihu](https://www.zhihu.com/people/young-40-31) | [LinkedIn](https://www.linkedin.com/in/zhenhua-yang-3911982b2)
</div>

## News

<div class="news-scroll-container">
  <ul class="news-list">
    <li><span class="news-date">05/2025</span> 🎉🎉🎉 Our work <a href="https://arxiv.org/abs/2507.05108">AutoHDR</a> is accepted by <span class="conf-tag">ACL 2025 Main</span>. I am the project leader. Code released.</li>
    <li><span class="news-date">02/2025</span> 🎉🎉🎉 Our paper <a href="https://arxiv.org/abs/2412.11634">HDR</a> is selected as the <b>Oral</b> presentation.</li>
    <li><span class="news-date">12/2024</span> The inference code of our paper <a href="https://arxiv.org/abs/2412.11634">HDR</a> is released at <a href="https://github.com/yeungchenwa/HDR">GitHub</a>.</li>
    <li><span class="news-date">12/2024</span> Our paper <a href="https://arxiv.org/abs/2412.11634">HDR</a> is accepted by <span class="conf-tag">AAAI 2025</span> 🎉🎉🎉.</li>
    <li><span class="news-date">07/2024</span> I will attend the <span class="conf-tag">ICML 2024</span> conference in person in Vienna, Austria.</li>
    <li><span class="news-date">06/2024</span> Interning at <a href="https://www.idea.edu.cn/">IDEA</a>, supervised by Prof. Lei Zhang, working on vision-language large models for video understanding.</li>
    <li><span class="news-date">05/2024</span> Our paper <a href="https://arxiv.org/abs/2312.02694">UPOCR</a> is accepted by <span class="conf-tag">ICML 2024</span> 🎉🎉🎉.</li>
    <li><span class="news-date">12/2023</span> 🔥🔥🔥 The <a href="https://huggingface.co/spaces/yeungchenwa/FontDiffuser-Gradio">Hugging Face Demo</a> and <a href="https://github.com/yeungchenwa/FontDiffuser">GitHub</a> of <b>FontDiffuser</b> are released!</li>
    <li><span class="news-date">12/2023</span> 🎉 Paper <a href="https://arxiv.org/abs/2312.12142">FontDiffuser</a> is accepted by <span class="conf-tag">AAAI 2024</span>.</li>
    <li><span class="news-date">12/2023</span> Our paper <a href="https://arxiv.org/abs/2312.02694">UPOCR</a> is released to arXiv.</li>
  </ul>
</div>

## Education

<div class="item-row">
  <div class="item-logo"><img src="/my_images/SCUT_logo.png" width="100"></div>
  <div class="item-content" markdown="1">
### South China University of Technology
Sep. 2022 - Present
{: .date-text}

M.S. Student at [SCUT-DLVCLab](https://github.com/HCIILAB), School of Electronic and Information Engineering
  </div>
</div>

<div class="item-row">
  <div class="item-logo"><img src="/my_images/SCUT_logo.png" width="100"></div>
  <div class="item-content" markdown="1">
### South China University of Technology
Sep. 2018 - Jun. 2022
{: .date-text}

B.E. Student in School of Automation Science and Engineering
  </div>
</div>

## Experience

<div class="item-row">
  <div class="item-logo"><img src="/my_images/experiences/alibaba.png" width="150"></div>
  <div class="item-content" markdown="1">
### Alibaba - Taobao & Tmall Group
July 2025 - Present
{: .date-text}

**Full-time AIGC Algorithm Engineer**

Post-Training for Image Generation and Editing.
  </div>
</div>

<div class="item-row">
  <div class="item-logo"><img src="/my_images/experiences/kling.png" width="150"></div>
  <div class="item-content" markdown="1">
### KuaiShou - Kling Team
Jan. 2025 - Apr. 2025
{: .date-text}

**Research Intern**, supervised by Xin Tao.

<span class="highlight-topic">Topic:</span> Unifying Understanding and Generation for Next Generation Model.
  </div>
</div>

<div class="item-row">
  <div class="item-logo"><img src="/my_images/experiences/idea.png" width="150"></div>
  <div class="item-content" markdown="1">
### International Digital Economy Academy (IDEA) - CVR
Jun. 2024 - Sep. 2024
{: .date-text}

**Research Intern**, supervised by Prof. Lei Zhang.

<span class="highlight-topic">Topic:</span> MLLM for Streaming Video Narration and QA.
  </div>
</div>

## Selected Publications [[Full List](https://scholar.google.com/citations?hl=zh-CN&user=2ITs6lUAAAAJ)]

<div class="item-row">
  <div class="item-logo"><img src="/my_images/publications/HDR.png" width="150"></div>
  <div class="item-content" markdown="1">
### Predicting the Original Appearance of Damaged Historical Documents
**Zhenhua Yang***, Dezhi Peng*, Yongxin Shi, Yuyi Zhang, Chongyu Liu, Lianwen Jin†

*Proc. of the AAAI Conference on Artificial Intelligence (<span class="conf-tag">AAAI Oral</span>), 2025*

<div class="badge-container">
<a href='https://arxiv.org/abs/2412.11634'><img src='https://img.shields.io/badge/paper-9cf'></a>
<a href='https://yeungchenwa.github.io/hdr-homepage/'><img src='https://img.shields.io/badge/project-green'></a>
<a href='https://github.com/yeungchenwa/HDR'><img src='https://img.shields.io/github/stars/yeungchenwa/HDR.svg?style=social&label=Star'></a>
</div>
  </div>
</div>

<div class="item-row">
  <div class="item-logo"><img src="/my_images/publications/FontDiffuser.png" width="150"></div>
  <div class="item-content" markdown="1">
### FontDiffuser: One-Shot Font Generation via Denoising Diffusion with Multi-Scale Content Aggregation and Style Contrastive Learning
**Zhenhua Yang**, Dezhi Peng, Yuxin Kong, Yuyi Zhang, Cong Yao, Lianwen Jin†

*Proc. of the AAAI Conference on Artificial Intelligence (<span class="conf-tag">AAAI</span>), 2024*

<div class="badge-container">
<a href='https://arxiv.org/abs/2312.12142'><img src='https://img.shields.io/badge/paper-9cf'></a>
<a href='https://yeungchenwa.github.io/fontdiffuser-homepage/'><img src='https://img.shields.io/badge/project-green'></a>
<a href='https://github.com/yeungchenwa/FontDiffuser'><img src='https://img.shields.io/github/stars/yeungchenwa/FontDiffuser.svg?style=social&label=Star'></a>
<a href='https://huggingface.co/spaces/yeungchenwa/FontDiffuser-Gradio'><img src='https://img.shields.io/badge/demo-purple'></a>
</div>
  </div>
</div>

<div class="item-row">
  <div class="item-logo"><img src="/my_images/publications/UPOCR.png" width="150"></div>
  <div class="item-content" markdown="1">
### UPOCR: Towards Unified Pixel-Level OCR Interface
Dezhi Peng*, **Zhenhua Yang***, Jiaxin Zhang, Chongyu Liu, Yongxin Shi, Lianwen Jin†

*International Conference on Machine Learning (<span class="conf-tag">ICML</span>), 2024*

<div class="badge-container">
<a href='https://arxiv.org/abs/2312.02694'><img src='https://img.shields.io/badge/paper-9cf'></a>
<a href='https://github.com/shannanyinxiang/UPOCR'><img src='https://img.shields.io/github/stars/shannanyinxiang/UPOCR.svg?style=social&label=Star'></a>
</div>
  </div>
</div>

<div class="item-row">
  <div class="item-logo"><img src="/my_images/publications/AutoHDR.png" width="150"></div>
  <div class="item-content" markdown="1">
### Reviving Cultural Heritage: A Novel Approach for Comprehensive Historical Document Restoration
Yuyi Zhang, Peirong Zhang, **Zhenhua Yang* (Project Lead)**, et al., Lianwen Jin†

*Meeting of the Association for Computational Linguistics (<span class="conf-tag">ACL Main</span>), 2025*

<div class="badge-container">
<a href='https://arxiv.org/abs/2507.05108'><img src='https://img.shields.io/badge/paper-9cf'></a>
<a href='https://github.com/SCUT-DLVCLab/AutoHDR'><img src='https://img.shields.io/github/stars/yeungchenwa/HDR.svg?style=social&label=Star'></a>
<a href='http://121.41.49.212:8432/'><img src='https://img.shields.io/badge/demo-purple'></a>
</div>
  </div>
</div>

<div class="item-row">
  <div class="item-logo"><img src="/my_images/publications/UniHIR.png" width="150"></div>
  <div class="item-content" markdown="1">
### Draft, Verify, Restore: Self-Refining Historical Inscription Restoration with a Unified MLLM
<span class="highlight-topic">Topic:</span> Unify Content Reasoning (Understanding) and Generation

Yuyi Zhang, Peirong Zhang, **Zhenhua Yang* (Project Lead)**, et al., Lianwen Jin†

***Submitted to*** Meeting of the Association for Computational Linguistics (<span class="conf-tag">ACL</span>), 2026
  </div>
</div>

## Open-Source Projects

<div class="project-item" markdown="1">
<div class="project-header" markdown="1">
### Optical Character Recognition with Segment Anything (OCR-SAM)
<a href='https://github.com/yeungchenwa/OCR-SAM'><img src='https://img.shields.io/github/stars/yeungchenwa/OCR-SAM.svg?style=social&label=Star'></a>
</div>
**Zhenhua Yang**, Qing Jiang

<span class="highlight-topic">Focus:</span> Exploring SAM's zero-shot generalization in OCR tasks. Integrated SAM with MMOCR to develop specialized application demos, including precise text removal and high-fidelity text inpainting with a Gradio-based WebUI.
</div>

<div class="project-item" markdown="1">
<div class="project-header" markdown="1">
### Flexible Diffusion-based Font Generation Framework
<a href='https://github.com/yeungchenwa/FontDiffuser'><img src='https://img.shields.io/github/stars/yeungchenwa/FontDiffuser.svg?style=social&label=Star'></a>
</div>
**Zhenhua Yang**

<span class="highlight-topic">Focus:</span> A robust generative framework for few-shot font stylization. Capable of synthesizing unseen characters and complex styles, supporting cross-lingual generation (e.g., Chinese to Korean) via advanced diffusion denoising.
</div>

<div class="project-item" markdown="1">
<div class="project-header" markdown="1">
### Recommendations of Diffusion for Text-Image
<a href='https://github.com/yeungchenwa/Recommendations-Diffusion-Text-Image'><img src='https://img.shields.io/github/stars/yeungchenwa/Recommendations-Diffusion-Text-Image.svg?style=social&label=Star'></a>
</div>
**Zhenhua Yang**

<span class="highlight-topic">Focus:</span> A curated academic collection of state-of-the-art diffusion models for text-centric visual tasks, including visual text generation, font synthesis, and scene text recognition.
</div>

<div class="project-item" markdown="1">
<div class="project-header" markdown="1">
### Recommendations of Document Image Processing
<a href='https://github.com/ZZZHANG-jx/Recommendations-Document-Image-Processing'><img src='https://img.shields.io/github/stars/ZZZHANG-jx/Recommendations-Document-Image-Processing.svg?style=social&label=Star'></a>
</div>
Jiaxin Zhang, **Zhenhua Yang**

<span class="highlight-topic">Focus:</span> A comprehensive survey of document image restoration techniques, covering appearance enhancement, deshadowing, dewarping, deblurring, and binarization.
</div>

## Awards
* **Shenzhen HighPower Technology Scholarship**, 2022 (Top 2%)
* **First-Class Campus Scholarship**, 2021 (Top 5%)
* **American Mathematical Contest in Modeling**, Meritorious Prize, 2020
* **Alibaba Tianchi Competition**, Top 1.2%, 2021

## Mics
**Hobby**: 🎣 Fishing, 🏊‍♂️ Swimming, 🚲 Riding, 🏓 Table tennis, 🏀 Basketball, 🎤 Singing. Learning 🎹 Piano.  
**Languages**: Chinese (Mandarin, Cantonese, Hakka), English.  
**Habit**: A heavy coffee drinker ☕.

<div style="text-align: center; margin-top: 50px;">
  <script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=ffffff&w=a&t=tt&d=TuVRvKdiJmKZ6t0SuQ7FsO2avdiz4cQm8yys_lX28-Q&co=2d78ad&cmo=3acc3a&cmn=ff5353&ct=ffffff'></script>
</div>

</div>