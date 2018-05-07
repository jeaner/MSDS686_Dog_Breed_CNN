# MSDS686_Dog_Breed_CNN
CNN image recognition project for Deep Learning course

# Results
A CNN network for determing the breed of a dog based on its photo. The network has 99% train and 28% validation accuracy. 

## Progression of Project
1) Data Exploration
2) Preliminary Models
  I reduced the data to just the top breeds to perform some test models. These quickly overfit with very low validation accuracy. 
3) Transfer Learning models
  Using VGG with imagenet weights as a starting block increased the validation accuracy.
4) Final Model
  The final model was used by making some of the layers' weights trainable and implementing globalaveragepooling andd dropout to reduce overfitting.
