# MScThesis

# Improving Object Detection through Contextual Rescoring

Thesis to obtain the Master of Science Degree in Electrical and Computer Engineering at Instituto Superior Técnico, ULisboa
November 2019
### Author: Lourenço Vaz Pato
#### Supervisors: Pedro M. Q. Aguiar, Renato Negrinho

**[[PDF](https://github.com/LourencoVazPato/MScThesis/blob/master/Thesis.pdf)]** **[[arXiv](https://arxiv.org/abs/1912.12290)]** **[[CVPR2020]()]** **[[Code](https://github.com/LourencoVazPato/seeing-without-looking)]**

**Abstract:**
Current state-of-the-art object detectors rely on a two-stage approach: first, identify regions in the image that are likely to contain objects, then predict the object class inside the regions. Class predictions are made independently from other regions, thus having an insufficient use of context that can be inferred from the presence of other objects. Sharing this information would clearly improve the results of the recognition problem since there are strong dependencies between co-occurrences of objects in the same image (e.g., an image is unlikely to contain both a couch and a horse).

We tackle the problem of incorporating context in object detection. We analyse the errors that current detectors make and what sources of context can be used to mitigate these errors. To incorporate the information relative to object co-occurrences, we propose a bidirectional recurrent neural network with attention model that learns a rescoring rule, given a set of object detections from an existing detection architecture. The training target we propose is the set of rescored confidences that maximises Average Precision for the given set of detections. Through experiments in the MS COCO dataset, our model obtains consistent improvements in Average Precision that range from 0.5 to 1, across different convolutional backbones (ResNet-50 and ResNet-101) and different architectures (Cascade R-CNN and Faster R-CNN).

**Keywords:** Deep Learning, Computer Vision, Object Detection, Average Precision, Context, Recurrent Neural Networks, Attention Mechanisms
