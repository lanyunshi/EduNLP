# Educational NLP
![](https://img.shields.io/github/last-commit/txsun1997/LMaaS-Papers?color=green) ![](https://img.shields.io/badge/PaperNumber-63-brightgreen)

This is a list of "Application of NLP in Education" papers.
We strongly encourage the nlp researchers who are interested in this topic to make pull request and collaborate with us!

## Updates

- 2023/05/19: Create this paper list

## Contents

- [Introduction](#introduction)
  - [Scope](#scope)
  - [Advantages](#advantages)
- [Keywords](#keywords)
- [Papers](#papers)
  - [Readability Assessment](#readability-assessment)
  - [Grammar Error Correction](#grammar-error-correction)
  - [Text Rewriting](#text-rewriting)
  - [Controllable Text Generation](#controllable-text-generation)
  - [Educational NLP and LLMs](#educational-large language models)
- [Contributing](#contributing)

## Introduction

Natural Language Processing (NLP) can be applied to different domains, such as finance, medicine, and education. We focus on the application of NLP on education domain. And discuss multiple tasks such as readability assessment, grammar error correction, text rewriting and educational LLMs. To make this page benefit a wider range audiences, we collect papers that fit into this topic to facilitate future research.

### Scope

In this github page, we mainly focus on the tasks which are related to the Educational NLP and the tasks that play siginificant role in Education scenarios. In our scope, we prefer serving general knowledge and models for a variety of audients who are intersted in Educational NLP.

In existing literature, we identify serveral lines of researches that fit into Educational NLP.

- **Readability Assessment** is a task aiming to assess the readability of a text. In Educational scenarios, evaluating the readability level for readers is important. The teachers can assign sutiable reading materials to the students with certain-level reading capabilities. Similairly, students can choose the reading materials for themselves to improve the their reading skills. However, readability assessment is built upon different aspects, such as the word-level, gramamtical complexity and so on. How to identfy these significant aspects and how to model them are the targets of this task.
- **Grammar Error Correction** is an important task in NLP. During language teaching, a tool that can automatically correct students' grammar errors can help a student do self-learning. Moreover, a grammar error correction system which can provide interpretation to the students can help them identify their weaknesses and identify the weakness of their knowledge.
- **Text Rewriting** is to paraphrase a sentence. By controlling the semantics of the sentence unchangeable, we can change the syntax of the sentence and change the readability, style or even sentiment of the sentences. In Education scenarios, this not only benefits the teachers to prepare enriched teaching meterials, but also benefits the students learn more expressions for a single purpose.
- **Controllable Text Generation** is to generate sentences with contraint words, which fits into the storytelling and sentence making applications. Two objectives should be hold. On the one hand, the generated sentences should contain the given constraints. On the other hand, the generated sentences should make sense in logical aspect and have fluent expression.
- **Educational LLMs** denotes large language model in Educational domain. Existing LLMs are trained with general corpus and maintain knowledge to general domains. However, Education scenarios require LLMs equipped with Educational knowledge. For example, standard evaluation criterias of the language learning, essay writing and storytelling. These evaluation criterias are important to evaluate a student.



## Keywords

![](https://img.shields.io/badge/GECToR-blue) The abbreviation of the work. 

![](https://img.shields.io/badge/Supervised-red) The key feature of the work. (Prompt-based, supervised, unsupervised, ...)

![](https://img.shields.io/badge/Chinese-green) The main experimental language of the work. (Chinese, English, ... )

![](https://img.shields.io/badge/Survey-yellow) Survey or Technical paper or Dataset paper

## Papers

### Readability Assessment

1. **Lexical Complexity Prediction: An Overview**. ACM Computing Surveys 2023![](https://img.shields.io/badge/Survey-yellow)

   *Kai North, Marcos Zampieri, Matthew Shardlow*. [[pdf](https://arxiv.org/pdf/2303.04851.pdf)]

2. **Prompt-based Learning for Text Readability Assessment**. EACL 2023 Findings![](https://img.shields.io/badge/Prompt--based-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Bruce W. Lee, Jason Hyung-Jong Lee*. [[pdf](https://arxiv.org/pdf/2302.13139.pdf)] [[code](https://github.com/brucewlee/prompt-learning-readability)]

3. **Traditional Readability Formulas Compared for English**. Preprint 2023.1![](https://img.shields.io/badge/NERF-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Bruce W. Lee, Jason Hyung-Jong Lee*. [[pdf](https://arxiv.org/pdf/2301.02975.pdf)]

4. **基于新标准的汉语二语文本阅读难度分级体系构建与应用**. 世界汉语教学 2023 ![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

   *程勇;董军;晋淑华*. [[link](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7ioT0BO4yQ4m_mOgeS2ml3UGjhHxYRtK0YyE7JgxJdrmFNCqGN1JKD4Datb88yFZs0&uniplatform=NZKPT)]

5. **A Unified Neural Network Model for Readability Assessment with Feature Projection and Length-Balanced Loss**. EMNLP 2022![](https://img.shields.io/badge/BERT--FP--LBL-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Abu Dhabi, United Arab Emirates*. [[pdf](https://aclanthology.org/2022.emnlp-main.504.pdf)]

6. **Enhancing Automatic Readability Assessment with Pre-training and Soft Labels for Ordinal Regression**. EMNLP 2022 Findings![](https://img.shields.io/badge/DTRA-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

   *Jinshan Zeng, Yudong Xie, Xianglong Yu, John Lee, Ding-Xuan Zhou*. [[pdf](https://aclanthology.org/2022.findings-emnlp.334.pdf)]

7. **A Neural Pairwise Ranking Model for Readability Assessment**. ACL 2022 Findings![](https://img.shields.io/badge/NPRM-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English Spanish French-green)![](https://img.shields.io/badge/Technical--paper-yellow)

   *Justin Lee, Sowmya Vajjala*. [[pdf](https://arxiv.org/pdf/2203.07450.pdf)] [[code](https://github.com/jlee118/NPRM/)]

8. **CEFR-Based Sentence Difficulty Annotation and Assessment**. EMNLP 2022![](https://img.shields.io/badge/CEFR--SP-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Dataset-yellow)

   *Yuki Arase, Satoru Uchida, Tomoyuki Kajiwara*. [[pdf](https://arxiv.org/pdf/2210.11766.pdf)]

9. **Trends, Limitations and Open Challenges in Automatic Readability Assessment Research**. LREC 2022![](https://img.shields.io/badge/Survey-yellow)

   *Sowmya Vajjala*. [[pdf](https://arxiv.org/pdf/2105.00973.pdf)]

10. **汉语水平考试（HSK）阅读文本可读性自动评估研究**. 语言文字应用 2022![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

   *杜月明;王亚敏;王蕾*. [[link](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7iJTKGjg9uTdeTsOI_ra5_XVa5SQB5_9XY7pzGH8TwyZ9YQgL9OtGWJc3PXP1YQGb9&uniplatform=NZKPT)]

11. **篇章结构特征对文本可读性的影响**. 语言文字应用 2022![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

    *柏晓鹏;吉伶俐*. [[link](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7iJTKGjg9uTdeTsOI_ra5_XVa5SQB5_9XY5m6k3sSPmCFIoSo7W9sGxDB3IbrMhRe5&uniplatform=NZKPT)]

12. **汉语语法点特征及其在二语文本难度自动分级研究中的应用**. 语言文字应用 2022![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

    *朱君辉;刘鑫;杨麟儿;王鸿滨;杨尔弘*. [[link](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7iJTKGjg9uTdeTsOI_ra5_XVa5SQB5_9XYV79CwbfsprLStCtkIoh1h56keK3i-cqt&uniplatform=NZKPT)]

13. **文本可读性公式研究发展阶段及特点**.  语言教学与研究 2022![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

    *王蕾*. [[link](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7iJTKGjg9uTdeTsOI_ra5_XQmXIOHx8oxif3G7Bgci5IAp9NoNvgMz5mcOzqPO_2np&uniplatform=NZKPT)]

14. **结合深度学习和语言难度特征的句子可读性计算方法**. 中文信息学报 2022![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

    *唐玉玲;张宇飞;于东*. [[link](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7iJTKGjg9uTdeTsOI_ra5_Xf_c9lUDyv5pFimvaeosAS5iNXh87OS7YYTbB5TG6B7O&uniplatform=NZKPT)]

15. **Supervised and Unsupervised Neural Approaches to Text Readability**. Computational Linguistics 2021![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green) ![](https://img.shields.io/badge/Survey-yellow)

    *Matej Martinc, Senja Pollak, Marko Robnik-Šikonja*. [[pdf](https://direct.mit.edu/coli/article-pdf/47/1/141/1911429/coli_a_00398.pdf)]

16. **Automated Text Simplification: A Survey**. CSUR 2021![](https://img.shields.io/badge/Survey-yellow)

    *Al-Thanyyan S S, Azmi A M*. [[pdf](https://opencourses.ionio.gr/modules/document/file.php/DDI211/%CE%95%CE%A1%CE%93%CE%91%CE%A3%CE%99%CE%91/thesis.pdf)]

17. **Pushing on Text Readability Assessment: A Transformer Meets Handcrafted Linguistic Features**. EMNLP 2021![](https://img.shields.io/badge/RoBERTA--RF--T1-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Bruce W. Lee, Yoo Sung Jang, Jason Hyung-Jong Lee*. [[pdf](https://aclanthology.org/2021.emnlp-main.834v2.pdf)] [[code](https://github.com/brucewlee/lingfeat)] [[code](https://github.com/yjang43/pushingonreadability_transformers)] [[code](https://github.com/brucewlee/pushingonreadability_traditional_ML)]

11. **Learning Syntactic Dense Embedding with Correlation Graph for Automatic Readability Assessment**. ACL 2021![](https://img.shields.io/badge/Dual--Model-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Xinying Qiu, Yuan Chen, Hanwu Chen, Jian-Yun Nie, Yuming Shen, Dawei Lu*[[pdf](https://arxiv.org/ftp/arxiv/papers/2107/2107.04268.pdf)] [[code](https://github.com/luv2Lab/linguistic-feature-embedding)]

12. **Simple or Complex? Learning to Predict Readability of Bengali Texts**. AAAI 2021![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/Bengali-green)![](https://img.shields.io/badge/Technical-yellow)

    *Susmoy Chakraborty, Mir Tafseer Nayeem, Wasi Uddin Ahmad*.  [[pdf](https://arxiv.org/pdf/2012.07701.pdf)] [[code](https://github.com/tafseer-nayeem/BengaliReadability)]

13. **基于多元语言特征与深度特征融合的中文文本阅读难度自动分级研究**. 中文信息学报 2020![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

    程勇;徐德宽;董军. [[link](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7i8oRR1PAr7RxjuAJk4dHXohTl3Ytpz4iO9SkWJqliG6jNUUgUvGdllbxN_dRLwsA1&uniplatform=NZKPT)]

14. **Multiattentive Recurrent Neural Network Architecture for** **Multilingual Readability Assessment**. TACL 2019![](https://img.shields.io/badge/Vec2Read-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/Mutilingual-green)![](https://img.shields.io/badge/Technical-yellow)

    *Ion Madrazo Azpiazu, Maria Soledad Pera*. [[pdf](https://aclanthology.org/Q19-1028.pdf)] [[code](https://github.com/ionmadrazo/Vec2Read)]

15. **文本可读性的自动分析研究综述**. 中文信息学报 2018![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

    *吴思远;蔡建永;于东;江新*. [[link](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7iLik5jEcCI09uHa3oBxtWoInN11a1qPBjb-oMD4oOR1cQoRiT6ypX9IYhshL0I1u3&uniplatform=NZKPT)]

### Grammar Error Correction

1. **ChatGPT or Grammarly? Evaluating ChatGPT on Grammatical Error Correction Benchmark**. Preprint 2023  ![](https://img.shields.io/badge/Prompt--based-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Haoran Wu, Wenxuan Wang, Yuxuan Wan, Wenxiang Jiao, Michael Lyu*. [[pdf](https://arxiv.org/abs/2303.13648)]

2. **CLEME: Debiasing Multi-reference Evaluation for Grammatical Error Correction**. Preprint 2023  ![](https://img.shields.io/badge/CLEME-blue) ![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Evaluation-yellow)

   *Jingheng Ye, Yinghui Li, Qingyu Zhou, Yangning Li, Shirong Ma, Hai-Tao Zheng, Ying Shen*. [[pdf](https://arxiv.org/abs/2305.10819)] [[code](https://github.com/yejh123/CLEME)]

3. **Are Pre-trained Language Models Useful for Model Ensemble in Chinese Grammatical Error Correction?**. ACL 2023  ![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

   *Chenming Tang, Xiuyu Wu, Yunfang Wu*. [[pdf](https://arxiv.org/abs/2305.15183)] [[code](https://github.com/JamyDon/PLM-based-CGEC-Model-Ensemble)]

4. **Linguistic Rules-Based Corpus Generation for Native Chinese Grammatical Error Correction**. EMNLP 2022 ![](https://img.shields.io/badge/NaCGEC-blue) ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Dataset-yellow)

   *Shirong Ma, Yinghui Li, Rongyi Sun, Qingyu Zhou, Shulin Huang, Ding Zhang, Li Yangning, Ruiyang Liu, Zhongli Li, Yunbo Cao, Haitao Zheng, Ying Shen*. [[pdf](https://arxiv.org/abs/2210.10442)] [[code](https://github.com/masr2000/CLG-CGEC)]

5. **SynGEC: Syntax-Enhanced Grammatical Error Correction with a Tailored GEC-Oriented Parser**. EMNLP 2022  ![](https://img.shields.io/badge/SynGEC-blue) ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Yue Zhang, Bo Zhang, Zhenghua Li, Zuyi Bao, Chen Li, Min Zhang*. [[pdf](https://arxiv.org/abs/2210.12484)] [[code](https://github.com/HillZhang1999/SynGEC)]

6. **Revisiting Grammatical Error Correction Evaluation and Beyond**. EMNLP 2022  ![](https://img.shields.io/badge/PT--M2-blue) ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Evaluation-yellow)

   *Peiyuan Gong, Xuebo Liu, Heyan Huang, Min Zhang*. [[pdf](https://arxiv.org/abs/2211.01635)] [[code](https://github.com/pygongnlp/PT-M2)]

7. **Sequence-to-Action: Grammatical Error Correction with Action Guided Sequence Generation**. AAAI 2022 ![](https://img.shields.io/badge/S2A-blue) ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

   *Jiquan Li, Junliang Guo, Yongxin Zhu, Xin Sheng, Deqiang Jiang, Bo Ren, Linli Xu*. [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/21345)]

8. **MuCGEC: a Multi-Reference Multi-Source Evaluation Dataset for Chinese Grammatical Error Correction**. NAACL 2022 ![](https://img.shields.io/badge/MuCGEC-blue) ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Dataset-yellow)

   *Yue Zhang, Zhenghua Li, Zuyi Bao, Jiacheng Li, Bo Zhang, Chen Li, Fei Huang, Min Zhang*. [[pdf](https://arxiv.org/abs/2204.10994)] [[code](https://github.com/HillZhang1999/MuCGEC)]

9. **Frustratingly Easy System Combination for Grammatical Error Correction**. NAACL 2022 ![](https://img.shields.io/badge/ESC-blue) ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

10. **A Unified Strategy for Multilingual Grammatical Error Correction with Pre-trained Cross-Lingual Language Model**. Preprint 2022.6 ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

    *Xin Sun, Tao Ge, Shuming Ma, Jingjing Li, Furu Wei, Houfeng Wang*. [[pdf](https://arxiv.org/abs/2201.10707)] 

11. **Interpretability for Language Learners Using Example-Based Grammatical Error Correction**. ACL 2022 ![](https://img.shields.io/badge/EB--GEC-blue) ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Masahiro Kaneko, Sho Takase, Ayana Niwa, Naoaki Okazaki*. [[pdf](https://arxiv.org/abs/2203.07085)] [[code](https://github.com/kanekomasahiro/eb-gec)]

12. **Ensembling and Knowledge Distilling of Large Sequence Taggers for Grammatical Error Correction**. ACL 2022 ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Maksym Tarnavskyi, Artem Chernodub, Kostiantyn Omelianchuk*. [[pdf](https://arxiv.org/abs/2203.13064)] [[code](https://github.com/MaksTarnavskyi/gector-large)]

13. **FastCorrect: Fast Error Correction with Edit Alignment for Automatic Speech Recognition**. NeurIPS 2021 ![](https://img.shields.io/badge/FastCorrect-blue) ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

    *Yichong Leng, Xu Tan, Linchen Zhu, Jin Xu, Renqian Luo, Linquan Liu, Tao Qin, Xiangyang Li, Edward Lin, Tie-Yan Liu*. [[pdf](https://proceedings.neurips.cc/paper/2021/hash/b597460c506e8e35fb0cc1c1905dd3bc-Abstract.html)] [[code](https://github.com/microsoft/NeuralSpeech/tree/master/FastCorrect)]

14. **LM-Critic: Language Models for Unsupervised Grammatical Error Correction**. EMNLP 2021  ![](https://img.shields.io/badge/LM--Critic-blue) ![](https://img.shields.io/badge/Unsupervised-red) ![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Michihiro Yasunaga, Jure Leskovec, Percy Liang*. [[pdf](https://arxiv.org/abs/2109.06822)]

15. **Tail-to-Tail Non-Autoregressive Sequence Prediction for Chinese Grammatical Error Correction**. ACL 2021 ![](https://img.shields.io/badge/TtT-blue) ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

    *Piji Li, Shuming Shi*. [[pdf](https://arxiv.org/abs/2106.01609)] [[code](https://github.com/lipiji/TtT)]

16. **MaskGEC: Improving Neural Grammatical Error Correction via Dynamic Masking**. AAAI 2020 ![](https://img.shields.io/badge/MaskGEC-blue) ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Technical-yellow)

    *Zewei Zhao, Houfeng Wang*. [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/5476)]

17. **Encoder-Decoder Models Can Benefit from Pre-trained Masked Language Models in Grammatical Error Correction**. ACL 2020  ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Masahiro Kaneko, Masato Mita, Shun Kiyono, Jun Suzuki, Kentaro Inui*. [[pdf](https://arxiv.org/abs/2005.00987)] [[code](https://github.com/kanekomasahiro/bert-gec)]

18. **GECToR -- Grammatical Error Correction: Tag, Not Rewrite**. ACL 2020 ![](https://img.shields.io/badge/GECToR-blue) ![](https://img.shields.io/badge/Supervised-red) ![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Kostiantyn Omelianchuk, Vitaliy Atrasevych, Artem Chernodub, Oleksandr Skurzhanskyi*. [[pdf](https://arxiv.org/abs/2005.12592)] [[code](https://github.com/grammarly/gector)]

### Text Rewriting

1. **Context-Aware Document Simplification**. ACL 2023 Findings ![](https://img.shields.io/badge/ConBART-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Liam Cripwell, Joël Legrand, Claire Gardent*. [[pdf](https://arxiv.org/pdf/2305.06274.pdf)] [[code](https://github.com/liamcripwell/plan_simp)]

2. **ChatGPT as a Text Simplification Tool to Remove Bias**. Preprint 2023.5![](https://img.shields.io/badge/Prompt--based-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Charmaine Barker, Dimitar Kazakov*. [[pdf](https://arxiv.org/pdf/2305.06166.pdf)] [[code](https://github.com/CharmaineBarker/ChatGPT-as-a-Text-Simplification-Tool-to-Remove-Bias)]

3. **Sentence Simplification via Large Language Models**. Preprint 2023.2![](https://img.shields.io/badge/Prompt--based-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Yutao Feng, Jipeng Qiang, Yun Li, Yunhao Yuan, Yi Zhu*. [[pdf](https://arxiv.org/pdf/2302.11957.pdf)] [[code](https://github.com/BrettFyt/SS_Via_LLMs)]

4. **SimpLex: a lexical text simplification architecture**. Preprint 2023.4![](https://img.shields.io/badge/SimpLex-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Ciprian-Octavian Truică, Andrei-Ionut Stan, Elena-Simona Apostol*. [[pdf](https://arxiv.org/pdf/2304.07002.pdf)] [[code](https://github.com/elena-apostol/SimpLex)]

5. **Med-EASi: Finely Annotated Dataset and Models for Controllable Simplification of Medical Texts**. Preprint 2023.2![](https://img.shields.io/badge/ctrlSIM-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English Medical--domain-green)![](https://img.shields.io/badge/Dataset-yellow)

   *Chandrayee Basu, Rosni Vasu, Michihiro Yasunaga, Qian Yang*. [[pdf](https://arxiv.org/pdf/2302.09155.pdf)] [[code](https://github.com/Chandrayee/CTRL-SIMP)]

6. **Evaluating Factuality in Text Simplification**. ACL 2022![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Evaluation-green)![](https://img.shields.io/badge/Technical-yellow)

   *Ashwin Devaraj, William Sheffield, Byron C. Wallace, Junyi Jessy Li*. [[pdf](https://arxiv.org/pdf/2204.07562.pdf)] [[code](https://github.com/AshOlogn/Evaluating-Factuality-in-Text-Simplification)]

7. **GRS: Combining Generation and Revision in Unsupervised Sentence Simplification**. ACL 2022 Findings![](https://img.shields.io/badge/GRS-blue)![](https://img.shields.io/badge/Unsupervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Mohammad Dehghan, Dhruv Kumar, Lukasz Golab*. [[pdf](https://aclanthology.org/2022.findings-acl.77.pdf)] [[code](https://github.com/imohammad12/GRS)]

8. **An Unsupervised Method for Building Sentence Simplification Corpora in Multiple Languages**. EMNLP 2022 Findings![](https://img.shields.io/badge/Trans--SS-blue)![](https://img.shields.io/badge/Unsupervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Xinyu Lu, Jipeng Qiang, Yun Li, Yunhao Yuan, Yi Zhu*. [[pdf](https://aclanthology.org/2021.findings-emnlp.22.pdf)] [[code](https://github.com/luxinyu1/Trans-SS)]

9. **MUSS: Multilingual Unsupervised Sentence Simplification by Mining Paraphrases**. LREC 2022![](https://img.shields.io/badge/MUSS-blue)![](https://img.shields.io/badge/Unsupervised-red)![](https://img.shields.io/badge/Mutilingual-green)![](https://img.shields.io/badge/Technical-yellow)

   *Louis Martin, Angela Fan, Éric de la Clergerie, Antoine Bordes, Benoît Sagot*. [[pdf](https://aclanthology.org/2022.lrec-1.176.pdf)] [[code](https://github.com/facebookresearch/muss)]

10. **Unsupervised Simplification of Legal Texts**. Preprint 2022.9![](https://img.shields.io/badge/USLT-blue)![](https://img.shields.io/badge/Unsupervised-red)![](https://img.shields.io/badge/English Legal--domain-green)![](https://img.shields.io/badge/Technical-yellow)

   *Mert Cemri, Tolga Çukur, Aykut Koç*. [[pdf](https://arxiv.org/pdf/2209.00557.pdf)]

11. **Predicting Sentence Deletions for Text Simplification Using a Functional Discourse Structure**. ACL 2022![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Bohan Zhang, Prafulla Kumar Choubey, Ruihong Huang*. [[pdf](https://aclanthology.org/2022.acl-short.28.pdf)]

12. **(Psycho-)Linguistic Features Meet Transformer Models for Improved Explainable and Controllable Text Simplification**. EMNLP 2022![](https://img.shields.io/badge/ACCESS--XL-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Yu Qiao, Xiaofei Li, Daniel Wiechmann, Elma Kerz*. [[pdf](https://arxiv.org/pdf/2212.09848.pdf)]

13. **Predicting Sentence Deletions for Text Simplification Using a Functional Discourse Structure**. ACL 2022![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Bohan Zhang, Prafulla Kumar Choubey, Ruihong Huang*. [[pdf](https://aclanthology.org/2022.acl-short.28.pdf)]

14. **(Psycho-)Linguistic Features Meet Transformer Models for Improved Explainable and Controllable Text Simplification**. EMNLP 2022![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Yu Qiao, Xiaofei Li, Daniel Wiechmann, Elma Kerz*. [[pdf](https://arxiv.org/pdf/2212.09848.pdf)]

15. **Paragraph-level Simplification of Medical Texts**. NAACL 2021![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English Medical--domain-green)![](https://img.shields.io/badge/Technical-yellow)

    *Ashwin Devaraj, Iain J. Marshall, Byron C. Wallace, Junyi Jessy Li*. [[pdf](https://arxiv.org/pdf/2104.05767.pdf)] [[code](https://github.com/AshOlogn/Paragraph-level-Simplification-of-Medical-Texts)]

16. **Keep it Simple: Unsupervised Simplification of Multi-Paragraph Text**. ACL-IJCNLP 2021![](https://img.shields.io/badge/KiS-blue)![](https://img.shields.io/badge/Unsupervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Philippe Laban, Tobias Schnabel, Paul Bennett, Marti A. Hearst*. [[pdf](https://arxiv.org/pdf/2107.03444.pdf)] [[code](https://github.com/tingofurro/keep_it_simple)]

17. **Explainable Prediction of Text Complexity: The Missing Preliminaries for Text Simplification**. ACL 2021![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Cristina Garbacea, Mengtian Guo, Samuel Carton, Qiaozhu Mei*. [[pdf](https://arxiv.org/pdf/2007.15823.pdf)]

18. **A Non-Autoregressive Edit-Based Approach** **to Controllable Text Simplification**. ACL 2021 Findings![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Sweta Agrawal, Weijia Xu, Marine Carpuat*. [[pdf](https://aclanthology.org/2021.findings-acl.330.pdf)]

19. **Elaborative Simplification: Content Addition and Explanation Generation in Text Simplification**. ACL 2021 Findings![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Neha Srikanth, Junyi Jessy Li*. [[pdf](https://aclanthology.org/2021.findings-acl.455.pdf)] [[code](https://github.com/nehasrikn/elaborative-simplification)]

20. **Document-Level Text Simplification: Dataset, Criteria and Baseline**. EMNLP 2021![](https://img.shields.io/badge/Survey-yellow)

    *Renliang Sun, Hanqi Jin, Xiaojun Wan*. [[pdf](https://arxiv.org/pdf/2110.05071.pdf)] [[code](https://github.com/RLSNLP/Document-level-text-simplification)]

21. **Text Simplification by Tagging**. EACL 2021![](https://img.shields.io/badge/TST-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Kostiantyn Omelianchuk, Vipul Raheja, Oleksandr Skurzhanskyi*. [[pdf](https://arxiv.org/pdf/2103.05070.pdf)] [[code](https://github.com/grammarly/gector#text-simplification)]

22. **Chinese lexical simplification**. IEEE/ACM Transactions on Audio, Speech, and Language Processing 2021![](https://img.shields.io/badge/HanLS-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/Chinese-green)![](https://img.shields.io/badge/Dataset Technical-yellow)

    *Qiang J, Lu X, Li Y*. [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9439908)] [[code](https://github.com/luxinyu1/Chinese-LS/tree/master)]

23. **自动词语简化方法综述**. 中文信息学报 2021![](https://img.shields.io/badge/Survey-yellow)

    *强继朋;李云;吴信东*. [[link](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7iJTKGjg9uTdeTsOI_ra5_Xf_c9lUDyv5pX0Q6dgE6HaRw_-yTdM-BUGCgO0ZmLQ5G&uniplatform=NZKPT)]

24. **Neural CRF Model for Sentence Alignment in Text Simplification**. ACL 2020![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Chao Jiang, Mounica Maddela, Wuwei Lan, Yang Zhong, Wei Xu*. [[pdf](https://arxiv.org/pdf/2005.02324.pdf)] [[code](https://github.com/chaojiang06/wiki-auto)]

25. **Iterative Edit-Based Unsupervised Sentence Simplification**. ACL 2020![](https://img.shields.io/badge/Unsupervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Dhruv Kumar, Lili Mou, Lukasz Golab, Olga Vechtomova*. [[pdf](https://arxiv.org/pdf/2006.09639.pdf)] [[code](https://github.com/ddhruvkr/Edit-Unsup-TS)]

26. **Semi-Supervised Text Simplification with Back-Translation and Asymmetric Denoising Autoencoders**. AAAI2020![](https://img.shields.io/badge/Semi--Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Yanbin Zhao, Lu Chen, Zhi Chen, Kai Yu*. [[pdf](https://x-lance.sjtu.edu.cn/en/papers/2020/ybz79-zhao-aaai20.pdf)]

27. **Zero-Shot Crosslingual Sentence Simplification**. EMNLP2020![](https://img.shields.io/badge/Unsupervised-red)![](https://img.shields.io/badge/Crosslingual-green)![](https://img.shields.io/badge/Technical-yellow)

    *Jonathan Mallinson, Rico Sennrich, Mirella Lapata*. [[pdf](https://aclanthology.org/2020.emnlp-main.415.pdf)] [[code](https://github.com/Jmallins/ZEST)]

28. **ASSET: A Dataset for Tuning and Evaluation of Sentence Simplification Models with Multiple Rewriting Transformations**. ACL 2020![](https://img.shields.io/badge/ASSET-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Survey-yellow)

    *Fernando Alva-Manchego, Louis Martin, Antoine Bordes, Carolina Scarton, Benoît Sagot, Lucia Specia*. [[pdf](https://arxiv.org/pdf/2005.00481.pdf)] [[code](https://github.com/facebookresearch/asset)]

29. **Lexical Simplification with Pretrained Encoders**. AAAI 2020![](https://img.shields.io/badge/BERT--LS-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Jipeng Qiang, Yun Li, Yi Zhu, Yunhao Yuan, Xindong Wu*. 

30. **Controllable Sentence Simplification**. LREC 2020![](https://img.shields.io/badge/ACCESS-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Louis Martin, Éric de la Clergerie, Benoît Sagot, Antoine Bordes*. [[pdf](https://aclanthology.org/2020.lrec-1.577.pdf)] [[code](https://github.com/facebookresearch/access)]

31. **基于序列到序列模型的无监督文本简化方法**. 计算机应用研究 2020![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *李天宇;李云;钱镇宇*. [[link](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7iy_Rpms2pqwbFRRUtoUImHdegf0lN1c8uRclyQvnW618dwL-fkhfDnAX13FzyMcFU&uniplatform=NZKPT)]

### Controllable Text Generation

1. **BLIP-Diffusion: Pre-trained Subject Representation for Controllable Text-to-Image Generation and Editing**. arXiv 2023![](https://img.shields.io/badge/BLIP--Diffusion-blue)![](https://img.shields.io/badge/Self--supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Dongxu Li, Junnan Li, Steven C. H. Hoi*. [[pdf](https://dxli94.github.io/BLIP-Diffusion-website/)] [[code](https://github.com/salesforce/LAVIS/tree/main/projects/blip-diffusion)]

2. **COLD Decoding: Energy-based Constrained Text Generation with Langevin Dynamics**. arXiv 2022![](https://img.shields.io/badge/COLD Decoding-blue)![](https://img.shields.io/badge/Unsupervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Lianhui Qin, Sean Welleck, Daniel Khashabi, Yejin Choi*. [[pdf](https://arxiv.org/pdf/2202.11705v3.pdf)] [[code](https://github.com/qkaren/cold_decoding)]

3. **Diffusion-lm improves controllable text generation**. NeurIPS 2022![](https://img.shields.io/badge/Diffusion--LM-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Xiang Lisa Li, John Thickstun, Ishaan Gulrajani, Percy Liang, Tatsunori B. Hashimoto*. [[pdf](https://proceedings.neurips.cc/paper_files/paper/2022/file/1be5bc25d50895ee656b8c2d9eb89d6a-Paper-Conference.pdf)] [[code](https://github.com/XiangLi1999/Diffusion-LM.git)]

4. **A survey of controllable text generation using transformer-based pre-trained language models**. arXiv 2022![](https://img.shields.io/badge/Survey-yellow)

   *Hanqing Zhang, Haolin Song, Shaoyu Li, Ming Zhou, Dawei Song*. [[pdf](https://arxiv.org/abs/2201.05337)]

5. **Fine-Grained Controllable Text Generation Using Non-Residual Prompting**. ACL 2022![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Fredrik Carlsson, Joey Öhman, Fangyu Liu, Severine Verlinden, Joakim Nivre, Magnus Sahlgren*. [[pdf](https://aclanthology.org/2022.acl-long.471.pdf)] [[code](https://github.com/freddefrallan/non-residual-prompting)]

6. **MReD: A meta-review dataset for structure-controllable text generation**. ACL 2022 Findings![](https://img.shields.io/badge/MReD-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Chenhui Shen, Liying Cheng, Ran Zhou, Lidong Bing, Yang You, Luo Si*. [[pdf](https://arxiv.org/pdf/2110.07474v6.pdf)] [[code](https://github.com/shen-chenhui/mred)]

7. **Quark: Controllable Text Generation with Reinforced Unlearning**. NeurIPS 2022![](https://img.shields.io/badge/Quark-blue)![](https://img.shields.io/badge/Semi--Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Ximing Lu, Sean Welleck, Jack Hessel, Liwei Jiang, Lianhui Qin, Peter West, Prithviraj Ammanabrolu, Yejin Choi*. [[pdf](https://arxiv.org/pdf/2205.13636v2.pdf)] [[code](https://github.com/gximinglu/quark)]

8. **PCAE: A Framework of Plug-in Conditional Auto-Encoder for Controllable Text Generation**. Elsevier 2022![](https://img.shields.io/badge/PCAE-blue)![](https://img.shields.io/badge/Semi--Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Haoqin Tu, Zhongliang Yang, Jinshuai Yang, Siyu Zhang, Yongfeng Huang*. [[pdf](https://arxiv.org/pdf/2210.03496v1.pdf)] [[code](https://github.com/imkett/pcae)]

9. **Controllable Text Generation via Probability Density Estimation in the Latent Space**. arXiv 2022![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Yuxuan Gu, Xiaocheng Feng, Sicheng Ma, Lingyuan Zhang, Heng Gong, Weihong Zhong, Bing Qin*. [[pdf](https://arxiv.org/pdf/2212.08307v2.pdf)] [[code](https://github.com/happygu0524/multicontrol)]

10. **An Overview on Controllable Text Generation via Variational Auto-Encoders**. arXiv 2022![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Survey-yellow)

   *Haoqin Tu, Yitong Li*. [[pdf](https://arxiv.org/pdf/2211.07954v1.pdf)] [[code](https://github.com/imkett/ctg-latentaes)]

11. **Tailor: Generating and Perturbing Text with Semantic Controls**. ACL 2022![](https://img.shields.io/badge/Tailor-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Alexis Ross, Tongshuang Wu, Hao Peng, Matthew E. Peters, Matt Gardner*. [[pdf](https://arxiv.org/pdf/2107.07150v2.pdf)] [[code](https://github.com/allenai/tailor)]

12. **DisCup: Discriminator Cooperative Unlikelihood Prompt-tuning for Controllable Text Generation**. arXiv 2022![](https://img.shields.io/badge/DisCup-blue)![](https://img.shields.io/badge/Unsupervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Hanqing Zhang, Dawei Song*. [[pdf](https://arxiv.org/pdf/2210.09551v1.pdf)] [[code](https://github.com/littlehacker26/discriminator-cooperative-unlikelihood-prompt-tuning)]

13. **Classifiers are Better Experts for Controllable Text Generation**. arXiv 2022![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Askhat Sitdikov, Nikita Balagansky, Daniil Gavrilov, Alexander Markov*. [[pdf](https://arxiv.org/pdf/2205.07276v3.pdf)]

14. **A causal lens for controllable text generation**. NeurIPS 2021 ![](https://img.shields.io/badge/Unsupervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Zhiting Hu1, Li Erran Li*. [[pdf](https://proceedings.neurips.cc/paper/2021/file/d0f5edad9ac19abed9e235c0fe0aa59f-Paper.pdf)]

15. **DExperts: Decoding-time controlled text generation with experts and anti-experts**. arXiv 2021![](https://img.shields.io/badge/DExperts-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Alisa Liu, Maarten Sap, Ximing Lu, Swabha Swayamdipta, Chandra Bhagavatula, Noah A. Smith, Yejin Choi*. [[pdf](https://arxiv.org/pdf/2105.03023)] [[code](https://github.com/alisawuffles/Dexperts)]

16. **A Distributional Approach to Controlled Text Generation**. ICLR 2021![](https://img.shields.io/badge/gdc-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Muhammad Khalifa, Hady Elsahar, Marc Dymetman*. [[pdf](https://arxiv.org/pdf/2012.11635v2.pdf)] [[code](https://github.com/naver/gdc)]

17. **Controlled Text Generation as Continuous Optimization with Multiple Constraints**. NeurIPS 2021![](https://img.shields.io/badge/mucoco-blue)![](https://img.shields.io/badge/Semi--Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Sachin Kumar, Eric Malmi, Aliaksei Severyn, Yulia Tsvetkov*. [[pdf](https://arxiv.org/pdf/2108.01850v1.pdf)] [[code](https://github.com/sachin19/mucoco)]

18. **CoCon: A Self-Supervised Approach for Controlled Text Generation**. ICLR 2021![](https://img.shields.io/badge/CoCon-blue)![](https://img.shields.io/badge/Semi--Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Alvin Chan, Yew-Soon Ong, Bill Pung, Aston Zhang, Jie Fu*. [[pdf](https://arxiv.org/pdf/2006.03535v3.pdf)] [[code](https://github.com/alvinchangw/COCON_ICLR2021)]

19. **FUDGE: Controlled text generation with future discriminators**. arXiv 2021![](https://img.shields.io/badge/FUDGE-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Kevin Yang, Dan Klein*. [[pdf](https://arxiv.org/pdf/2104.05218)] [[code](https://arxiv.org/pdf/2104.05218)]

20. **Plug and play language models: A simple approach to controlled text generation**. ICLR 2020![](https://img.shields.io/badge/PPLM-blue)![](https://img.shields.io/badge/Semi--Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Sumanth Dathathri, Andrea Madotto, Janice Lan, Jane Hung, Eric Frank, Piero Molino, Jason Yosinski, Rosanne Liu*. [[pdf](https://arxiv.org/pdf/1912.02164)] [[code](https://github.com/uber-research/PPLM)]

21. **POINTER: Constrained Progressive Text Generation via Insertion-based Generative Pre-training**. EMNLP 2020![](https://img.shields.io/badge/POINTER-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Yizhe Zhang, Guoyin Wang, Chunyuan Li, Zhe Gan, Chris Brockett, Bill Dolan*. [[pdf](https://github.com/dreasysnail/POINTER)]

22. **Exploring Controllable Text Generation Techniques**. ACL 2020![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Shrimai Prabhumoye, Alan W. Black, Ruslan Salakhutdinov*. [[pdf](https://aclanthology.org/2020.coling-main.1)]

23. **Controlled Text Generation for Data Augmentation in Intelligent Artificial Agents**. WS 2019![](https://img.shields.io/badge/Semi--Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

    *Nikolaos Malandrakis, Minmin Shen, Anuj Goyal, Shuyang Gao, Abhishek Sethi, Angeliki Metallinou*. [[pdf](https://arxiv.org/pdf/1910.03487v1.pdf)]

### Educational Large Language Models

1. **Solving Math Word Problems by Combining Language Models With Symbolic Solvers**. arXiv 2023![](https://img.shields.io/badge/Semi--Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Joy He-Yueya, Gabriel Poesia, Rose E. Wang, Noah D. Goodman*. [[pdf](https://arxiv.org/pdf/2304.09102v1.pdf)] [[code](https://github.com/joyheyueya/declarative-math-word-problem)]

2. **Generating High-Precision Feedback for Programming Syntax Errors using Large Language Models**. arXiv 2023![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Tung Phung, José Cambronero, Sumit Gulwani, Tobias Kohn, Rupak Majumdar, Adish Singla, Gustavo Soares*. [[pdf](https://arxiv.org/pdf/2302.04662v2.pdf)] [[code](https://github.com/machine-teaching-group/edm2023_pyfixv)]

3. **M4: Multi-generator, Multi-domain, and Multi-lingual Black-Box Machine-Generated Text Detection**. arXiv 2023![](https://img.shields.io/badge/M4-blue)![](https://img.shields.io/badge/Supervised-red)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Yuxia Wang, Jonibek Mansurov, Petar Ivanov, Jinyan Su, Artem Shelmanov, Akim Tsvigun, Chenxi Whitehouse, Osama Mohammed Afzal, Tarek Mahmoud, Alham Fikri Aji, Preslav Nakov*. [[pdf](https://arxiv.org/pdf/2305.14902v1.pdf)] [[code](https://github.com/mbzuai-nlp/m4)]

4. **VNHSGE: VietNamese High School Graduation Examination Dataset for Large Language Models**. arXiv 2023![](https://img.shields.io/badge/VNHSGE-blue)![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Dataset-yellow)

   *Dao Xuan-Quy, Le Ngoc-Bich, Vo The-Duy, Phan Xuan-Dung, Ngo Bac-Bien, Nguyen Van-Tien, Nguyen Thi-My-Thanh, Nguyen Hong-Phuoc*. [[pdf](https://arxiv.org/pdf/2305.12199v1.pdf)] [[code](https://github.com/xdao85/vnhsge)]

5. **GPT Takes the Bar Exam**. arXiv 2022![](https://img.shields.io/badge/English-green)![](https://img.shields.io/badge/Technical-yellow)

   *Michael Bommarito II, Daniel Martin Katz*. [[pdf](https://arxiv.org/pdf/2212.14402v1.pdf)]


## Contributing



### Contributors
In addition to the following contributors who submitted pull requests, we would also like to thank Keren Tan, Jiani Wang, and Lei Pan for recommending papers. 



