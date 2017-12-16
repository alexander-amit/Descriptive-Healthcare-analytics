## Regression-Healthcare-analytics
### Overview:
  - Language: R
  - DataSet:
    - BRFSS: Behavioural Risk factor Survelliance system. Recommended. Contains large dataset
    - NHNES: National Health and Nutrition Examination Survey. Not recommended as low participation and rejection rate.
#### Risk factor surveillance - keeping track of the rates of risk factors which are things we do or states we are in that confer risk to our health. Ex - 14.7% of Massachusetts adults smoked in 2014.

### What is BRFSS Analyses: it is divided into 2 parts:
  - Descriptive: Aimed at developing population-based rating. Depends upon sampling approach-"uses weights" means we can predict how many people are out htere with certain condition, such as having no jobs,educated etc. Conclusion: Any particular having higher rates will imapct more the result/prediction. Ex - 51% are uneducated in population then framing policy will be impacted more by uneducated section as we use weights in Descriptive analysis.
  - Analytic(cross-sectional): all the variables are considered for finding the dependency.
### Why use BRFSS:
  - Data sets and related supportive files
  - Published reports
  - Codebooks, questionnaries and explanatory doc
#### Install following package:
  - foreign: read data in different formats
  - gtools: allows to make macros
  - dplyr: calculate means and standard deviations
  - questionr: weighted analysis
  - MASS: Allows you to do bivariate test


