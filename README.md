![image](https://github.com/sonila15/Online_Shopping_Intention_Model/assets/118692087/0dc919df-63b7-4e82-b6d1-9d8fc31ef5d3)

# Online_Shopping_Intention_Model

- Source: The dataset is sourced from the UCI Machine Learning Repository, a well-known repository for machine learning datasets.
- Purpose: The dataset aims to analyze and understand online shoppers' purchasing intention and behavior, providing valuable insights for e-commerce businesses.
- Features: The dataset consists of various features that capture different aspects of online visitor behavior and characteristics. These features include:
  - Administrative, Informational, and Product-Related Pageviews: The number of pages visited by the user in each category.
  - Administrative, Informational, and Product-Related Duration: The total time spent by the user on each category of pages.
  - Bounce Rates: The percentage of visits that resulted in only a single page view.
  - Exit Rates: The percentage of visits that ended on a particular page.
  - Page Value: The average value of the pages viewed by the user.
  - Special Day: A binary feature indicating whether the visit occurred on a special day (e.g., holidays, promotional events).
  - Month: The month of the year when the visit occurred.
  - Operating System, Browser, Region, Traffic Type: Features capturing user device and location information.
  - Revenue: The target variable indicating whether a purchase was made (TRUE) or not (FALSE).

# Model Selection
For the project, we analyze machine learning models in order to define the best model as the one that generalizes the best on future data. The models analized are:

  - ## Decision Tree that is a supervised learning algorithm that is used for classification and regression modeling. These trees are used to either classify data or predict what will come next. The results obtained were:
  
  ![image](https://github.com/sonila15/Online_Shopping_Intention_Model/assets/118692087/9caff2a8-3421-4788-9ba4-688f7392f4ac)

  - Random Forest which combines the output of multiple decision trees to reach a single result. The random forest algorithm provides a higher level of accuracy in predicting outcomes over the decision tree algorithm. The results obtained were:
  
  ![image](https://github.com/sonila15/Online_Shopping_Intention_Model/assets/118692087/37669ba9-5dba-46b8-bdba-c60463536b29)
  
  - Logistic Regression Model, that is used for predicting the categorical dependent variable using a given set of independent variables and it is used for solving the classification problems. The results obtained were:
   
   ![image](https://github.com/sonila15/Online_Shopping_Intention_Model/assets/118692087/67af0cd0-b487-4003-a360-a49efac128c1)

  - Support Vector Machine (SVM). It is a model with associated learning algorithms that analyze data for classification and regression analysis. However, primarily, it is used for Classification problems in Machine Learning, for example SVM Face detection, image classification, text categorization, etc. The results obtained were:
 
 ![image](https://github.com/sonila15/Online_Shopping_Intention_Model/assets/118692087/996ffd0e-254e-4315-bcf3-517ba263e88d)




