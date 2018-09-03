# 100_days_of_ml_code
Attempting the #100_days_of_ml_code challenge inspired by Siraj Raval. Will be writing my thoughts at the end of the day, here. All the code can be found in the './code' folder.

# Day 1 (Aug 2)
Revised tensorflow from scratch. Created a program to train a model on the fashion-mnist data set. However not being able to train for over a few epochs. Working on it. code in the 'code' folder.

# Day 2
Attained 96% accuracy on the fashion-mnist dataset and debugged tensorflow code. Code to the working ipnb linked below.
https://github.com/aditya9898/100_days_of_ml_code/blob/master/code/%5Bday%202%5D%20tf%20practice%20%5B3%20aug%202018%5D.ipynb

# Day 3
Attended the ml code jam workshop conducted by Google. Learnt about tf.estimators and intro to tensorflow.

# Day 4
Revised keras modes and made a 3 layer conv model to fit the fashion mnist dataset. Attained 90% accuracy on both test and train sets. Have to learn why batch normalization affects the training of conv nets so much.

# Day 5
Created a convolutional neural net in tensorflow and trained a model on the fashion-mnist dataset. A few errors left to debug. Once finnished, will do an analysis on which architecture is best suited to train a model on fashion-mnist.  Code will be uploaded in the ./code folder.

# Day 6
Spent the whole day debugging tensorflow conv net code. When making conv nets in tf, we initialize the weight variables(w1,w2,w3) but tf automatically manages the bias and fully connected layer weights. After training how to return these parameters so as to make predictions on new data? 

# Day 7
Learnt transfer learning using keras. Tried using different models such as ResNet50 and MobileNet. Froze the initial layers and trained the final layers to make a smiling/not smiling classifier using MobileNet. Also worked on google colaboratory and used transfer learning on the resnet50 model to train a dataset of 'cats/dogs'. Link to the code below.....
https://github.com/aditya9898/100_days_of_ml_code/blob/master/code/%5Bday%207%5D%20keras%20transfer%20learning%20%5B8%20aug%202018%5D.ipynb

# Day 8
Implemented transfer learning on a few real world datasets. Learnt about Train_data_generators in keras and used it to train the dog breed classifier. Used python to make nested folders and to sort the pictures of different breeds of dogs in different folders for it to be used with train data generator.

# Day 9
Used transfer learning to train the dog breed classifier on MobileNet. Achieved an accuracy of 77% in the training set but not much accuracy on the test set.

# Day 10
Attended Week 2 of ML Code Jam by Google and Kerala AI. Met a few freelancers in the field and interracted with them. Got to know about several hackathons and methods to learn ML.

# Day 11
Attempted training the dog breed classifier in a kaggle kernel. Attended a meetup and met a lot of people. Planning on submitting the predictions of the test dataset of the dog breed clkassification competition. Code will be posted in the './code' folder.

# Day 12 
Took a break from coding today. Went through a couple of repositories. Revised neural style transfer. Planing on implementing it tomorrow.

# August 14-August 22
Took a break. Could not find time everyday.

# Day 13 [aug 23]
Revisited transfer learning in keras. Went through Lesson 1 of fast.ai on google colab. Worked on Neural Style Transfer with help from Siraj Ravals video.

# Day 14 
Learnt neural style transfer and the concept of gram matrix. Learnt how to use a pretrained conv net in tensorflow. Also uploaded code for some simple file transfers in python so as to enable the use of keras ImageDataGenerators. For code view ImportantCodeSnipets repo.

# Day 15
Attempted to do style transfer on kaggle. Learnt the tensorflow code to do the same. However errors exist. Working on it.

# Day 16
Continuing to do style transfer on kaggle. Have doubts with the working of tensorflow optimizers and how they work. Working on it.
Refreshed knowledge on gram matrices and style cost of neural style transfer.
[Link to code](https://github.com/aditya9898/100_days_of_ml_code/blob/master/code/kernel.ipynb)

# Day 17
Found this amazing [blog](https://harishnarayanan.org/writing/artistic-style-transfer/) on style transfer.
Going through it. Cleared a few doubts about tensorflow optimizers through [reddit](https://www.reddit.com/r/MachineLearning/).

# Day 18
Tried debugging the style transfer ipnb.

# Day 19
Understood neural style transfer. Learnt features of tensorflow. Implementing neural style transfer from scratch using vgg 19 pretrained model on imagenet.

# Day 20
Implemented neural style transfer on kaggle kernel. The model trains fine. Error in computing style cost. The model used is vgg19 and trained on tensorflow. Working on the style cost function. Find the code [here](https://github.com/aditya9898/100_days_of_ml_code/blob/master/code/%5BAug%2030%5Dstyle%20transfer%20partly%20working.ipynb).

# Day 21
Attempted style transfer from scratch again. Still refining model and fixing bugs. The model trains however the content cost fails to decrease. Doing on kaggle kernel.

# Day 22
Attended week 3 of Google ML study jam. Cleared a few doubts about style transfer.

# Day 23
Started writing a ablog on medium about transfer learning in keras. Ran the style transfer ipnb on kaggle and colaboratory. Results are the same. Some errors still exist.
