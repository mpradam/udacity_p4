# Income prediction and validation

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)
6. [Libraries](#libraries)

## Installation <a name="installation"></a>

There are no special requirements to run this project. The Anaconda distribution of Python should be more than enough, running with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

Assessing payment capacity is one of the most important issues when financial institutions need to assign credit limits. Although it might seem trivial, in some cases the information is no available, and due to the informality of some latinamercian economies (Colombia for this study case), it is important to build statistical models that can estimate the income of the customers. 

What question do we want to answer?

1. Can the income be modeled after the spending patterns of the household?
2. Can the income be modeled after the financial burden of the household?
3. Is there a possible way financial institutions can include this informetion in their models?


Acknowledgement
We are going to be using the data from the National Administrative Department of Statistics of Colombia DANE. The database is the result of a survey conducted to more than 25k households in three major cities in Colombia for 2018.

All the data and metadata can be found in [this link](http://microdatos.dane.gov.co/index.php/catalog/626). The data has 331 variables including spending behaviours and financial burden of the households.


## File Descriptions <a name="files"></a>

There is one notebooks available here to showcase work related to the above questions. The notebook is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

## Results<a name="results"></a>

Public available information can be used to identify what variables coud make for good predictors for income. This information can be used for financial entities to identify which variables are important to capture new information and include it in the models.

Further improvements can be made to both, the model and the insights extracted from it.

The model: There are almost 300 additional variables to extract information from. The problem is the underrepresentation of some variables.
Insights: Some further analysis can be made on the variables that we found important explaining the income. Some transformation and created variables can be used to do this.

The main findings of the code can be found at the post available [here](https://mpradam.medium.com/income-prediction-and-validation-ec7fece1cd8a).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to DANE for the data.  You can find the Licensing for the data and other descriptive information at the link available [here](http://microdatos.dane.gov.co/index.php/catalog/626).  Otherwise, feel free to use the code here as you would like! 

## Libraries<a name="libraries"></a>

The libraries used in this project are the following:

numpy, pandas, math, matplotlib, sklearn, seaborn and xgboost