# Customer_Retention

This Project was one of our Data Mining class project.

# Introduction
  Scholastic Travel Company is an educational tourism firm and customer retention is of key
  importance for it to grow sustainably. This is why the management has started a new data
  initiative where they want to develop a model that helps them predict whether or not a
  customer would book again in the future. The dataset provided has all the known information
  about the previous clients including multiple numerical and categorical variables such as
  total school enrollment, tuition, income level, travel and grade type etc.
  Since it’s a huge dataset with multiple variables and records, prior to fitting any models, we
  have cleaned the data to improve our operability. As part of the cleaning exercise, we also
  reduce the level of variable outcome by aggregating. We started by aggregating the
  categorical variables ‘From.Grade’ and ‘To.Grade’ into ‘Elementary’, ‘Middle’, and ‘High’
  class categories. Next, the ‘Days’ variable was aggregated into ‘Short_Length’,
  ‘Middle_Length’, and ‘Long_Length’ trip categories. Similarly, states were grouped into 5
  categories: NorthEast, MidWest, South, West, and missing. The above mentioned variables
  were converted to ‘Category’ type along with all of the other categorical variables in the
  dataset. Missing values were filled with either ‘Missing’ or 0 for character or numeric
  variables, respectively. Some of our categorical variables had rare levels, i.e. categories that
  only appeared less than 20 times in our data (arbitrary cutoff chosen by us). These categories
  were rolled up into an ‘Other’ category.
  Next, an exploratory data analysis was conducted to determine which variables could be
  disqualified as predictors. For example, we explored the relationship between the trip’s
  length, whether the customers were existing or new etc against their retention. This helped us
  refine our predictors.
  
  # Models Used 
  - KNN
  - Classficiation Tree
  - Logit Regression
  
