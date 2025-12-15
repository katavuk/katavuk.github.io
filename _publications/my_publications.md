---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Provable Recovery of Locally Important Signed Features and Interactions from Random Forest
------
(2025+)

**Abstract:** Feature and Interaction Importance (FII) methods are essential in supervised
learning for assessing the relevance of input variables and their interactions
in complex prediction models. In many domains, such as personalized medicine,
local interpretations for individual predictions are often required, rather
than global scores summarizing overall feature importance. Random Forests (RFs)
are widely used in these settings, and existing interpretability methods
typically exploit tree structures and split statistics to provide
model-specific insights. However, theoretical understanding of local FII
methods for RF remains limited, making it unclear how to interpret high
importance scores for individual predictions. We propose a novel, local,
model-specific FII method that identifies frequent co-occurrences of features
along decision paths, combining global patterns with those observed on paths
specific to a given test point. We prove that our method consistently recovers
the true local signal features and their interactions under a Locally Spike
Sparse (LSS) model and also identifies whether large or small feature values
drive a prediction. We illustrate the usefulness of our method and theoretical
results through simulation studies and a real-world data example.

Download paper [here](https://arxiv.org/abs/2512.11081)


Power of weighted test statistics for structural change in time series
------
Published in *Electronic Journal of Statistics*, 2024

**Abstract:** We investigate the power of some common change-point tests as a function of the location of the change-point. The test statistics are maxima of weighted U-statistics, with the CUSUM test and the Wilcoxon change-point test as special examples. We study the power under local alternatives, where we vary both the change-point’s location and the magnitude of the change. We quantify in which way weighted versions of the tests exhibit greater power when the change occurs near the beginning or the end of the time interval, while losing power against changes located in the center.

Download paper [here](https://projecteuclid.org/journals/electronic-journal-of-statistics/volume-18/issue-1/Power-of-weighted-test-statistics-for-structural-change-in-time/10.1214/24-EJS2248.full)


Change-point detection based on weighted two-sample U-statistics
------
Published in *Electronic Journal of Statistics*, 2022

**Abstract:** We investigate the large-sample behavior of change-point tests based on weighted two-sample U-statistics, in the case of short-range dependent data. Under some mild mixing conditions, we establish convergence of the test statistic to an extreme value distribution. A simulation study shows that the weighted tests are superior to the non-weighted versions when the change-point occurs near the boundary of the time interval, while they loose power in the center.

Download paper [here](https://projecteuclid.org/journals/electronic-journal-of-statistics/volume-16/issue-1)
