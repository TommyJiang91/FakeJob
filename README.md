# Fake Job Posting Detection

### Introduction:

The risk of online recruitment fraud arises as companies are highly dependent on online and automated systems in the hiring processes. Such fraud not only negatively impact job seekers, but also causes harm to the reputation of the hiring organizations. 

Our motivation is to build an effective classification model to identify fake job postings to prevent any potential risk of the frauds. For this project, we used advanced word embedding techniques and neural network models and bring in additional predictors to identify fake job postings more effectively. 

Our project uses the “Real or Fake: Fake Job Description Prediction” dataset from Kaggle (https://www.kaggle.com/shivamb/real-or-fake-fake-jobposting-prediction), which contains 18 thousand job descriptions across 18 features with disk size of 50.1 MB. The data is imbalanced with only 866 fake postings. Below is the word cloud of the fake job postings from the dataset.

### Results:

#### Baseline Result :



#### Final Model Result:



### Documents (Codes in the format of jupyter notebooks):

1. Data_Cleaning_and_Salary_Matching_Final.ipynb:
  a. Data cleaning
  b. Salary Matching and Feature Engineering
  c. Feature Selection using Random Forest Model Feature Importance.

2. Baseline.ipynb: Contains baseline models implemented with Logistic Regression and Random Forest

3. Vectorization.ipynb: Contains result of different vectorization method on text

4. Semi_Supervised_Final.ipynb: Semi_Supervised Learning by bringing Monster.com job posting dataset

5. NLP Project_Text Generation.ipynb: Fake jobs generation

6. nn_Final.ipynb: Final neural net model for classification using Countvectorizer

7. nn_LSTM_Final.ipynb: Final LSTM neural net model for classification using Tokenizer

8. nn_Elmo_Final.ipynb: Final Neural net model with Elmo embedding

9. team_25_final_report.pdf: Final Report

10. Project Slides.pptx: Presentation Slides
