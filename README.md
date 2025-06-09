# Data Analytics Portfolio

# About
I am Cynthia Nakachwa and I have a strong foundation in mathematics and statistics. This is a display of my technical and analytical skills to the field of data. I have enjoyed exploring new data analysis tools and techniques, and I am always looking for new opportunities to expand my knowledge and skills, whether individually or through team work. I am driven by the ability to use statistical analysis to solve complex problems.

This is a repository to showcase my capabilities, share projects and track my progress in Data Analytics
# Table of content
[About](#About)\
[Portfolio projects](#Portfolio-projects)\
python
* [What factors can be analysed to determine the success of the banks marketing strategy](#Bank-Marketing-Strategy)
* [Predicting the price of used cars depending on its specifications](#Cars)
* [Based on what information should we predict whether an employee is expected to be absent or present?](#Absenteeism)

SQL
* [The organisation seeks to ensure data accuracy and alignment with business policies regarding employees records and salary structures](#Business-case)

Tableau -> [go to Tableau](https://public.tableau.com/app/profile/cynthia.nakachwa/vizzes)

[Certificates](#Certificates)\
[Contact](#Contact)

# Portfolio projects
In this section, i will list the data analytics project briefly describing the technology stack used to solve cases

## Bank Marketing Strategy
Code: [What factors can be analysed to determine the success of the banks marketing strategy](https://github.com/CynthiaMiriam/Data-Analyst-Portfolio/blob/main/Bank%20marketing%20analysis.ipynb)

Overview:
*  Previous - shows whether the last campaign was successful with the consumer.
*  march & may - when the last call was made to the specific customer
*  credit - shows if the customer had enogh credit to avoid defaulting
*  duration - the time since the last contact with the customer

Skills: data cleaning, logistic regression, data visualization\
Technology: python libraries(pandas, numpy, Matplotlib, sklearn, seaborn)

Results: The model to determing the success of a bank marketing strategy using the above factors was 86.04%

## Cars
code: [Predicting the price of used cars depending on its specifications. ](https://github.com/CynthiaMiriam/Data-Analyst-Portfolio/blob/main/used%20cars.ipynb)

Problem statement\
Predict the price of a used car depending on its specifications.

Preprocessing
* Handling missing variables, the missing values where drop since they represented less than 5% of the data
* Outliers, removing the 99th percentile of the outliers on some and impossible values for others
* Checking and relaxing the ordinary least square assumptions.
* Ensuring consistency in the data types 
* Declare the inputs (Mileage, EngineV, (Body, Brand, Engine Type and Registration categories)) and targets (price).  Then scale your data to fix the difference in magnitude of the variables.

Skills: data cleaning, linear regression, data visualisation\
Technology: python libraries(pandas, numpy, Matplotlib, sklearn, seaborn, statsmodels)

Top Predictors
*  Registration (yes) 45%
*  Mileage 7%
*  EngineV 8%
*  Brand (Mitsubishi) 7%

Results:
* 	A positive weight on EngineV shows that as it increases so does the price respectively.
* 	A negative weight on Mileage shows that as it increases, the price decreases.
*  A positive weight shows that the respective brand is more expensive than the Audi.
*  A negative weight shows that the respective brand is less expensive than the Audi.
*  A positive weight shows that the respective body is more expensive than the crossover.
*  A negative weight shows that the respective body is less expensive than the crossover.
*  A positive weight shows that the respective Engine Type is more expensive than the Diesel.
*  A negative weight shows that the respective Engine Type is less expensive than the Diesel.
*  A positive weight shows that the respective Registration ‘yes’ is more expensive than the benchmark ‘no’.



## Business case
code: [The organisation seeks to ensure data accuracy and alignment with business policies regarding employees records and salary structures](https://github.com/CynthiaMiriam/Data-Analyst-Portfolio/blob/main/Business%20case.sql)

Overview: By analyzing trends in salaries and department changes, as well as validating key data fields such as hire date, the company can improve decision-making, compliance and workforce planning.

Problem statement
* 	Understanding how employees’ salaries evolved overtime.
*  Tracking the most recent department where the employee is working.
*  Ensuring that the hire dates entered into the system are valid and not set to future dates.

Skills: Joins, Triggers, Procedures, Functions.\
Technology: SQL

Results:
* Visualization salary trends over time
* Tracking employee departments
* Ensuring data integrity 


## Absenteeism
code: [Based on what information should we predict whether an employee is expected to be absent or present?](https://github.com/CynthiaMiriam/Data-Analyst-Portfolio/blob/a9bf4e9095086dd1c1ff87d6a003a59e899f4f44/Absenteeism%20Machine%20Learning%20(all%20inputs%20standardized).ipynb)

Target: Divided the absenteeism in hours into two classes that is moderately absent and excessively absent. 

Overview: Absence from work during normal working hours, resulting in temporary incapacity to execute regular working activities.

Data Preprocessing: [Preprocessed data](https://github.com/CynthiaMiriam/Data-Analyst-Portfolio/blob/main/Absenteeism.ipynb)\
Splitting the reasons for absence into multiple dummy variables, and then group them in the following ways with no reason as the baseline:  
* Reason type 1: Various diseases
* Reason type 2: Pregnacy and giving birth
* Reason type 3: Poisoning
* Reason type 4: Light diseases

Skills: Data Preprocessing, Exploratory data analysis, Model selection and evaluation, Deployment\
Technonolgy: python libraries (pandas, numpy, Matplotlib, sklearn)

Top Predictors:
* Various diseases 19%
* Poisoning 15%
* Light diseases 26%
* Transport expenses 17%
* Children 11%

Results:

# Certificates
Here is a list of the ones i have.
* Course: [SQL - MySQL for Data Analytics and Business Intelligence](https://www.udemy.com/certificate/UC-a555ae99-f4d7-45dc-a6a6-2b5045b14d71/)\
  Institution: Udemy
 
* Course: [Linux Shell Scripting](https://www.udemy.com/certificate/UC-1bc76ee0-7416-406f-8654-5543c8cfc0dc/)\
  Institution: Udemy 
  
* Course: [The Data ScienceCourse](https://www.udemy.com/certificate/UC-a7326c3d-ba65-48bd-b1df-523f7227f5af/)\
  Institution: Udemy
  
# Contact
LinkedIn: [linkedin.com/in/cynthianakachwa](https://www.linkedin.com/in/cynthia-nakachwa/)\
Email: cynthiammiriam@gmail.com
