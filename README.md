# Neural_Network_Charity_Analysis
## Purpose of Analysis
The purpose for this analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by the company Alphabet Soup. 

The [dataset](https://github.com/Ariannatopbjerg/Neural_Network_Charity_Analysis/blob/main/Resources/charity_data.csv) used for this analysis consists of more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

### Analysis Methods 
Machine Learning and Neural Networks

## Results
- Data Preprocessing
  
  - What variable(s) are considered the target(s) for your model?
    
    Column IS_SUCCESSFUL 
  
  - What variable(s) are considered to be the features for your model?
    
    All columns excluding IS_SUCCESSFUL and the dropped ones
  
  - What variable(s) are neither targets nor features, and should be removed from the input data?
    
    Columns EIN, NAME, STATUS, SPECIAL_CONSIDERATIONS

- Compiling, Training, and Evaluating the Model
  
  - How many neurons, layers, and activation functions did you select for your neural network model, and why?
    
    For my neural network model, I attempted to increase the accuracy three times by using different amounts of nuerons in each layer, added on layers, and used different activation functions per layer. My second attempt had the highest accuracy of about 71%.
    
    ![](https://github.com/Ariannatopbjerg/Neural_Network_Charity_Analysis/blob/main/images/attempt2.PNG)
   
   **What I used**
   - Two hidden layers:
   - Layer one: 50 neurons, activation function: relu
   - Layer two: 10 neurons, activation function: relu
   - Output layer: activation function: sigmoid
  
  - Were you able to achieve the target model performance?
   
    For this analysis, the model goal was to have an accuracy of 75%. Unfortunately, the highest accuracy percentage I received was 71%. 
  
  - What steps did you take to try and increase model performance?
  
    I decreased the amount of neurons in each of the hidden layers, as well as dropped columns STATUS and SPECIAL_CONSIDERATIONS
    
## Summary

