# Module_21

## Table of Contents
1.  Resources
2.  Starter_Code.ipynb
3.  AlphabetSoupCharity_Optimzation.ipynb
4.  charity_data.csv
5.  ReadMe
6.  License 


--------------------------------------
### Step 4: Report on the Neural Network
* Overview: This project demonstrates how a non-linear data source can be analyzed using the neural network. We used multiple layers to imporve accuracy to catch factors that may have an effect on the data. This process tests mnay scenarios after being trained.
* Results:
   *  Data Preprocessing:
      1.  What variable(s) are considered the target(s) for your model? Is Successful
      2.  What variable(s) are considered to be the features for your model? APPLICATION_TYPE and CLASSIFICATION 
      3.  What variable(s) are neither targets nor features, and should be removed from the input data? STATUS and SPECIAL_CONSIDERATIONS
   *  Compiling, Training, and Evaluating the Model:
      1.  How many neurons, layers, and activation functions did you select for your neural network model, and why? 3 layers and 2 activations(relu and sigmoid). Mainly these were defaulted, but also didn't want to overfit the model by adding too many layers.
      2.  Were you able to achieve the target model performance? No, max accuracy reached was 0.73
      3.  What steps did you take to try and increase model performance? 1) Increase hidden layers, 2) Increas epochs from 100-200 and 3) removed additional columns
* Summary: Even with the changes to the model, the accuracy did not change much with each attempts. It's possible a different activation model would be better to run on this data instead of reul. 
