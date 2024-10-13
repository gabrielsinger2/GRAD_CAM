# GRAD_CAM
In this tutorial, we re-code the GradCam algorithm by following https://arxiv.org/pdf/1610.02391.pdf. 
GradCam visualizes as a heatmap the areas used by a convolutional neural network (CNN) during a classfication task.

We experimentally demonstrate that the heat-map converges on the area of the image that a human (i.e. us) would have found useful for the classification problem. 
To do this, we came up with the idea of applying gradCam along the layers of the CNN network, rather than just at the last layer as in the article. 

Final grade 18/20. 
