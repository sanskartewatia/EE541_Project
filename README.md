# EE541 Project

# https://github.com/sanskartewatia/EE541_Project.git
 
There are 4 jupyter notebooks in this repository. 2 of them are for datagen, and 2 of them are for actual model training and testing. 

CNN_image_datagen.ipynb is the notebook where the audiofiles are opened from the "af/Minor" or "af/Major" folder and are converted to spectrogram JPGs and then saved into a folder called pics. 
cnnatt1.ipynb is the notebook where spectrogram images from the pics folders are imported and used for training, validation and testing. And I have also saved the model locally and on github and it is called "80A.pth"

harmonics_Datagen.ipynb is the notebook where the dataframe of harmonics is generated and is then exported to a csv file called "dataframe.csv" so that it can be used later on for training models.
harmonics_classification.ipynb is the notebook where the pandas dataframe is imported and the ANN is trained and tested, along with testing the performance of XGBoost Classifier.


Since we are not allowed to upload any datasets, but we actually generated and exported datasets, we will be uploading them to the supplementary section on canvas.
