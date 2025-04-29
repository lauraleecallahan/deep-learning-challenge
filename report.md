# Report
### Overview of Analysis: 
Explain the purpose of this analysis.

- The purpose of this analysis is to create a tool for the nonprofit foundation, Alphabet Soup, that can help it select applicants for funding with the best chance of success in their ventures. 

### Results: 
Using bulleted lists and images to support your answers, address the following questions:

**Data Preprocessing**

What variable(s) are the target(s) for your model?
- The target for this model is X, or all of the columns in the new_application_df, excluding the "IS_SUCCESSFUL" column.
  
What variable(s) are the features for your model?
- The feature for this model is the y, or the "IS_SUCCESSFUL" column in the new_application_df.
  
<img width="714" alt="image" src="https://github.com/user-attachments/assets/f3e23224-43d3-4440-9f14-2a4ed085446d" />


What variable(s) should be removed from the input data because they are neither targets nor features?
- The ID columns should be removed.
  
**Compiling, Training, and Evaluating the Model**

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - A sequential model with 3 layers (First Hidden, Second Hidden, and Output layer), 'relu' actvation functions for each, and 80, 30, and 1 units, respectively- for the Funding notebook.

<img width="1024" alt="image" src="https://github.com/user-attachments/assets/e301d054-493c-4a5f-9ded-72d7d80a11ef" />


- Were you able to achieve the target model performance?
    - I was unable to achieve the target model performance.
  
- What steps did you take in your attempts to increase model performance?
  - With my 3 attempts, I tried removing/adding columns, changing the number of units and activation type, increasing/decreasing the number of epochs, creating different bins, and choosing different cutoff values.
  
### Summary: 

Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

- Overall, this deep learning model displays accuracy between ~ 65% to ~ 67%. Because this a large dataset with multiple varying factors, perhaps a modular neural network model would have been best to compress the data and help select applicants for funding.
