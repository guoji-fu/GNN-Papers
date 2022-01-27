# GNN-Papers
Awsome Papers for Graph Neural Networks (GNNs).

## Contents
- [Survey](#survey)
- [Theory](#theory)
- [Model](#model)
  - [Graph Convolutional Networks](#gcn)
  - [Graph Attention Networks](#gan)
  - [Graph Auto-encoder](#gae)
  - [Graph Generative Networks](#ggn)
  - [Graph Reinforcement Learning](#grl)
  - [Graph Spatial-Temporal Networks](#gstn)

- [Library](#library)

<a name="survey" />

## Survey

1. **Geometric deep learning: going beyond euclidean data.** 
    - arXiv 2016. 
    - *Michael M. Bronstein, Joan Bruna, Yann LeCun, Arthur Szlam, Pierre Vandergheynst.*  
    - [paper](https://arxiv.org/pdf/1611.08097.pdf)

1. **Neural Message Passing for Quantum Chemistry.**
    - arXiv 2017. 
    - *Gilmer, Justin and Schoenholz, Samuel S and Riley, Patrick F and Vinyals, Oriol and Dahl, George E.* 
    - [paper](https://arxiv.org/pdf/1704.01212.pdf)

1. **Relational Inductive Biases, Deep Learning, and Graph Networks.** 
    - arXiv 2018. 
    - *Battaglia, Peter W and Hamrick, Jessica B and Bapst, Victor and Sanchez-Gonzalez, Alvaro and Zambaldi, Vinicius and Malinowski, Mateusz and Tacchetti, Andrea and Raposo, David and Santoro, Adam and Faulkner, Ryan and others.* 
    - [paper](https://arxiv.org/pdf/1806.01261.pdf)

1. **Graph Neural Networks: A Review of Methods and Applications.** 
    - arXiv 2018.
    - *Jie Zhou, Ganqu Cui, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Maosong Sun.* 
    - [paper](https://arxiv.org/pdf/1812.08434.pdf)

1. **Deep learning on graphs: A survey.** 
    - arXiv 2018.
    - Ziwei Zhang, Peng Cui and Wenwu Zhu. 
    - [paper](https://arxiv.org/pdf/1812.04202.pdf)

1. **Attention models in graphs.** 
    - arXiv 2018.
    - *John Boaz Lee, Ryan A. Rossi, Sungchul Kim, Nesreen K. Ahmed, Eunyee Koh.* 
    - [paper](https://arxiv.org/pdf/1807.07984.pdf)

1. **A Comprehensive Survey on Graph Neural Networks.**
    - arXiv 2019.
    - *Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, Philip S. Yu.* 
    - [paper](https://arxiv.org/pdf/1901.00596.pdf)


<a name="theory" />

## Theory

1. **Mean-Field Theory of Graph Neural Networks in Graph Partitioning.**
    - NeurIPS 2018.
    - *Tatsuro Kawamoto, Masashi Tsubaki, Tomoyuki Obuchi.*
    - [paper](https://proceedings.neurips.cc/paper/2018/file/f6e794a75c5d51de081dbefa224304f9-Paper.pdf)

1. **Stability and Generalization of Graph Convolutional Neural Networks.**
    - KDD 2019.
    - *Saurabh Verma, Zhi-Li Zhang.*
    - [paper](https://arxiv.org/pdf/1905.01004.pdf)

1. **Understanding the Representation Power of Graph Neural Networks in Learning Graph Topology.**
    - NIPS 2019.
    - *Nima Dehmamy, Albert-László Barabási, Rose Yu.*
    - [paper](https://arxiv.org/pdf/1907.05008.pdf)

1. **Fundamental Limits of Deep Graph Convolutional Networks.**
    - arXiv 2019.
    - *Abram Magner, Mayank Baranwal, Alfred O. Hero III.*
    - [paper](https://arxiv.org/pdf/1910.12954.pdf)

1. **What Can Neural Networks Reason About?**
    - ICLR 2020.
    - *Keyulu Xu, Jingling Li, Mozhi Zhang, Simon S. Du, Ken-ichi Kawarabayashi, Stefanie Jegelka.*
    - [paper](https://arxiv.org/pdf/1905.13211.pdf)

1. **Graph Neural Networks Exponentially Lose Expressive Power for Node Classification.**
    - ICLR 2020.
    - *Kenta Oono, Taiji Suzuki.*
    - [paper](https://arxiv.org/pdf/1905.10947.pdf)
    - [code](https://github.com/delta2323/gnn-asymptotics)

1. **What Graph Neural Networks Cannot Learn: Depth vs Width.**
    - ICLR 2020.
    - *Andreas Loukas.*
    - [paper](https://arxiv.org/pdf/1907.03199.pdf)

1. **How Hard is to Distinguish Graphs with Graph Neural Networks?**
    - Neurips 2020.
    - *Andreas Loukas.*
    - [paper](https://arxiv.org/pdf/2005.06649.pdf)

1. **On the Equivalence of Molecular Graph Convolution and Molecular Wave Function with Poor Basis Set.**
    - Neurips 2020.
    - *Masashi Tsubaki, Teruyasu Mizoguchi.*
    - [paper](https://arxiv.org/pdf/2011.07929.pdf)

1. **Convergence and Stability of Graph Convolutional Networks on Large Random Graphs.**
    - NeurIPS 2020.
    - *Nicolas Keriven, Alberto Bietti, Samuel Vaiter.*
    - [paper](https://arxiv.org/pdf/2006.01868.pdf)

1. **Fast Learning of Graph Neural Networks with Guaranteed Generalizability: One-hidden-layer Case.**
    - ICML 2020.
    - *Shuai Zhang, Meng Wang, Sijia Liu, Pin-Yu Chen, Jinjun Xiong.*
    - [paper](https://arxiv.org/pdf/2006.14117.pdf)
    
1. **Generalization and Representational Limits of Graph Neural Networks.**
    - arXiv 2020.
    - *Vikas K. Garg, Stefanie Jegelka, Tommi Jaakkola.*
    - [paper](https://arxiv.org/pdf/2002.06157.pdf)

1. **How Neural Networks Extrapolate: From Feedforward to Graph Neural Networks.**
    - ICLR 2021.
    - *Keyulu Xu, Mozhi Zhang, Jingling Li, Simon S. Du, Ken-ichi Kawarabayashi, Stefanie Jegelka.*
    - [paper](https://arxiv.org/pdf/2009.11848.pdf)

1. **A PAC-Bayesian Approach to Generalization Bounds for Graph Neural Networks.**
    - ICLR 2021.
    - *Renjie Liao, Raquel Urtasun, Richard Zemel.*
    - [paper](https://arxiv.org/pdf/2012.07690.pdf)

1. **On the Bottleneck of Graph Neural Networks and its Practical Implications.**
    - ICLR 2021.
    - *Uri Alon, Eran Yahav.*
    - [paper](https://arxiv.org/pdf/2006.05205.pdf)

1. **Subgroup Generalization and Fairness of Graph Neural Networks.**
    - NeurIPS 2021.
    - *Jiaqi Ma, Junwei Deng, Qiaozhu Mei.*
    - [paper](https://arxiv.org/pdf/2106.15535.pdf)

1. **Learning Theory Can (Sometimes) Explain Generalisation in Graph Neural Networks.**
    - NeurIPS 2021.
    - *Pascal Mattia Esser, Leena C. Vankadara, Debarghya Ghoshdastidar.*
    - [paper](https://arxiv.org/pdf/2112.03968.pdf)

1. **On Provable Benefits of Depth in Training Graph Convolutional Networks.**
    - NeurIPS 2021.
    - *Weilin Cong, Morteza Ramezani, Mehrdad Mahdavi.*
    - [paper](https://papers.nips.cc/paper/2021/file/524265e8b942930fbbe8a5d979d29205-Paper.pdf)

1. **Reconstruction for Powerful Graph Representations.**
    - NeurIPS 2021.
    - *Leonardo Cotta, Christopher Morris, Bruno Ribeiro.*
    - [paper](https://arxiv.org/pdf/2110.00577.pdf)

1. **On the Universality of Graph Neural Networks on Large Random Graphs.**
    - NeurIPS 2021.
    - *Nicolas Keriven, Alberto Bietti, Samuel Vaiter.*
    - [paper](https://arxiv.org/pdf/2105.13099.pdf)

1. **GemNet: Universal Directional Graph Neural Networks for Molecules.**
    - NeurIPS 2021.
    - *Johannes Klicpera, Florian Becker, Stephan Günnemann.*
    - [paper](https://arxiv.org/pdf/2106.08903.pdf)

1. **From Local Structures to Size Generalization in Graph Neural Networks.**
    - ICML 2021.
    - *Gilad Yehudai, Ethan Fetaya, Eli Meirom, Gal Chechik, Haggai Maron.*
    - [paper](https://arxiv.org/pdf/2010.08853.pdf)

1. **A Unified Lottery Ticket Hypothesis for Graph Neural Networks.**
    - ICML 2021.
    - *Tianlong Chen, Yongduo Sui, Xuxi Chen, Aston Zhang, Zhangyang Wang.*
    - [paper](https://arxiv.org/pdf/2102.06790.pdf)

1. **Generalization Bounds for Graph Convolutional Neural Networks via Rademacher Complexity.**
    - arXiv 2021.
    - *Shaogao Lv.*
    - [paper](https://arxiv.org/pdf/2102.10234.pdf)

1. **Towards a Rigorous Theoretical Analysis and Evaluation of GNN Explanations.**
    - arXiv 2021.
    - *Chirag Agarwal, Marinka Zitnik, Himabindu Lakkaraju.*
    - [paper](https://arxiv.org/pdf/2106.09078.pdf)


<a name="model" />

## Model

<a name="gcn" />

### Graph Convolutional Networks

#### 2019

1. **LanczosNet: Multi-Scale Deep Graph Convolutional Networks** 
*Renjie Liao, Zhizhen Zhao, Raquel Urtasun, Richard S. Zemel1* ICLR 2019. [paper](https://openreview.net/pdf?id=BkedznAqKQ) [code](https://github.com/lrjconan/LanczosNetwork)

1. **Deep Graph Infomax.**
*Petar Veličković, William Fedus, William L. Hamilton, Pietro Liò, Yoshua Bengio, R Devon Hjelm.* ICLR 2019. [paper](https://openreview.net/pdf?id=rklz9iAcKQ) [code](https://github.com/PetarV-/DGI)

1. **Combining Neural Networks with Personalized PageRank for Classification on Graphs.**
*Johannes Klicpera, Aleksandar Bojchevski, Stephan Günnemann.* ICLR 2019. [paper](https://arxiv.org/pdf/1810.05997.pdf)

1. **Capsule Graph Neural Network.** 
*Zhang Xinyi, Lihui Chen.* ICLR 2019. [paper](https://openreview.net/pdf?id=Byl8BnRcYm) [code](https://github.com/benedekrozemberczki/CapsGNN)

1. **Diffusion Scattering Transforms on Graphs.** 
*Fernando Gama, Alejandro Ribeiro, Joan Bruna.* ICLR 2019. [paper](https://arxiv.org/pdf/1806.08829.pdf)

1. **Graph Wavelet Neural Network.** *Bingbing Xu, Huawei Shen, Qi Cao, Yunqi Qiu, Xueqi Cheng.* ICLR 2019. [paper](https://openreview.net/pdf?id=H1ewdiR5tQ) [code](https://github.com/benedekrozemberczki/GraphWaveletNeuralNetwork)

1. **GMNN: Graph Markov Neural Networks.** 
*Meng Qu, Yoshua Bengio, Jian Tang.* ICML 2019. [paper](https://arxiv.org/pdf/1905.06214.pdf) [code](https://github.com/DeepGraphLearning/GMNN)

1. **Position-aware Graph Neural Networks.**
*Jiaxuan You, Rex Ying, Jure Leskovec.* ICML 2019. [paper](http://proceedings.mlr.press/v97/you19b.html) [code](https://github.com/JiaxuanYou/P-GNN)

1. **Compositional Fairness Constraints for Graph Embeddings.**
*Avishek Joey Bose, William L. Hamilton.* ICML 2019. [paper](http://proceedings.mlr.press/v97/bose19a/bose19a.pdf) [code](https://github.com/joeybose/Flexible-Fairness-Constraints)

1. **Learning Discrete Structures for Graph Neural Networks.**
*Luca Franceschi, Mathias Niepert, Massimiliano Pontil, Xiao He.* ICML 2019. [paper](http://proceedings.mlr.press/v97/franceschi19a.html) [code](https://github.com/lucfra/LDS)

1. **Graph U-Nets.**
*Hongyang Gao, Shuiwang Ji.* ICML 2019. [paper](http://proceedings.mlr.press/v97/gao19a.html) [code](https://github.com/HongyangGao/gunet)

1. **MixHop: Higher-Order Graph Convolutional Architectures via Sparsified Neighborhood Mixing.**
*Sami Abu-El-Haija, Bryan Perozzi, Amol Kapoor, Hrayr Harutyunyan, Nazanin Alipourfard, Kristina Lerman, Greg Ver Steeg, and Aram Galstyan.* ICML 2019. [paper](https://arxiv.org/pdf/1905.00067.pdf) [code(tensorflow)](https://github.com/samihaija/mixhop) [code(pytorch)](https://github.com/benedekrozemberczki/MixHop-and-N-GCN)

1. **Graph Matching Networks for Learning the Similarity of Graph Structured Objects.**
*Yujia Li, Chenjie Gu, Thomas Dullien, Oriol Vinyals, Pushmeet Kohli.* ICML 2019. [paper](http://proceedings.mlr.press/v97/li19d.html)

1. **Disentangled Graph Convolutional Networks.**
*Jianxin Ma, Peng Cui, Kun Kuang, Xin Wang, Wenwu Zhu.* ICML 2019. [paper](http://proceedings.mlr.press/v97/ma19a.html)

1. **Bayesian Graph Convolutional Neural Networks for Semi-supervised Classification.** *Yingxue Zhang, Soumyasundar Pal, Mark Coates, Deniz Üstebay.* AAAI 2019. [paper](https://arxiv.org/pdf/1811.11103.pdf)

1. **Geniepath: Graph neural networks with adaptive receptive paths.** Ziqi Liu, Chaochao Chen, Longfei Li, Jun Zhou, Xiaolong Li, Le Song, Yuan Qi. AAAI 2019. [paper](https://arxiv.org/pdf/1802.00910.pdf) [code](https://github.com/shawnwang-tech/GeniePath-pytorch)

1. **Hypergraph Neural Networks.** *Yifan Feng, Haoxuan You, Zizhao Zhang, Rongrong Ji, Yue Gao* AAAI 2019. [paper](https://arxiv.org/pdf/1809.09401.pdf) [code](https://github.com/iMoonLab/HGNN)

1. **Weisfeiler and Leman Go Neural: Higher-order Graph Neural Networks.** *Christopher Morris, Martin Ritzert, Matthias Fey, William L. Hamilton, Jan Eric Lenssen, Gaurav Rattan, Martin Grohe* AAAI 2019. [paper](https://arxiv.org/pdf/1810.02244.pdf) [code](https://github.com/k-gnn/k-gnn)

1. **EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs** 
*Aldo Pareja, Giacomo Domeniconi, Jie Chen, Tengfei Ma, Toyotaro Suzumura, Hiroki Kanezashi, Tim Kaler, Charles E. Leisersen* 2019. [paper](https://arxiv.org/pdf/1902.10191.pdf)

1. **Are Powerful Graph Neural Nets Necessary? A Dissection on Graph Classification.**
*Ting Chen, Song Bian, Yizhou Sun.* 2019. [paper](https://arxiv.org/pdf/1905.04579.pdf) [code](https://github.com/chentingpc/gfn)

#### 2018

1. **FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling.**
*Jie Chen, Tengfei Ma, Cao Xiao.* ICLR 2018. [paper](https://arxiv.org/pdf/1801.10247.pdf) [code](https://github.com/matenure/FastGCN)

1. **Relational neural expectation maximization: Unsupervised discovery of objects and their interactions.**
*Sjoerd van Steenkiste, Michael Chang, Klaus Greff, Jürgen Schmidhuber.* ICLR 2018. [paper](https://arxiv.org/pdf/1802.10353.pdf) [code](https://github.com/sjoerdvansteenkiste/Relational-NEM)

1. **Contextual Graph Markov Model: A Deep and Generative Approach to Graph Processing.**
*Davide Bacciu, Federico Errica, Alessio Micheli.* ICML 2018. [paper](https://arxiv.org/pdf/1805.10636.pdf)

1. **Deep Gaussian Embedding of Graphs:  Unsupervised Inductive Learning via Ranking** *Aleksandar Bojchevski, Stephan Günnemann.* ICML 2018. [paper](https://openreview.net/forum?id=r1ZdKJ-0W) [code](https://github.com/abojchevski/graph2gauss)

1. **Learning Steady-States of Iterative Algorithms over Graphs.**
*Hanjun Dai, Zornitsa Kozareva, Bo Dai, Alex Smola, Le Song.* ICML 2018. [paper](http://proceedings.mlr.press/v80/dai18a/dai18a.pdf) [code](https://github.com/Hanjun-Dai/steady_state_embedding)

1. **Representation learning on graphs with jumping knowledge networks.** *Keyulu Xu, Chengtao Li, Yonglong Tian, Tomohiro Sonobe, Ken-ichi Kawarabayashi, Stefanie Jegelka.* ICML 2018. [paper](https://arxiv.org/pdf/1806.03536.pdf)

1. **Hierarchical Graph Representation Learning with Differentiable Pooling.**
*Zhitao Ying, Jiaxuan You, Christopher Morris, Xiang Ren, Will Hamilton, Jure Leskovec.* NeurIPS 2018. [paper](https://papers.nips.cc/paper/7729-hierarchical-graph-representation-learning-with-differentiable-pooling.pdf) [code](https://github.com/RexYing/diffpool)

1. **Bayesian Semi-supervised Learning with Graph Gaussian Processes.**
*Yin Cheng Ng, Nicolò Colombo, Ricardo Silva.* NeurIPS 2018. [paper](https://arxiv.org/pdf/1809.04379) [code](https://github.com/yincheng/GGP)

1. **Link Prediction Based on Graph Neural Networks**
*Muhan Zhang, Yixin Chen.* NIPS 2018. [paper](https://arxiv.org/pdf/1802.09691.pdf) [code](https://github.com/muhanzhang/SEAL)

1. **Structure-Aware Convolutional Neural Networks.**
*Jianlong Chang, Jie Gu, Lingfeng Wang, Gaofeng Meng, Shiming Xiang, Chunhong Pan.* NeurIPS 2018. [paper](http://papers.nips.cc/paper/7287-structure-aware-convolutional-neural-networks.pdf)

1. **Adaptive Sampling Towards Fast Graph Representation Learning.**
*Wenbing Huang, Tong Zhang, Yu Rong, Junzhou Huang.* NeurIPS 2018. [paper](https://arxiv.org/pdf/1809.05343.pdf)

1. **Mean-field theory of graph neural networks in graph partitioning.**
*Tatsuro Kawamoto, Masashi Tsubaki, Tomoyuki Obuchi.* NeurIPS 2018. [paper](http://papers.nips.cc/paper/7689-mean-field-theory-of-graph-neural-networks-in-graph-partitioning.pdf)

1. **Large-Scale Learnable Graph Convolutional Networks.** *Hongyang Gao, Zhengyang Wang, Shuiwang Ji.* KDD 2018. [paper](https://arxiv.org/pdf/1808.03965.pdf)

1. **Graph-to-Sequence Learning using Gated Graph Neural Networks.**
*Daniel Beck, Gholamreza Haffari, Trevor Cohn.* ACL 2018. [paper](https://arxiv.org/pdf/1806.09835.pdf) [code](https://github.com/beckdaniel/acl2018_graph2seq)

1. **Deeper Insights into Graph Convolutional Networks for Semi-Supervised Learning.**
*Qimai Li, Zhichao Han, Xiao-Ming Wu.* AAAI 2018. [paper](https://arxiv.org/pdf/1801.07606.pdf) [code](https://github.com/Davidham3/deeper_insights_into_GCNs)

1. **Covariant Compositional Networks For Learning Graphs.**
*Risi Kondor, Hy Truong Son, Horace Pan, Brandon Anderson, Shubhendu Trivedi.* 2018. [paper](https://arxiv.org/pdf/1801.02144.pdf) [code](https://github.com/HyTruongSon/GraphFlow)

1. **Graph capsule convolutional neural networks.** *Saurabh Verma, Zhi-Li Zhang.* 2018. [paper](https://arxiv.org/abs/1805.08090) [code](https://github.com/vermaMachineLearning/Graph-Capsule-CNN-Networks)

#### 2017

1. **Semi-Supervised Classification with Graph Convolutional Networks.**
*Thomas N. Kipf, Max Welling.* ICLR 2017. [paper](https://arxiv.org/pdf/1609.02907.pdf)

1. **Neural message passing for quantum chemistry.** *Justin Gilmer, Samuel S. Schoenholz, Patrick F. Riley, Oriol Vinyals, George E. Dahl.* ICML 2017. [paper](https://arxiv.org/pdf/1704.01212.pdf)

1. **Inductive Representation Learning on Large Graphs.**
*William L. Hamilton, Rex Ying, Jure Leskovec.* NIPS 2017. [paper](https://arxiv.org/pdf/1706.02216.pdf)

1. **Deep Sets.**
*Manzil Zaheer, Satwik Kottur, Siamak Ravanbakhsh, Barnabas Poczos, Ruslan Salakhutdinov, Alexander Smola.* NIPS 2017. [paper](https://arxiv.org/pdf/1703.06114.pdf)

1. **Dynamic Edge-Conditioned Filters in Convolutional Neural Networks on Graphs.**
*Martin Simonovsky, Nikos Komodakis.* CVPR 2017. [paper](https://arxiv.org/pdf/1704.02901)

1. **Geometric deep learning on graphs and manifolds using mixture model cnns.** *Federico Monti, Davide Boscaini, Jonathan Masci, Emanuele Rodolà, Jan Svoboda, Michael M. Bronstein.* CVPR 2017. [paper](https://arxiv.org/pdf/1611.08402.pdf)

1. **Robust spatial filtering with graph convolutional neural networks.** 2017. *Felipe Petroski Such, Shagan Sah, Miguel Dominguez, Suhas Pillai, Chao Zhang, Andrew Michael, Nathan Cahill, Raymond Ptucha.* [paper](https://arxiv.org/abs/1703.00792)

1. **Cayleynets: graph convolutional neural networks with complex rational spectral filters.** *Ron Levie, Federico Monti, Xavier Bresson, Michael M. Bronstein.* 2017. [paper](https://arxiv.org/pdf/1705.07664.pdf)

#### 2016

1. **Learning convolutional neural networks for graphs.** *Mathias Niepert, Mohamed Ahmed, Konstantin Kutzkov.* ICML 2016. [paper](https://arxiv.org/pdf/1605.05273.pdf)

1. **Diffusion-Convolutional Neural Networks.**
*James Atwood, Don Towsley.* NIPS 2016. [paper](https://arxiv.org/pdf/1511.02136.pdf)

1. **Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering.**
*Michaël Defferrard, Xavier Bresson, Pierre Vandergheynst.* NIPS 2016. [paper](http://papers.nips.cc/paper/6081-convolutional-neural-networks-on-graphs-with-fast-localized-spectral-filtering.pdf)

1. **Molecular graph convolutions: moving beyond fingerprints.** *Steven Kearnes, Kevin McCloskey, Marc Berndl, Vijay Pande, Patrick Riley* 2016. [paper](https://arxiv.org/pdf/1603.00856.pdf)

#### 2015

1. **Gated graph sequence neural networks.** *Yujia Li, Richard Zemel, Marc Brockschmidt, Daniel Tarlow.* ICLR 2015. [paper](https://arxiv.org/pdf/1511.05493.pdf)

1. **Convolutional networks on graphs for learning molecular fingerprints.** *David Duvenaud, Dougal Maclaurin, Jorge Aguilera-Iparraguirre Rafael Go ́mez-Bombarelli, Timothy Hirzel, Ala ́n Aspuru-Guzik, Ryan P. Adams.*, NIPS 2015. [paper](http://papers.nips.cc/paper/5954-convolutional-networks-on-graphs-for-learning-molecular-fingerprints.pdf)

1. **Accelerated filtering on graphs using lanczos method.** *Ana Susnjara, Nathanael Perraudin, Daniel Kressner, Pierre Vandergheynst.* 2015. [paper](https://arxiv.org/pdf/1509.04537.pdf)

1. **Deep convolutional networks on graph-structured data.** *Mikael Henaff, Joan Bruna, Yann LeCun.* 2015. [paper](https://arxiv.org/abs/1506.05163)

#### 2014

1. **Spectral Networks and Locally Connected Networks on Graphs.**
*Joan Bruna, Wojciech Zaremba, Arthur Szlam, Yann LeCun.* ICLR 2014. [paper](https://arxiv.org/pdf/1312.6203.pdf)

#### 2011

1. **Neural networks for relational learning: an experimental comparison.**
*Werner Uwents, Gabriele Monfardini, Hendrik Blockeel, Marco Gori, Franco Scarselli.* Machine Learning 2011. [paper](https://link.springer.com/content/pdf/10.1007%2Fs10994-010-5196-5.pdf)

#### 2009

1. **The graph neural network model.** *Franco Scarselli,Marco Gori,Ah Chung Tsoi,Markus Hagenbuchner,
Gabriele Monfardini.* 2009. [paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1015.7227&rep=rep1&type=pdf)

#### 2006

1. **A Comparison between Recursive Neural Networks and Graph Neural Networks.**
*Vincenzo Di Massa, Gabriele Monfardini, Lorenzo Sarti, Franco Scarselli, Marco Maggini, Marco Gori.* IJCNN 2006. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1716174)


<a name="gan" />

### Graph Attention Networks

#### 2019

1. **Heterogeneous Graph Attention Network.**
*Xiao Wang, Houye Ji, Chuan Shi, Bai Wang, Peng Cui, P. Yu, Yanfang Ye.* WWW 2019. [paper](https://arxiv.org/pdf/1903.07293.pdf)

#### 2018

1. **Graph Attention Networks.**
*Petar Velickovic, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Lio, Yoshua Bengio.* ICLR 2018. [paper](https://mila.quebec/wp-content/uploads/2018/07/d1ac95b60310f43bb5a0b8024522fbe08fb2a482.pdf) [code](https://github.com/PetarV-/GAT)

1. **Watch your step: Learning node embeddings via graph attention.** *Sami Abu-El-Haija, Bryan Perozzi, Rami Al-Rfou, Alex Alemi.* NeurIPS 2018. [paper](https://arxiv.org/pdf/1710.09599.pdf) [code](https://github.com/benedekrozemberczki/AttentionWalk)

1. **Graph Classification using Structural Attention.**
*John Boaz Lee, Ryan Rossi, Xiangnan Kong.* KDD 2018. [paper](https://dl.acm.org/ft_gateway.cfm?id=3219980&ftid=1988883&dwn=1&CFID=38275959&CFTOKEN=6938a464cf972252-DF065FDC-9FED-EB68-3528017EA04F0D29) [code](https://github.com/benedekrozemberczki/GAM)

1. **Hyperbolic Attention Networks.**
*Caglar Gulcehre, Misha Denil, Mateusz Malinowski, Ali Razavi, Razvan Pascanu, Karl Moritz Hermann, Peter Battaglia, Victor Bapst, David Raposo, Adam Santoro, Nando de Freitas* 2018. [paper](https://arxiv.org/pdf/1805.09786)

#### 2017

1. **Attention Is All You Need.**
*Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, Illia Polosukhin.* NIPS 2017. [paper](https://arxiv.org/pdf/1706.03762)


<a name="gae" />

### Graph Auto-encoder

#### 2019

1. **Deep Graph Infomax.** *Petar Veličković, William Fedus, William L. Hamilton, Pietro Liò, Yoshua Bengio, R Devon Hjelm.* ICLR 2019. [paper](https://arxiv.org/abs/1809.10341) [code](https://github.com/PetarV-/DGI)

#### 2018

1. **SpectralNet: Spectral Clustering using Deep Neural Networks.** *Uri Shaham, Kelly Stanton, Henry Li, Boaz Nadler, Ronen Basri, Yuval Kluger.* ICLR 2018. [paper](https://arxiv.org/pdf/1801.01587.pdf)

1. **Constrained Generation of Semantically Valid Graphs via Regularizing Variational Autoencoders.** *Tengfei Ma, Jie Chen, Cao Xiao.* NeurIPS 2018. [paper](https://papers.nips.cc/paper/7942-constrained-generation-of-semantically-valid-graphs-via-regularizing-variational-autoencoders.pdf)

1. **Deep Recursive Network Embedding with Regular Equivalence.**
*Ke Tu, Peng Cui, Xiao Wang, Philip S. Yu, Wenwu Zhu.* KDD 2018. [paper](http://cuip.thumedialab.com/papers/NE-RegularEquivalence.pdf)

1. **Learning Deep Network Representations with Adversarially Regularized Autoencoders.**
*Wenchao Yu, Cheng Zheng, Wei Cheng, Charu Aggarwal, Dongjin Song, Bo Zong, Haifeng Chen, Wei Wang.* KDD 2018. [paper](http://www.cs.ucsb.edu/~bzong/doc/kdd-18.pdf)

1. **Adversarially Regularized Graph Autoencoder for Graph Embedding.**
*Shirui Pan, Ruiqi Hu, Guodong Long, Jing Jiang, Lina Yao, Chengqi Zhang.* IJCAI 2018. [paper](https://www.ijcai.org/proceedings/2018/0362.pdf)


#### 2017

1. **Mgae: Marginalized Graph Autoencoder for Graph Clustering.** *Chun Wang, Shirui Pan, Guodong Long, Xingquan Zhu, Jing Jiang.* CIKM 2017. [paper](https://shiruipan.github.io/pdf/CIKM-17-Wang.pdf)

#### 2016

1. **Variational Graph Auto-Encoders.** *Thomas N. Kipf, Max Welling.* 2016. [paper](https://arxiv.org/pdf/1611.07308.pdf) [code](https://github.com/tkipf/gae)


<a name="ggn" />

### Graph Generative Networks

#### 2018

1. **NetGAN: Generating Graphs via Random Walks.**
*Aleksandar Bojchevski, Oleksandr Shchur, Daniel Zügner, Stephan Günnemann.* ICML 2018. [paper](https://arxiv.org/abs/1803.00816)

1. **Learning Deep Generative Models of Graphs.** *Yujia Li, Oriol Vinyals, Chris Dyer, Razvan Pascanu, Peter Battaglia.* ICML 2018. [paper](https://arxiv.org/abs/1803.03324)

1. **Graph Convolutional Policy Network for Goal-Directed Molecular Graph Generation.** *Jiaxuan You, Bowen Liu, Rex Ying, Vijay Pande, Jure Leskovec.* NeurIPS 2018. [paper](https://arxiv.org/abs/1806.02473)

1. **Adversarial Attacks on Neural Networks for Graph Data.**
*Daniel Zügner, Amir Akbarnejad, Stephan Günnemann.* KDD 2018. [paper](http://delivery.acm.org/10.1145/3230000/3220078/p2847-zugner.pdf?ip=101.5.139.169&id=3220078&acc=ACTIVE%20SERVICE&key=BF85BBA5741FDC6E%2E587F3204F5B62A59%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1545706391_e7484be677293ffb5f18b39ce84a0df9)

1. **MolGAN: An Implicit Generative Model for Small Molecular Graphs.**
*Nicola De Cao, Thomas Kipf.* 2018. [paper](https://arxiv.org/pdf/1805.11973.pdf)

#### 2016

1. **Learning Graphical State Transitions.** *Daniel D. Johnson.* ICLR 2016. [paper](https://openreview.net/pdf?id=HJ0NvFzxl)

<a name="grl" />

### Graph Reinforcement Learning

#### 2018

1. **NerveNet: Learning Structured Policy with Graph Neural Networks.**
*Tingwu Wang, Renjie Liao, Jimmy Ba, Sanja Fidler.* ICLR 2018. [paper](https://openreview.net/pdf?id=S1sqHMZCb)

1. **Relational Deep Reinforcement Learning.**
*Vinicius Zambaldi, David Raposo, Adam Santoro, Victor Bapst, Yujia Li, Igor Babuschkin, Karl Tuyls, David Reichert, Timothy Lillicrap, Edward Lockhart, Murray Shanahan, Victoria Langston, Razvan Pascanu, Matthew Botvinick, Oriol Vinyals, Peter Battaglia.* 2018. [paper](https://arxiv.org/abs/1806.01830)

<a name="gstn" />

### Graph Spatial-Temporal Networks

#### 2019

1. **Attention Based Spatial-Temporal Graph Convolutional Networks for Traffic Flow Forecasting.** *Shengnan Guo, Youfang Lin, Ning Feng, Chao Song, HuaiyuWan* AAAI 2019. [paper](https://github.com/Davidham3/ASTGCN/blob/master/2019%20AAAI_Attention%20Based%20Spatial-Temporal%20Graph%20Convolutional%20Networks%20for%20Traffic%20Flow%20Forecasting.pdf)

1. **Spatiotemporal Multi-Graph Convolution Network for Ride-hailing Demand Forecasting.** *Xu Geng, Yaguang Li, Leye Wang, Lingyu Zhang, Qiang Yang, Jieping Ye, Yan Liu.* AAAI 2019. [paper](http://www-scf.usc.edu/~yaguang/papers/aaai19_multi_graph_convolution.pdf)

1. **Spatio-Temporal Graph Routing for Skeleton-based Action Recognition.** *Bin Li, Xi Li, Zhongfei Zhang, Fei Wu.*  AAAI 2019. [paper](https://www.aaai.org/Papers/AAAI/2019/AAAI-LiBin.6992.pdf)

#### 2018

1. **Diffusion Convolutional Recurrent Neural Network: Data-Driven Traffic Forecasting.** *Yaguang Li, Rose Yu, Cyrus Shahabi, Yan Liu.* ICLR 2018. [paper](https://arxiv.org/pdf/1707.01926.pdf)

1. **GraphRNN: Generating Realistic Graphs with Deep Auto-Regressive Models.**
*Jiaxuan You, Rex Ying, Xiang Ren, William L. Hamilton, Jure Leskovec.* ICML 2018. [paper](https://arxiv.org/abs/1802.08773) [code](https://github.com/JiaxuanYou/graph-generation)

1. **Recurrent Relational Networks.**
*Rasmus Palm, Ulrich Paquet, Ole Winther.* NeurIPS 2018. [paper](http://papers.nips.cc/paper/7597-recurrent-relational-networks.pdf)

1. **Deep Multi-View Spatial-Temporal Network for Taxi.** *Huaxiu Yao, Fei Wu, Jintao Ke, Xianfeng Tang, Yitian Jia, Siyu Lu, Pinghua Gong, Jieping Ye, Zhenhui Li.* AAAI 2018. [paper](https://arxiv.org/abs/1802.08714)

1. **Spatial Temporal Graph Convolutional Networks for Skeleton-Based Action Recognition.** *Sijie Yan, Yuanjun Xiong, Dahua Lin.* AAAI 2018. [paper](https://arxiv.org/abs/1801.07455) [code](https://github.com/yysijie/st-gcn)

#### 2017

1. **Spatio-Temporal Graph Convolutional Networks: A Deep Learning Framework for Traffic Forecasting.** *Bing Yu, Haoteng Yin, Zhanxing Zhu.* IJCAI 2018. [paper](https://arxiv.org/pdf/1709.04875.pdf)

#### 2016

1. **Structural-Rnn: Deep learning on Spatio-Temporal Graphs.** *Ashesh Jain, Amir R. Zamir, Silvio Savarese, Ashutosh Saxena.* CVPR 2016. [paper](https://arxiv.org/abs/1511.05298)

1. **Semantic Object Parsing with Graph LSTM.**
*Xiaodan LiangXiaohui ShenJiashi FengLiang Lin, Shuicheng Yan.* ECCV 2016. [paper](https://link.springer.com/content/pdf/10.1007%2F978-3-319-46448-0_8.pdf)

1. **Structured Sequence Modeling with Graph Convolutional Recurrent Networks.** *Youngjoo Seo, Michaël Defferrard, Pierre Vandergheynst, Xavier Bresson.* 2016. [paper](https://arxiv.org/pdf/1612.07659.pdf) [code](https://github.com/youngjoo-epfl/gconvRNN)


<a name="theory" />

### Theoretical Analysis

#### 2019

1. **How Powerful are Graph Neural Networks?.**
*Keyulu Xu, Weihua Hu, Jure Leskovec, Stefanie Jegelka.* ICLR 2019. [paper](https://openreview.net/pdf?id=ryGs6iA5Km) [code](https://github.com/weihua916/powerful-gnns)

1. **Simplifying Graph Convolutional Networks.**
*Felix Wu, Amauri Souza, Tianyi Zhang, Christopher Fifty, Tao Yu, Kilian Weinberger.* ICML 2019. [paper](http://proceedings.mlr.press/v97/wu19e.html) [code](https://github.com/Tiiiger/SGC)

1. **Can GCNs Go as Deep as CNNs?.**
*Guohao Li, Matthias Müller, Ali Thabet, Bernard Ghanem.* 2019. [paper](https://arxiv.org/pdf/1904.03751.pdf) [code](https://github.com/lightaime/deep_gcns) [website](https://sites.google.com/view/deep-gcns)

1. **Revisiting Graph Neural Networks: All We Have is Low-Pass Filters.** 
*Hoang NT, Takanori Maehara.* 2019. [paper](https://arxiv.org/pdf/1905.09550.pdf) [code](https://github.com/gear/gfnn)

1. **On Asymptotic Behaviors of Graph CNNs from Dynamical Systems Perspective.**
*Kenta Oono, Taiji Suzuki.* 2019 [paper](https://arxiv.org/pdf/1905.10947.pdf)

#### 2018

1. **Stochastic Training of Graph Convolutional Networks with Variance Reduction.**
*Jianfei Chen, Jun Zhu, Le Song.* ICML 2018. [paper](http://www.scipaper.net/uploadfile/2018/0716/20180716100330880.pdf)

#### 2016

**Revisiting Semi-Supervised Learning with Graph Embeddings.**
*Zhilin Yang, William W. Cohen, Ruslan Salakhutdinov* ICML 2016. [paper](https://arxiv.org/pdf/1603.08861.pdf) [code](https://github.com/kimiyoung/planetoid)


<a name="Library" />

## Library

1. [pytorch geometric](https://github.com/rusty1s/pytorch_geometric)

1. [deep graph library](https://github.com/dmlc/dgl)

1. [graph nets library](https://github.com/deepmind/graph_nets)
