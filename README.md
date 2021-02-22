
## Traffic Sign Recognition

### Project #3 for Udacity Self-Driving Car Nanodegree
The goals / steps of this project are the following:

* Load the data set
* Explore, summarize and visualize the data set
* Augment the training data set 
* Design, train and test a model architecture
* Use the model to make predictions on new images
* Analyze the softmax probabilities of the new images




#### Load data set
Number of training examples = 34799
Number of testing examples = 12630
Image data shape = (32, 32, 3)
Number of classes = 43

![alt text](./examples/1_.png)

#### Visualize the data
Augment the training data set by rotating and moving exist images
![alt text](./examples/2_barh1.png)

#### Normalize and Augment the training data set 
the image data should be normalized so that the data has mean zero and equal variance. So I use *standard deviation* 

![alt text](./examples/2-1.png)
±10 degree rotation
3 pixel movement
![alt text](./examples/3_barh2.png)

#### Train and test a model

![alt text](./examples/0_vggnet.png)

![alt text](./examples/4_accuracy.png)
Validation Accuracy = 0.962
Test Accuracy = 0.946
#### Predictions on new images

![alt text](./examples/5_new.png)
model prediction : [2, 39, 26, 31, 12]
answer     : [2, 39, 26, 31, 12]

Image 1 Accuracy = 1
Image 2 Accuracy = 1
Image 3 Accuracy = 1
Image 4 Accuracy = 1
Image 5 Accuracy = 1
Total Accuracy : 100.0%

![alt text](./examples/6_result1.png)
![alt text](./examples/6_result2.png)
![alt text](./examples/6_result3.png)
![alt text](./examples/6_result.png)
![alt text](./examples/6_result4.png)



