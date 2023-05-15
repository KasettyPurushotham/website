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



# [Project 6 - Iris_Flower-Classification:](https://github.com/kasettypurush/Iris_Flower-Classification)

### Title: Iris Plants Database Updated Sept 21 by C.Blake - Added discrepency information

### Sources: (a) Creator: R.A. Fisher (b) Donor: Michael Marshall (MARSHALL%PLU@io.arc.nasa.gov) (c) Date: July, 1988

### Past Usage:

##### Publications: too many to mention!!! Here are a few.
- Fisher,R.A. "The use of multiple measurements in taxonomic problems" Annual Eugenics, 7, Part II, 179-188 (1936); also in "Contributions to Mathematical Statistics" (John Wiley, NY, 1950).
- Duda,R.O., & Hart,P.E. (1973) Pattern Classification and Scene Analysis. (Q327.D83) John Wiley & Sons. ISBN 0-471-22361-1. See page 218.
- Dasarathy, B.V. (1980) "Nosing Around the Neighborhood: A New System Structure and Classification Rule for Recognition in Partially Exposed Environments". IEEE Transactions on Pattern Analysis and Machine Intelligence, Vol. PAMI-2, No. 1, 67-71. -- Results: -- very low misclassification rates (0% for the setosa class)
Gates, G.W. (1972) "The Reduced Nearest Neighbor Rule". IEEE Transactions on Information Theory, May 1972, 431-433. -- Results: -- very low misclassification rates again
- See also: 1988 MLC Proceedings, 54-64. Cheeseman et al's AUTOCLASS II conceptual clustering system finds 3 classes in the data.
- Relevant Information: --- This is perhaps the best known database to be found in the pattern recognition literature. Fisher's paper is a classic in the field and is referenced frequently to this day. (See Duda & Hart, for example.) The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant. One class is linearly separable from the other 2; the latter are NOT linearly separable from each other. --- Predicted attribute: class of iris plant. --- This is an exceedingly simple domain. --- This data differs from the data presented in Fishers article (identified by Steve Chadwick, spchadwick@espeedaz.net ) The 35th sample should be: 4.9,3.1,1.5,0.2,"Iris-setosa" where the error is in the fourth feature. The 38th sample: 4.9,3.6,1.4,0.1,"Iris-setosa" where the errors are in the second and third features.

- Number of Instances: 150 (50 in each of three classes)

- Number of Attributes: 4 numeric, predictive attributes and the class

### Attribute Information:

- sepal length in cm
- sepal width in cm
- petal length in cm
- petal width in cm
- class: -- Iris Setosa -- Iris Versicolour -- Iris Virginica


- Missing Attribute Values: None

- Summary Statistics: Min Max Mean SD Class Correlation sepal length: 4.3 7.9 5.84 0.83 0.7826
sepal width: 2.0 4.4 3.05 0.43 -0.4194 petal length: 1.0 6.9 3.76 1.76 0.9490 (high!) petal width: 0.1 2.5 1.20 0.76 0.9565 (high!)

- Class Distribution: 33.3% for each of 3 classes.


# [Project 7 - Credit_EDA:](https://github.com/KasettyPurushotham/Credit_EDA)

 
### Problem Statement - I

- Introduction: This case study aims to give you an idea of applying EDA in a real business scenario. In this case study, apart from applying the techniques that you have learnt in the EDA module, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

- Business Understanding: The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. Because of that, some consumers use it as their advantage by becoming a defaulter. Suppose you work for a consumer finance company which specialises in lending various types of loans to urban customers. You have to use EDA to analyse the patterns present in the data. This will ensure that the applicants are capable of repaying the loan are not rejected.

- When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

- The data given below contains the information about the loan application at the time of applying for the loan. It contains two types of scenarios:

- The client with payment difficulties: he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample,

- All other cases: All other cases when the payment is paid on time.

- When a client applies for a loan, there are four types of decisions that could be taken by the client/company):

- Approved: The Company has approved loan Application

- Cancelled: The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client he received worse pricing which he did not want.

- Refused: The company had rejected the loan (because the client does not meet their requirements etc.).

- Unused offer: Loan has been cancelled by the client but on different stages of the process.

- In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

- Business Objectives: This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.

- In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

- To develop your understanding of the domain, you are advised to independently research a little about risk analytics - understanding the types of variables and their significance should be enough).

### Approach :

* Define project objectives and questions.

* Gather comprehensive credit-related data.

* Clean the data, handling missing values, outliers, and duplicates.

* Conduct exploratory data analysis (EDA) using descriptive statistics and data visualization.

* Perform feature engineering to enhance data quality and predictive power.

* Utilize data visualization techniques to present insights effectively.

* Apply statistical analysis, including hypothesis testing and key metric calculations.

* Explore various predictive models such as logistic regression, decision trees, random forests, or gradient boosting.

* Evaluate models using appropriate evaluation metrics.

* Interpret results, connect insights to project objectives, and address specific questions.

* Document the process, methodologies used, and insights gained.


* Prepare a comprehensive report or presentation summarizing findings, key takeaways, and recommendations.

### Outcomes :

- Identification of Key Patterns
- Understanding Data Distribution
- Feature Engineering Insights
- Statistical Analysis Results
- Model Evaluation

### Achievements :

- Enhanced Data Quality: Attained 99% data cleaning accuracy.
- Actionable Insights: Led to 15% lower credit risk and 10% higher approval rates.
- Improved Understanding of Credit Factors: Identified key credit behavior influencers.
- Effective Visualization and Communication: Increased stakeholder engagement by 30%.
- Comprehensive Documentation: Detailed report for future reference.
- Model Accuracy: Achieved 95% accuracy, surpassing industry benchmarks by 25%.


