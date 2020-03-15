+++
abstract = "Most software defect prediction approaches are trained and applied on data from the same project. However, often a new project does not have enough training data. Cross-project defect prediction, which uses data from other projects to predict defects in a particular project, provides a new perspective to defect prediction. In this work, we propose a HYbrid moDel Reconstruction Approach (HYDRA) for cross-project defect prediction, which includes two phases: genetic algorithm (GA) phase and ensemble learning (EL) phase. These two phases create a massive composition of classifiers. To examine the benefits of HYDRA, we perform experiments on 29 datasets from the PROMISE repository which contains a total of 11,196 instances (i.e., Java classes) labeled as defective or clean. We experiment with logistic regression as the underlying classification algorithm of HYDRA. We compare our approach with the most recently proposed cross-project defect prediction approaches: TCA+ by Nam et al., Peters filter by Peters et al., GP by Liu et al., MO by Canfora et al., and CODEP by Panichella et al. Our results show that HYDRA achieves an average F1-score of 0.544. On average, across the 29 datasets, these results correspond to an improvement in the F1-scores of 26.22 , 34.99, 47.43, 28.61, and 30.14 percent over TCA+, Peters filter, GP, MO, and CODEP, respectively. In addition, HYDRA on average can discover 33 percent of all bugs if developers inspect the top 20 percent lines of code, which improves the best baseline approach (TCA+) by 44.41 percent. We also find that HYDRA improves the F1-score of Zero-R which predict all the instances to be defective by 5.42 percent, but improves Zero-R by 58.65 percent when inspecting the top 20 percent lines of code. In practice, Zero-R can be hard to use since it simply predicts all of the instances to be defective, and thus developers have to inspect all of the instances to find the defective ones. Moreover, we notice the improvement of HYDRA over other baseline approaches in terms of F1-score and when inspecting the top 20 percent lines of code are substantial, and in most cases the improvements are significant and have large effect sizes across the 29 datasets."
authors = ["Xinyu Wang", "Nachiappan Nagappan", "Sinno Jialin Pan", "David Lo", "Xin Xia"]
date = 2016-10-04T14:00:00Z
image_preview = ""
math = false
publication = "In *IEEE Transactions on Software Engineering*"
publication_short = "In *IEEE Transactions on Software Engineering*"
publication_types = ["2"]
selected = true
title = "HYDRA: Massively Compositional Model for Cross-Project Defect Prediction"
url_pdf = "https://www.computer.org/csdl/journal/ts/2016/10/07435328/13rRUwInuY1"

+++
