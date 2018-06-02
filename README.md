This is the official Caffe implementation of [Learning  Deep  NBNN  Representations  for  Robust  Place  Categorization](https://ieeexplore.ieee.org/document/7930504/). 

## Content

Here we provide 4 files:

* `train_val.prototxt` : the multiscale AlexNet architecture used for the experiments.
* `deploy.prototxt` : the same architecture for deploy purposes.
* `solver.prototxt` : the template of the solver used for the experiments.
* `classifier.prototxt` : the template of the NBNN classifier used.

Notice that each of these files have some fields delimited by `%` which must be specified before their usage.


## Abstract and citation

This letter presents an approach for semantic place categorization using data obtained from RGB cameras. Previous studies on visual place recognition and classification have shown that by considering features derived from pretrained convolutional neural networks (CNNs) in combination with part-based classification models, high recognition accuracy can be achieved, even in the presence of occlusions and severe viewpoint changes. Inspired by these works, we propose to exploit local deep representations, representing images as set of regions applying a Naïve Bayes nearest neighbor (NBNN) model for image classification. As opposed to previous methods, where CNNs are merely used as feature extractors, our approach seamlessly integrates the NBNN model into a fully CNN. Experimental results show that the proposed algorithm outperforms previous methods based on pretrained CNN models and that, when employed in challenging robot place recognition tasks, it is robust to occlusions, environmental and sensor changes.

    @ARTICLE{mancini2018learning,
	author={M. Mancini and S. Rota Bulò and E. Ricci and B. Caputo},
	journal={IEEE Robotics and Automation Letters},
	title={Learning Deep NBNN Representations for Robust Place Categorization},
	year={2017},
	volume={2},
	number={3},
	pages={1794-1801},
	doi={10.1109/LRA.2017.2705282},
	month={July}
    }



