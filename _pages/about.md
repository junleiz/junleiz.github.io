---
permalink: /
# title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student at [Zhejiang University](https://www.zju.edu.cn/english/) and [Westlake University](https://www.westlake.edu.cn/). I am fortunate to be advised by [Zhenzhong Lan](https://scholar.google.com/citations?user=tlDABkgAAAAJ&hl=zh-CN). I am also a remote visiting student at [The HongKong University of Science and Technology](https://www.ust.hk/) and fortunately to be advised by  [Junxian He](https://jxhe.github.io/). 


I am generally interested in LLM as Agent ([Agentboard](https://github.com/hkust-nlp/AgentBoard), [Predictive Decoding](https://arxiv.org/abs/2410.17195)), GUI agent ([GUIMid](https://github.com/hkust-nlp/GUIMid)) and Synthetic Data ([SynCSE](https://github.com/hkust-nlp/SynCSE), [IS-CSE](https://arxiv.org/abs/2305.07424)).

Most recent publications on [Google Scholar](https://scholar.google.com/citations?user=wsZNfbgAAAAJ&hl=en).  

======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).


### 📚 Preprint
#### Compression Represents Intelligence Linearly  
 
**Junlei Zhang\***, Zichen Ding\*, Chang Ma, Zijie Chen,  Qiushi Sun, Zhenzhong Lan, Junxian He†. **Submitted to COLM 2025**   
[Paper](https://arxiv.org/abs/2504.10127)  | [Dataset](https://huggingface.co/datasets/hkust-nlp/GUIMid/)

<!-- > **Abstract:** In this paper, we study the relationship between compression rate and intelligence of LLMs. -->

### 📚 Publications

\* denotes co‑first authors

---

#### AgentBoard: An Analytical Evaluation Board of Multi-turn LLM Agents 
Ma Chang\*, **Junlei Zhang\***, Zhihao Zhu\*, Cheng Yang\*, Yujiu Yang, Yaohui Jin, Zhenzhong Lan, Lingpeng Kong, Junxian He†. **NeurIPS 2024 Oral**  
[Paper](https://arxiv.org/abs/2401.13178) | [Dataset](https://huggingface.co/datasets/hkust-nlp/agentboard) | [Code](https://github.com/hkust-nlp/AgentBoard)  

<!-- > **Abstract:** In this paper, we study the relationship between compression rate and intelligence of LLMs. -->

---

#### Non-myopic Generation of Language Models for Reasoning and Planning

Chang Ma, Haiteng Zhao, **Junlei Zhang**, Junxian He†, Lingpeng Kong†.  **ICLR 2025**
[Paper](https://arxiv.org/pdf/2410.17195) | [Code](https://github.com/chang-github-00/llm-predictive-decoding)  


---

#### Instance smoothed contrastive learning for unsupervised sentence embedding

Hongliang He\*, **Junlei Zhang\***, Zhenzhong Lan†, Yue Zhang†. **AAAI 2023, Project leader**  
[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/26512) | [Code](https://github.com/dll-wu/IS-CSE)  

---

#### Contrastive learning of sentence embeddings from scratch

**Junlei Zhang**, Zhenzhong Lan, Junxian He†. **EMNLP 2023**  
[Paper](https://arxiv.org/abs/2305.15077) | [Code](https://github.com/hkust-nlp/SynCSE)  

---

#### C‑Eval: A Multi‑Level Multi‑Discipline Chinese Evaluation Suite for Foundation Models  
  
Yuzhen Huang\*, Yuzhuo Bai\*, Zhihao Zhu, **Junlei Zhang**, Jinghan Zhang, Tangjun Su, Junteng Liu, Chuancheng Lv, Yikai Zhang, Jiayi Lei, Yao Fu, Maosong Sun, Junxian He†. **NeurIPS 2023**  
[Paper](https://arxiv.org/abs/2305.08322) | [Website](https://cevalbenchmark.com) | [Dataset](https://huggingface.co/datasets/ceval/ceval-exam) | [Code](https://github.com/hkust-nlp/ceval)  

---

#### Residual Distillation: Towards Portable Deep Neural Networks without Shortcuts


Guilin Li\*, **Junlei Zhang\***, Yunhe Wang, Chuanjian Liu, Matthias Tan, Yunfeng Lin, Wei Zhang, Jiashi Feng, Tong Zhang **NeurIPS 2020**    
[Paper](https://proceedings.neurips.cc/paper/2020/hash/657b96f0592803e25a4f07166fff289a-Abstract.html) | [Code](https://github.com/leoozy/JointRD_Neurips2020)  

---

<!-- **Composing Parameter-Efficient Modules with Arithmetic Operations**  
*<ins>Jinghan Zhang</ins>*, Shiqi Chen, Junteng Liu, Junxian He$^\dagger$  
NeurIPS 2023. [[arxiv]](https://arxiv.org/abs/2306.14870) [[github]](https://github.com/hkust-nlp/PEM_composition)

**C-Eval: A Multi-Level Multi-Discipline Chinese Evaluation Suite for Foundation Models**  
Yuzhen Huang\*, Yuzhuo Bai\*, Zhihao Zhu, Junlei Zhang, *<ins>Jinghan Zhang</ins>*, Tangjun Su, Junteng Liu, Chuancheng Lv, Yikai Zhang, Jiayi Lei, Yao Fu, Maosong Sun, Junxian He$^\dagger$  
NeurIPS 2023 (Datasets and Benchmarks track). [[arxiv]](https://arxiv.org/abs/2305.08322) [[github]](https://github.com/hkust-nlp/ceval) [[website]](https://cevalbenchmark.com) [[dataset]](https://huggingface.co/datasets/ceval/ceval-exam)

**FELM: Benchmarking Factuality Evaluation of Large Language Models**  
Shiqi Chen, Yiran Zhao, *<ins>Jinghan Zhang</ins>*, I-Chun Chern, Siyang Gao, Pengfei Liu, Junxian He$^\dagger$  
NeurIPS 2023 (Datasets and Benchmarks track). [[arxiv]](https://arxiv.org/abs/2310.00741) [[github]](https://github.com/hkust-nlp/felm) [[website]](https://hkust-nlp.github.io/felm/) [[dataset]](https://huggingface.co/datasets/hkust-nlp/felm)
-->

## 🌟 Internship
- *2019.09 - 2020.09 Huawei Noah's Ark Lab, Hong Kong, China.
## 🎖 Awards 
- *2014.7* National Scholarship 


## 📖 Education
- *2020.09 - now* PhD Candidate, [Zhejiang University](https://www.zju.edu.cn/), Hangzhou, China.
 - *2020.09 - now* PhD Candidate, [Westlake University](https://www.westlake.edu.cn/), Hangzhou, China.
- *2017.09 - 2019.07* Master, Computer Technology, [Harbin Institute of Technology](https://www.hit.edu.cn/), Harbin, China.
- *2013.09 - 2017.06* Undergraduate, Electrical Engineering and Automation, [Southwest jiaotong University](https://www.swjtu.edu.cn/), Chengdu, China.