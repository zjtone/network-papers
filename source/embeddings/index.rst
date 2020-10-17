图/网络嵌入
================
| 图嵌入和网络嵌入指的都是同一样东西，首先解释一下什么是图，什么是网络，想象一张蜘蛛网，上面有许许多多的线，线与线连接在一起，连接处就是节点。节点和节点之间通过边进行连接，最终就构成了一张图。因此在我们的生活中，图或网络是无处不在的。这里讲的图和网络是广义的，不仅仅指的是某一张具体的图像或计算机网络。
| 具体而言，网络理论是图论的一部分：网络可以定义为节点/边具有属性的图。简而言之，网络和图指的都是，节点以及节点之间的联系。
| 而图嵌入和网络嵌入，指的是将图或者网络从高维度的空间降维到低维空间，将具有空间和结构复杂性的图上的节点，编码为一个向量表示，这个向量表示保存了节点的结构信息和特征信息，可以作为节点的表示而存在。我们也可以利用这个向量进行节点分类，链路预测等多种多样的任务，实现图结构的充分利用。
| 下方将介绍一些图嵌入、图表示学习方法。

.. toctree::
   :maxdepth: 2
   :caption: 基础介绍:

   link_prediction

.. toctree::
   :maxdepth: 2
   :caption: 基于结构的embedding算法:
   DeepWalk
   node2vec
   LINE

.. toctree::
   :maxdepth: 2
   :caption: 学习特征的embedding算法:
   GraphSAGE
   Graph_inference_learning_for_semi_supervised_classification
   Curvature_neural_network
   Topology_Optimization_based_Graph_Convolutional_Network
   Attributed_Graph_Clustering_A_Deep_Attentional_Embedding_Approach
   Attributed_Graph_Clustering_via_Adaptive_Graph_Convolution
   DropEdge
   Link_Prediction_Based_on_Graph_Neural_Networks
   Graph_Neural_Networks_with_Composite_Kernels
   .. Graph_Homomorphism_Convolution

.. toctree::
   :maxdepth: 2
   :caption: 更多:
   Articles
