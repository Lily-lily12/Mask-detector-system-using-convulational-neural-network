# Mask-detector-system-using-convulational-neural-network
Convulational neural network comes under deep learning. It is used mainly for images and videos. For convulational neural networks,black and white images are considered to be two dimensional arrays and colored images are three dimenaional arrays. In the images, each pixel holds a value between 0 and 255 which are converted to binary form. 
Different steps in forming convulational neural network are

1.Convolutional
The input image in binary form is multiplied by a feature detector/filter, element wise to get a feature map, each time a 3/3 or 4/4 matrix is taken in the input image.We shift to the next matric in strides, In each stride a different feature map is formed . Each of these feature maps together form a convolutional layer. In summary, in the process of convolution, we are extracting features from our image using feature detector and we put them into feature map.

2.In a convolutional neural network (CNN), a ReLU (Rectified Linear Unit) layer is a type of activation function applied after a convolutional layer. The primary role of the ReLU layer is to introduce non-linearity into the model, which allows it to learn and model more complex patterns in the data. The ReLU function is defined as: ReLU(x)=max(0,x).If x is greater than 0, ReLU returns 𝑥.If x is less than or equal to 0, ReLU returns 0.

3.Max Pooling= In the feature map,we pick a box of given dimensions, and the maximum value is detected from it, and we form a pooled feature map.By pooling, we get rid of 75% of the information which are not features

4.Flattening=Pooled feature maps are flattened, put into one long column,one after another, by this method, we will get a huge vector of inputs for our artificial neural network

5.Full Connection= We add our convulational neural network to artificial neural network.

6.Softmax function = The output probabilities go into the activation function and the probabilities that we get after that sum up to 1

7.Cross Entropy function= This acts like cost function, it is applied after soft max function. It back propogates error into the model so that weights can be adjusted and forward propogation occcur.
