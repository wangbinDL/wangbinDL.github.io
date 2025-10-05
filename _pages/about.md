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
I am currently a Research Scientist at [Shanghai AI Lab](https://www.shlab.org.cn/), working with Dr. [Conghui He](https://conghui.github.io/). My research focuses on Intelligent Document Understanding, Multimodal Large Language Models, and Data-Centric AI.  

I am the Head of R&D for the [MinerU project](https://github.com/opendatalab/MinerU), an open-source toolkit for high-quality document parsing that has garnered over 40k stars on GitHub. MinerU supports both traditional model pipelines and advanced multimodal large model approaches. 

Prior to joining Shanghai AI Lab, I was engaged in data algorithm research at SenseTime Group Inc. (2020-2022). I obtained my Ph.D. from the University of Chinese Academy of Sciences in 2020. Between 2018 and 2019,  I participated in the National Natural Science Foundation of China's joint Ph.D. training program at the University of Central Florida, under the supervision of Professors [Yongdong Zhang](https://scholar.google.com.hk/citations?user=hxGs4ukAAAAJ&hl=zh-CN) and [Guo-Jun Qi](https://scholar.google.com/citations?user=Nut-uvoAAAAJ&hl=zh-CN).


# 欢迎加入

我们持续招收对科研有强烈兴趣、自驱力强、有责任心的同学。开放职位包括：  
- 算法实习生  
- 青年研究员  
- 博士联培生（欢迎希望来实验室读博的同学投递，直博和普博均可） 

让我们一起做有影响力的事情。请将简历发送至：wangbin@pjlab.org.cn 或 ictwangbin@gmail.com。

<!-- We are seeking long-term internship candidates and looking for research collaboration. Please send email to me if you want to join us. -->


# 🔥 News

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
- *2020.07 - 2022.08*, Researcher, SenseTime, Shenzhen, China.


# 📖 Education 
- *2015.09 - 2020.06*, Ph.D., University of Chinese Academy of Sciences, Beijing, China.
- *2013.09 - 2015.06*, M.S., Beijing Jiaotong University, Beijing, China.