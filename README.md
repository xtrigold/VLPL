# VLPL: Vision Language Pseudo Label for Multi-label Learning with Single Positive Labels
This is the official Pytorch implementation paper "VLPL: Vision Language Pseudo Label for Multi-label Learning with Single Positive Labels".

Authors: Xin Xing, Zhexiao Xiong, Abby Stylianou, Liyu Gong, and Nathan Jacobs

Corresponding author: Xin Xing (xxi242@g.uky.edu)
###Abstract
We address the task of multi-label image classification, which is essentially single-label image classification without the constraint that there is a single class present in the image. This task is similar to object detection, without the need to localize or count individual objects. Unfortunately, much like object detection, obtaining high-quality multi-label annotations is time-consuming and error-prone. To address this challenge, we consider the single-positive label setting, in which only a single positive class is annotated, even when multiple classes are present in a given image. The current state-of-the-art (SOTA) methods for this setting mainly propose novel loss functions to improve model performance. Several works have attempted to use pseudo-labels, but these approaches haven’t worked well. We propose a novel model called Vision-Language Pseudo-Labeling (VLPL) which uses a vision-language model to suggest strong positive and negative pseudo-labels. We demonstrate the effectiveness of the proposed VLPL model on four popular benchmarks: Pascal VOC, MS-COCO, NUS-WIDE, and CUB-Birds datasets. The results of VLPL outperform several strong baselines and indicate the effectiveness of the proposed approach. Furthermore, we explore the backbone architecture and outperform the SOTA method by 5.4% on Pascal VOC, 15.6% on MS-COCO, 15.2% on NUS-WIDE, and 11.3% on CUB-Birds.

## Prerequisites:


## Workflow:


## Data:
### Downloading
1. MSCOCO：
 
The dataset can be downloaded from the official website [link](https://cocodataset.org/#download). The same as the previous works, we use the COCO2014 for train/val processing. 

2. PASCAL VOC2007：

The dataset can be downloaded from the official website [link](http://host.robots.ox.ac.uk/pascal/VOC/voc2007/).

3. NUS-WIDE：

4. CUB
### Data Preprocessing:   

## Implementation:

## Results:

## Acknowledgement:
Many thanks to the authors of [single-positive-multi-label](https://github.com/elijahcole/single-positive-multi-label) and [SPML-AckTheUnknown
](https://github.com/Correr-Zhou/SPML-AckTheUnknown). Our scripts are highly based on their scripts.

