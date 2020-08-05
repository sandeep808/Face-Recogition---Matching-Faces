# Face-Recogition_Matching-Faces

Intro:

In this section, we will be running code that loads a pre-trained model called VGGFaces

http://www.robots.ox.ac.uk/~vgg/software/vgg_face/

The VGG-Face CNN descriptors are computed using our CNN implementation based on the VGG-Very-Deep-16 CNN architecture as described and are evaluated on the Labeled Faces in the Wild and the YouTube Faces dataset.

Lesson:

The code in this notebook loads VGGFace and defines a similarity function. This similarity function compares two faces using the VGGFace output descriptors. We then define a threshold metric that determines if the two faces under comparison are the same person.

References: 

Labeled Faces in the Wild - http://vis-www.cs.umass.edu/lfw/lfw.pdf

YouTube Faces - https://www.cs.tau.ac.il/~wolf/ytfaces/WolfHassnerMaoz_CVPR11.pdf
