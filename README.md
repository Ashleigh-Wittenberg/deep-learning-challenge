Moduele Deep_Learning
Completed by Ashleigh Wittenberg

Overview of the analysis: 

The purpose of the analysis is to assist Alphabet Soup in creating a binary classifier for predicting the success of applicants for funding.

Results: 

Data Preprocessing

What variable(s) are the target(s) for your model? 

The target variable for the model is the category 'IS_SUCCESSFUL'.

What variable(s) are the features for your model? 

The features for the model are all other catagories excluding those listed below.

What variable(s) should be removed from the input data because they are neither targets nor features?

The 'EIN' and 'NAME' categories were removed as they are neither targets nor features.

Compiling, Training, and Evaluating the Model

Model 1

![Screenshot 2024-06-02 104010](https://github.com/Ashleigh-Wittenberg/deep-learning-challenge/assets/152832328/93d08a74-4466-4c52-85bc-92ab1d0becd1)

First optimized model

![Screenshot 2024-06-02 104032](https://github.com/Ashleigh-Wittenberg/deep-learning-challenge/assets/152832328/a5957ee2-0a15-4a5c-adef-55adf457c29f)

Secound optimized model

![Screenshot 2024-06-02 104052](https://github.com/Ashleigh-Wittenberg/deep-learning-challenge/assets/152832328/f51f9425-bcf8-4c39-94f0-98540b7cac5b)

Third optimized model

![Screenshot 2024-06-02 104114](https://github.com/Ashleigh-Wittenberg/deep-learning-challenge/assets/152832328/31e6da47-3c68-4fdf-b5d6-95f182bf0a97)



With a data set this small finding the right number of layers and neurons is a bit of a delicate challenge.
With each new iteration of the model I tried to adjust those componets as well as the epochs, with the changing accuracy percentage.
Unfortunetly I was not able to create a model to succesfully reach the target goal of 75%. 
The highest accurecy I was able to achieve was 73%.

My recomendation for reaching the desired outcome is to use a model that is more geared toward smaller datasets or using a more adaptive and personalized tool.

