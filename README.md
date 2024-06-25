# newproject

# Install Requirement.txt


# The initila step of this project is that data collection process

# This data Can be downloaded using the Kaggle Website Intel Image Classification

# this dataset has divided into three folders like train,test,prediction

# train folder has the 14,000 images of six different classes like Building,sea,mountain,street,glacier and forest

# test folder has 3000 images of six different classed like Building,sea,mountain,street,glacier and forest

# prediction folder has more then 7000+ images used to predict the model

# Next Step 2 Data Preprocessing

# using the opencv library we can read the images into array and store into x_train,and the classes was stored into y_train array (Train_Folder)

# Similary this process happened both test folder as well as Prediction folder

# Step 3 : Normalization

In this step array values which stored in the pixles values(RGB) it was converted into numberical values 0 to 1.

# Step 4 : Model Creation :
This Project was trained with CNN Techniques with multiple layers and ANN Layer

# Step 5 : Model Training :
It was trained using the adam optimizer and sparse_categorical_entroy with early_stopping 

# Step 6: Model Serialization 
After the successful training model was serialized into h5 file for the prediction

# Step 7 : Model Evaluation 

The model evalution was performed by the test dataset . It gives the overall accuracy of the model .Our Model achieves 82% Accuracy.It is amazing.Model Accuracy and Model Loss was plotted using the matplotlib library.Classification report generates the accuracy if each class prediction with actual_values

# Step 8 :Model Prediction 

Model prediction was using the h5 file for prediction dataset .I am showing the images of the all of the above details clearly.


