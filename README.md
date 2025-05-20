# Image-Classification-Journey
This project applies Machine Learning to classify scanned document images into four categories: resumes, ads, emails, and handwritten notes. It covers data analysis to model evaluation, aiming for accurate, efficient, and robust image classification to support automation and smarter decisions.

## Project Description
The objective is to construct a model capable of accurately classifying images into their
respective categories. Initially, thorough analysis of the dataset is deemed necessary. This
entails examining its structure and meticulously cleansing it. The cleaning phase is pivotal as
well-organized data simplifies subsequent tasks significantly. Key considerations during this
phase include verifying image sizes, brightness levels, eliminating blank spaces, and addressing
similar factors. During the modeling phase, meticulous attention is directed towards selecting
optimal hyperparameters and ensuring model accuracy to mitigate overfitting and other
undesirable outcomes. Additionally, it is advisable to evaluate the model's performance with
new data to validate its robustness.

## Dataset Features
- more than 2000 images of scanned documents in .tif format
- 4 different classes (resumè, advertisement, emails, Handwritten documents)

## Models used
- **Transfer Learning** with *VGG16*
- **Deep Convolutional Neural Network**
For the weights of the model please find out the folder "model_weights" which can be found in the folder "models"

## Structure of the repository
- **EDA.ipynb**: self explanatory
- **data** folder: it contains the links to download the document images required to perform this task
- **model** folder: it contains the notebooks used during this project and moreover a subfolder where the models' weights are stored
