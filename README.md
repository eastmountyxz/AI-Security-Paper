# AI-Security-Paper
This resource mainly counts papers related to APT attacks, including APT traceability, APT knowledge graph construction, APT malicious sample detection, and APT overview. Hope these summarized papers are helpful to you~

- sec-deadlines：https://sec-deadlines.github.io/
- GAN：https://github.com/hindupuravinash/the-gan-zoo

安全学术大佬博客：

- https://people.engr.tamu.edu/guofei/sec_conf_stat.htm

---

## 一.Classified by subject

### APT
- [1] **NDSS 2020**. Xueyuan Han, Thomas F. J.-M. Pasquier, Adam Bates, James Mickens, Margo I. Seltzer:
**Unicorn: Runtime Provenance-Based Detector for Advanced Persistent Threats**.  图结构提升隐蔽APTs检测 <br />
https://arxiv.org/abs/2001.01525 <br />
https://blog.csdn.net/xjxtx1985/article/details/106473928 【中文后续自归纳】
- [2] **S&P 2019**. Sadegh Momeni Milajerdi, Rigel Gjomemo, Birhanu Eshete, et al. **HOLMES: Real-Time APT Detection through Correlation of Suspicious Information Flows**. IEEE Symposium on Security and Privacy 2019: 1137-1152. 协同信息溯源、日志、TTPs  <br />
https://arxiv.org/pdf/1810.01594.pdf <br />
https://www.secrss.com/articles/14488 【中文后续自归纳】
- [3] **USENIX 2017**. **SLEUTH Real-time Attack Scenario Reconstruction from COTS Audit Data**
- [4] **CCS 2019**. Sadegh M. Milajerdi，Birhanu Eshete, et al. **Poirot: Aligning Attack Behavior with Kernel Audit Records for Cyber Threat Hunting**. 实体构建、攻击威胁猎杀 <br />
https://arxiv.org/pdf/1910.00056.pdf <br />
https://blog.csdn.net/sc0fie1d/article/details/105103342 【中文后续自归纳】
- [5] **TIFS 2018**. Yuqing Li, Wenkuan Dai, Jie Bai, et al. **An Intelligence-Driven Security-Aware Defense Mechanism for Advanced Persistent Threats**   <br />
https://ieeexplore.ieee.org/abstract/document/8386813
- [6] **Computer & Science**. LIU H B, WU T B, SHEN J, et al, **Advanced Persistent Threat Detection Based on Generative Adversarial Networks and Long Short-term Memory**. in Computer Science, vol.47, no.1, pp.281-286, 2020.  恶意DNS和流量分析的APT恶意软件检测  <br />
- [7] **RAID2020**. Jun Zhao, Qiben Yan, Xudong Liu, Bo Li, Guangsheng Zuo. **Cyber Threat Intelligence Modeling Based on Heterogeneous Graph Convolutional Network**. 基于异构图卷积网络的网络威胁情报建模   <br />
https://www.usenix.org/system/files/raid20-zhao.pdf  <br />
https://mp.weixin.qq.com/s/TszbHM__hpYvdHsCoMmkUQ 【中文后续自归纳】


---

### Knowledge Graph + Security
- [1] **CCS 2020**. Zhang X H, Zhang Y, Zhong M, et al. **Enhancing State-of-the-art Classifiers with API Semantics to Detect Evolved Android Malware**. API语义增强图+检测   <br />
https://dl.acm.org/doi/pdf/10.1145/3372297.3417291  <br />
https://mzgao.blog.csdn.net/article/details/114366920 【中文后续自归纳】 <br />
https://www.cnblogs.com/sjtuguyang/p/13860430.html 【中文后续自归纳】 <br />
https://blog.csdn.net/qq_30303857/article/details/111356626 【中文后续自归纳】
- [2] **CCS 2019**. Sadegh M. Milajerdi，Birhanu Eshete, et al. **Poirot: Aligning Attack Behavior with Kernel Audit Records for Cyber Threat Hunting**. 实体构建、攻击威胁猎杀 <br />
https://arxiv.org/pdf/1910.00056.pdf <br />
https://blog.csdn.net/sc0fie1d/article/details/105103342 【中文后续自归纳】
- [3] **RAID2020**. Jun Zhao, Qiben Yan, Xudong Liu, Bo Li, Guangsheng Zuo. **Cyber Threat Intelligence Modeling Based on Heterogeneous Graph Convolutional Network**. 基于异构图卷积网络的网络威胁情报建模 <br />
https://www.usenix.org/system/files/raid20-zhao.pdf  <br />
https://mp.weixin.qq.com/s/TszbHM__hpYvdHsCoMmkUQ 【中文后续自归纳】


---

### GNN\DNN\CNN\RNN + Security
- [1] **NDSS 2020**. Yue Duan, Xuezixiang Li, Jinghan Wang, Heng Yin, **DeepBinDiff: Learning Program-Wide Code Representations for Binary Diffing**. 深度学习二进制相似比对  <br />
https://www.ndss-symposium.org/wp-content/uploads/2020/02/24311-paper.pdf

- [2] 深度长文：图神经网络欺诈检测方法总结. https://mp.weixin.qq.com/s/ewzsURiU7bfG3gObzIP2Mw <br />


- [3] 腾讯科恩实验室论文Order Matters的工具 Binaryai 工具复现. https://www.anquanke.com/post/id/235580 <br />


---

### Malware Family Clustering and Classification


---

### Malware Analysis
- [1] **NDSS 2020**. Hojjat Aghakhani, Fabio Gritti, Francesco Mecca, et al. **When Malware is Packin' Heat; Limits of Machine Learning Classifiers Based on Static Analysis Features**.  加壳检测、对抗加壳 <br />
https://www.ndss-symposium.org/wp-content/uploads/2020/02/24310-paper.pdf <br />
https://github.com/ucsb-seclab/packware <br />
https://mzgao.blog.csdn.net/article/details/109822304 【中文后续自归纳】
- [2] **Usenix 2020**. Shuofei Zhu, Jianjun Shi, Limin Yang, et al. **Measuring and Modeling the Label Dynamics of Online Anti-Malware Engines**. VirusTotal分类优化  <br />
https://www.usenix.org/system/files/sec20fall_zhu_prepub.pdf



---

### Intrusion Detection System 
- [1] **Computers & Security**. Jianwu Zhang, Yu Ling, Xingbing Fu, et al. **Model of the intrusion detection system based on the integration of spatial-temporal features**. Comput. Secur. 89 (2020).  时空LSTM实现入侵检测 <br />
https://www.sciencedirect.com/science/article/pii/S0167404819302214


---

### Interesting repositories
- https://github.com/RedDrip7/APT_Digital_Weapon
- https://github.com/QData/deepWordBug
- https://github.com/angr/angr
- https://github.com/angr/angr-doc/tree/master/examples
- https://baimafujinji.blog.csdn.net/article/details/50926010
- https://app.any.run/submissions/
- https://github.com/kbandla/APTnotes
- https://github.com/cyber-research/APTMalware


---


### AI 对抗样本 

文本攻击与防御的论文概述

**(1) 文本攻击与防御的论文概述**
- Analysis Methods in Neural Language Processing: A Survey. Yonatan Belinkov, James Glass. TACL 2019.
- Towards a Robust Deep Neural Network in Text Domain A Survey. Wenqi Wang, Lina Wang, Benxiao Tang, Run Wang, Aoshuang Ye. 2019.
- Adversarial Attacks on Deep Learning Models in Natural Language Processing: A Survey. Wei Emma Zhang, Quan Z. Sheng, Ahoud Alhazmi, Chenliang Li. 2019.

**(2) 黑盒攻击**
- PAWS: Paraphrase Adversaries from Word Scrambling. Yuan Zhang, Jason Baldridge, Luheng He. NAACL-HLT 2019.
- Text Processing Like Humans Do: Visually Attacking and Shielding NLP Systems. Steffen Eger, Gözde Gül ¸Sahin, Andreas Rücklé, Ji-Ung Lee, Claudia Schulz, Mohsen Mesgar, Krishnkant Swarnkar, Edwin Simpson, Iryna Gurevych.NAACL-HLT 2019.
- Adversarial Over-Sensitivity and Over-Stability Strategies for Dialogue Models. Tong Niu, Mohit Bansal. CoNLL 2018.
- Generating Natural Language Adversarial Examples. Moustafa Alzantot, Yash Sharma, Ahmed Elgohary, Bo-Jhang Ho, Mani Srivastava, Kai-Wei Chang. EMNLP 2018.
- Breaking NLI Systems with Sentences that Require Simple Lexical Inferences. Max Glockner, Vered Shwartz, Yoav Goldberg ACL 2018.
- AdvEntuRe: Adversarial Training for Textual Entailment with Knowledge-Guided Examples. Dongyeop Kang, Tushar Khot, Ashish Sabharwal, Eduard Hovy. ACL 2018.
- Semantically Equivalent Adversarial Rules for Debugging NLP Models. Marco Tulio Ribeiro, Sameer Singh, Carlos Guestrin ACL 2018.
- Robust Machine Comprehension Models via Adversarial Training. Yicheng Wang, Mohit Bansal. NAACL-HLT 2018.
- Adversarial Example Generation with Syntactically Controlled Paraphrase Networks. Mohit Iyyer, John Wieting, Kevin Gimpel, Luke Zettlemoyer. NAACL-HLT 2018.
- Black-box Generation of Adversarial Text Sequences to Evade Deep Learning Classifiers. Ji Gao, Jack Lanchantin, Mary Lou Soffa, Yanjun Qi. IEEE SPW 2018.  <br />
https://arxiv.org/pdf/1801.04354.pdf
- Synthetic and Natural Noise Both Break Neural Machine Translation. Yonatan Belinkov, Yonatan Bisk. ICLR 2018.
- Generating Natural Adversarial Examples. Zhengli Zhao, Dheeru Dua, Sameer Singh. ICLR 2018.
Adversarial Examples for Evaluating Reading Comprehension Systems. Robin Jia, and Percy Liang. EMNLP 2017.

**(3) 白盒攻击**
- On Adversarial Examples for Character-Level Neural Machine Translation. Javid Ebrahimi, Daniel Lowd, Dejing Dou. COLING 2018.
- HotFlip: White-Box Adversarial Examples for Text Classification. Javid Ebrahimi, Anyi Rao, Daniel Lowd, Dejing Dou. ACL 2018.
- Towards Crafting Text Adversarial Samples. Suranjana Samanta, Sameep Mehta. ECIR 2018.

**(4) 同时探讨黑盒和白盒攻击**
- TEXTBUGGER: Generating Adversarial Text Against Real-world Applications. Jinfeng Li, Shouling Ji, Tianyu Du, Bo Li, Ting Wang. NDSS 2019.
- Comparing Attention-based Convolutional and Recurrent Neural Networks: Success and Limitations in Machine Reading Comprehension. Matthias Blohm, Glorianna Jagfeld, Ekta Sood, Xiang Yu, Ngoc Thang Vu. CoNLL 2018.
- Deep Text Classification Can be Fooled. Bin Liang, Hongcheng Li, Miaoqiang Su, Pan Bian, Xirong Li, Wenchang Shi.IJCAI 2018.

**(5) 对抗防御**
- Combating Adversarial Misspellings with Robust Word Recognition. Danish Pruthi, Bhuwan Dhingra, Zachary C. Lipton. ACL 2019.
评估

**(6) 对文本攻击和防御研究提出新的评价方法**
- On Evaluation of Adversarial Perturbations for Sequence-to-Sequence Models. Paul Michel, Xian Li, Graham Neubig, Juan Miguel Pino. NAACL-HLT 2019



https://www.cnblogs.com/zzxb/p/13246967.html

《网络攻防实践》实践作业


---

### NLP经典论文



**图神经网络**
- 01.Node2Vec：Node2Vec: Scalable Feature Learning for Networks
- 02.LINE：LINE: Large-scale Information Network Embedding
- 03.SDNE：Structural Deep Network Embedding
- 04.metapath2vec：metapath2vec:Scalable Representation Learning for Heterogeneous Networks
- 05.TransE/H/R/D:
TransE：Translating Embeddings for Modeling Multi-relational Data <br />
TransH：Knowledge Graph Embedding by Translating on Hyperplanes <br />
TransR：Learning entity and relation embeddings for knowledge graph completion <br />
TransD：Knowledge Graph Embedding via Dynamic Mapping Matrix <br />
- 06.GAT：Graph Attention Networks
- 07.GraphSAGE：Inductive Representation kearping on Large Graphs
- 08.GCN：Semi-Supervised Classification with Graph Convolutional Networks
- 09.GGNN：Gated Graph Sequence Neural Networks
- 10.MPNN：Neural Message Passing for Quantum Chemistry

**NLP精读论文目录**
- 01.Deep learning：Deep learning
- 02.word2vec：Efficient Estimation of Word Representations in Vector Space
- 03.句和文档的embedding：Distributed representations of sentences and docments
- 04.machine translation：Neural Machine Translation by Jointly Learning to Align and Translate
- 05.transformer：Transformer: attention is all you need
- 06.GloVe：GloVe: Global Vectors for Word Representation
- 07.Skip：Skip-Thought Vector
- 08.TextCNN：Convolutional Neural Networks for Sentence Classification
- 09.基于CNN的词级别的文本分类：Character-level Convolutional Networks for Text Classification
- 10.DCNN：A Convolutional Neural Network For Modelling Sentences
- 11.FASTTEXT：Bag of Tricks for Efficient Text Classification
- 12.HAN：Hierarchical Attention Network for Document Classification
- 13.PCNNATT：Neural Relation Extraction with Selective Attention over Instances
- 14.E2ECRF：End-to-end Sequence Labeling via Bi-directional LSTM-CNNS-CRF
- 15.多层LSTM：Sequence to Sequence Learning with Neural Networks
- 16.卷积seq2seq：Convolutional Sequence to Sequence Learning
- 17.GNMT：Google’s Neural Machine Translation System：Bridging the Gap between Human and Machine Translation
- 18.UMT：Phrase-Based&Neural Unsupervised Machine Translation
- 19.指针生成网络：Get To The Point:Summarization with Pointer-Generator Networks
- 20.End-to-End Memory Networks：End-to-End Memory Networks
- 21.QANet：QANet:Combining Local Convolution with Global Self-Attention for Reading Comprehension
- 22.双向Attention：Bi-Directional Attention Flow for Machine Comprehension
- 23.Dialogue：Adversarial Learning for Neural Dialogue Generation
- 24.缺
- 25.R-GCNs：Modeling Relational Data with GraphConvolutional Networks
- 26.大规模语料模型：Exploring the limits of language model
- 27.Transformer-XL：Transformer-XL:Attentive Language Models Beyond a Fixed-Length Context
- 28.TCN：An Empirical Evaluation of Generic Convolutional and Recurrent Networks for Sequence Modeling
- 29.Deep contextualized word representations
- 30.BERT:Pre-training of Deep Bidirectional Transformers for Language Understanding

**NLP Baseline**
- 1.Word2Vec.Efficient Estimation of Word Representations in Vector Space
- 2.GloVe.GloVe: Global Vectors for Word Representation
- 3.C2W.Finding Function in Form: Compositional Character Models for Open Vocabulary Word Representation
- 4.TextCNN.Convolutional Neural Networks for Sentence Classification
- 5.CharCNN.Character-level Convolutional Networks for Text Classification
- 6.FastText.Bag of Tricks for Efficient Text Classification
- 7.Seq2Seq.Sequence to Sequence Learning with Neural Networks
- 8.Attention NMT.Neural Machine Translation by Jointly Learning to Align and Translate
- 9.HAN.Hierarchical Attention Network for Document Classification
- 10.SGM.SGM: Sequence Generation Model for Multi-Label Classification


---

## 二.Classified by source

### Conferences & Journals Abroad


---

### Chinese Conference & Periodical



---

### Enterprise Analysis Report



----





By:Eastmount 2021-03-26
