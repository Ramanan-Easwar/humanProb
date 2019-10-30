A Recurrent Neural Net that returns a list of probabilities that whether the given element, keyed by ID according to the openpose results are actual human or not. Where a probability of more that 0.9 denotes it is a human for sure and a probability of less than 0.1 denotes that it is not.

# OUTPUT FORMAT
Here, the output is of the ndjson format. It is the OpenPose's COCO Pose format in the form of JSON file. Each of the reading has an x-coordinate, y-coordinate and the probability of the prediction, i.e. [x,y, p(x,y)]. To know more about the OpenPose output format, refer: https://github.com/CMU-Perceptual-Computing-Lab/openpose/

# Requirements:
    Tensorflow-GPU 2.0
    CUDA (Nvidia GPU)
    
