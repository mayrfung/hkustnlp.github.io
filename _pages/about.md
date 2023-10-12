---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- ## About Me -->
I am a tenure-track assistant professor in [The Hong Kong University of Science and Technology](https://hkust.edu.hk), [Department of Computer Science and Engineering](https://cse.hkust.edu.hk). 
<!-- in [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/), [John Hopcroft Center for Computer Science](http://jhc.sjtu.edu.cn/). -->
I obtained my PhD from [Carnegie Mellon University](https://www.cmu.edu), [Language Technologies Institute](https://www.lti.cs.cmu.edu) in the [School of Computer Science](https://www.cs.cmu.edu) in 2022, where I was co-advised by [Graham Neubig](http://www.phontron.com) and [Taylor Berg-Kirkpatrick](https://cseweb.ucsd.edu/~tberg/). Before that, I received the bachelor degree in Electronic Engineering from Shanghai Jiao Tong University in 2017. I also spent some time at Facebook AI Research (2019) and Salesforce Research (2020).  

<!-- I have interned at Facebook AI Research (2019), working with [Jiatao Gu](https://jiataogu.me) and [Marc'Aurelio Ranzato](https://ranzato.github.io); interned at Salesforce Research (2020), working with [Bryan McCann](https://bmccann.github.io); and visited Machine Learning Department of Carnegie Mellon University (2016), working with [Zhiting Hu](http://zhiting.ucsd.edu) and [Eric Xing](https://www.cs.cmu.edu/~epxing/).  -->

### <span style="color:red">Prospective Students:</span>
I am always actively looking for strong and self-motivated students to join us! I have multiple PhD/Mphil openings starting in 2024 Fall at HKUST, as well as RA positions starting anytime. If you are interested, please drop me an email with your CV (the email subject line should include "Prospective PhD/Mphil/RA Student"). For 2024 Fall PhD/Mphil applicants, I encourage you to reach out as soon as possible to ensure consideration. I may not be able to respond to all emails, sorry. 

# Research
        
I am generally interested in natural language processing and machine learning. Current interests are on several aspects around large language models: 
- parameter-efficient tuning -- efficiency, modular, composition 
- multi-step reasoning
- factuality -- method and evaluation
- evaluation of foundation models -- knowledge, reasoning, tool use, etc.
- data-centric approaches 
- language model as agent


<!-- My research covers (latent-variable) generative models, controllable text generation, efficient text generation, and non-parametric language models.  -->


# Publications
Most recent publications on [Google Scholar](https://scholar.google.com/citations?user=BIFGeoUAAAAJ&hl=en).  
\* denotes co-first authors
<!-- $^\dagger$ denotes corresponding author/main advisor -->

**Composing Parameter-Efficient Modules with Arithmetic Operations**  
Jinghan Zhang, Shiqi Chen, Junteng Liu, *<ins>Junxian He</ins>*  
NeurIPS 2023. [[arxiv]](https://arxiv.org/abs/2306.14870) [[code]](https://github.com/hkust-nlp/PEM_composition)

**Decomposition Enhances Reasoning via Self-Evaluation Guided Decoding**  
Yuxi Xie, Kenji Kawaguchi, Yiran Zhao, Xu Zhao, Min-Yen Kan, *<ins>Junxian He</ins>*, Qizhe Xie  
NeurIPS 2023. [[arxiv]](https://arxiv.org/abs/2305.00633) [[code]](https://github.com/YuxiXie/SelfEval-Guided-Decoding)

**C-Eval: A Multi-Level Multi-Discipline Chinese Evaluation Suite for Foundation Models**  
Yuzhen Huang\*, Yuzhuo Bai\*, Zhihao Zhu, Junlei Zhang, Jinghan Zhang, Tangjun Su, Junteng Liu, Chuancheng Lv, Yikai Zhang, Jiayi Lei, Yao Fu, Maosong Sun, *<ins>Junxian He</ins>*  
NeurIPS 2023 (Datasets and Benchmarks track). [[arxiv]](https://arxiv.org/abs/2305.08322) [[github]](https://github.com/hkust-nlp/ceval) [[website]](https://cevalbenchmark.com) [[dataset]](https://huggingface.co/datasets/ceval/ceval-exam)

**FELM: Benchmarking Factuality Evaluation of Large Language Models**  
Shiqi Chen, Yiran Zhao, Jinghan Zhang, I-Chun Chern, Siyang Gao, Pengfei Liu, *<ins>Junxian He</ins>*  
NeurIPS 2023 (Datasets and Benchmarks track). [[arxiv]](https://arxiv.org/abs/2310.00741) [[github]](https://github.com/hkust-nlp/felm) [[website]](https://hkust-nlp.github.io/felm/) [[dataset]](https://huggingface.co/datasets/hkust-nlp/felm)

**Contrastive Learning of Sentence Embeddings from Scratch**  
Junlei Zhang, Zhenzhong Lan, *<ins>Junxian He</ins>*  
EMNLP 2023. [[arxiv]](https://arxiv.org/abs/2305.15077)  [[code]](https://github.com/hkust-nlp/SynCSE)

**Simple Temporal Adaptation to Changing Label Sets: Hashtag Prediction via Dense KNN**  
Fatemehsadat Mireshghallah, Nikolai Vogler, *<ins>Junxian He</ins>*, Omar Florez, Ahmed El-Kishky, Taylor Berg-Kirkpatrick  
EMNLP 2023. [[arxiv]](https://arxiv.org/abs/2209.05706)

**Automatic Model Selection with Large Language Models for Reasoning**  
Xu Zhao, Yuxi Xie, Kenji Kawaguchi, *<ins>Junxian He</ins>*, Qizhe Xie  
EMNLP 2023 Findings. [[arxiv]](https://arxiv.org/abs/2305.14333) [[code]](https://github.com/XuZhao0/Model-Selection-Reasoning)

**Mega: Moving Average Equipped Gated Attention**  
Xuezhe Ma\*, Chunting Zhou\*, Xiang Kong, *<ins>Junxian He</ins>*, Liangke Gui, Graham Neubig, Jonathan May, Luke Zettlemoyer  
ICLR 2023. [[arxiv]](https://arxiv.org/abs/2209.10655)

**CTRLsum: Towards Generic Controllable Text Summarization**  
*<ins>Junxian He</ins>*, Wojciech Kryściński, Bryan McCann, Nazneen Rajani, Caiming Xiong  
EMNLP 2022. [[arxiv]](https://arxiv.org/abs/2012.04281) [[code]](https://github.com/salesforce/ctrl-sum) [[huggingface demo]](https://huggingface.co/spaces/akhaliq/ctrl-sum) [[streamlit demo]](https://share.streamlit.io/jxhe/ctrlsum-demo/ctrlsum_demo.py)

**Prompt Consistency for Zero-Shot Task Generalization**  
Chunting Zhou* , *<ins>Junxian He</ins>*\*, Xuezhe Ma, Taylor Berg-Kirkpatrick, Graham Neubig  
EMNLP 2022 Findings. [[arxiv]](https://arxiv.org/abs/2205.00049)

**Towards a Unified View of Parameter-Efficient Transfer Learning**  
*<ins>Junxian He</ins>*\*, Chunting Zhou*, Xuezhe Ma, Taylor Berg-Kirkpatrick, Graham Neubig   
ICLR 2022 (<span style="color:red">spotlight, 5%</span>). [[OpenReview]](https://openreview.net/forum?id=0RDcd5Axok) [[arxiv]](http://arxiv.org/abs/2110.04366) [[code]](https://github.com/jxhe/unify-parameter-efficient-tuning)

**Capturing Structural Locality in Non-parametric Language Models**  
Frank F. Xu, *<ins>Junxian He</ins>*, Graham Neubig, Vincent Josua Hellendoorn  
ICLR 2022. [[arxiv]](https://arxiv.org/abs/2110.02870)

**Neuro-Symbolic Language Modeling with Automaton-augmented Retrieval**  
Uri Alon, Frank F. Xu, *<ins>Junxian He</ins>*, Sudipta Sengupta, Dan Roth, Graham Neubig  
ICML 2022. [[arxiv]](https://arxiv.org/abs/2201.12431) [[code]](https://github.com/neulab/retomaton)

**Efficient Nearest Neighbor Language Models**  
*<ins>Junxian He</ins>*, Graham Neubig, Taylor Berg-Kirkpatrick  
EMNLP 2021. [[arxiv]](https://arxiv.org/abs/2109.04212) [[code]](https://github.com/jxhe/efficient-knnlm)

**The Source-Target Domain Mismatch Problem in Machine Translation**  
Jiajun Shen, Peng-Jen Chen, Matthew Le, *<ins>Junxian He</ins>*, Jiatao Gu, Myle Ott, Michael Auli, Marc'Aurelio Ranzato  
EACL 2021. [[arxiv]](https://arxiv.org/abs/1909.13151)

**Dependency Induction Through the Lens of Visual Perception**  
Ruisi Su, Shruti Rijhwani, Hao Zhu, *<ins>Junxian He</ins>*, Xinyu Wang, Yonatan Bisk, Graham Neubig  
CoNLL 2021. [[arxiv]](https://arxiv.org/abs/2109.09790) [[code]](https://github.com/ruisi-su/concrete_dep)

**Learning Sparse Protoypes for Text Generation**  
*<ins>Junxian He</ins>*, Taylor Berg-Kirkpatrick, Graham Neubig  
NeurIPS 2020. [[arxiv]](https://arxiv.org/abs/2006.16336) [[code]](https://github.com/jxhe/sparse-text-prototype)

**Revisiting Self-Training for Neural Sequence Generation**  
*<ins>Junxian He</ins>*\*, Jiatao Gu*, Jiajun Shen, Marc'Aurelio Ranzato  
ICLR 2020. [[arxiv]](https://arxiv.org/abs/1909.13788) [[code]](https://github.com/jxhe/self-training-text-generation)

**A Probabilistic Formulation of Unsupervised Text Style Transfer**  
*<ins>Junxian He</ins>*\*, Xinyi Wang*, Graham Neubig, Taylor Berg-Kirkpatrick  
ICLR 2020 (<span style="color:red">spotlight, 5%</span>). [[arxiv]](https://arxiv.org/abs/2002.03912) [[code]](https://github.com/cindyxinyiwang/deep-latent-sequence-model)

**On the Sentence Embeddings from Pre-trained Language Models**  
Bohan Li, Hao Zhou, *<ins>Junxian He</ins>*, Mingxuan Wang, Yiming Yang, Lei Li  
EMNLP 2020. [[arxiv]](https://arxiv.org/abs/2011.05864) [[code]](https://github.com/bohanli/BERT-flow)

**A Surprisingly Effective Fix for Deep Latent Variable Modeling of Text**  
Bohan Li\*, *<ins>Junxian He</ins>*\*, Graham Neubig, Taylor Berg-Kirkpatrick, Yiming Yang  
EMNLP 2019 (short paper). [[arxiv]](https://arxiv.org/abs/1909.00868) [[code]](https://github.com/bohanli/vae-pretraining-encoder)

**Cross-Lingual Syntactic Transfer through Unsupervised Adaptation of Invertible Projections**  
*<ins>Junxian He</ins>*, Zhisong Zhang, Taylor Berg-Kirkpatrick, Graham Neubig  
ACL 2019. [[arxiv]](https://arxiv.org/abs/1906.02656) [[code]](https://github.com/jxhe/cross-lingual-struct-flow)

**Texar: A modularized, versatile, and extensible toolkit for text generation**  
Zhiting Hu, Haoran Shi, Bowen Tan, Wentao Wang, Zichao Yang, Tiancheng Zhao, *<ins>Junxian He</ins>*, Lianhui Qin, Di Wang, Xuezhe Ma, Zhengzhong Liu, Xiaodan Liang, Wangrong Zhu, Devendra Singh Sachan, Eric P. Xing  
ACL 2019 (demo paper). <span style="color:red">Best demo paper nomination</span>. [[arxiv]](https://arxiv.org/abs/1809.00794) [[GitHub]](https://github.com/asyml/texar)

**Lagging Inference Networks and Posterior Collapse in Variational Autoencoders**  
*<ins>Junxian He</ins>*, Daniel Spokoyny, Graham Neubig, Taylor Berg-Kirkpatrick  
ICLR 2019. [[arxiv]](http://arxiv.org/abs/1901.05534) [[code]](https://github.com/jxhe/vae-lagging-encoder)

**Unsupervised Learning of Syntactic Structure with Invertible Neural Projections**   
*<ins>Junxian He</ins>*, Graham Neubig, Taylor Berg-Kirkpatrick  
EMNLP 2018. [[arxiv]](https://arxiv.org/abs/1808.09111) [[code]](https://github.com/jxhe/struct-learning-with-flow)

**StructVAE: Tree-structured Latent Variable Models for Semi-supervised Semantic Parsing**  
Pengcheng Yin, Chunting Zhou, *<ins>Junxian He</ins>*, Graham Neubig  
ACL 2018. [[arxiv]](https://arxiv.org/abs/1806.07832)

**Efficient Correlated Topic Modeling with Topic Embedding**  
*<ins>Junxian He</ins>*\*, Zhiting Hu*, Taylor Berg-Kirkpatrick, Ying Huang, Eric Xing  
KDD 2017. [[arxiv]](https://arxiv.org/abs/1707.00206)

**Text Network Exploration via Heterogeneous Web of Topics**  
*<ins>Junxian He</ins>*, Ying Huang, Changfeng Liu, Jiaming Shen, Yuting Jia, Xinbing Wang  
ICDM 2016 WorkShop. [[arxiv]](https://arxiv.org/abs/1610.00219) [[demo]]({{ site.baseurl }}/demo/TopicAtlas/CiteseerX.html) 

# Service
Area Chair: EMNLP22, ACL23, EMNLP23    
Reviewer: ICLR, NeurIPS, ICML, ACL, EMNLP, NAACL, ARR, TMLR

# Awards
Baidu PhD Fellowship, class of 2020 (10 recipients worldwide)  
Outstanding Undergraduate Thesis in SJTU (top 1%)  
National Scholarship in China (2014/2015/2016)
