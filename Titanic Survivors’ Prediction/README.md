# CMSE202_Final_Project
CMSE202 Titanic Survivor Prediction

Titus Merriam, Zhishan Li, Colin Williams

Required Packages:
1. numpy
2. pandas
3. matplotlib
4. seaborn
5. sklearn
6. keras

To run this notebook, ensure the datasets 'complete_titanic2.xlsx' and 'titanic.csv' have been downloaded.

These datasets include information about specific passengers that were aboard the Titanic.
The data fields within include:

complete_titanic2.xlsx - 

Name - The name of the passenger

Age - The age of the passenger in years

Class/Dept - For passengers - The class of ticket. For crew - The section they worked in

Ticket (Cabin) - Ticket information including price and number

Joined - The city in which the passenger boarded the ship

Job - The profession of the passenger

Survived? - The status of the passenger following the shipwreck, SAVED = lived, LOST = perished

Sex - 1 = Female, 2 = Male

Nationality - The nationality of the passenger

titanic.csv - 

pclass - The class of the passenger

survived - The status of the passenger following the shipwreck, 1 = lived, 2 = perished

sex - The sex of the passenger

Age - The age of the passenger in years

sibsp - The number of siblings and spouses aboard the Titanic for this passenger

parch - The number of parents and children aboard the Titanic for this passenger

ticket - The ticket number

fare - The price of the ticket

cabin - The number of the cabin

embarked - The city in which the passenger boarded the ship - C = Cherbourg, Q = Queenstown, S = Southampton

Group Contribution -

Titus Merriam - Wrote the code for several cells including the data importing, Random Forest classifier, Support Vector Machine and the SGD Classifier.

Zhishan Li - Created the powerpoint, organized meetings, wrote the first draft of the notebook, did the initial analysis, created several of the visualizations

Colin Williams - Created Neural Network and integrated into the presentation. Created Github repository and Readme.