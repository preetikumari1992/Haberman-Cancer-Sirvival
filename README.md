# Haberman-Cancer-Sirvival

A dataset of breast cancer patients is given and predict whether patient will survive next 5 years or not based upon patient's **Age, Operation Year, NO. of Lymph nodes**. We have the dataset contains cases from a study that was conducted between 1958 and 1970 at the University of Chicago's Billings Hospital on the survival of patients who had undergone surgery for breast cancer.



## Table of Contents:
*[content]
*[technology]
*[objective]
*[conclusion/observation]




### CONTENT : 


305 datapoints/rows
4 fearures includeing class label

(**4 features** including class label/dependent variable.

30 - It represents age of patient at the time of operation(numerical)
64 - It represents year of operation(numerical)
1 - It tells no of +ve auxillry node detected(numerical)
1.1 - Survival status 1 = the patient survived 5 years or longer 2 = the patient died within 5 year)



#### TECHNOLOGY: 
Python 3.x


##### OBJECTIVES

To predict a patient survival for next 5 years who had undergone surgery for breast cancer. 
We convert Survival_status from numerical to categorical data type and use Univariate analysis to see whether an independent variable affects the target variable or not.
We use Bivariate analysis to see the relationship between numerical variables which will infer about the survival_status of a patient.


###### OBSERVATIONS

**Univariate analysis**


*_PDF plot_* 

We observed approx 60% people having 0 to 5 lymph_nodes may survive and approx 10% died as well.



*_CDF plot_*

CDF plot of age: Almost 18% people of AGE below or equals to 40,survived.
CDF plot of lymph_node: People having 8 or more lymph_node are not survived.


*_BOX plot_*

There are no missing values and outliers present in the dataset.



*_VIOLIN plot_*

VIOLIN plot of lymph_node: Approx 80% have equals to or less than 5 lymph nodes. Lymph node plot is highly densed for 0 to 5 lymph nodes.
VIOLIN plot of operation year: Patients treated before 1955 have lower chance to survive and after 1962 have higher chance to survive.



*_SCATTER plot_*

It gave us relationship between independent variable and target(dependent) variable, which is a non-linear relation here. 
More patient survived having 0 to 5 lymph nodes.



*_PAIR plot_*


So much of overlapping cause non-linear relationship between independent numerical variables hence, Linear Regression will be unappropriate algorithm to be used for its predictive modelling.

Patient of age 64-68 with 5 to 10 lymph nodes have more chances to not survive/die.




**CONCLUSION**


~~ This is an imbalanced dataset with no particularly defined class.Its high overlapping of classes cause non-linear relationship between variables which is difficult to classify using regression method. The survival status of patient dependency on lymph nodes is somehow realisitic/relatable. 

**We need to use some other clustering mnethods like 'K-means' etc to classify this non-linear dataset and to predict patient's survival status in future**.







