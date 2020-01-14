###  Convolutional Neural Network

#### Week1 Lectures
1. Edge Detection
2. Padding
3. Stride
4. Pooling

#### Week2 Lectures
1. Classic Network
2. Resnet
3. 1 * 1 Convolutions
4. Inception Network
5. Transfer Learning
5. Data Augmentation

#### Week3 Lectures
1. Object Localization
2. Landmark Detection
3. Object Detection  
4. Convolutional implementation of sliding windows
5. Bounding Box Predictions
6. Intersection Over Union
7. Anchor Box
8. YOLO Algorithm

#### Week4 Lectures
1. Face Recognition
*  Definition
* One Shot Learning
* Siamese Network
* Triplet Loss
* Face Verification  and Binary Classification
2. Neural Style Transfer
* Definition
* Deep Convnet Learning
* Cost Function
* Content Cost Function
* Style Cost Function
* 1D and 3D Generalizations


### Assignments:
##### Week4 Summary
*Neural Style Transfer*
- Build the content cost function
- Build the style cost function
- Calculate the total_cost Function  

Pseudo_Algorithm for the cost function
Here's what the program will have to do:
1. Create an Interactive Session
2. Load the content image
3. Load the style image
4. Randomly initialize the image to be generated
5. Load the VGG19 model
7. Build the TensorFlow graph:
    - Run the content image through the VGG19 model and compute the content cost
    - Run the style image through the VGG19 model and compute the style cost
    - Compute the total cost
    - Define the optimizer and the learning rate
8. Initialize the TensorFlow graph and run it for a large number of iterations, updating the generated image at every step.


#### Bibliography
- Leon A. Gatys, Alexander S. Ecker, Matthias Bethge, (2015). [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576)
- Harish Narayanan, [Convolutional neural networks for artistic style transfer.](https://harishnarayanan.org/writing/artistic-style-transfer/)
- Log0, [TensorFlow Implementation of "A Neural Algorithm of Artistic Style".](http://www.chioka.in/tensorflow-implementation-neural-algorithm-of-artistic-style)
- Karen Simonyan and Andrew Zisserman (2015). [Very deep convolutional networks for large-scale image recognition](https://arxiv.org/pdf/1409.1556.pdf)
- [MatConvNet.](http://www.vlfeat.org/matconvnet/pretrained/)
