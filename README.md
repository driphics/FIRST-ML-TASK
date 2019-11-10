# FIRST-ML-TASK

This is my first machine learning task although an explanation has been given on lucid but i thought i should also include it in my README file
The task is a simple image classifier that is able to differentiate plate number images from non-plate number images.

Here is a break down of how i went about it 
The fist task that was given to us was to build an image classifier. At first i did not know what to do as a beginner into the ML world till i read up on the Image Classification with Convolutional Neural Networks ( CNN ) which is used by popular applications like facebook for automatic tagging of pictures. CNNs are used for image classification and recognition because of its high accuracy.

STEPS TAKEN IN THE TASK:

-Preparation and Pre-processing of Dataset
-Implementation of Machine Learning Algorithms
-Testing of Trained Model
-Conclusion

Preparation and Pre-processing of Dataset
In this stage of building the image classifier ( the initial phase ). we start by importing packages and the needed libraries needed for the various features of the classifier such as;

Pandas: for data manipulation
Numpy: for scientific computing
Keras: deep learning framework
Least i forget, i was using coLAB notebooks for the building of the model i found it easy to use and it was convinent because of its various features such as the stack overflow question space which links you directly to the stack overflow page asking your questions for you.

back to the preparation i connected colab notebook to my google drive which was where my images to be used for the training were uploaded.

Next, we define a function “prep_data(images)” which takes the list of all the image path (train_images, test_images) and prepare the data in the format needed by the Scikit Learn Logistic Regression method.

Conclusion

i had a 76% accuracy in my KNN classification and it performs poorly compared to the Logic regression. in my opinion i think it is because of the insufficient data to train the model

A better explanation can be found @ https://lucid.blog/sodiqbuhari08/post/building-a-simple-image-classifier-first-ml-task-aa6   PLEASE CHECK IT OUT
