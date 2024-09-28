# deep-learning-challenge
module_21. Neural Network Model
Deep Learning Challenge 
Intro
Using Data from Alphabet Soup’s business team, we will train a model to assertively select candidates and their possible outcomes in their projects, whether they could be successful or not. We will demonstrate how neural networks classify the applicants into two categories and how accurate these predictions are. The data has around 34,000 organizations.
Process
We started by identifying the target and the features of our dataset. For this data, our target was “IS_SUCCESSFUL.” This column will show the analysis results as 1- success. 0 not successful. Starting by dropping 'EIN', and 'NAME' as columns because they were considered non-beneficial ID columns. On the other hand, we also organized the data by using a cutoff and replacing the less common values with one group of “others.” 
We encode the categorical values using “pd.get_dummies()”

![image](https://github.com/user-attachments/assets/c80a2e13-c0d9-4218-b44a-cd1a225318f8)
![image](https://github.com/user-attachments/assets/a9d7cba2-b56a-4b8a-a028-d1a30f87cfa9)


 

Training, optimizing and results of the model
The goal was to obtain a minimum of 75% accuracy. We made three attempts to optimize the model by increasing the layers and the number of epochs. Our highest result was 63% accuracy using 2 hidden layers and one output layer with only one neuron. 
 ![image](https://github.com/user-attachments/assets/da66fb15-f88d-4fc5-b1e5-8e674597f4d0)

 
Based on our results and the model's performance in the different trials, the goal of 75% wasn’t reached. However, with more intent on optimizing by changing the layers and number of neurons, a better accuracy result could be reached, confirming that the model effectively classifies each of the company's successful or not prosperous applications. In future work, we will suggest trying different models too. 
