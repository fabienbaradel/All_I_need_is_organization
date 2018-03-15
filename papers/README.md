# My favorites papers

## Reasoning
* [Visual Interaction Networks](https://arxiv.org/abs/1706.01433) - Waters et al. - NIPS 2017 - Deepmind
    * Prediction of future state of physical engines
* [A Simple Neural Network for Relational Reasoning](https://arxiv.org/pdf/1706.01427.pdf) - Santoro et al - NIPS 2017 - Deepmind (P. Battaglia & T. Lillicrap)
    * Oral presentation at NIPS - simple network computation in parellel object pairwise relation an sum for aggregate them - Objects are cell from feature maps
* [FiLM: Visual Reasoning with a General Conditioning Layer](https://arxiv.org/pdf/1709.07871.pdf) - Perez et al. - ICLR 2017 - MILA (A. Courville)
    * Feature-wise affine transformation based on conditioning information - VQA task - CLEVR
* [Relational Neural Expectation Maximization: Unsupervised Discovery of Objects and their Interactions](https://openreview.net/forum?id=ryH20GbRW) - Steenkiste et al. ICLR 2018 - IDISA
    * Extension of "RN" for discovering objects and their interactions for virtual environments.
* [Temporal Reasoning in Videos](https://arxiv.org/abs/1711.08496) - Zhou et al - arXiv 2017 - MIT
    * Extension of "RN" for video classification by setting frames as objects described by their 2D-CNN feature vector.
* [Compositional Attention Networks for Machine Reasoning](https://openreview.net/forum?id=S1Euwz-Rb) Hudson et al. - ICLR 18 - Standford
    * VQA using Memory, Attention, and Control (MAC) operations through an external memory, computationally efficient
* [DeepSets](https://papers.nips.cc/paper/6931-deep-sets) - Zahheer - NIPS 2017 - Carnegie Mellon University
    * Extraction of information from a set of vectors invariant to permutations
* [PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation](https://arxiv.org/abs/1612.00593)
    * Reasoning from 3D points clouds - Similar to DeepSets - Empirical & Theoritical justifications
* [NOT-SO-CLEVR: Visual Relations strain feedforward neural networks](https://arxiv.org/abs/1802.03390) - Ricci et al. - arXiv 2017 - Brown Univeristy (. Serre)
    * Study of the limitations of CLEVR dataset and the new introduced RN module - Link with neuroscience and ren-entrant/feedback signal for visual relation
* [SCAN: Learning Abstract Hierarchical
Compositional Visual Concepts](https://arxiv.org/abs/1707.03389) - Higgings et al. - NIPS 2017 - Deepmind (D. Hassabis)
    * Learn of a disentangle representation of the latent structure of the visual world and then SCAN (Symbol-Concept Association Network)
* [Transparency by Design: Closing the Gap Between Performance and Interpretability in Visual Reasoning](https://arxiv.org/abs/1803.05268) - Mascharka et al - CVPR 2018 - MIT


## Causality
* [Discovering Causal Signals in Images](https://arxiv.org/abs/1605.08179) - Lopez-Paz et al. - CVPR 2017 - Facebook (L. Bottou)
    * Study about causal and anticausal signals in images using annotations from object detection dataset
* [Seeing the Arrow of Time](http://openaccess.thecvf.com/content_cvpr_2014/html/Pickup_Seeing_the_Arrow_2014_CVPR_paper.html) -  Pickup et al. - CVPR 2014 - Oxford VGG (Zisserman)
* [Counterfactual Reasoning and Learning Systems](https://arxiv.org/abs/1209.2355) - Bottou et al - JMLR 2012 - Microsoft
    * **to read!**
## Cognition
* [Flexible visual processing of spatial relationships](https://pdfs.semanticscholar.org/0c95/8101f639f11c3b635fdb4d5c5aa1169368ca.pdf) - Franconeri et al. - ???
    * The representation of the visual relationship in process in a sequential manner rather than in parrallel
    
## Object Detection - Tracking
* [R-FCN](https://arxiv.org/abs/1605.06409) - Dai et al - CVPR 2016 - Microsoft (K.He)
    * Fully convolutional network for object detection
* [Detect to Track and Track to Detect](https://arxiv.org/abs/1710.03958) -  Feichtenhofer et al. - ICCV 2017 - Graz (A. Pinz & A. Zisserman)
    * Cross correlation from feature maps - no 3D CNN

## Activity Understanding
* [Structure Inference Machines: Recurrent Neural Networks for Analyzing
Relations in Group Activity Recognition](https://arxiv.org/abs/1511.04196) - Deng et al - CVPR 2016 - Simon Fraser University (G. Mori)
    * Gating mechanism allowing to take into account only certain relations between people - Fully differentiable

## Unsupervised Learning in Videos
* [Rank Pooling for Action Recognition](https://arxiv.org/abs/1512.01848) - Fernando et al. - TPAMI 2016
    * Learning from unlabelled videos via ranking frames in the temporal domain
* [Unsupervised Representation Learning by Sorting Sequences](https://arxiv.org/abs/1708.01246) - Lee et al - ICCV 2017
    * Sorting set of 4 sampled frames to build a strong video system in a unsupervised way  
    
    
## Action Recogntion
* [A Closer Look at Spatiotemporal Convolutions for Action Recognition](https://arxiv.org/abs/1711.11248) - Tran et al. - arXiv 2017 - Facebook (Y. LeCun)
* [VideoLSTM Convolves, Attends and Flows
for Action Recognition](https://arxiv.org/abs/1607.01794) - Li et al. - ECCV 2016 - University of Amsterdam
    * Everything is in the title - Learn from feature maps instead of learning directly from feature representation



## Sequence Modeling
* [An Empirical Evaluation of Generic Convolutional and Recurrent Networks for Sequence Modeling](https://arxiv.org/abs/1803.01271) -  Bai et al. - arXiv 2018 -  Carnegie Mellon University
    * Study of Convolution vs RNN on sequence - [code available](https://github.com/locuslab/TCN/tree/master/TCN) - dilated and causal convolution are important

## Geometry matching
* [Convolutional neural network architecture for geometric matching](https://arxiv.org/abs/1703.05593) - Rocco et al - ICCV 2017 - ENS/INRIA (J. Sivic)
    * Finding the pix to pix matching between two RGB images using supervised learning
* [End-to-end weakly-supervised semantic alignment](https://arxiv.org/abs/1712.06861) -  Rocco et al - CVPR 2018 - ENS/INRIA (P. Sivic)
    * Align two images on a weakly supervised manner using RANSAC

## Limitations of Deep Learning
* [Measuring the tendency of CNNs to Learn Surface Statistical Regularities](https://arxiv.org/abs/1711.11561) - Jo et al - arXiv 2017 - MILA (J. Bengio)
    * CNNs tend to learn surface statistical regularities in the dataset rather than higher-level abstract concepts - Study by applying Fourir transformation on dataset
 

## Extra --- High-Level Concepts
* [Arrow of time](https://en.wikipedia.org/wiki/Arrow_of_time#The_causal_arrow_of_time)
    * Introduced by Arthur Eddington in 1927 involving the "one-way direction" or "asymmetry" of time
    * Unsolved general physics question
