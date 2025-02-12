---
title: "Predictions on multi-class terminal ballistics datasets using conditional Generative Adversarial Networks"
date: 2022-10-01
categories:
  - Publication
classes: wide
---

## 2022 - Neural Networks

### Abstract

Ballistic impacts are a primary risk in both civil and military defence applications, where successfully predicting the dynamic response of a material or structure to impact crucial to the design of safe and fit-for-purpose protective structures. This study proposes a conditional Generative Adversarial Network (cGAN) architecture that can learn directly from available ballistic data and can be conditioned on additional information, such as class labels, to govern its output. A single Multi-Layer Perceptron (MLP) cGAN architecture is trained on a multi-class ballistic training set consisting of 10 classes labelled 0-9 where each class refers to a ballistic curve with a different ballistic limit velocity, v_bl. A total of 5 models are trained on datasets consisting of 5, 10, 15, 20 and 25 samples within each class. For integer class labels 0-9, all cGAN models successfully predict the v_bl with a maximum error of 4.12%. Additionally, for non-integer class labels between 0-9 the v_bl predictions are similar despite not explicitly appearing in the training set. Moreover, each cGAN model is challenged to generate new samples for class labels that exist beyond the scope of the training set for class labels between 9-20. Four of the models predict the v_bl with an error of less than 1.5% in all cases. This study showcases how a cGAN model can learn directly from a multi-class ballistic dataset and generate additional samples representative of that data for classes that do not appear explicitly in the training set.


[<em>Link to Publication</em>](https://www.sciencedirect.com/science/article/pii/S0893608022002994)