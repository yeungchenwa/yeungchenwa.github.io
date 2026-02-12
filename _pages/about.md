---
permalink: /
title: "Zhenhua Yang"
excerpt: "Zhenhua Yang's Homepage"
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
    font-size: 16px;
  }
  
  .about-container h2 {
    border-bottom: 1px solid #ddd;
    padding-bottom: 8px;
    margin-top: 35px;
    margin-bottom: 20px;
    font-variant: small-caps;
    color: #2c3e50;
    letter-spacing: 1px;
    display: block;
    width: 100%;
    font-weight: bold;
    font-size: 1.5em;
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

  /* --- 核心修改：Publication / Education / Experience 标题样式 --- */
  .item-content h3 { 
    margin: 0 0 6px 0; 
    /* 将字体大小从 1.15em 调为 1.05em 或 1.1em */
    font-size: 1.0em; 
    color: #333; 
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Helvetica, Arial, sans-serif;
    /* 将字重从 700 (Bold) 降为 600 (Semi-Bold) 或 500 (Medium) */
    font-weight: 600; 
    line-height: 1.3;
  }
  
  .item-content p { margin: 3px 0; font-size: 0.92em; }
  .date-text { color: #7f8c8d; font-style: italic; font-size: 0.88em !important; }
  
  .highlight-topic { color: #e74c3c; font-weight: bold; }
  .conf-tag { font-weight: bold; color: #2980b9; }

  /* Project 标题样式 (保持一致性) */
  .project-item h3, .project-header h3 {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-weight: 700;
    color: #333;
    font-size: 1.15em;
    margin-top: 0;
    margin-bottom: 8px;
  }

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

  .badge-container { margin-top: 10px; display: flex; flex-wrap: wrap; gap: 5px; }
  .badge-container img { height: 18px; }

  /* 针对 Awards 和 Mics 的列表样式修复 */
  .custom-list {
    padding-left: 20px;
    margin-top: 10px;
  }
  .custom-list li {
    margin-bottom: 6px;
  }

  hr { border: 0; border-top: 1px solid #f0f0f0; margin: 20px 0; }
</style>

<div class="about-container">

<p>My name is <strong>Zhenhua Yang (杨振华, Yeung Chenwa)</strong>.</p>

<p>
I am a Full-time Algorithm Engineer in Taobao & Tmall Group of <a href="https://www.alibaba.com/">Alibaba</a> (2025). 
I received my Master's and Bachelor's degree from <a href="https://github.com/HCIILAB">SCUT-DLVCLab</a> [supervised by <a href="http://www.dlvc-lab.net/lianwen/Index.html">Prof. Lianwen Jin</a>] in South China University of Technology.
</p>

<p>
Fortunately, I have interned at the <a href="https://klingai.com/global/">Kling Team</a> (advised by <a href="https://www.xtao.website/">Xin Tao</a>) and <a href="https://www.idea.edu.cn/">IDEA, Shenzhen</a> (advised by <a href="https://www.leizhang.org/">Lei Zhang</a> and <a href="https://haozhang534.github.io/">Hao Zhang</a>).
</p>

<p>My research interests are focused on:</p>
<ul class="custom-list">
  <li><strong>Post-Training for Multi-modal Generation and Editing</strong></li>
  <li><strong>Unifying Understanding and Generation for Next Generation Model</strong></li>
  <li><strong>Visual Text Generation and Editting</strong></li>
</ul>

<div class="contact-bar">
<a href="https://github.com/yeungchenwa">GitHub</a> | 
<a href="https://scholar.google.com/citations?hl=zh-CN&user=2ITs6lUAAAAJ">Google Scholar</a> | 
<a href="mailto:eezhyang@gmail.com">Email</a> | 
<a href="https://www.zhihu.com/people/young-40-31">Zhihu</a> | 
<a href="https://www.linkedin.com/in/zhenhua-yang-3911982b2">LinkedIn</a>
</div>

<h2>News</h2>

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

<h2>Education</h2>

<div class="item-row">
  <div class="item-logo"><img src="/my_images/SCUT_logo.png" width="100"></div>
  <div class="item-content" markdown="1">
### South China University of Technology
Sep. 2022 - 2025
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

<h2>Experience</h2>

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

<h2>Selected Publications <a href="https://scholar.google.com/citations?hl=zh-CN&user=2ITs6lUAAAAJ" style="font-size:0.6em; vertical-align:middle; text-decoration:none;">[Full List]</a></h2>

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

<h2>Open-Source Projects</h2>

<div class="project-item">
<div class="project-header" markdown="1">
### Optical Character Recognition with Segment Anything (OCR-SAM)
<a href='https://github.com/yeungchenwa/OCR-SAM'><img src='https://img.shields.io/github/stars/yeungchenwa/OCR-SAM.svg?style=social&label=Star'></a>
</div>
<p style="margin-top:5px;"><span class="highlight-topic">Focus:</span> Exploring SAM's zero-shot generalization in OCR tasks. Integrated SAM with MMOCR to develop specialized application demos, including precise text removal and high-fidelity text inpainting with a Gradio-based WebUI.</p>
</div>

<div class="project-item">
<div class="project-header" markdown="1">
### Flexible Diffusion-based Font Generation Framework
<a href='https://github.com/yeungchenwa/FontDiffuser'><img src='https://img.shields.io/github/stars/yeungchenwa/FontDiffuser.svg?style=social&label=Star'></a>
</div>
<p style="margin-top:5px;"><span class="highlight-topic">Focus:</span> A robust generative framework for few-shot font stylization. Capable of synthesizing unseen characters and complex styles, supporting cross-lingual generation (e.g., Chinese to Korean) via advanced diffusion denoising.</p>
</div>

<div class="project-item">
<div class="project-header" markdown="1">
### Recommendations of Diffusion for Text-Image
<a href='https://github.com/yeungchenwa/Recommendations-Diffusion-Text-Image'><img src='https://img.shields.io/github/stars/yeungchenwa/Recommendations-Diffusion-Text-Image.svg?style=social&label=Star'></a>
</div>
<p style="margin-top:5px;"><span class="highlight-topic">Focus:</span> A curated academic collection of state-of-the-art diffusion models for text-centric visual tasks, including visual text generation, font synthesis, and scene text recognition.</p>
</div>

<div class="project-item">
<div class="project-header" markdown="1">
### Recommendations of Document Image Processing
<a href='https://github.com/ZZZHANG-jx/Recommendations-Document-Image-Processing'><img src='https://img.shields.io/github/stars/ZZZHANG-jx/Recommendations-Document-Image-Processing.svg?style=social&label=Star'></a>
</div>
<p style="margin-top:5px;"><span class="highlight-topic">Focus:</span> A comprehensive survey of document image restoration techniques, covering appearance enhancement, deshadowing, dewarping, deblurring, and binarization.</p>
</div>

<h2>Awards</h2>
<ul class="custom-list">
  <li><strong>Shenzhen HighPower Technology Scholarship</strong>, 2022 (Top 2%)</li>
  <li><strong>First-Class Campus Scholarship</strong>, 2021 (Top 5%)</li>
  <li><strong>American Mathematical Contest in Modeling</strong>, Meritorious Prize, 2020</li>
  <li><strong>Alibaba Tianchi Competition</strong>, Top 1.2%, 2021</li>
</ul>

<h2>Mics</h2>
<p style="margin-top: 10px;">
<strong>Hobby</strong>: 🎣 Fishing, 🏊‍♂️ Swimming, 🚲 Riding, 🏓 Table tennis, 🏀 Basketball, 🎤 Singing. Learning 🎹 Piano.<br>
<strong>Languages</strong>: Chinese (Mandarin, Cantonese, Hakka), English.<br>
<strong>Habit</strong>: A heavy coffee drinker ☕.
</p>

<div style="text-align: center; margin-top: 50px;">
  <script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=ffffff&w=a&t=tt&d=TuVRvKdiJmKZ6t0SuQ7FsO2avdiz4cQm8yys_lX28-Q&co=2d78ad&cmo=3acc3a&cmn=ff5353&ct=ffffff'></script>
</div>

</div>