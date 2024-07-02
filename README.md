# deep-learning-challenge

Write an analysis that includes a title and multiple sections, labeled with headers and subheaders (4 points)
Format images in the report so that they display correction (2)
Explain the purpose of the analysis (4)
Answer all 6 questions in the results section (10)
Summarize the overall results of your model (4)
Describe how you could use a different model to solve the same problem, and explain why you would use that model (6)

Deep Learning Challenge - Creating a deep learning model to predict success of ventures when given funding.

Overview of the analysis

The purpose of this analysis was to develop a deep learning model to predict the success of charitable organizations funded by Alphabet Soup. The goal was to create a binary classifier that could determine whether applicants will be successful if funded, based on various features provided in the dataset.

Data Preprocessing

What variable(s) are the target(s) for your model?

The key target variable from the dataset provided is the IS_SUCCESSFUL variable i.e. is the organisation successful when given funding in its desired outcomes.  This is a binary indicator of success, with success given a value of 1, and those which are unsuccessful given a value of 0.

What variable(s) are the features for your model?

The original variables given in the dataset to use as features for the model were EIN (Employer Identification Number), Name of Organisation,	Application type using a T code, Affiliation (if any) to Alphabet Soup, Classification using a C code, Use Case e.g. for healthcare, preservation etc, Organsiation type e.g. trust, co - operative, status i.e. active (1) or inactive (0), income amount in bands from 0 up to $50 million and above, whether there were any special considerations - a Yes / No, the amount requested and whether successful.

What variable(s) should be removed from the input data because they are neither targets nor features?

Initialy, the EIN and the name of the organisation requesting funding was removed, as these had no impact on determining whether the award of funding would lead to success of a venture.  Whilst they are a useful identifier of specific cases, they are not required for predicting success.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

Compiling, Training, and Evaluating the Model:

Neural Network Structure:

Input layer: [number] neurons (based on the number of features)
Hidden layers:

[number] neurons with [activation function]
[number] neurons with [activation function]
[Add more if you used more layers]


Output layer: 1 neuron with sigmoid activation

Reason for this structure: [Briefly explain your choices]
Target model performance:

[State whether you achieved the target 75% accuracy]
Actual model accuracy: [Your model's accuracy]


Steps taken to increase model performance:

[e.g., Increased the number of neurons in hidden layers]
[e.g., Added more hidden layers]
[e.g., Changed activation functions]
[e.g., Adjusted the learning rate]
[Any other steps you took]




Summary

[Provide a brief summary of your model's performance and the key findings from your analysis]
Recommendation for a different model:
[Suggest an alternative model that could potentially solve this classification problem, such as Random Forest, Gradient Boosting, or Support Vector Machines]
Explanation for the recommendation:
[Explain why you think this alternative model might perform well on this problem. Consider factors like the nature of the data, the binary classification task, and any limitations you observed with the neural network approach]
Remember to include any relevant visualizations or metrics that support your findings. This report structure provides a comprehensive overview of your analysis and results, addressing all the key points required in the assignment.

Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?
