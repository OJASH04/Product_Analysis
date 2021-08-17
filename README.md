# Product_Analysis
For this project, I collected real life dataset about people's preference on various product category using Google Form and applied **Exploratory Data Analysis** to gain useful insight from the data and see different trends related to Age, Gender, State, Education Level and Employement Status. I also used **Mutual Information** as part of feature selection to figure on which features the product category depended.   

After performing this data analysis, I used one-hot encoding to convert categorical values into numerical useful into my neural network. The **neural network** consisted of various dense layer with "relu" activation function and using "softmax" activation function in the final layer. I used "adam" optimizer along with "sparse_categorical_crossentropy" as the loss function to achieve the highest accuracy of about 0.64. I also tried **age_binning** to further improve the accuracy of the model.

After this I used **SHAP** values to figure out upon which features did the product category depended upon according to the model.
