
# TopFilter
This repository contains the source code implementation of TopFilter and the datasets used to replicate the experimental results of our paper which has been accepted for publication in the Proceedings of the International Symposium on Empirical Software Engineering and Measurement (ESEM 2020):

_TopFilter: An Approach to Recommend Relevant GitHub Topics_

A pre-print version of the paper is available <a href="https://github.com/MDEGroup/TopFilter/blob/master/ESEM2020.pdf"> here</a>.



## Introduction

In the context of software development, GitHub has been at the forefront of platforms to store, analyze and maintain a large number of software repositories. Topics have been introduced by GitHub as an effective 
method to annotate stored repositories. However, labeling GitHub repositories should be carefully conducted to avoid adverse effects on project popularity and reachability. We present TopFilter, a novel approach to assist open source 
software developers in selecting suitable topics for GitHub repositories being 
created.
We built a project-topic matrix and applied a syntactic-based similarity function to recommend missing topics by representing repositories and related topics in a graph. The ten-fold cross-validation methodology has been used to assess the performance of TopFilter by considering different 
metrics, i.e., success rate, precision, recall, and catalog coverage. The results show that TopFilter recommends good topics depending on different factors, i.e., collaborative filtering settings, 
considered datasets, and pre-processing activities. Moreover, TopFilter can be combined with a state-of-the-art topic recommender system (i.e., MNB 
network) to improve the overall prediction performance. Our results confirm that collaborative filtering techniques can successfully be used to provide relevant topics for GitHub 
repositories. Moreover, TopFilter can gain a significant boost in prediction performances by employing the outcomes obtained by the MNB network as its initial set of topics.

