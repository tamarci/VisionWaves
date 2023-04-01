---
layout: post
title:  "Improving efficiency of lung cancer detection methods on CT"
date:   2022-12-20 01:30:13 +0800
categories: Biomedical
tags: biomedical publication
---
**Bachelor Thesis**

In this thesis, I will process and analyse computed tomography lung images
using different image processing techniques. The thesis focuses on tumour
detection within image processing.
The topic is challenging due to the diverse shape and small size of tumours
in the lung, and therefore I put a strong emphasis on designing an appropriate
database. To perform this task, I use LIDC/IDRI dataset, which contains 2269,
larger than 3 mm tumours annotated as positive and 400 000 lung sections annotated
as negative training samples. Using the data augmentation techniques I have
presented, I increased the number of positive training data to 7745 and further
improved the ratio by applying traditionel data augmentation methods.
In my solution, I present and implement a U-net type neural networks. The
training of the three-dimensional segmentation net was performed using small
cubes of 64 mm x 64 mm x 64 mm, which were cut out from lung images.
By using my proposed pre-processing improvement methods, I was able to
reduce the loss during training and improve the training result.
At the end of this thesis, I will demonstrate different image masking
techniques using my user interface and experiment to improve masking using
different morphological operations.