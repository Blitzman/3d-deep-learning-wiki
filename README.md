# 3D Deep Learning

## Cloning the wiki
```
$ git clone git@github.com:Blitzman/3d-deep-learning-wiki.git
```

## Interesting Reads and Links

- [Awesome Deep Vision](https://github.com/kjw0612/awesome-deep-vision). A curated list of deep learning resources for computer vision.
- [Deep down the rabbit hole: CVPR 2015 and beyond](http://www.computervisionblog.com/2015/06/deep-down-rabbit-hole-cvpr-2015-and.html). Insightful review of the CVPR2015, including ConvNets, Torch vs Caffe, object detectors, and ArXiv publishing.
- [CVPR2015 recap and where we are going](http://zoyathinks.blogspot.com.es/2015/06/cvpr-recap-and-where-were-going.html). Nice summary of the whole conference, as well as a cool summary/highlights [document](http://web.mit.edu/zoya/www/CVPR2015brief.pdf) of some selected papers.

### NVIDIA Deep Learning Course

- Introduction to Deep Learning. [Video](https://www.youtube.com/watch?v=6eBpjEdgSm0)/[Slides](http://on-demand.gputechconf.com/gtc/2015/webinar/deep-learning-course/intro-to-deep-learning.pdf)/[Hands-on lab](https://nvidia.qwiklab.com/focuses/preview/102)/[Office hours Q&A](http://on-demand.gputechconf.com/gtc/2015/webinar/deep-learning-course/intro-to-deep-learning-questions-answers.pdf).
- Getting started with the Caffe Framework. [Video](https://www.youtube.com/watch?v=rvMVqPsXL10)/[Slides](http://on-demand.gputechconf.com/gtc/2015/webinar/deep-learning-course/getting-started-with-caffe.pdf)/[Hands-on lab](https://nvidia.qwiklab.com/focuses/preview/136)/[Office hours Q&A](http://on-demand.gputechconf.com/gtc/2015/webinar/deep-learning-course/getting-started-with-caffe-questions-answers.pdf).

## Theoretical Background

### Convolutional Neural Networks (CNN)

Check out the nice Stanford CS course titled [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.github.io/). There is a nice lecture on [Convolutional Neural Networks (CNNs / ConvNets)](http://cs231n.github.io/convolutional-networks/) which provides an architectural overview as well as detailed explanations of the different layers and popular architectures.

A nice collection of final reports by the course students is available [here](http://cs231n.stanford.edu/reports.html). The following ones are specially remarkable:

- [Tiny ImageNet Challenge - Dissection of a convolutional neural network](http://cs231n.stanford.edu/reports/jbboin_finalreport.pdf). Explains a simple architecture and dissects it with useful insight. Besides, the figures are nice and can serve as inspiration.
- [Learning 3D Object Orientations From Synthetic Images](http://cs231n.stanford.edu/reports/rqi_final_report.pdf). Cool approach to mix 3D training data (which is converted to 2D) with 2D input images for object orientation detection.
- [Convolutional Neural Networks for Fashion Classification and Object Detection](http://cs231n.stanford.edu/reports/BLAO_KJAG_CS231N_FinalPaperFashionClassification.pdf). Multiple object detection in the same image, instead of single object per image.

### Deep Neural Networks (DNN)

## Frameworks

### Torch

[Torch](http://torch.ch/) is a scientific computing framework which supports a wide variety of machine learning algorithms. Characterized by an easy use thanks to its LuaJIT scripting language. It also features significant efficiency due to the underlying CUDA/C implementation.

- [GitHub repository](https://github.com/torch/torch7)
- [Convolutional Neural Network example with Lua](https://github.com/nicholas-leonard/dp/blob/master/examples/convolutionneuralnetwork.lua)
- [Object detection with Recursive Convolutional Neural Network and Lua](https://github.com/fmassa/object-detection.torch)

### Caffe

[Caffe](https://github.com/BVLC/caffe/) is a deep learning framework developed by the [Berkeley Vision and Learning Center (BVLC)](http://bvlc.eecs.berkeley.edu/). It is implemented mainly in C++ and supports GPU computing thanks to CUDA.

- [GitHub repository](https://github.com/BVLC/caffe/)
- [arXiv / ACM MM ‘14 paper. Caffe: Convolutional Architecture for Fast Feature Embedding](http://arxiv.org/abs/1408.5093)
- [Hands-On Tutorial: Deep Learning for Vision with Caffe](https://docs.google.com/presentation/d/1UeKXVgRvvxg9OUdh_UiC5G71UMscNPlvArsWER41PsU/edit#slide=id.p)

### Theano
