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

I am currently a Research Scientist at [Shanghai AI Lab](https://www.shlab.org.cn/) and an Adjunct Ph.D. Supervisor at the School of AI, Shanghai Jiao Tong University. My research interests focus on **Multimodal Large Language Models**, **Next-Generation Document Understanding**, and **Data-Centric AI**.

I believe that true innovation stems from deep diving, and more importantly, from the relentless refinement and bold reshaping of existing technologies. **Refusing to settle for the status quo**, my goal is to deliver research that is not only scientifically rigorous but also practically transformative—tackling the "hard problems" others cannot, to provide unique solutions for the industry's most critical challenges.

Guided by this philosophy, I lead the R&D of **[MinerU](https://github.com/opendatalab/MinerU)**, an open-source toolkit for high-quality document parsing. The project has garnered over **50k GitHub stars** in just 1.5 years, frequently topping GitHub Trending charts. It is widely adopted by both academia and industry, serving as a **mainstream solution** for enterprises and developers building high-quality **LLM and RAG corpora**. Additionally, I have published over 40 papers in top-tier conferences such as CVPR, ICCV, NeurIPS, and ICLR, with over 4,000 Google Scholar citations.

---

我是上海人工智能实验室（Shanghai AI Lab）的青年科学家，上海交通大学人工智能学院兼职博士生导师，入选上海市东方英才拔尖人才项目。我的研究聚焦于**多模态大模型**、**下一代智能文档理解**以及**以数据为中心的人工智能（Data-Centric AI）**。

我相信真正的创新源于深耕，更源于对现有技术的极致打磨与勇敢重塑。我不囿于既有的技术边界，而是致力于产出既具备科学严谨性，又具有变革意义的研究——通过攻克那些别人做不到的难题，为行业最关键的挑战提供独一无二的解决方案。秉持这一理念，我主导研发了开源文档解析工具 **[MinerU](https://github.com/opendatalab/MinerU)**。该项目在一年半内斩获 **50k+ GitHub Stars**，多次登顶 GitHub Trending 全球榜单，不仅在学术界广受好评，更被产业界广泛采用，成为众多企业与开发者构建高质量大模型语料及 RAG 语料库的主流选择。同时，我在 CVPR, ICCV, NeurIPS, ICLR 等顶级会议发表论文 40 余篇，谷歌学术引用超 4000 次。

我们持续寻找优秀的博士生（上交等顶尖高校博士联培名额）、博士后研究员、实习生及全职研究人员，如果你对人工智能方向充满热情，自驱力强，欢迎电子邮件联系加入我们。

📧 **Email:** ictwangbin@gmail.com / wangbin@pjlab.org.cn

# 为什么加入我们？

**1. 做有价值的前沿研究**  
我们的方向——多模态大模型、智能文档解析和 Data-Centric AI，是通往 AGI 的必经之路。我不想带大家为了发论文而发论文，或者做低水平的重复建设。在这里，我们只做两件事：要么解决产业界最棘手的痛点，要么挑战学术界未解的难题。**要做，就做能被同行记住、被开发者真正使用的工作。**

**2. 充足的资源与纯粹的氛围**  
算力是做大模型研究的底气。实验室拥有充足的 GPU 集群，你不必因为资源受限而缩手缩脚，可以大胆去验证那些昂贵的想法。组里的小伙伴均来自顶尖高校，大家年龄相仿，科研氛围很纯粹。对于博士生和实习生，实验室提供不错的津贴，让大家可以专注于技术突破。

**3. 亦师亦友，全流程指导**  
我自己也是从学生过来的，深知大家在不同阶段的痛点，所以我拒绝“放养”。
*   **定制化培养**：我不会当“甩手掌柜”。从选题、Coding 到写 Paper，我会提供一对一指导，并根据你的特长规划路线。
*   **清晰的路径**：我们每周都有前沿 Paper Reading。我的目标很明确：带你走完从【夯实基础】到【独立发顶会】，再到【做出影响力工作】的全过程，最终把你培养成能独当一面的研究者。
*   **平等的交流**：作为青年导师，我们之间没有代沟。无论是科研卡壳了，还是对未来迷茫了，随时都可以找我聊。

**4. 期待你的加入**  
目前 2026 级博士生名额已满，非常欢迎 **2027 级直博生、普博生** 提前联系来组里实习。
做科研是一场长跑，希望能找到志同道合的你，**一起在大模型时代做点不一样的事情。**
*(注：对于已经毕业的优秀研究人员，如果渴望在具有影响力的平台上施展拳脚，同样欢迎联系加入。)*




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