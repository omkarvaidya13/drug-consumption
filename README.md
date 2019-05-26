# drug consumption dataset
Data Mining - Drug Consumption Dataset

Drug Consumption Dataset URL : https://archive.ics.uci.edu/ml/datasets/Drug+consumption+%28quantified%29

Programming Language Used : R

The main objective of the project is to perofrm analysis on the dataset and gain insight on the factors which can influence a person to consume drugs.

The dataset contains records for 1885 respondents. For each respondent 12 attributes are known : personality measurements which include (neuroticism, extraversion, openness to experience, agreeableness, conscientiousness, impulsivity, sensation seeking) , age, gender, level of education, country of residence and ethnicity.
For each drug the consumption of drug by the user is mentioned which is broadly categorized into the following - never used the drug, used it over a decade ago, or in the last decade, year, month, week, or day.

The data mining technique used is Classification. 

Naïve Bayes Classifier is used to perform the classification. 

This technique is best suited for the classification of the dataset as all the attributes which determine the drug consumption are independent of each other and the drug consumption is dependent on the probabilities of individual attributes. ( Age, Gender, Education, Neuroticism, Extraversion, Openness, Agreeableness, Conscientiousness, Impulsiveness and Sensation).

The different activites performed in the project are as follows :
1.	Operations on Dataset – Decoding the data values, Initial visualization to obtain insight on attributes of data.
2.	Understand each attribute and it’s values.
3.	Transformation of the dataset – Scaling of dataset, Cross-validation of data (Data Partitioning)
4.	Implementing Naïve Baye’s classifier on the data set and prepare visual aids for the results of data mining.

To know in detail description of the project, have a look at the report given : Data Analysis-Drug Consumption Dataset.pdf

To know the source code, have a look at the R file given : analysis.R
