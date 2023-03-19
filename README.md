# website
kasetty purushotham portfolio


# [Project 1 - pandas :](https://github.com/kasettypurush/pandas)



DESCRIPTION Problem: Analyze the Federal Aviation Authority (FAA) dataset using Pandas to do the following: 1.View

aircraft make name , state name , aircraft model name , text information , flight phase , event description type , fatal flag ,

- Clean the dataset and replace the fatal flag NaN with “No” 
- Find the aircraft types and their occurrences in the dataset 
- Remove all the observations where aircraft names are not available 



# [Project 2 - Housing-in-California:](https://github.com/kasettypurush/-Housing-in-California)



Context : This is the dataset used in the second chapter of Aurélien Géron's recent book 'Hands-On Machine learning with Scikit-Learn and TensorFlow'. It serves as an excellent introduction to implementing machine learning algorithms because it requires rudimentary data cleaning, has an easily understandable list of variables and sits at an optimal size between being to toyish and too cumbersome.

The data contains information from the 1990 California census. So although it may not help you with predicting current housing prices like the Zillow Zestimate dataset, it does provide an accessible introductory dataset for teaching people about the basics of machine learning.

Content The data pertains to the houses found in a given California district and some summary stats about them based on the 1990 census data. Be warned the data aren't cleaned so there are some preprocessing steps required! The columns are as follows, their names are pretty self explanitory:

- longitude

- latitude

- housing_median_age

- total_rooms

- total_bedrooms

- population

- households

- median_income

- median_house_value

- ocean_proximity


![](https://github.com/kasettypurush/website/blob/master/images/housing1.png)
![](https://github.com/kasettypurush/website/blob/master/images/housing2.png)










# [Project 3 - IBM-HR-Analytics-Employee-Attrition-Modeling :](https://github.com/kasettypurush/IBM-HR-Analytics-Employee-Attrition-Modeling)






DESCRIPTION :

IBM is an American MNC operating in around 170 countries with major business vertical as computing, software, and hardware. Attrition is a major risk to service-providing organizations where trained and experienced people are the assets of the company. The organization would like to identify the factors which influence the attrition of employees.

- Data Dictionary

- Age: Age of employee

- Attrition: Employee attrition status

- Department: Department of work

- DistanceFromHome

- Education: 1-Below College; 2- College; 3-Bachelor; 4-Master; 5-Doctor;

- EducationField

- EnvironmentSatisfaction: 1-Low; 2-Medium; 3-High; 4-Very High;

- JobSatisfaction: 1-Low; 2-Medium; 3-High; 4-Very High;

- MaritalStatus

- MonthlyIncome

- NumCompaniesWorked: Number of companies worked prior to IBM

- WorkLifeBalance: 1-Bad; 2-Good; 3-Better; 4-Best;

- YearsAtCompany: Current years of service in IBM

Analysis Task:

Import attrition dataset and import libraries such as pandas, matplotlib.pyplot, numpy, and seaborn.
Exploratory data analysis
Find the age distribution of employees in IBM

- Explore attrition by age

- Explore data for Left employees

- Find out the distribution of employees by the education field

- Give a bar chart for the number of married and unmarried employees

- Build up a logistic regression model to predict which employees are likely to attrite.

![](https://github.com/kasettypurush/website/blob/master/images/ibm.png)

# [Project 4 - Hate_Speech_Detection- :](https://github.com/kasettypurush/Hate_Speech_Detection-)

### Problem Statement:
Dataset using Twitter data, is was used to research hate-speech detection. The text is classified as: hate-speech, offensive language, and neither. Due to the nature of the study, it’s important to note that this dataset contains text that can be considered racist, sexist, homophobic, or generally offensive

##### here are the tasks that can be performed on the Twitter dataset in a step-by-step manner:
Data Collection: The first step is to collect the Twitter dataset. This may involve using a web scraping tool or accessing pre-existing Twitter data sets.

- Data Preprocessing: The second step is to preprocess the data by cleaning and normalizing the text data. This may involve removing irrelevant data, such as links or emojis, and standardizing the text data to a consistent format.

- Labeling the Data: The third step is to label the data based on the research question. In this case, the text data is labeled as hate-speech, offensive language, or neither.

- Data Exploration: The fourth step is to explore the data to gain insights into the characteristics of the text data. This may involve analyzing the distribution of labels, identifying common words or phrases, and understanding the context of the text data.

- Training Machine Learning Models: The fifth step is to train machine learning models to perform specific tasks on the text data. For example, a model can be trained to classify text as hate-speech or not hate-speech using supervised learning techniques.

- Model Evaluation: The sixth step is to evaluate the performance of the machine learning models. This may involve calculating metrics to determine how well the model is performing.


# [Project 5 - SMS-ham-spam-Classification :](https://github.com/kasettypurush/SMS-ham-spam-Classification)


### Importing & Feature Engineering

##### Import Dataset
Handling imbalanced dataset using Oversampling

Creating new features from existing features
e.g.

- word_count
- contains_currency_symbol
- contains_numbers, etc.
### Data Cleaning (NLTK)
-Removing special character and numbers using regular expression

-Converting the entire SMS into lower case

-Tokenizing the SMS by words

-Removing the stop words

-Lemmatizing the words

-Joining the lemmatized words

-Building a corpus of messages

### Machine Learning Model
Model Building and Evaluation

-Multinomial Naive Bayes

-Decision Tree

### Model Prediction


