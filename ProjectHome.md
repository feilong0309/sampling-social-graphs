# Sampling Social Graphs #


## Understanding Graph Sampling Algorithms for Social Network Analysis ##

Being able to keep the graph scale small while capturing the properties of the original social graph, graph sampling provides an efﬁcient, yet inexpensive solution for social network analysis. The challenge is how to create a small, but representative sample out of the massive social graph with millions or even billions of nodes. Several sampling algorithms have been proposed in previous studies, but there lacks fair evaluation and
comparison among them. In this paper, we analyze the state-of-art graph sampling algorithms and evaluate their performance on some widely recognized graph properties on directed graphs using large-scale social network datasets. We evaluate not only the commonly used node degree distribution, but also clustering coefﬁcient, which quantiﬁes how well connected are the neighbors of a node in a graph. Through the comparison we have found that none of the algorithms is able to obtain satisﬁed sampling results in both of these properties, and the performance of each algorithm differs much in different kinds of datasets.

## What is Albatross Sampling? ##

Nowadays, Online Social Networks (OSNs) become dramatically popular and the study of social graph attracts the interests of a large number of researchers. One critical challenge is the huge size of the social graph, which makes the graph analyzing or even the data crawling incredibly time consuming, and sometimes impossible to do to completion. Thus, graph sampling algorithms have been introduced to obtain a smaller subgraph which reﬂects the properties of the original huge graph well. Breadth-First Sampling (BFS) is very widely used in graph sampling but it is biased towards high-degree vertices during the process of sampling. Besides, Metropolis-Hasting Random Walk (MHRW), which is proposed to get unbiased samples of the social graph, requires the graph to be well connected. In this paper, we propose a vertex sampling algorithm, so-called Albatross Sampling (AS), which introduces random jump strategy into MHRW during the sampling process. The embedded random jump makes the sampling procedure more ﬂexible and avoids being trapped in some locally well connected part. According to our evaluation, we ﬁnd that no matter using tightly or loosely connected graphs, AS performs signiﬁcantly better than MHRW and BFS. On one hand, AS estimates the degree distribution with much lower Normalized Mean Square Error (NMSE) by consuming the same resource budget. One the other hand, to get an acceptable estimation of the degree distribution, AS requires much fewer resource budget.


## Publications ##

Tianyi Wang, Yang Chen, Zengbin Zhang, Peng Sun, Beixing Deng, Xing Li, "Unbiased Sampling in Directed Social Graph", ACM SIGCOMM 2010 Poster Session, August 2010. (Acceptance Rate: 22/85=25.88%, won the First Place of the undergraduate division in ACM Student Research Competition)  (Also to appear in ACM SIGCOMM Computer Communication Review, 2010, 40(4):401-402)

Tianyi Wang, Yang Chen, Zengbin Zhang, Tianyin Xu, Long Jin, Pan Hui, Beixing Deng, Xing Li, “Understanding Graph Sampling Algorithms for Social Network Analysis”, in Proc. of the 3rd Annual Workshop on Simplifying Complex Networks for Practitioners (Simplex'11) , co-located with IEEE ICDCS, Minneapolis, USA, June 2011.

Long Jin, Yang Chen, Pan Hui, Cong Ding, Tianyi Wang, Athanasios Vasilakos, Beixing Deng, Xing Li, “Albatross Sampling: Robust and Effective Hybrid Vertex Sampling for Social Graphs”, in Proc. of the 3rd ACM Workshop on Hot Topics in Planet-scale Measurement (HotPlanet'11), co-located with ACM MobiSys 2011, June 2011.