---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
 
<!-- # Short Bio  -->
# Biography

I am an Adjunct Ph.D. Supervisor at the School of AI, Shanghai Jiao Tong University. From August 2022 to July 2026, I served as a Research Scientist at [Shanghai AI Lab](https://www.shlab.org.cn/). My work focuses on the R&D of **General-Purpose Foundation Models**, with extensive experience in **Multimodal Understanding**, **Document Parsing**, and **Data-Centric AI**.

I believe that true innovation stems from deep diving, and more importantly, from the relentless refinement and bold reshaping of existing technologies. **Refusing to settle for the status quo**, my goal is to deliver research that is not only scientifically rigorous but also practically transformative—tackling the "hard problems" others cannot, to provide unique solutions for the industry's most critical challenges.

Guided by this philosophy, I led the R&D of **[MinerU](https://github.com/opendatalab/MinerU)**, an open-source toolkit for high-quality document parsing. The project has garnered over **50k GitHub stars** in just 1.5 years, frequently topping GitHub Trending charts. It is widely adopted by both academia and industry, serving as a **mainstream solution** for enterprises and developers building high-quality **LLM and RAG corpora**. Additionally, I have published over 50 papers in top-tier conferences such as CVPR, ICCV, NeurIPS, and ICLR, with over 6,000 Google Scholar citations.

---

我是上海交通大学人工智能学院兼职博士生导师，入选上海市东方英才拔尖人才项目。2022年8月至2026年7月，我曾在上海人工智能实验室（Shanghai AI Lab）担任青年科学家。我专注于**通用基础大模型**的研发；在**多模态理解**、**智能文档解析**与**以数据为中心的人工智能（Data-Centric AI）**等方向有长期积累。

我相信真正的创新源于深耕，更源于对现有技术的极致打磨与勇敢重塑。我不囿于既有的技术边界，而是致力于产出既具备科学严谨性，又具有变革意义的研究——通过攻克那些别人做不到的难题，为行业最关键的挑战提供独一无二的解决方案。秉持这一理念，我主导研发了开源文档解析工具 **[MinerU](https://github.com/opendatalab/MinerU)**。该项目在一年半内斩获 **50k+ GitHub Stars**，多次登顶 GitHub Trending 全球榜单，不仅在学术界广受好评，更被产业界广泛采用，成为众多企业与开发者构建高质量大模型语料及 RAG 语料库的主流选择。我在AI相关领域发表高水平论文50余篇，包含CVPR, ICCV, NeurIPS, ICLR 等顶级会议，谷歌学术引用超 6000 次。

📧 **Email:** ictwangbin@gmail.com

# 🔥 News

### 2026:
- *2026.04*: &nbsp;🔥🔥🔥 MinerU2.5-Pro is released! Pushing the limits of data-centric document parsing — achieves **95.69** on OmniDocBench v1.6, surpassing models with 200× more parameters (Gemini 3 Pro, GPT-5.2, Qwen3-VL-235B). [[Paper]](https://arxiv.org/abs/2604.04771) [[GitHub]](https://github.com/opendatalab/MinerU/)
- *2026.03*: &nbsp;🔥🔥🔥 MinerU-Diffusion is released! Rethinking Document OCR as inverse rendering via diffusion decoding — up to **3.26× faster** than MinerU2.5 with near-lossless accuracy. [[Paper]](https://arxiv.org/abs/2603.22458) [[GitHub]](https://github.com/opendatalab/MinerU-Diffusion)
- *2026.02*: &nbsp;🎉🎉 UniMERNet, TRivia, OmniDocLayout and ARM-Thinker are accepted by CVPR 2026.
- *2026.02*: &nbsp;🎉🎉 MoDora is accepted by SIGMOD 2026.


### 2025:
- *2025.09*: &nbsp;🎉🎉  MinerU 2.5 is released! A 1.2B vision-language model for document parsing. [[Tech Report]](https://arxiv.org/abs/2509.22186) [[Hugging Face Model]](https://huggingface.co/opendatalab/MinerU2.5-2509-1.2B) [[GitHub]](https://github.com/opendatalab/MinerU/)   
  - SOTA Performance: Surpasses general models (Gemini 2.5-Pro, GPT-4o, etc.) and specialized tools (MonkeyOCR, PP-StructureV3).  
  - High Efficiency: Achieves top accuracy with significantly greater speed than large-model solutions.  

- *2025.06*: &nbsp;🎉🎉 OHR, LEGION and Chimera are accepted by ICCV 2025.
- *2025.02*: &nbsp;🎉🎉 OmniDocBench and CDM are accepted by CVPR 2025.
- *2025.01*: &nbsp;🎉🎉 GeoX and OmniCorpus are accepted by ICLR 2025.

### 2024:
- *2024.09*: &nbsp;🎉🎉 InternLM-XComposer2-4KHD is accepted by NeurIPS 2024.
- *2024.07*: &nbsp;🔥🔥🔥 [<img src="images/pdf-extract-kit_logo.png" width="150px" style="vertical-align:bottom;">](https://github.com/opendatalab/PDF-Extract-Kit) has received **<span style="color:red">3500+</span>** GitHub stars within one month.
- *2024.07*: &nbsp;🔥🔥🔥 [<img src="images/mineru-logo.png" width="90px" style="vertical-align:bottom;">](https://github.com/opendatalab/MinerU) has received **<span style="color:red">4200+</span>** GitHub stars and **<span style="color:red">ranked #1</span>** on the GitHub Trending list.
- *2024.07*: &nbsp;🎉🎉 CLIP-Parrot-Bias is accepted by ECCV 2024 (<span style="color:red">**Oral**</span>).
- *2024.02*: &nbsp;🎉🎉 OPERA is accepted by CVPR 2024. 
- *2023.12*: &nbsp;🎉🎉 VIGC is accepted by AAAI 2024. 
- *2023.12*: &nbsp;🎉🎉 One paper is accepted by IJAEOG 2024. 
- *2023.08*: &nbsp;🎉🎉 DropQueries is accepted by TMM 2023. 
- *2023.08*: &nbsp;🎉🎉 V3Det is accepted by ICCV 2023 (<span style="color:red">**Oral**</span>). 
<!-- - *2022.07*: &nbsp;🎉🎉 PG-MPI is accepted by ECCV2022. -->

# 🚀 Project

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">New 🔥</div><img src='images/mineru2_5_pro.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**MinerU2.5-Pro**: Pushing the Limits of Data-Centric Document Parsing at Scale <strong>(Project Lead)</strong>](https://arxiv.org/abs/2604.04771) \|
 [**Models(Hugging Face)**](https://huggingface.co/opendatalab/MinerU2.5-Pro-2604-1.2B) \| [**Models(ModelScope)**](https://modelscope.cn/models/OpenDataLab/MinerU2.5-Pro-2604-1.2B) \| [**Github** ![](https://img.shields.io/github/stars/opendatalab/MinerU)](https://github.com/opendatalab/MinerU)

- **Current SOTA** on OmniDocBench v1.6, scoring **95.69** overall — surpassing models with **200× more parameters** (Gemini 3 Pro, GPT-5.2, Qwen3-VL-235B).
- Key insight: **data quality is the real ceiling**, not model size. We maintain the same **1.2B** model and unlock its full potential through **data engineering**: diversity-aware sampling (65.5M samples), cross-model verification for reliable annotations, and iterative refinement for hard samples.
- Three-stage progressive training: large-scale pre-training → hard sample fine-tuning → GRPO alignment.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">New 🔥</div><img src='images/mineru_diffusion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**MinerU-Diffusion**: Rethinking Document OCR as Inverse Rendering via Diffusion Decoding <strong>(Project Lead)</strong>](https://arxiv.org/abs/2603.22458) \| [**Github** ![](https://img.shields.io/github/stars/opendatalab/MinerU-Diffusion)](https://github.com/opendatalab/MinerU-Diffusion)

- A novel paradigm that reframes document OCR as **inverse rendering via diffusion decoding**, replacing autoregressive generation with block-wise parallel processing.
- Achieves up to **3.26× faster** throughput compared to MinerU2.5, with **2.12× speedup at 99.9% relative accuracy**.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Github Repo</div><img src='images/mineru2_5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**MinerU2.5**: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing <strong>(Project Lead)</strong>](https://arxiv.org/abs/2509.22186)| 
 [**Demo(Hugging Face)**](https://huggingface.co/spaces/opendatalab/MinerU) \| 
 [**Models(Hugging Face)**](https://huggingface.co/opendatalab/MinerU2.5-2509-1.2B) \| [**Models(ModelScope)**](https://modelscope.cn/models/OpenDataLab/MinerU2.5-2509-1.2B) \| [**Github** ![](https://img.shields.io/github/stars/opendatalab/MinerU)](https://github.com/opendatalab/MinerU)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Github Repo</div><img src='images/pdf-extract-kit-pipeline.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**PDF-Extract-Kit**: A Comprehensive Toolkit for High-Quality PDF Content Extraction <strong>(Project Lead)</strong>

[**Models(Hugging Face)**](https://huggingface.co/wanderkid/PDF-Extract-Kit) \| [**Models(ModelScope)**](https://www.modelscope.cn/models/wanderkid/PDF-Extract-Kit) \| [**Github** ![](https://img.shields.io/github/stars/opendatalab/PDF-Extract-Kit)](https://github.com/opendatalab/PDF-Extract-Kit)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Github Repo</div><img src='images/mineru-pipeline.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**MinerU**: An Open-Source Solution for Precise Document Content Extraction <strong>(Project Lead)</strong>](https://arxiv.org/abs/2409.18839)
 <a href="https://trendshift.io/repositories/11174" target="_blank"><img src="https://trendshift.io/api/badge/repositories/11174" alt="opendatalab%2FMinerU | Trendshift" style="width: 200px; height: 55px;"/></a> | [**Github** ![](https://img.shields.io/github/stars/opendatalab/MinerU)](https://github.com/opendatalab/MinerU)
</div>
</div>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/eccv2024_clip-parrot-bias.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Parrot Captions Teach CLIP to Spot Text](https://arxiv.org/abs/2312.14232)

Yiqi Lin<sup>*</sup>, Conghui He<sup>*</sup>, Alex Jinpeng Wang<sup>*</sup>, **Bin Wang**<sup>*</sup>, Weijia Li, Mike Zheng Shou

ECCV 2024 <span style="color:red">**Oral**</span>, \| [**Project**](https://linyq17.github.io/CLIP-Parrot-Bias/) \| [**Github** ![](https://img.shields.io/github/stars/opendatalab/CLIP-Parrot-Bias)](https://github.com/opendatalab/CLIP-Parrot-Bias)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/AAAI2024_VIGC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VIGC: Visual Instruction Generation and Correction](https://arxiv.org/abs/2308.12714)

**Bin Wang**, Fan Wu, Xiao Han, Jiahui Peng, Huaping Zhong, Pan Zhang, Xiaoyi Dong, Weijia Li, Wei Li, Jiaqi Wang, Conghui He

AAAI 2024, \| [**Project**](https://opendatalab.github.io/VIGC/) \| [**Github** ![](https://img.shields.io/github/stars/opendatalab/VIGC)](https://github.com/opendatalab/VIGC)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJAEOG 2024</div><img src='images/IJAEOG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring the user guidance for more accurate building segmentation from high-resolution remote sensing images](https://www.sciencedirect.com/science/article/pii/S1569843223004338)

Dinghao Yang<sup>*</sup>, **Bin Wang**<sup>*</sup>, Weijia Li, Conghui He

IJAEOG 2024,  \| [**Github** ![](https://img.shields.io/github/stars/StephenDHYang/UGBS-pytorch)](https://github.com/StephenDHYang/UGBS-pytorch)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2023</div><img src='images/DropQuery.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DropQueries: A Simple Way to Discover Comprehensive Segment Representations](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=WljXYoYAAAAJ&sortby=pubdate&citation_for_view=WljXYoYAAAAJ:ufrVoPGSRksC)

Haojie Ding, **Bin Wang**, Guoliang Kang, Weijia Li, Conghui He, Yao Zhao, and Yunchao Wei

TMM 2023 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/V3Det.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[V3Det: Vast Vocabulary Visual Detection Dataset](https://arxiv.org/abs/2304.03752)

Jiaqi Wang, Pan Zhang, Tao Chu, Yuhang Cao, Yujie Zhou, Tong Wu, **Bin Wang**, Conghui He, and Dahua Lin

ICCV 2023 <span style="color:red">**Oral**</span>, \| [**Project**](https://v3det.openxlab.org.cn/) \| [**Github** ![](https://img.shields.io/github/stars/V3Det/V3Det?style=social)](https://github.com/V3Det/V3Det) 

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2019</div><img src='images/IJCAI2019_BPG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Boundary perception guidance: A scribble-supervised semantic segmentation approach](https://opus.lib.uts.edu.au/bitstream/10453/141475/2/0508.pdf)

**Bin Wang**, Guojun Qi, Sheng Tang, Tianzhu Zhang, Yunchao Wei, Linghui Li, and Yongdong Zhang

IJCAI 2019
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2019</div><img src='images/MICCAI2019.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Spatiotemporal Breast Mass Detection Network(MD-Net) in 4D DCE-MRI Images](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=WljXYoYAAAAJ&citation_for_view=WljXYoYAAAAJ:u5HHmVD_uO8C)

Lixi Deng, Sheng Tang, Huazhu Fu, **Bin Wang**, and Yongdong Zhang

MICCAI 2019
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2018</div><img src='images/MICCAI2018_Nodule.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Automated pulmonary nodule detection: High sensitivity with few candidates](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=WljXYoYAAAAJ&citation_for_view=WljXYoYAAAAJ:2osOgNQ5qMEC)

**Bin Wang**, Guojun Qi, Sheng Tang, Liheng Zhang, Lixi Deng, and Yongdong Zhang

MICCAI 2018
</div>
</div>



<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021</div><img src='images/cocosnet_v2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CoCosNet v2: Full-Resolution Correspondence Learning for Image Translation](https://arxiv.org/pdf/2012.02047.pdf)

Xingran Zhou, Bo Zhang, Ting Zhang, **Pan Zhang**, Jianmin Bao, Dong Chen, Zhongfei Zhang, Fang Wen

CVPR 2021 <span style="color:red">**Oral**</span>, [<span style="color:red">**Best Paper Candidate**</span>](https://cvpr2021.thecvf.com/node/290) \| [**Github** ![](https://img.shields.io/github/stars/microsoft/CoCosNet-v2?style=social)](https://github.com/microsoft/CoCosNet-v2) \| [**Slides**](https://www.dropbox.com/s/g7dezxm2mhw6gqo/CoCosNet%20slides.pptx?dl=0)

</div>
</div> -->




<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2020.06*, Zhu Li Yuehua Outstanding Ph.D. student Scholarship, Chinese Academy of Sciences (CAS).
- *2016.09*, Won 3rd place in the ILSVRC 2016 VID task (Object Detection from Video).
 
<!-- - *2017.06*, Honor Ranking of Talent Program in Information Science and Technology (For top 5% students by USTC). 
- *2015.06*, National Scholarship (The highest scholarship awarded by the Ministry of Education, China).
- *2014.06*, National Scholarship (The highest scholarship awarded by the Ministry of Education, China). -->

# 🏢 Work Experience
- *2022.08 - 2026.07*, Research Scientist, Shanghai AI Lab, Shanghai, China.
- *2020.07 - 2022.08*, Researcher, SenseTime, Shenzhen, China.


# 📖 Education 
- *2015.09 - 2020.06*, Ph.D., University of Chinese Academy of Sciences, Beijing, China.
- *2013.09 - 2015.06*, M.S., Beijing Jiaotong University, Beijing, China.