[stars-img]: https://img.shields.io/github/stars/Jeaninezpp/Incomplete-multi-view-clustering?style=plastic
[stars-url]: https://github.com/Jeaninezpp/Incomplete-multi-view-clustering/stargazers
[fork-img]: https://img.shields.io/github/forks/Jeaninezpp/Incomplete-multi-view-clustering?style=plastic
[fork-url]: https://github.com/Jeaninezpp/Incomplete-multi-view-clustering/network/members

[![GitHub stars][stars-img]][stars-url]
[![GitHub forks][fork-img]][fork-url]

# Incomplete Multi-view Clustering (IMC)
Collections for **incomplete multi-view clustering** methods (papers and codes).
We are looking forward for other participants to share their papers and codes. If interested, please contact <zhangpei@nudt.edu.cn>.



**[:bell: News! :bell: ] Update at November 2022.**

## Content
  - [Survey](#survey)
  - [Kernel IMC](#kernel-imc)
  - [Subspace IMC](#subspace-imc)
  - [Graph IMC](#graph-imc)
  - [Tensor IMC](#tensor-imc)
  - [Deep IMC](#deep-imc)
## Survey
|Paper|Year|Publish|
|:--|:--|:--|
|[A survey on multi-view learning](https://arxiv.org/pdf/1304.5634.pdf)|2017|IEEE transactions on artificial intelligence|
|Multi-view learning overview: Recent progress and new challenges|2017|Information Fusion|
|Multi-view clustering: A survey|2018|Big Data Mining and Analytics|
|A study of graph-based system for multi-view clustering|2019|Knowledge-Based Systems|
|An overview of recent multi-view clustering|2020|Neurocomputing|
|[A Survey on Incomplete Multiview Clustering](https://github.com/DarrenZZhang/Survey_IMC/tree/87b9775fffdfe1098f9deeea195675afaf0c6acf)|2022|IEEE TSMCA|
|Representation Learning in Multi-view Clustering: A Literature Review|2022|Data Science and Engineering|



## Kernel IMC
|Paper|Abbreviation|Year|Publish|Code|
|  :-----| :------:  | :------: | :------: | :------: |
|[Incomplete Multi-view Clustering](https://link.springer.com/content/pdf/10.1007/978-3-319-48390-0_25.pdf)|IVC|2016|-||
|[Late fusion incomplete multi-view clustering](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6494716/pdf/nihms-1010540.pdf)|LF-IMVC|2018|IEEE TPAMI|[code](https://github.com/xinwangliu/Late-Fusion-Incomplete-Multi-view-Clustering)|
|Localized Incomplete Multiple Kernel k-means||2018|IJCAI||
|Multiple kernel k-means with incomplete kernels| MKKM-IK-MK|2019|IEEE TPAMI|[code](https://github.com/wangsiwei2010/multiple_kernel_clustering_with_absent_kernel)|
|[Efficient and effective incomplete multi-view clustering](https://dl.acm.org/doi/pdf/10.1609/aaai.v33i01.33014392)|EE-IMVC|2019|AAAI||
|[Efficient and effective regularized incomplete multi-view clustering](http://www.lilyliliu.com/upload/P5f09526a86574c6d811b271d7dbff5a1.pdf)|EE-R-IMVC|2020|IEEE TPAMI|[code](https://github.com/xinwangliu/TPAMI_EEIMVC)|
|[One-Stage Incomplete Multi-view Clustering via Late Fusion](https://dl.acm.org/doi/pdf/10.1145/3474085.3475204?casa_token=TyAtxwNp_pQAAAAA:1MzpayzNojweyfN_FwYrR_i_jT-PJIblJd4rRHS7wGXnSdjcYLppI1l2P0VCNQ7Ocf0N8shkKW7_mGM)|OS-LF-IMVC|2021|ACM MM|[code](https://github.com/ethan-yizhang/OSLF-IMVC)|
|Incomplete multiple kernel alignment maximization for clustering||2021|IEEE TPAMI||
|Localized Incomplete Multiple Kernel k-Means With Matrix-Induced Regularization||2021|IEEE TCYB||
|[Dynamic Incomplete Multi-view Imputing and Clustering](https://dl.acm.org/doi/pdf/10.1145/3503161.3548245?casa_token=Q3oj24QKJlYAAAAA:YzyoTzFFgVSSV07cUZblDirzHq_c5IhQqJS6G_KKoCtteJnT-gA0wgssDo9FfGBYNU_gVtVcsEULtpo)||2022|ACM MM||
## Subspace IMC
|Paper|Abbreviation|Year|Publish|Code|
|  :-----| :------:  | :------: | :------: | :------: |
|[Partial Multi-View Clustering](https://ojs.aaai.org/index.php/AAAI/article/view/8973)|PVC|2014|AAAI|[code](https://github.com/chaytonmin/Partial-Multi-View-Clustering/tree/master/PVC)|
|[Multiple Incomplete Views Clustering via Weighted Nonnegative Matrix Factorization with $L_{21}$ Regularization](https://link.springer.com/content/pdf/10.1007/978-3-319-23528-8_20.pdf)|MIC|2015|Machine Learning and Knowledge Discovery in Databases||
|[Incomplete Multi-view Clustering via Subspace Learning](https://dl.acm.org/doi/pdf/10.1145/2806416.2806526?casa_token=t96qL3uqDTIAAAAA:3DDmY4q0GoZR-cX9yVFhwqP1HEtp4Y4xC63soeU-D4Qqf_Jnq17rbeIO9MR2GD4Ru1R-aRXD2Dnzlq8)||2015|CIKM||
|Multi-view learning with incomplete views||2015|IEEE TIP|
|[Online Multi-view Clustering with Incomplete Views](https://www.cs.uic.edu/~wshao/files/bigdata2016_paper.pdf)|OMVC|2016|IEEE International Conference on Big Data|[code](https://github.com/software-shao/online-multiview-clustering-with-incomplete-view)|
|[Incomplete multi-modal visual data grouping](https://www.ijcai.org/Proceedings/16/Papers/341.pdf)|IMG|2016|IJCAI|[code](https://github.com/hdzhao/IMG)|
|Unified subspace learning for incomplete and unlabeled multi-view data||2017|Pattern Recognition||
|[Incomplete multi-view clustering via graph regularized matrix factorization](https://openaccess.thecvf.com/content_ECCVW_2018/papers/11132/Wen_Incomplete_Multi-view_Clustering_via_Graph_Regularized_Matrix_Factorization_ECCVW_2018_paper.pdf)|IMC_GRMF|2018|ECCV|[code](https://drive.google.com/file/d/14QgLE8qc2sRum4w7Qk-0qRhGdwr2OZAi/view)|
|[Partial multi-view subspace clustering](https://dl.acm.org/doi/10.1145/3240508.3240679)||2018|ACM MM||
|[Doubly aligned incomplete multi-view clustering](https://www.ijcai.org/proceedings/2018/0313.pdf)|DAIMC|2018|IJCAI|[code](https://github.com/DarrenZZhang/Survey_IMC/tree/main/DAIMC)|
|[Joint embedding learning and low-rank approximation: A framework for incomplete multiview learning](https://arxiv.org/pdf/1812.10012.pdf)||2019|IEEE TCYB||
|[One-pass incomplete multi-view clustering](https://dl.acm.org/doi/pdf/10.1609/aaai.v33i01.33013838)|OPIMC|2019|AAAI|[code](https://github.com/DarrenZZhang/Survey_IMC/tree/main/OPIMC)|
|[Unified embedding alignment with missing views inferring for incomplete multi-view clustering](https://dl.acm.org/doi/pdf/10.1609/aaai.v33i01.33015393)|UEAF|2019|AAAI||
|[ICMSC: Incomplete cross-modal subspace clustering](https://github.com/IMKBLE/iCmSC)||2020|IEEE TIP|
|Generalized Incomplete Multi-view Clustering With Flexible Locality Structure Diffusion||2021|IEEE TCYB||
|Self-representation subspace clustering for incomplete multi-view data|IMSR|2022|ACM MM|[code](https://github.com/liujiyuan13/IMSR-code_release)|
|Highly-efficient incomplete large-scale multi-view clustering with consensus bipartite graph||2022|CVPR||
|High-order correlation preserved incomplete multi-view subspace clustering||2022|IEEE TIP||
|[Localized Sparse Incomplete Multi-view Clustering](https://arxiv.org/pdf/2208.02998.pdf)||2022|IEEE TMM||
|Incomplete multi-view clustering with cosine similarity||2022|Pattern Recognition||

## Graph IMC
|Paper|Abbreviation|Year|Publish|Code|
|  :-----| :------:  | :------: | :------: | :------: |
|[Spectral perturbation meets incomplete multi-view data](https://www.ijcai.org/proceedings/2019/0510.pdf)|PIC|2019|IJCAI|[code](https://github.com/cshaowang/pic)|
|[A Survey on Incomplete Multiview Clustering](https://www.ijcai.org/Proceedings/2019/0623.pdf)||2019|IJCAI||
|Anchors bring ease: An embarrassingly simple approach to partial multi-view clustering||2019|AAAI||
|Adaptive graph completion based incomplete multi-view clustering||2020|IEEE TMM||
|[Incomplete Multiview Spectral Clustering with Adaptive Graph Learning](http://www.yongxu.org/paper/FINALVERSION.pdf)|IMSC_AGL|2020|IEEE TCYB|[code](https://drive.google.com/file/d/1gz6oBXt1qxi1Hdz9jEn6Q42xU75dnubE/view)|
|A novel consensus learning approach to incomplete multi-view clustering||2021|Pattern Recognition||
|Incomplete multi-view clustering with joint partition and graph learning||2021|IEEE TKDE||
|Incomplete multi-view clustering with reconstructed views||2021|IEEE TKDE||
|Consensus guided incomplete multi-view spectral clustering||2021|Neural Networks||
|Refining Graph Structure for Incomplete Multi-View Clustering||2022|IEEE TNNLS||
|Auto-weighted sample-level fusion with anchors for incomplete multi-view clustering||2022|Pattern Recognition||
|Structured anchor-inferred graph learning for universal incomplete multi-view clustering||2022|World Wide Web||
|Incomplete Multi-view Clustering with Sample-level Auto-weighted Graph Fusion||2022|IEEE TKDE||


## Tensor IMC
|Paper|Abbreviation|Year|Publish|Code|
|  :-----| :------:  | :------: | :------: | :------: |
|Unified tensor framework for incomplete multi-view clustering and missing-view inferring||2021|AAAI|
|Tensor-Based Multi-View Block-Diagonal Structure Diffusion for Clustering Incomplete Multi-View Data||2021|ICME|
|Incomplete Multi-View Subspace Clustering with Low-Rank Tensor||2021|ICASSP|

## Deep IMC
|Paper|Abbreviation|Year|Publish|Code|
|  :-----| :------:  | :------: | :------: | :------: |
|Incomplete multi-view clustering via deep semantic mapping||2018|Neurocomputing||
|[Partial Multi-view Clustering via Consistent GAN](https://ieeexplore.ieee.org/abstract/document/8594983/)||2018|ICDM||[code](https://github.com/IMKBLE/PVC-GAN)|
|[Adversarial Incomplete Multi-view Clustering](https://www.ijcai.org/proceedings/2019/0546.pdf)|AIMC|2019|IJCAI||
|CPM-Nets: Cross partial multi-view networks||2019|NeurIPS||
|Deep incomplete multi-view multiple clusterings||2020|ICDM||
|[CDIMC-net: Cognitive Deep Incomplete Multi-view Clustering Network](https://drive.google.com/file/d/1k6M4kw1gKrjAyLdVpiV8wf7rClt_8W3Q/view)|CDIMC-net|2020|IJCAI|[code](https://drive.google.com/file/d/1oOAWuRBicme0M8YTm1R3Hg8HQ2ydwzfM/view)|
|Structural Deep Incomplete Multi-view Clustering Network||2021|CIKM||
|[Clustering-Induced Adaptive Structure Enhancing Network for Incomplete Multi-View Data](https://www.ijcai.org/proceedings/2021/0445.pdf)|CASEN|2021|IJCAI||
Generative partial multi-view clustering with adaptive fusion and cycle consistency||2021|IEEE TIP||
|[COMPLETER: Incomplete multi-view clustering via contrastive prediction](https://openaccess.thecvf.com/content/CVPR2021/papers/Lin_COMPLETER_Incomplete_Multi-View_Clustering_via_Contrastive_Prediction_CVPR_2021_paper.pdf)|COMPLETER|2021|CVPR|[code](https://github.com/XLearning-SCU/2021-CVPR-Completer)|
|[Incomplete multi-view clustering via cross-view relation transfer](https://arxiv.org/pdf/2112.00739.pdf)||2022|IEEE TCSVT||
|[Robust Diversified Graph Contrastive Network for Incomplete Multi-view Clustering](https://dl.acm.org/doi/pdf/10.1145/3503161.3547894?casa_token=n8zDt6DzIqsAAAAA:fvPNViJhY4psiEbsATlDAtoCbGc3akUpY2UPvTX1X8rdepg-PQlJ4M1ja1gqydqfei11orp_JYVz8CA)||2022|ACM MM||
|Group Correspondence: A Statistical Perspective for Incomplete Multi-View Clustering Augmentation||2022|ICME||
|Deep Incomplete Multi-view Clustering via Mining Cluster Complementarity|DIMVC|2022|AAAI|[TensorFlow](https://github.com/SubmissionsIn/DIMVC)|
|Robust multi-view clustering with incomplete information|SURE|2022|IEEE TPAMI|[PyTorch](https://github.com/XLearning-SCU/2022-TPAMI-SURE)|
|[Dual contrastive prediction for incomplete multi-view representation learning](http://pengxi.me/wp-content/uploads/2022/08/DCP.pdf)|DCP|2022|IEEE TPAMI|[code](https://github.com/XLearning-SCU/2022-TPAMI-DCP/tree/d4eae074a2b420e6d28f04cc68b769db07b814bc)|
|Graph Contrastive Partial Multi-View Clustering|AGCL|2022|IEEE TMM|[code](https://github.com/wangemm/AGCL-TMM-2022)|
|[Dimc-net: Deep incomplete multi-view clustering network](https://dl.acm.org/doi/pdf/10.1145/3394171.3413807)|DIMC-net|2020|ACM MM||
|[Deep safe incomplete multi-view clustering: Theorem and algorithm](https://proceedings.mlr.press/v162/tang22c/tang22c.pdf)|DSIMVC|2022|ICML|[code](https://github.com/Gasteinh/DSIMVC)|




---

###### TIPS
- If you find this repository useful to your research or work, it is really appreciate to star this repository. 
- We are looking forward to any comments or discussions or contributions on this topic. :)