# Project Name: 
   Dog Breed Identification using CNN (Convolutional Neural Networks)
   
   - Udacity Data Scientist Nanodegree Capstone Project
   

## Data source:
   Keras and other data provided within the project by Udacity 


## Python libraries:
   See requirements.txt    


## Project Definition:
   This project is to create a Convolutional Neural Networks model to complete two jobs:
   1. Detect the object on an image as dog or human or neither. 
   2. If the object was detected as a dog, based on the given classes of the world-wide dog breeds, the model should be able to identify the dog breed. 
   With such an algorithm and CNN model, a web or mobile app could be developped to process the user provided image and estimate the breed if it is a dog. 
   
   
## Process:
  Step 0: Import Datasets - 
  Including dog classes data, human data, images ;
  Also split data into training/validation/testing ;
      
  Step 1: Detect Human - 
      Use OpenCV's implementation of Haar feature-based cascade classifiers 
      Create Face Detector function
      
  Step 2: Detect Dogs - 
      Use use a pre-trained ResNet-50 model ;
      Pre-process data and make prediction with the model;
      Create Dog Detector function;
      
  Step 3: Create a CNN to Classify Dog Breeds (from Scratch) - 
      Pre-process data ;
      Build the model architecture with mix of layerse;
      Compile and train the built model;
      Load model with best valiation loss;
      Test model by the accuracy;
      
  Step 4: Use a CNN to Classify Dog Breeds (using Transfer Learning) - 
      (shown as example using VGG-19 model)
      
  Step 5: Create a CNN to Classify Dog Breeds (using Transfer Learning) - 
       Use InceptionV3 model
       
  Step 6: Write my own Algorithm - 
       Use the predefined face detector function and dog detector function  
       
  Step 7: Test my own Algorithm - 
       Test the algorithm wiht various images, including samples selected from internet


## Analysis:
   Through the process of building the algorithm and CNN achitechture, multiple structures were tested and different approaches were applied to achieve better performance of the model. A data pre-processing was also implemented. 
   
  Alternative approach than building own algorithm, we can utilize some pre-trained model such as ResNet-50, VGG-19, InceptionV3, etc. These models present significant enhancement in accuracy. 
   
   We use transfer learning to create CNN model leveraging the above pre-trained model bottlenect features as input, and then build own algorithm to finalize CNN model for our purpose. The final output detected the image with 100% accuracy.


## Conclusion:
   The final built CNN model (based on the pre-trained InceptionV3 model) in this project had 78% testing accuracy, which was not as desired. It successfully detected the object shown on the given image, dog or human or neither. When classified the dog breed, one of the testing image did not correct result from the model, which indicates the need of more improvements. However, it approves that CNN model works mostly on image identification.  
   
   
## Next step:
   There are a few ways to improved the model performance, including but not limited to the following. During my process to build the CNN achitechture, I already applied some of these approach such as increasing number of epochs which approved the improvements.
   
   Increase number of epoches  
   
   Augmentate training data (but can't be too much)
   
   Tune some of the model parameters
   
   Adjust the pre-processing method
   
   Change loss function
   
   Reduce batch size
   
   Increase the breeds of dog and train more images
   
   
 ## Publication link:
   
   https://medium.com/@yanzhang14689/dog-breed-classification-using-cnn-e9883d473dc9

