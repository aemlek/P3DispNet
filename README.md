# P3SNet: Parallel Pyramid Pooling Stereo Network

This repository contains the code (in PyTorch) for "[P3SNet: Parallel Pyramid Pooling Stereo Network]" paper   

### Reference
```

```

## Contents

1. [Introduction](#introduction)
2. [Usage](#usage)
3. [Results](#results)
4. [Contacts](#contacts)

## Introduction

In autonomous driving and advanced driver assistance systems (ADAS), stereo matching is a challenging research topic. Recent work has shown that high accuracy disparity maps can be obtained with end-to-end training with the help of deep convolutional neural networks from stereo images. However, many of these methods suffer from long run-time for real-time studies. Therefore, in this paper, we introduce P3SNet, which can generate both real-time results and  competitive disparity maps to the state-of-the-art. P3SNet architecture consists of two main modules: parallel pyramid pooling and hierarchical disparity aggregation. The parallel pyramid pooling structure makes it possible to obtain local and global information intensively from its multi-scale features. The hierarchical disparity aggregation provides multi-scale disparity maps by using a coarse-to-fine training strategy with the help of the costs obtained from multi-scale features. The proposed approach was evaluated on several benchmark datasets. The results on all datasets showed that the proposed P3SNet achieved better or competitive results while having lower runtime.

## Usage

## Results

#### Evaluations on SceneFlow Dataset

![Image](https://github.com/aemlek/P3SNet/blob/main/figure/table-4.png "KITTI20215_results")



#### Evaluations on KITTI 2012 and KITTI 2015 benchmarks

![Image](https://github.com/aemlek/P3SNet/blob/main/figure/table-5.png "KITTI20215_results")

![Image](https://github.com/aemlek/P3SNet/blob/main/figure/KITTI20212_results.png "KITTI20212_results")

![Image](https://github.com/aemlek/P3SNet/blob/main/figure/KITTI20215_results.png "KITTI20215_results")


## Contacts
