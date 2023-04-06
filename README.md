# End to end machine learning project  

This is the a machine learning project ready to by deployed.  
The main task is to evaluate the "math score" for a student based on information about the parental level of education, testpreparation course, gender, race ethnicity, reading score, writing score.  
One can choose different parameters for this features on the site web form  and get the estimated "math score" in response.  

The following functions are implemented in this project:  
- data processing:  
  * data ingestion: getting and splitting the data  
  * pipelines for data transformation, including SimpleImputer, StandardScaler, OneHotEncoder for numerical and categorical features  
- training different models with various hyperparameters and saving the best one for deployment task  
- the project contains logging and exception modules, which are used through all the project  
- the web part implemented with flask contains two basic templates and a prediction pipeline
