# Project Name: Capstone
Udacity Data Scientist Nanodegree - Dog Breed Identification using Convolutional Neural Networks

## Data source
Provided within the project by Udacity 

## Python libraries used:
   See requirements.txt    

## Project Definition:
   This project is to create a Convolutional Neural Networks model to complete two jobs:
   1. Detect the object on an image as dog or human or neither. 
   2. If the object was detected as a dog, based on the given classes of the world-wide dog breeds, the model should be able to identify the dog breed. 
   With such an algorithm and CNN model, a web or mobile app could be developped to process the user provided image and estimate the breed if it is a dog. 
   
   
## Process:
  Step 0: Import Datasets
  
  Step 1: Detect Humans
  
  Step 2: Detect Dogs
  
  Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
  
  Step 4: Use a CNN to Classify Dog Breeds (using Transfer Learning)
  
  Step 5: Create a CNN to Classify Dog Breeds (using Transfer Learning)
  
  Step 6: Write my own Algorithm
  
  Step 7: Test my own Algorithm

## Analysis
   Through the process of building the algorithm and CNN achitechture, multiple structures were tested and different approaches were applied to achieve better performance of the model. A data pre-processing was also implemented. 
   
  Alternative approach than building own algorithm, we can utilize some pre-trained model such as ResNet-50, VGG-19, InceptionV3, etc. These models present significant enhancement in accuracy. 
   
   We use transfer learning to create CNN model leveraging the above pre-trained model bottlenect features as input, and then build own algorithm to finalize CNN model for our purpose.   

## Conclusion
   The final built CNN model (based on the pre-trained InceptionV3 model) in this project correctly detected the object shown on the given image, dog or human or neither. And, it successfully classified the dog breed if it was a dog. It approves that CNN model works very well on image identification. 
   
   However, compared to the final model, the one I built on my own as the first architechture did not work well given the accuracy rate was only 5%. There are a big room to improve my model.
   
## Next step:
   There are a few ways to improved the model performance, including but not limited to the following. During my process to build the CNN achitechture, I already applied some of these approach such as increasing number of epochs which approved the improvements.
   
   Increase number of epoches  
   
   Augmentate training data (but can't be too much)
   
   Tune some of the model parameters
   
   Adjust the pre-processing method
   
   Change loss function
   
   Reduce batch size
   
