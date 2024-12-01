Key Highlights of the YOLOv4 Implementation:
Here  have implemented the Backbone of Yolov2 called Darknet_19 containing 19 layers, yolov3 Darknet53 and yolov4 Full architecture Implementations
Backbone (CSP-Darknet53):

CSP-Darknet53, the backbone of YOLOv4, is designed for efficient feature extraction.
It leverages residual blocks and skip connections to preserve gradient flow during training.
Features are aggregated using element-wise addition for combining shared information and concatenation for retaining diverse features.
Feature Aggregation (FPN & PANet):

Feature Pyramid Network (FPN):
Employs a top-down approach to enhance semantic feature extraction.
Uses linear interpolation to upscale lower-resolution features, maintaining smooth transitions in feature maps.
Path Aggregation Network (PANet):
Further refines features by combining FPN outputs with additional layers for better spatial and semantic information.
Concatenation enhances feature diversity, while element-wise summation helps in fusing features for clearer object representations.
Multi-Scale Detection:


The architecture enables robust detection across multiple scales, ensuring accuracy in recognizing both small and large objects.
In addition to YOLOv4, I have also implemented the Darknet19 backbone (YOLOv2) and Darknet53 backbone (YOLOv3).

Soon I will further work on the yolov4 to train a model using the given yolov4 architecture on diverage dataset.
