# neural-network-challenge-1

## Student Loan Risk with Deep Learning:
  This project is to create a model to predict student loan repayment.The dataset contains information about previous student loan recipients. We have to use the features in the provided dataset to create a model that will predict the likelihood that an applicant will repay their student loans. 

  ### Part 1: Data preparation
  1. Read the data into a Pandas DataFrame. Review the DataFrame, looking for columns that could eventually define your features and target variables.

  2. Create the features (X) and target (y) datasets. The target dataset should be defined by the “credit_ranking” column. The remaining columns should define the features dataset.

  3. Split the features and target sets into training and testing datasets.

  4. Stardize the data.

  ### Part 2: Compile and Evaluate a Model Using a Neural Network
  1. Create a deep neural network by assigning the number of input features, the number of layers, and the number of neurons on each layer
     
  2. Compile and fit the model
  3. Evaluate the model using the test data to determine the model’s loss and accuracy.
  4. Save and export your model to a keras file

  ### Part 3: Predict loan repayment success by using your neural network model
  1. Reload the saved model.
  2. Make predictions on the testing data, saving them to a DataFrame and rounding the predictions to binary values.
  3. Generate a classification report with the predictions and testing data.

  ### Part 4: Discuss creating a recommendation system for student loans
  
  **1. Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.**

*Students personal data like- Educational background, location, Stem career, time to complete the studies, Financial data like - payment history, credit score, financial loan options are all relevant for designing the recommendation system as this ensures a system that can deliver accurate and personalized loan options for the particular student.*

**2. Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.**

*The data needed such as the educational background, financial data aligns with the principals of content based filtering where recommendations are based on the features itself. In this case, the recommendation system suggests loans that match the features of the student’s profile and the available loan options.* 

**3. Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.**

*1. Data privacy and security. These student's data needed to build the system are sensitive data and are confidential. If these are not handled carefully, the data would be exposed to cyber threats leading to identity theft and financial fraud.*

*2. The recommendation system might have a bias over certain students from certain educational and financial background if we do not have the necessary data from a diverse population.*
