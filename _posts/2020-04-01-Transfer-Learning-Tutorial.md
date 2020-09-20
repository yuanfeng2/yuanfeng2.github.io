---
layout: post
title: Transfer-Learning-Tutorial
subtitle: 
cover-img: /assets/img/tl.png
thumbnail-img: /assets/img/tl.png
share-img: /assets/img/path.jpg
---

## Summary

In the supervised learning context, deep neural networks have become more and more accurate in recent years. Convolutional neural networks using a residual learning network are particularly good at finding the optimal model parameters while improving accuracy. However, it is not possible to apply these deep models into a different situation or phenomena other than what they were trained and designed for. It is important to have this flexibility in real-world scenarios where we rarely encounter data structured in the same way as our training data. Transfer learning allows us to transfer some of the information learned from an ideal situation into a different and related situation for which our data is more limited.

<div align="center">
<img src="https://raw.githubusercontent.com/yuanfeng2/yuanfeng2.github.io/master/assets/img/ant.png" >
  <p>Sample Images from the hymenoptera_data dataset</p>
</div>


In this paper we will define a common transfer learning technique for computer vision and image classification problem: inductive transfer learning using feature extraction or embedding using the hymenoptera_data dataset. By using a model previously trained on a robust training dataset, we can take advantage of its optimal parameters as a way to extract features for new data, reducing training time and improving performance considerably. First, we shall implement this method classically. Later, we will discuss one particular cutting-edge approach to this problem using quantum computing for a hybrid transfer learning method. In this approach, we replace a neural network’s output layer with a dressed quantum circuit that we then train for our target domain and task.

## Results

<div align="center">
<img src="https://raw.githubusercontent.com/yuanfeng2/yuanfeng2.github.io/master/assets/img/re.png" >
  <p>Model Performance</p>
</div>

Transfer learning techniques can improve significantly on similar models built from scratch. Training time can be reduced by one half with classical parameter transfer methods, and performance in terms of AUC, AP and accuracy can also be improved significantly. These results can be attained with a minimum amount of training data as long as there is a pre-existing model trained in a similar domain. Both the classical and the CQ hybrid approach accomplished very similar performance in terms of accuracy and AUC. This both highlights the advantages of transfer learning and positive outlook of novel quantum methods to perform classifications. 

The project report can be found [here](https://github.com/yuanfeng2/Transfer_Learning_Tutorial).
