# Awesome Early Exiting with stars

A curated list of early exiting.

## Paper

### NLP

#### **for LLM**

1. Mixture-of-Depths: Dynamically allocating compute in transformer-based language models. arxiv 2024.

   *David Raposo, Sam Ritter, Blake Richards, Timothy Lillicrap, Peter Conway Humphreys, Adam Santoro*. \[[pdf](https://arxiv.org/abs/2404.02258)] \[[code](https://github.com/kyegomez/Mixture-of-Depths) ⭐ 124 | 🐛 6 | 🌐 Python | 📅 2026-08-31]

2. EE-Tuning: An Economical yet Scalable Solution for Tuning Early-Exit Large Language Models. arxiv 2024.

   *Xuchen Pan, Yanxi Chen, Yaliang Li, Bolin Ding, Jingren Zhou*. \[[pdf](https://arxiv.org/abs/2402.00518)] \[[code](https://github.com/pan-x-c/ee-llm) ⭐ 83 | 🐛 7 | 🌐 Python | 📅 2024-06-14]

3. EE-LLM: Large-Scale Training and Inference of Early-Exit Large Language Models with 3D Parallelism. ICML 2024.

   *Yanxi Chen, Xuchen Pan, Yaliang Li, Bolin Ding, Jingren Zhou*. \[[pdf](https://arxiv.org/abs/2312.04916)] \[[code](https://github.com/pan-x-c/EE-LLM) ⭐ 83 | 🐛 7 | 🌐 Python | 📅 2024-06-14]

4. Kangaroo: Lossless Self-Speculative Decoding via Double Early Exiting. arxiv 2024.

   *Fangcheng Liu, Yehui Tang, Zhenhua Liu, Yunsheng Ni, Kai Han, Yunhe Wang.* \[[pdf](https://arxiv.org/abs/2404.18911)] \[[code](https://github.com/Equationliu/Kangaroo) ⭐ 73 | 🐛 0 | 🌐 Python | 📅 2024-06-26]

5. Fast and Robust Early-Exiting Framework for Autoregressive Language Models with Synchronized Parallel Decoding. EMNLP 2023.

   *Sangmin Bae, Jongwoo Ko, Hwanjun Song, Se-Young Yun.* \[[pdf](https://arxiv.org/abs/2310.05424)] \[[code](https://github.com/raymin0223/fast_robust_early_exit) ⭐ 67 | 🐛 0 | 🌐 Python | 📅 2024-09-28]

6. Accelerating Inference in Large Language Models with a Unified Layer Skipping Strategy. arxiv 2024.

   *Yijin Liu, Fandong Meng, Jie Zhou*. \[[pdf](https://arxiv.org/abs/2404.06954)] \[[code](https://github.com/Adaxry/Unified_Layer_Skipping) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2024-04-11]

7. Lossless Acceleration of Large Language Model via Adaptive N-gram Parallel Decoding. NAACL 2024.

   *Jie Ou, Yueming Chen, Wenhong Tian*. \[[pdf](https://arxiv.org/abs/2404.08698)] \[[code](https://github.com/oujieww/anpd) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-02-05]

8. Confident Adaptive Language Modeling. Neurips 2022.

   *Tal Schuster, Adam Fisch, Jai Gupta, Mostafa Dehghani, Dara Bahri, Vinh Q. Tran, Yi Tay, Donald Metzler.* \[[pdf](https://arxiv.org/abs/2207.07061)]

9. SkipDecode: Autoregressive Skip Decoding with Batching and Caching for Efficient LLM Inference. arxiv 2023.

   *Luciano Del Corro, Allie Del Giorno, Sahaj Agarwal, Bin Yu, Ahmed Awadallah, Subhabrata Mukherjee.* \[[pdf](https://arxiv.org/abs/2307.02628)]

10. Layer Skip: Enabling Early Exit Inference and Self-Speculative Decoding. ACL 2024.

    *Mostafa Elhoushi, Akshat Shrivastava, Diana Liskovich, Basil Hosmer, Bram Wasti, Liangzhen Lai, Anas Mahmoud, Bilge Acun, Saurabh Agarwal, Ahmed Roman, Ahmed A Aly, Beidi Chen, Carole-Jean Wu.* \[[pdf](https://arxiv.org/abs/2404.16710)]

11. FFN-SkipLLM: A Hidden Gem for Autoregressive Decoding with Adaptive Feed Forward Skipping. arxiv 2024.

    *Ajay Jaiswal, Bodun Hu, Lu Yin, Yeonju Ro, Shiwei Liu, Tianlong Chen, Aditya Akella*. \[[pdf](https://arxiv.org/abs/2404.03865)]

12. Hierarchical Skip Decoding for Efficient Autoregressive Text Generation. arxiv 2024.

    *Yunqi Zhu, Xuebing Yang, Yuanyuan Wu, Wensheng Zhang*. \[[pdf](https://arxiv.org/abs/2403.14919)]

13. Not All Layers of LLMs Are Necessary During Inference. arxiv 2024.

    *Siqi Fan, Xin Jiang, Xiang Li, Xuying Meng, Peng Han, Shuo Shang, Aixin Sun, Yequan Wang, Zhongyuan Wang*. \[[pdf](https://arxiv.org/abs/2403.02181))]

14. Investigating Acceleration of LLaMA Inference by Enabling Intermediate Layer Decoding via Instruction Tuning with 'LITE'. NAACL 2024

    *Neeraj Varshney, Agneet Chatterjee, Mihir Parmar, Chitta Baral*. \[[pdf](https://aclanthology.org/2024.findings-naacl.232/)]

#### **Dynamic Methods**

1. FastBERT: a Self-distilling BERT with Adaptive Inference Time. ACL 2020.

   *Weijie Liu, Peng Zhou, Zhiruo Wang, Zhe Zhao, Haotang Deng, and Qi Ju.* \[[pdf](https://aclanthology.org/2020.acl-main.537.pdf)] \[[code](https://github.com/autoliuweijie/FastBERT) ⭐ 606 | 🐛 31 | 🌐 Python | 📅 2021-10-29]

2. DeeBERT: Dynamic Early Exiting for Accelerating BERT Inference. ACL 2020.

   *Ji Xin, Raphael Tang, Jaejun Lee, Yaoliang Yu, and Jimmy Lin.* \[[pdf](https://aclanthology.org/2020.acl-main.204.pdf)] \[[code](https://github.com/castorini/DeeBERT) ⭐ 161 | 🐛 3 | 🌐 Python | 📅 2022-03-25]

3. BERT Loses Patience: Fast and Robust Inference with Early Exit. NeurIPS 2020.

   *Wangchunshu Zhou, Canwen X u, Tao Ge, Julian McAuley, Ke Xu, Furu Wei.* \[[pdf](https://proceedings.neurips.cc//paper/2020/file/d4dd111a4fd973394238aca5c05bebe3-Paper.pdf)] \[[code](https://github.com/JetRunner/PABEE) ⭐ 66 | 🐛 3 | 🌐 Python | 📅 2021-06-19]

4. BERxiT: Early Exiting for BERT with Better Fine-Tuning and Extension to Regression. EACL 2021.

   *Ji Xin, Raphael Tang, Yaoliang Yu, Jimmy Lin.* \[[pdf](https://aclanthology.org/2021.eacl-main.8.pdf)] \[[code](https://github.com/castorini/berxit) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2021-01-18]

5. RomeBERT: Robust Training of Multi-Exit BERT. Preprint Jan 2021.

   *Shijie Geng, Peng Gao, Zuohui Fu, Yongfeng Zhang.* \[[pdf](https://arxiv.org/pdf/2101.09755.pdf)] \[[code](https://github.com/romebert/RomeBERT) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2021-05-06]

6. SkipBERT: Efficient Inference with Shallow Layer Skipping. ACL 2022

   Jue Wang, Ke Chen, Gang Chen, Lidan Shou, Julian McAuley \[[pdf](https://aclanthology.org/2022.acl-long.503.pdf)] \[[project](https://github.com/LorrinWWW/SkipBERT) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2022-06-22]

7. Consistent Accelerated Inference via Confident Adaptive Transformers. EMNLP 2021.

   *Tal Schuster, Adam Fisch, Tommi Jaakkola, Regina Barzilay.* \[[pdf](https://arxiv.org/pdf/2104.08803.pdf)] \[[code](https://github.com/TalSchuster/CATs) ⭐ 15 | 🐛 3 | 🌐 Python | 📅 2021-04-18]

8. CascadeBERT: Accelerating Inference of Pre-trained Language Models via Calibrated Complete Models Cascade. EMNLP 2021.

   *Lei Li, Yankai Lin, Deli Chen, Shuhuai Ren, Peng Li, Jie Zhou, Xu Sun.* \[[pdf](https://arxiv.org/pdf/2012.14682.pdf)] \[[code](https://github.com/lancopku/CascadeBERT) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2022-03-30]

9. A Global Past-Future Early Exit Method for Accelerating Inference of Pre-trained Language Models. NAACL 2021.

   *Kaiyuan Liao, Yi Zhang, Xuancheng Ren, Qi Su, Xu Sun, Bin He.* \[[pdf](https://aclanthology.org/2021.naacl-main.162.pdf)] \[[code](https://github.com/lancopku/Early-Exit) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2021-04-19]

10. PCEE-BERT: Accelerating BERT Inference via Patient and Confident Early Exiting, NAACL Findings 2022.

    *Zhen Zhang, Wei Zhu, Jinfan Zhang, Peng Wang, Rize Jin, Tae-Sun Chung.*  \[[pdf](https://aclanthology.org/2022.findings-naacl.25/)] \[[code](https://github.com/michael-wzhu/PCEE-BERT) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2022-05-01]

11. Finding the SWEET Spot: Analysis and Improvement of Adaptive Inference in Low Resource Settings. ACL 2023.

    *Daniel Rotem, Michael Hassid, Jonathan Mamou, Roy Schwartz.* \[[pdf](https://arxiv.org/pdf/2306.02307.pdf)] \[[code](https://github.com/schwartz-lab-NLP/SWEET) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2025-01-14]

12. EBERT: Efficient BERT Inference with Dynamic Structured Pruning. ACL Findings2021.

    *Zejian Liu, Fanrong Li, Gang Li, Jian Cheng.* \[[pdf](https://aclanthology.org/2021.findings-acl.425.pdf)] \[[code](https://github.com/zejiangp/EBERT) ⭐ 6 | 🐛 2 | 🌐 Python | 📅 2021-12-22]

13. Unsupervised Early Exit in DNNs with Multiple Exits. AI-ML systems 2022

    *Hari Narayan N U, Manjesh K. Hanawal, Avinash Bhardwaj*. \[[pdf](https://arxiv.org/pdf/2209.09480.pdf)] \[[code](https://github.com/MLiONS/MutiExitDNNs) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2022-08-15]

14. The Right Tool for the Job: Matching Model and Instance Complexities. ACL 2020.

    *Roy Schwartz, Gabriel Stanovsky, Swabha Swayamdipta, Jesse Dodge, and Noah A. Smith.* \[[pdf](https://aclanthology.org/2020.acl-main.593.pdf)]

15. Early Exiting BERT for Efficient Document Ranking. ACL 2020.

    *Ji Xin, Rodrigo Nogueira, Yaoliang Yu, Jimmy Lin.* \[[pdf](https://aclanthology.org/2020.sustainlp-1.11.pdf)]

16. DynaBERT: Dynamic BERT with Adaptive Width and Depth. NeurlPS 2020.

    *Lu Hou, Zhiqi Huang, Lifeng Shang, Xin Jiang, Xiao Chen, Qun Liu.* \[[pdf](https://arxiv.org/pdf/2004.04037.pdf)]

17. Accelerating BERT Inference for Sequence Labeling via Early-Exit. ACL 2021.

    *Xiaonan Li, Yunfan Shao, Tianxiang Sun, Hang Yan, Xipeng Qiu, Xuanjing Huang.* \[[pdf](https://aclanthology.org/2021.acl-long.16.pdf)]

18. LeeBERT: Learned Early Exit for BERT with Cross-Level Optimization. ACL 2021.

    *Wei Zhu.* \[[pdf](https://aclanthology.org/2021.acl-long.231.pdf)]

19. TR-BERT: Dynamic Token Reduction for Accelerating BERT Inference. ACL 2021.

    *Deming Ye, Yankai Lin, Yufei Huang, Maosong Sun.* \[[pdf](https://aclanthology.org/2021.naacl-main.463.pdf)]

20. Early Exiting with Ensemble Internal Classifiers. Preprint May 2021.

    *Tianxiang Sun, Yunhua Zhou, Xiangyang Liu, Xinyu Zhang, Hao Jiang, Zhao Cao, Xuanjing Huang, Xipeng Qiu.* \[[pdf](https://arxiv.org/pdf/2105.13792.pdf)]

21. ELBERT: Fast Albert with Confidence-Window Based Early Exit. ICASSP 2021.

    *Keli Xie, Siyuan Lu, Meiqi Wang, Zhongfeng Wang.* \[[pdf](https://arxiv.org/pdf/2107.00175.pdf)]

22. DACT-BERT: Differentiable Adaptive Computation Time for an Efficient BERT Inference. ACL NLP Power workshop 2022

    *Cristóbal Eyzaguirre, Felipe del Río, Vladimir Araujo, Álvaro Soto.* \[[pdf](https://aclanthology.org/2022.nlppower-1.10/)]

23. Towards Efficient NLP: A Standard Evaluation and A Strong Baseline. NAACL 2022.

    *Xiangyang Liu*, Tianxiang Sun\*, Junliang He, Lingling Wu, Xinyu Zhang, Hao Jiang, Zhao Cao, Xuanjing Huang, Xipeng Qiu.\* \[[pdf](https://arxiv.org/pdf/2110.07038.pdf)]

24. E2CM: Early Exit via Class Means for Efficient Supervised and Unsupervised Learning. IJCNN 2022 (WCCI 2022)

    *Alperen Görmez, Venkat R. Dasari, Erdem Koyuncu.* \[[pdf](https://arxiv.org/abs/2103.01148v3)] \[code]

25. SmartBERT: A Promotion of Dynamic Early Exiting Mechanism for Accelerating. IJCAI 2023.

    *Boren Hu, Yun Zhu, Jiacheng Li, Siliang Tang.* \[[pdf](https://arxiv.org/pdf/2303.09266.pdf)]

26. BADGE: Speeding Up BERT Inference after Deployment via Block-wise BypAsses and DiverGence-Based Early Exiting. ACL 2023.

    *Wei Zhu, Peng Wang, Yuan Ni, Guotong Xie, Xiaoling Wang*. \[[pdf](https://aclanthology.org/2023.acl-industry.48/)]

#### **Static Methods**

1. Reducing Transformer Depth on Demand with Structured Dropout, ICLR 2020.

   Angela Fan, Edouard Grave, Armand Joulin. \[[pdf](https://openreview.net/forum?id=SylO2yStDr)] \[[code](https://github.com/facebookresearch/fairseq/blob/main/examples/layerdrop/README.md) ⚠️ Archived]

2. A Simple Hash-Based Early Exiting Approach For Language Understanding and Generation. Findings of ACL 2022.

   *Tianxiang Sun, Xiangyang Liu, Wei Zhu, Zhichao Geng, Lingling Wu, Yilong He, Yuan Ni, Guotong Xie, Xuanjing Huang, Xipeng Qiu* \[[pdf](https://arxiv.org/pdf/2203.01670.pdf)] \[[code](https://github.com/txsun1997/HashEE) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2022-09-30]

3. Depth-Adaptive Transformer. ICLR 2020.

   *Maha Elbayad, Jiatao Gu, Edouard Grave, Michael Auli.* \[[pdf](https://openreview.net/pdf?id=SJg7KhVKPH)]

4. Faster Depth-Adaptive Transformers. AAAI 2021.

   *Yijin Liu, Fandong Meng, Jie Zhou, Yufeng Chen, Jinan Xu.* \[[pdf](https://arxiv.org/pdf/2004.13542.pdf)]

### CV

1. Self-Distillation Towards Efficient and Compact Neural Networks. TPAMI 2021

   *Linfeng Zhang , Chenglong Bao, Kaisheng Ma* \[[pdf](https://ieeexplore.ieee.org/document/9381661/)] \[[code](https://github.com/ArchipLab-LinfengZhang/pytorch-self-distillation-final) ⭐ 130 | 🐛 5 | 🌐 Python | 📅 2020-11-02]

2. Improved Techniques for Training Adaptive Deep Networks. ICCV 2019

   Hao Li, Hong Zhang, Xiaojuan Qi, Ruigang Yang, Gao Huang. \[[pdf](https://arxiv.org/abs/1908.06294)] \[[code](https://github.com/kalviny/IMTA) ⭐ 47 | 🐛 2 | 🌐 Python | 📅 2019-12-26]

3. Dynamic Perceiver for Efficient Visual Recognition. ICCV 2023.

   *Yizeng Han, Dongchen Han, Zeyu Liu, Yulin Wang, Xuran Pan, Yifan Pu, Chao Deng, Junlan Feng, Shiji Song, Gao Huang* \[[pdf](https://arxiv.org/pdf/2306.11248.pdf)] \[[code](https://github.com/leaplabthu/dynamic_perceiver) ⭐ 44 | 🐛 2 | 🌐 Python | 📅 2023-11-16]

4. Shallow-Deep Networks: Understanding and Mitigating Network Overthinking. ICML 2019

   *Yigitcan Kaya, Sanghyun Hong, and Tudor Dumitras.* \[[pdf](http://proceedings.mlr.press/v97/kaya19a/kaya19a.pdf)] \[[code](https://github.com/yigitcankaya/Shallow-Deep-Networks) ⭐ 38 | 🐛 0 | 🌐 Python | 📅 2023-12-22]

5. Learning to Weight Samples for Dynamic Early-Exiting Networks. ECCV 2022

   *Yizeng Han, Yifan Pu, Zihang Lai, Chaofei Wang, Shiji Song, Junfen Cao, Wenhui Huang, Chao Deng, Gao Huang* \[[pdf](https://arxiv.org/pdf/2209.08310.pdf)] \[[code](https://github.com/LeapLabTHU/L2W-DEN) ⭐ 38 | 🐛 0 | 🌐 Python | 📅 2023-09-28]

6. Learning to stop while learning to predict. ICML 2021

   *Xinshi Chen, Hanjun Dai, Yu Li, Xin Gao, Le Song, Le Song*  \[[pdf](https://arxiv.org/abs/2006.05082)] \[[code](https://github.com/xinshi-chen/l2stop) ⭐ 36 | 🐛 2 | 🌐 Python | 📅 2022-11-02]

7. DeeCap: Dynamic Early Exiting for Efficient Image Captioning. CVPR 2022

   Zhengcong Fei, Xu Yan, Shuhui Wang , Qi Tian \[[pdf](https://ieeexplore.ieee.org/document/9879601/)] \[[code](https://github.com/feizc/DeeCap) ⭐ 17 | 🐛 4 | 🌐 Python | 📅 2022-10-25]

8. Zero Time Waste: Recycling Predictions in Early Exit Neural Networks. NeurIPS 2021

   Maciej Wołczyk, Bartosz Wójcik, Klaudia Bałazy, Igor Podolak, Jacek Tabor, Marek Śmieja, Tomasz Trzciński \[[pdf](https://arxiv.org/abs/2106.05409)] \[[code](https://github.com/gmum/Zero-Time-Waste) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2023-12-19]

9. Meta-GF: Training Dynamic-Depth Neural Networks Harmoniously. ECCV 2022

   *Yi Sun, Jian Li, Xin Xu*. \[[pdf](https://link.springer.com/chapter/10.1007/978-3-031-20083-0_41)] \[[code](https://github.com/SYVAE/MetaGF) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2023-12-15]

10. Boosted Dynamic Neural Networks. AAAI 2023.

    *Haichao Yu, Haoxiang Li, Gang Hua, Gao Huang, Humphrey Shi* \[[pdf](https://arxiv.org/abs/2211.16726)] \[[code](https://github.com/SHI-Labs/Boosted-Dynamic-Networks) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2022-12-01]

11. Window-Based Early-Exit Cascades for Uncertainty Estimation: When Deep Ensembles are More Efficient than Single Models. ICCV 2023.

    *Guoxuan Xia, Christos-Savvas Bouganis* \[[pdf](https://arxiv.org/abs/2303.08010)] \[[code](https://github.com/Guoxoug/window-early-exit) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2023-08-18]

12. Conditional deep learning for energy-efficient and enhanced pattern recognition. DATE 2016

    *Priyadarshini Panda, Abhronil Sengupta, and Kaushik Roy.* \[[pdf](https://arxiv.org/pdf/1509.08971)]

13. BranchyNet: Fast Inference via Early Exiting from Deep Neural Networks. ICPR 2016

    *Surat Teerapittayanon, Bradley McDanel, and HT Kung.* \[[pdf](https://arxiv.org/pdf/1709.01686)]

14. HAPI: Hardware-Aware Progressive Inference. ICCAD 2020

    *S. Laskaridis et al.* \[[pdf](https://arxiv.org/pdf/2008.03997)]

15. Edge AI: On-Demand Accelerating Deep Neural Network Inference via Edge Computing. IEEE TWC 2020

    *E. Li et al.* \[[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=\&arnumber=8876870) ]

16. SPINN: Synergistic Progressive Inference of Neural Networks over Device and Cloud. MobiCom 2020

    *Stefanos Laskaridis et al.* \[[pdf](https://dl.acm.org/doi/pdf/10.1145/3372224.3419194) ]

17. FlexDNN: Input-Adaptive On-Device Deep Learning for Efficient Mobile Vision. SEC 2020

    *Biyi Fang et al.* \[[pdf](https://www.egr.msu.edu/~mizhang/papers/2020_SEC_FlexDNN.pdf) ]

18. Dual Dynamic Inference: Enabling more efficient, adaptive, and controllable deep inference. IEEE Journal of Selected Topics in Signal Processing, 2020

    *Yue Wang et al.* \[[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=\&arnumber=9028245)]

19. Multi-Exit Semantic Segmentation Networks. ECCV 2022

    *Alexandros Kouris, Stylianos I. Venieris, Stefanos Laskaridis, and Nicholas D. Lane.* \[[pdf](https://arxiv.org/pdf/2106.03527)]

20. Single-layer vision transformers for more accurate early exits with less overhead. 2022 Neural Network. \[[pdf](https://www.sciencedirect.com/science/article/pii/S0893608022002532)]

21. ReX: An Efficient Approach to Reducing Memory Cost in Image Classification. AAAI 2022.

    *Xuwei Qian, Renlong Hang, Qingshan Liu* \[[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/20106/19865)]

22. You Need Multiple Exiting: Dynamic Early Exiting for Accelerating Unified Vision Language Model. CVPR 2023.

    *Shengkun Tang, Yaqing Wang, Zhenglun Kong, Tianchi Zhang, Yao Li, Caiwen Ding, Yanzhi Wang, Yi Liang, Dongkuan Xu* \[[pdf](https://openaccess.thecvf.com/content/CVPR2023/papers/Tang_You_Need_Multiple_Exiting_Dynamic_Early_Exiting_for_Accelerating_Unified_CVPR_2023_paper.pdf)]

23. HarvNet: Resource-Optimized Operation of Multi-Exit Deep Neural Networks on Energy Harvesting Devices.  MobiSys 2023.

    *Seunghyeok Jeon, Yonghun Choi , Yeonwoo Cho , and Hojung Cha* \[[pdf](https://dl.acm.org/doi/pdf/10.1145/3581791.3596845)]

24. LGViT: Dynamic Early Exiting for Accelerating Vision Transformer. ACM MM 2023.

    *Guanyu Xu, Jiawei Hao, Li Shen, Han Hu, Yong Luo, Hui Lin, Jialie Shen* \[[pdf](https://arxiv.org/abs/2308.00255)] \[code]

### Survey

1. Adaptive Inference through Early-Exit Networks: Design, Challenges and Directions. EMDL 2021.

   *Stefanos Laskaridis, Alexandros Kouris, Nicholas D. Lane*. \[[pdf](https://arxiv.org/pdf/2106.05022.pdf)]

2. An Empirical Study on Adaptive Inference for Pretrained Language Model. TNNLS 2021.

   *Weijie Liu , Xin Zhao, Zhe Zhao, Qi Ju, Xuefeng Yang, and Wei Lu*.\[[pdf](https://ieeexplore.ieee.org/document/9585316)]

3. Split Computing and Early Exiting for Deep Learning Applications: Survey and Research Challenges. ACM Computing Surveys 2022.

   *Y Matsubara, M Levorato, F Restuccia*. \[[pdf](https://dl.acm.org/doi/pdf/10.1145/3527155)]

4. Dynamic Neural Networks. A Survey.

   *Yizeng Han, Gao Huang, Shiji Song, Le Yang, Honghui Wang, Yulin Wang.* \[[pdf](https://arxiv.org/pdf/2102.04906.pdf)]

5. A Survey on Dynamic Neural Networks for Natural Language Processing. Journal of Mechanics of Continua and Mathematical Sciences 2022.

   *Canwen Xu, Julian McAuley.* \[[pdf](https://arxiv.org/pdf/2202.07101.pdf)]

## Acknowledgments

This repository is built upon [awesome-early-exiting](https://github.com/txsun1997/awesome-early-exiting) ⭐ 119 | 🐛 3 | 📅 2023-10-26. Thanks for the awesome project!

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-05._
