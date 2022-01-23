# Learning on Graphs
Awesome papers on learning on graphs with theoretical guarantees.

## Contents
- [Books](#book)
- [Survey](#survey)
- [Regularization on graphs](#regularization)
- [Graph clustering](#clustering)
- [Analysis of Laplacian](#laplacian)
- [Graph signal processing](#gsp)
- [Theory of graph neural networks](#gnn)
- [Special graphs](#special)
- [Graph Neural Tangent Kernel](#gntk)
- [OOD on Graphs](#graph-ood)
- [GNN & PDE](#gnn-pde)
- [Graph Optimal Transport](#got)
- [New GNN Architectures](#arch)


<a name="book" />

## Books

1. **Spectra of Graphs.**
    - arXiv 2017.
    - *Andries E. Brouwer, Willem H. Haemers.*
    - [paper](https://homepages.cwi.nl/~aeb/math/ipm/ipm.pdf)

1. **Geometric Structures on Manifolds.**
    - arXiv 2021.
    - *William M. Goldman.*
    - [paper](http://www2.math.umd.edu/~wmg/gstom.pdf)


<a name="survey" />

## Survey

1. **A Survey on Graph Kernels.**
    - arXiv 2020.
    - *Nils M. Kriege, Fredrik D. Johansson, and Christopher Morris.*
    - [paper](https://arxiv.org/pdf/1903.11835.pdf)


<a name="regularization" />

## Regularization on Graphs

1. **Kernels and Regularization on Graphs.**
    - COLT 2003.
    - *Alexander J. Smola, Risi Kondor.*
    - [paper](https://people.cs.uchicago.edu/~risi/papers/SmolaKondor.pdf)
    
1. **Regularization and Semi-supervised Learning on Large Graphs.**
    - COLT 2004.
    - *Mikhail Belkin, Irina Matveeva, Partha Niyogi.*
    - [paper](http://people.cs.uchicago.edu/~niyogi/papersps/reg_colt.pdf)
    
1. **Regularization on Discrete Spaces.**
    - DAGM 2005.
    - *Dengyong Zhou, Bernhard Scholkopf.*
    - [paper](https://link.springer.com/content/pdf/10.1007%2F11550518_45.pdf)
    
1. **Towards a Theoretical Foundation for Laplacian-Based Manifold Methods.**
    - COLT 2005.
    - *Mikhail Belkin, Partha Niyogi.*
    - [paper](http://people.cs.uchicago.edu/~niyogi/papersps/BNcolt05.pdf)
    
1. **From Graphs to Manifolds - Weak and Strong Pointwise Consistency of Graph Laplacians.**
    - COLT 2005.
    - *Matthias Hein, Jean-Yves Audibert, Ulrike von Luxburg.*
    - [paper](https://www.tml.cs.uni-tuebingen.de/team/luxburg/publications/HeiAudLux05.pdf)
    
1. **Uniform Convergence of Adaptive Graph-based Regularization.**
    - COLT 2006.
    - *Matthias Hein.*
    - [paper](http://is.tuebingen.mpg.de/fileadmin/user_upload/files/publications/Hein-Unif_Conv_Graph_Reg(2006)_3893[1].pdf)

1. **On the Sample Complexity of Learning Smooth Cuts on a Manifold.**
    - COLT 2009.
    - *Hariharan Narayanan, Partha Niyogi.*
    - [paper](http://www.mit.edu/~har/ManifoldSample.pdf)

1. **Semi-Supervised Learning with the Graph Laplacian: The Limit of Infinite Unlabelled Data.**
    - NIPS 2009.
    - *Boaz Nadler, Nathan Srebro, Xueyuan Zhou.*
    - [paper](https://papers.nips.cc/paper/3652-statistical-analysis-of-semi-supervised-learning-the-limit-of-infinite-unlabelled-data.pdf)

1. **Sample Complexity of Testing the Manifold Hypothesis.**
    - NIPS 2010.
    - *Hariharan Narayanan, Sanjoy Mitter.*
    - [paper](http://www.mit.edu/~har/Testing_Manifold_Hypothesis.pdf)

1. **Testing the Manifold Hypothesis.**
    - arXiv 2013.
    - *Charles Fefferman, Sanjoy Mitter, Hariharan Narayanan.*
    - [paper](https://arxiv.org/pdf/1310.0425.pdf)

1. **Algorithms for Lipschitz Learning on Graphs.**
    - COLT 2015.
    - *Rasmus Kyng, Anup Rao, Sushant Sachdeva, Daniel A. Spielman.*
    - [paper](http://proceedings.mlr.press/v40/Kyng15.pdf)

1. **Analysis of p-Laplacian Regularization in Semi-Supervised Learning.**
    - SIAM Journal on Mathematical Analysis 2019.
    - *Dejan Slepčev, Matthew Thorpe.*
    - [paper](https://arxiv.org/pdf/1707.06213.pdf)

1. **On Consistency of Graph-based Semi-supervised Learning.**
    - ICDCS 2019.
    - *Chengan Du, Yunpeng Zhao, Feng Wang.*
    - [paper](https://arxiv.org/pdf/1703.06177.pdf)

1. **Consistent Semi-Supervised Graph Regularization for High Dimensional Data.**
    - JMLR 2021.
    - *Xiaoyi Mai, Romain Couillet.*
    - [paper](https://www.jmlr.org/papers/volume22/19-081/19-081.pdf)


<a name="clustering" />

## Graph Clustering

1. **Limits of Spectral Clustering.**
    - NIPS 2004.
    - *Ulrike von Luxburg, Olivier Bousquet, Mikhail Belkin.*
    - [paper](http://www.tml.cs.uni-tuebingen.de/team/luxburg/publications/LuxBouBel05_nips04.pdf)

1. **A Sober Look on Clustering Stability.**
    - COLT 2006.
    - *Shai Ben-David1, Ulrike von Luxburg, David Pal.*
    - [paper](http://www.tml.cs.uni-tuebingen.de/team/luxburg/publications/BenLuxPal06.pdf)

1. **Consistency of Spectral Clustering.**
    - Annals of Statistcs 2008.
    - *Ulrike von Luxburg, Mikhail Belkin, Oliver Bousquet.*
    - [paper](http://www.tml.cs.uni-tuebingen.de/team/luxburg/publications/LuxBelBou08.pdf)
    
1. **How the Results of Graph Clustering Methods Depends on the Construction of the Graph.**
    - Probability and Statistics 2012.
    - *Markus Maier, Ulrike von Luxburg, Mikhail Belkin.*
    - [paper](http://www.tml.cs.uni-tuebingen.de/team/luxburg/publications/MaierLuxburgHein12.pdf)

1. **K-Way p-Spectral Clustering on Grassmann Manifolds.**
    - JMLR 2021.
    - *Dimosthenis Pasadakis, Christie Louis Alappat, Olaf Schenk, Gerhard Wellein.*
    - [paper](https://arxiv.org/pdf/2008.13210.pdf)

1. **Statistical Guarantees for Local Graph Clustering.**
    - JMLR 2021.
    - *Wooseok Ha, Kimon Fountoulakis, Michael W. Mahoney.*
    - [paper](https://www.jmlr.org/papers/volume22/20-029/20-029.pdf)


<a name="laplacian" />

## Analysis of Laplacian

1. **Bounds for the Largest p-Laplacian Eigenvalue for Graphs.**
    - Discrete Mathematics 2006.
    - *S. Amghibech.*
    - [paper](https://core.ac.uk/download/pdf/82137839.pdf)
    
3. **On the Eigenvectors of p-Laplacian.**
    - Machine Learning 2010.
    - *Dijun Luo, Heng Huang, Chris Ding, Feiping Nie.*
    - [paper](https://link.springer.com/content/pdf/10.1007/s10994-010-5201-z.pdf)
    
1. **On the p-Laplacian and ![](http://latex.codecogs.com/gif.latex?\\infty)-Laplacian on Graphs with Applications in Image and Data Processing.**
    -  SIAM Journal on Imaging Science 2015.
    -  *Abderrahim Elmoataz, Matthieu Toutain, Daniel Tenbrinck.*
    -  [paper](https://epubs.siam.org/doi/pdf/10.1137/15M1022793?casa_token=1UrBrpsZ9M8AAAAA:UnXDGs_QAyqTk8ZhBjn1Pl37pfTAHzZ424P866DsMtTLbQzmBaOJumjZ3WZabbinuiBuWFbvG4pvGA)

1. **Spectrum of the 1-Laplacian and Cheeger's Constant on Graphs.**
    - Journal of Graph Theory.
    - K.C. Chang.
    - [paper](https://arxiv.org/pdf/1412.1150.pdf)
    
1. **The 1-Laplacian Cheer Cut: Theory and Algorithms.**
    - Journal of Computational Mathematics 2015.
    - *K.C. Chang, Sihong Shao, Dong Zhang.*
    - [paper](https://www.jstor.org/stable/pdf/43693873.pdf?casa_token=2UDp4e3dTCgAAAAA:QkZVSHQaQLAyMRAYb-7FlJBbM2ONeZqK_tzxQxISBXo4uzX4rEYE8ifkrCGkaMOvPCaoNm6WGvA3dxlYBS_yJwM7kDE2AYK_QkMFmQjVvsBcerG2CJVrSg)

1. **A nodal domain theorem and a higher-order Cheeger inequality for the graph p-Laplacian.**
    - arXiv 2016.
    - *Francesco Tudisco, Matthias Hein.*
    - [paper](https://arxiv.org/pdf/1602.05567.pdf)

1. **Analysis of p-Laplacian Regularization in Semi-Supervised Learning.**
    - SIAM Journal on Mathematical Analysis 2019.
    - *Dejan Slepčev, Matthew Thorpe.*
    - [paper](https://epubs.siam.org/doi/pdf/10.1137/17M115222X)

1. **Strong Consistency, Graph Laplacians, and the Stochastic Block Model.**
    - JMLR 2021.
    - *Shaofeng Deng, Shuyang Ling, Thomas Strohmer.*
    - [paper](https://www.jmlr.org/papers/volume22/20-391/20-391.pdf)

1. **Understanding Over-Squashing and Bottlenecks on Graphs via Curvature.**
    - ICLR 2022.
    - *Jake Topping, Francesco Di Giovanni, Benjamin Paul Chamberlain, Xiaowen Dong, Michael M. Bronstein.*
    - [paper](https://arxiv.org/pdf/2111.14522.pdf)


<a name="gsp" />

## Graph Signal Processing

1. **A Sampling Theory Perspective of Graph-based Semi-supervised Learning.**
    -  IEEE Transactions on Information Theory 2017.
    - *Aamir Anis, Aly El Gamal, Salman Avestimehr, Antonio Ortega.*
    - [paper](https://arxiv.org/pdf/1705.09518.pdf)

1. **Sampling on Graphs: From Theory to Applications.**
    - arXiv 2020.
    - *Yuichi Tanaka, Yonina C. Eldar, Antonio Ortega, Gene Cheung.*
    - [paper](https://arxiv.org/pdf/2003.03957.pdf)

1. **Exploiting Structure In Data: Sampling and Signal Processing on Graphs.**
    - Ph.D Thesis of Carnegie Mellon University 2020.
    - *Rohan Varma.*
    - [paper](https://kilthub.cmu.edu/articles/Exploiting_Structure_In_Data_Sampling_and_Signal_Processing_on_Graphs/12026448)

1. **Interpretable Stability Bounds for Spectral Graph Filters.**
    - arXiv 2021.
    - *Henry Kenlay, Dorina Thanou, Xiaowen Dong.*
    - [paper](https://arxiv.org/pdf/2102.09587.pdf)


<a name="gnn" />

## Theory of Graph Neural Networks
    
1. **Mean-Field Theory of Graph Neural Networks in Graph Partitioning.**
    - NeurIPS 2018.
    - *Tatsuro Kawamoto, Masashi Tsubaki, Tomoyuki Obuchi.*
    - [paper](https://proceedings.neurips.cc/paper/2018/file/f6e794a75c5d51de081dbefa224304f9-Paper.pdf)
    
1. **How Powerful are Graph Neural Networks?**
    - ICLR 2019.
    - *Keyulu Xu, Weihua Hu, Jure Leskovec, Stefanie Jegelka.*
    - [paper](https://arxiv.org/pdf/1810.00826.pdf)

1. **Invariant and Equivariant Graph Networks.**
    - ICLR 2019.
    - *Haggai Maron, Heli Ben-Hamu, Nadav Shamir & Yaron Lipman.*
    - [paper](https://arxiv.org/pdf/1812.09902.pdf)

1. **Stability and Generalization of Graph Convolutional Neural Networks.**
    - KDD 2019.
    - *Saurabh Verma, Zhi-Li Zhang.*
    - [paper](https://arxiv.org/pdf/1905.01004.pdf)

1. **Understanding the Representation Power of Graph Neural Networks in Learning Graph Topology.**
    - NIPS 2019.
    - *Nima Dehmamy, Albert-László Barabási, Rose Yu.*
    - [paper](https://arxiv.org/pdf/1907.05008.pdf)
    
1. **Universal Invariant and Equivariant Graph Neural Networks.**
    - NIPS 2019.
    - *Nicolas Keriven, Gabriel Peyré.*
    - [paper](https://arxiv.org/pdf/1905.04943.pdf)
    
1. **On the Equivalence Between Graph Isomorphism Testing and Function Approximation with GNNs.**
    - NIPS 2019.
    - *Zhengdao Chen, Soledad Villar, Lei Chen, Joan Bruna.*
    - [paper](https://arxiv.org/pdf/1905.12560.pdf)

1. **Graph Neural Tangent Kernel: Fusing Graph Neural Networks with Graph Kernels.**
    - NeurIPS 2019.
    - *Simon S. Du, Kangcheng Hou, Barnabás Póczos, Ruslan Salakhutdinov, Ruosong Wang, Keyulu Xu.*
    - [paper](https://arxiv.org/pdf/1905.13192.pdf)

1. **Fundamental Limits of Deep Graph Convolutional Networks.**
    - arXiv 2019.
    - *Abram Magner, Mayank Baranwal, Alfred O. Hero III.*
    - [paper](https://arxiv.org/pdf/1910.12954.pdf)

1. **A Simple Proof of the Universality of Invariant/Equivariant Graph Neural Networks.**
    - arXiv 2019.
    - *Takanori Maehara, Hoang NT.*
    - [paper](https://arxiv.org/pdf/1910.03802.pdf)

1. **What Can Neural Networks Reason About?**
    - ICLR 2020.
    - *Keyulu Xu, Jingling Li, Mozhi Zhang, Simon S. Du, Ken-ichi Kawarabayashi, Stefanie Jegelka.*
    - [paper](https://arxiv.org/pdf/1905.13211.pdf)

1. **Graph Neural Networks Exponentially Lose Expressive Power for Node Classification.**
    - ICLR 2020.
    - *Kenta Oono, Taiji Suzuki.*
    - [paper](https://arxiv.org/pdf/1905.10947.pdf)
    - [code](https://github.com/delta2323/gnn-asymptotics)

1. **How Hard is to Distinguish Graphs with Graph Neural Networks?**
    - Neurips 2020.
    - *Andreas Loukas.*
    - [paper](https://arxiv.org/pdf/2005.06649.pdf)

1. **The Logical Expressiveness of Graph Neural Networks.**
    - ICLR 2020.
    - *Pablo Barceló, Egor V. Kostylev, Mikael Monet, Jorge Pérez, Juan Reutter, Juan Pablo Silva.*
    - [paper](https://openreview.net/pdf?id=r1lZ7AEKvB)

1. **What Graph Neural Networks Cannot Learn: Depth vs Width.**
    - ICLR 2020.
    - *Andreas Loukas.*
    - [paper](https://arxiv.org/pdf/1907.03199.pdf)
    
1. **Generalization and Representational Limits of Graph Neural Networks.**
    - arXiv 2020.
    - *Vikas K. Garg, Stefanie Jegelka, Tommi Jaakkola.*
    - [paper](https://arxiv.org/pdf/2002.06157.pdf)

1. **Fast Learning of Graph Neural Networks with Guaranteed Generalizability: One-hidden-layer Case.**
    - ICML 2020.
    - *Shuai Zhang, Meng Wang, Sijia Liu, Pin-Yu Chen, Jinjun Xiong.*
    - [paper](https://arxiv.org/pdf/2006.14117.pdf)

1. **On the Equivalence of Molecular Graph Convolution and Molecular Wave Function with Poor Basis Set.**
    - Neurips 2020.
    - *Masashi Tsubaki, Teruyasu Mizoguchi.*
    - [paper](https://arxiv.org/pdf/2011.07929.pdf)

1. **Convergence and Stability of Graph Convolutional Networks on Large Random Graphs.**
    - NeurIPS 2020.
    - *Nicolas Keriven, Alberto Bietti, Samuel Vaiter.*
    - [paper](https://arxiv.org/pdf/2006.01868.pdf)

1. **Expressive Power of Invariant and Equivariant Graph Neural Networks.**
    - arXiv 2020.
    - *Waïss Azizian, Marc Lelarge.*
    - [paper](https://arxiv.org/pdf/2006.15646.pdf)

1. **The Expressive Power of kth-Order Invariant Graph Networks.**
    - arXiv 2020.
    - *Floris Geerts.*
    - [paper](https://arxiv.org/pdf/2007.12035.pdf)

1. **Transferability of Spectral Graph Convolutional Neural Networks.**
    - JMLR 2021.
    - *Ron Levie, Wei Huang, Lorenzo Bucci, Michael M. Bronstein, Gitta Kutyniok.*
    - [paper](https://arxiv.org/pdf/1907.12972.pdf)

1. **How Neural Networks Extrapolate: From Feedforward to Graph Neural Networks.**
    - ICLR 2021.
    - *Keyulu Xu, Mozhi Zhang, Jingling Li, Simon S. Du, Ken-ichi Kawarabayashi, Stefanie Jegelka.*
    - [paper](https://arxiv.org/pdf/2009.11848.pdf)

1. **A PAC-Bayesian Approach to Generalization Bounds for Graph Neural Networks.**
    - ICLR 2021.
    - *Renjie Liao, Raquel Urtasun, Richard Zemel.*
    - [paper](https://arxiv.org/pdf/2012.07690.pdf)

1. **Subgroup Generalization and Fairness of Graph Neural Networks.**
    - NeurIPS 2021.
    - *Jiaqi Ma, Junwei Deng, Qiaozhu Mei.*
    - [paper](https://arxiv.org/pdf/2106.15535.pdf)

1. **Generalization Bounds for Graph Convolutional Neural Networks via Rademacher Complexity.**
    - arXiv 2021.
    - *Shaogao Lv.*
    - [paper](https://arxiv.org/pdf/2102.10234.pdf)

1. **Towards a Rigorous Theoretical Analysis and Evaluation of GNN Explanations.**
    - arXiv 2021.
    - *Chirag Agarwal, Marinka Zitnik, Himabindu Lakkaraju.*
    - [paper](https://arxiv.org/pdf/2106.09078.pdf)

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

1. **Weisfeiler and Leman go Machine Learning: The Story so far.**
    - arXiv 2021.
    - *Christopher Morris, Yaron Lipman, Haggai Maron, Bastian Rieck, Nils M. Kriege, Martin Grohe, Matthias Fey, Karsten Borgwardt.*
    - [paper](https://arxiv.org/pdf/2112.09992.pdf)

1. **On the Bottleneck of Graph Neural Networks and its Practical Implications.**
    - ICLR 2021.
    - *Uri Alon, Eran Yahav.*
    - [paper](https://arxiv.org/pdf/2006.05205.pdf)
    
1. **The Logic of Graph Neural Networks.**
    - arXiv 2021.
    - *Martin Grohe*
    - [paper](https://arxiv.org/pdf/2104.14624.pdf)

1. **A New Perspective on "How Graph Neural Networks Go Beyond Weisfeiler-Lehman?"**
    - ICLR 2022.
    - *.*
    - [paper](https://openreview.net/pdf?id=uxgg9o7bI_3)


<a name="special" />

## Special Graphs

1. **Semi-supervised Learning on Directed Graphs.**
    - NIPS 2004.
    - *Dengyong Zhou, Bernhard Scholkopf, Thomas Hofmann.*
    - [paper](https://papers.nips.cc/paper/2718-semi-supervised-learning-on-directed-graphs.pdf)
    
1. **Learning from Labeled and Unlabeled Data on a Directed Graph.**
    - ICML 2005.
    - *Dengyong Zhou, Jiayuan Huang, Bernhard Scholkopf.*
    - [paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.294.7765&rep=rep1&type=pdf)
    
1. **Learning with Hypergraphs: Clustering, Classification, and Embedding.**
    - NIPS 2007
    - *Dengyong Zhou, Jiayuan Huang, Bernhard Scholkopf.*
    - [paper](https://papers.nips.cc/paper/3128-learning-with-hypergraphs-clustering-classification-and-embedding.pdf)

1. **Submodular Hypergraphs: $p$-Laplacians, Cheeger Inequalities and Spectral Clustering.**
    - ICML 2018
    - *Pan Li, Olgica Milenkovic.*
    - [paper](http://proceedings.mlr.press/v80/li18e/li18e.pdf)
    
    
<a name="gntk" />

## Graph Neural Tangent Kernel

1. **Graph Neural Tangent Kernel: Fusing Graph Neural Networks with Graph Kernels.**
    - arXiv 2019.
    - *Simon S. Du, Kangcheng Hou, Barnabás Póczos, Ruslan Salakhutdinov, Ruosong Wang, Keyulu Xu.*
    - [paper](https://arxiv.org/pdf/1905.13192.pdf)

1. **Convolutional Kernel Networks for Graph-Structured Data.**
    - ICML 2020.
    - *Dexiong Chen, Laurent Jacob, Julien Mairal.*
    - [paper](https://arxiv.org/pdf/2003.05189.pdf)

1. **Fast Graph Neural Tangent Kernel via Kronecker Sketching.**
    - arXiv 2021.
    - *Shunhua Jiang, Yunze Man, Zhao Song, Zheng Yu, Danyang Zhuo.*
    - [paper](https://arxiv.org/pdf/2112.02446.pdf)


<a name="graph-ood" />

## OOD on Graphs

1. **Towards Distribution Shift of Node-Level Prediction on Graphs: An Invariance Perspective.**
    - arXiv 2021.
    - *Anonymous.*
    - [paper](https://openreview.net/pdf?id=FQOC5u-1egI)


<a name="gnn-pde" />

## GNN & PDE

1. **Neural Ordinary Differential Equations on Manifolds.**
    - arXiv 2020.
    - *Luca Falorsi, Patrick Forré.*
    - [paper](https://arxiv.org/pdf/2006.06663.pdf)

1. **PDE-GCN: Novel Architectures for Graph Neural Networks Motivated by Partial Differential Equations.**
    - NeurIPS 2021.
    - *Moshe Eliasof, Eldad Haber, Eran Treister.*
    - [paper](https://arxiv.org/pdf/2108.01938.pdf)
    
1. **Beltrami Flow and Neural Diffusion on Graphs.**
    - NeurIPS 2021.
    - *Benjamin Chamberlain, James Rowbottom, Davide Eynard, Francesco Di Giovanni, Xiaowen Dong, Michael Bronstein.*
    - [paper](https://arxiv.org/pdf/2110.09443.pdf)


<a name="got" />

## Graph Optimal Transport

1. **Graph Optimal Transport for Cross-Domain Alignment.**
    - ICML 2020.
    - *Liqun Chen, Zhe Gan, Yu Cheng, Linjie Li, Lawrence Carin, Jingjing Liu.*
    - [paper](https://arxiv.org/pdf/2006.14744.pdf)

1. **Optimal Transport Graph Neural Networks.**
    - arXiv 2021.
    - *Benson Chen, Gary Bécigneul, Octavian-Eugen Ganea, Regina Barzilay, Tommi Jaakkola.*
    - [paper](https://arxiv.org/pdf/2006.04804.pdf)

1. **Entropic Optimal Transport in Random Graphs.**
    - arXiv 2022.
    - *Nicolas Keriven.*
    - [paper](https://arxiv.org/pdf/2201.03949.pdf)


<a name="arch" />

1. **Hyperbolic Neural Networks.**
    - NeurIPS 2018.
    - *Octavian-Eugen Ganea, Gary Bécigneul, Thomas Hofmann.*
    - [paper](https://arxiv.org/pdf/1805.09112.pdf)

1. **Constant Curvature Graph Convolutional Networks.**
    - ICML 2020.
    - *Gregor Bachmann, Gary Bécigneul, Octavian-Eugen Ganea.*
    - [paper](https://arxiv.org/pdf/1911.05076.pdf)

1. **Graph Homomorphism Convolution.**
    - ICML 2020.
    - *Hoang NT, Takanori Maehara.*
    - [paper](https://arxiv.org/pdf/2005.01214.pdf)

1. **Building Powerful and Equivariant Graph Neural Networks with Structural Message-Passing.**
    - NeurIPS 2020.
    - *Clement Vignac, Andreas Loukas, Pascal Frossard.*
    - [paper](https://arxiv.org/pdf/2006.15107.pdf)

1. **Nested Graph Neural Networks.**
    - NeurIPS 2021.
    - *Muhan Zhang, Pan Li*
    - [paper](https://arxiv.org/pdf/2110.13197.pdf)
