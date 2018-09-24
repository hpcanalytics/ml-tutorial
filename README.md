% ### Welcome to the SPIDAL Image Processing and Optimization Library %

# Welcome

This site features documentation on the image processing and optimization routines available in SPIDAL. In addition to information about how to use the libraries themselves, we include background information about what these routines do, how they work, and when to use them, and show examples of their use on real problems.

# Contents

You can use this resource in several different ways:

* If you have a problem to solve and need to choose a model or algorithm see [Documentation by Problem Type].

* If you'd like to learn more about a particular model, see [Documentation by Models].

* If you'd like to learn more about a particular algorithm, see [Documentation by Algorithms](applications.html).

* If you'd like to see how to apply SPIDAL algorithsm to real problems, see [Exemplar Applications].


# Exemplar applications

## 3D Reconstruction of Polar Ice

![](http://vision.soic.indiana.edu/papers/thumbs/icesurface2017icip-thumb.png)

#### Reconstructs the three-dimensional surface of bedrock under polar ice using tomographic slices from ground-penetrating radar echograms.


* [Research paper (IEEE International Conference on Image Processing 2017)](http://vision.soic.indiana.edu/papers/icesurface2017icip.pdf)
* [Research project website](http://vision.soic.indiana.edu/projects/icelayers/)
* Technologies: Image reconstruction, image recognition, discrete optimization, probabilistic inference
* Models: Markov Random Fields
* Algorithms: Loopy Belief Propagation, Tree-Reweighted Message Passing (TRW-S)


## Segmentation of Radar Echograms

![](http://vision.soic.indiana.edu/papers/thumbs/icelayers2014icip-thumb.png)

#### Segments location bedrock, ice, and air in radar echograms of polar ice.

* [Research paper (IEEE International Conference on Pattern Recognition 2012)](http://vision.soic.indiana.edu/papers/icesheets2012icpr.pdf)
* [Research project website](http://vision.soic.indiana.edu/projects/icelayers/)
* Technologies: Image segmentation, discrete optimization, probabilistic inference
* Models: Hidden Markov Models
* Algorithms: Viterbi

#### Identifies layer boundaries in radar echograms, including "soft" confidence bounds on layer locations.

* [Research paper (IEEE International Conference on Image Processing 2014)](http://vision.soic.indiana.edu/papers/icelayers2014icip.pdf)
* [Research project website](http://vision.soic.indiana.edu/projects/icelayers/)
* Technologies: Image segmentation, discrete optimization, probabilistic inference
* Models: Hidden Markov Models, Markov Random Fields
* Algorithms: Markov Chain Monte Carlo (MCMC)

## 3D Reconstruction of Landmarks from Social Media images


![](http://vision.soic.indiana.edu/papers/thumbs/sfm2011cvpr-thumb.png)


#### Creates three-dimensional reconstructions of buildings and other landmarks from images downloaded from social media.

* [Research paper (IEEE Transactions on Pattern Analysis and Machine Intelligence 2013)](http://vision.soic.indiana.edu/papers/disco2013pami.pdf)
* [Research project website](http://vision.soic.indiana.edu/disco/)
* Technologies: Discrete optimization, continuous optimization, image feature point extraction
* Models: Mark Random Fields, Non-linear Least Squares
* Algorithms: Loopy Belief Propagation, Levenberg-Marquardt, Scale Invariant Feature Transforms

## Multi-modal Photo Clustering

![](http://vision.soic.indiana.edu/papers/thumbs/multimodal2014cvpr-thumb.png)

#### Clusters large-scale collections of images by combining visual, temporal, spatial, and textual features.

* [Research paper (IEEE Computer Vision and Pattern Recognition 2014)](http://vision.soic.indiana.edu/papers/multimodal2014cvpr.pdf)
* Technologies: Clustering, discrete optimization, image feature  extraction
* Models: Markov Random Fields, Scale Invariant Feature Transforms, Bag-of-words image features
* Algorithms: Tree-reweighted Message Passing, K-means, Scale Invariant Feature Transforms

#### Organizes and visualizes social media images using multimodal features.

* [Research paper (World Wide Web Conference 2009)](http://vision.soic.indiana.edu/papers/mapping2009www.pdf)
* [Research project website](http://www.cs.indiana.edu/~djcran/photomap/)
* Technologies: Clustering, image feature extraction
* Models: Bag-of-words features, Support vector machines
* Algorithms: K-means, Mean shift

## Photo segmentation

![](http://vision.soic.indiana.edu/papers/thumbs/mcl2016nips-thumb.png)

#### Produces multiple diverse candidate solutions for pixel-level semantic photo labeling.

* [Research paper (Neural Information Processing Systems 2016)](http://vision.soic.indiana.edu/papers/mcl2016nips.pdf)
* Technologies: Segmentation, deep learning, discrete optimization
* Models: Markov Random Fields, Deep Neural Networks
* Algorithms: Gradient descent, Tree-reweighted Message Passing


## Image recognition

![](http://vision.soic.indiana.edu/papers/thumbs/landmarks2015book-thumb.png)

#### Estimates where on Earth a photo was taken using visual, textual, and temporal features.

* [Research paper (Book Chapter)](http://vision.soic.indiana.edu/papers/landmarks2015book.pdf)
* Technologies: Recognition, deep learning, discrete optimization, continuous optimization, image feature extraction
* Models: Hidden Markov Models, Deep Neural Networks, Support Vector Machines, Bag-of-words
* Algorithms: Viterbi, Gradient Descent, k-means clustering, k-nearest neighbors


## Image captioning

![](http://vision.soic.indiana.edu/papers/thumbs/deepdiary2016eccvw-thumb.png)

#### Automatically produces diverse captions to describe an image.

* [Research paper (ECCV Workshop 2016)](http://vision.soic.indiana.edu/papers/deepdiary2016eccvw.pdf)
* [Research project website](http://vision.soic.indiana.edu/projects/deepdiary/)
* Technologies: Deep learning, discrete optimization
* Models: Hidden Markov Models, Deep Neural Networks, Long-short Term Memories
* Algorithms: Viterbi, Gradient Descent


