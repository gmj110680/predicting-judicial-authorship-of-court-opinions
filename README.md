## Springboard Capstone Project 2 - Predicting Judicial Authorship of Court Opinions

For this project, my goal is to build a multi-class text classifier that is able to accurately predict which judge authored a particular court opinion based on the text of that opinion.  The dataset used for this project was made publicly available by Harvard Law School's Caselaw Access Project.  Harvard has made a few state's caselaw decisions publicly available for bulk download [here](https://case.law/bulk/download/).  I elected to use the North Carolina caselaw database for this project. 


### Project Summary

In this project, I was able to build two models that could identify the judicial author of a court opinion at an overall accuracy rate of approximately 75% and 76%, respectively.  Given that the models had a pool of over 160 judges to choose from, generating accuracy rates as high as 75% indicates that the models were successfully able to identify meaningful distinctions between each of the judges' particular set of written opinions.

Overall, this project demonstrates that attempting to build machine learning models to identify judicial authorship of case decisions is a worthwhile endeavor that can provide real, tangible value to the legal industry.  The particular use cases for such a model are many.  For example, a practitioner could use a model to analyze a brief to be filed in order to see which judge or judges the text of the brief most resembles.  One could also feed opinions of a particular judge that were not used during training into the model to see which judge or judges the model finds to be most similar.  Or a practicing attorney could even simply perform some deeper analysis on the results of a fully-trained model to uncover more details about a particular judge (e.g., common word usage, grammatical patterns, etc.).  The potential for accurate judicial authorship classifiers is substantial.


### Iterative Project Work

The notebooks in this repository provide my findings and analysis at various stages of this project.  Please note - because the project is ever-evolving, some of the approaches and strategies discussed in these notebooks may change as my work progesses.  A brief description of each file is as follows:

-  [Data_Wrangling](https://github.com/gmj110680/predicting-judicial-authorship-of-court-opinions/blob/master/Data_Wrangling.ipynb): This file provides a narrative summary of the initial data wrangling steps I took to convert the dataset from its original `JSON` file into a format more compatible for my analysis.

-  [Data Preprocessing](https://github.com/gmj110680/predicting-judicial-authorship-of-court-opinions/blob/master/Data_Preprocessing.ipynb):  This notebook summarizes the steps I took to transform the data from its original format to a format ready for analysis.

-  [Exploratory Data Analysis](https://github.com/gmj110680/predicting-judicial-authorship-of-court-opinions/blob/master/Exploratory_Data_Analysis.ipynb):  This notebook outlines some exploratory data analysis that I performed to better understand my corpus of judicial opinions.

-  [Machine Learning](https://github.com/gmj110680/predicting-judicial-authorship-of-court-opinions/blob/master/Machine_Learning.ipynb):  This notebook provides a detailed, step-by-step explanation for how I successfully built two classifiers that are able to predict judical opinion authorship at approximately a 75% success rate.

-  [Final Analysis](https://github.com/gmj110680/predicting-judicial-authorship-of-court-opinions/blob/master/Final_Analysis.ipynb):  This notebook analyzes the final performance of the two judicial authorship classifiers that I built and then provides some overall conclusions and possible avenues for future work on this project.

-  [Final Report](https://github.com/gmj110680/predicting-judicial-authorship-of-court-opinions/blob/master/Final_Report.pdf):  This narrative report provides a summary of the entire project without the accompanying code, which can be found in the above-listed notebooks.


If you found this project interesting and/or have any feedback, I'd love to hear from you!  You can reach me at <jacobs.greg@gmail.com>.
