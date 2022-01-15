# ML_Model_Deployment_Flask  
Deploy a Machine Learning models in production as APIs(Flask)  
  
This project demonstrates use of Flask web framework for model deployment.    
    
FLASK is a python web framework that allows to build REST based API services quickly with minimum configuration and hassle.    
Its build around Werkzeug and Jinja.    
  
## Problem Statement :  
We use the telecom churn prediction problem for showcasing the deployment. The output of the model is either 0(Not Churn) or 1(Churn).  
We would follow the machine learning pipeline for this. The steps followed are as follows:  
  
1.	Data Acquisition  
2.	Data Pre-Processing  
3.	Feature Engineering  
4.  Train the Model  
5.	Save the Model  
6.	Create an API using Flask  
7.	Test API in Postman  
8.	Create a Webpage and test the application  
  
## How to run the application ?  
  
Option 1 : Through the web page UI application (preferred for users):  
  1.1 Run : python app.py  
  1.2 Open the local host server URL running in a browser  
  1.3 Input the required features and click on predict button to get the the ouput as churn or not  
    
Option 2 : Through the terminal for debugging:  
  2.1 Run : python request.py
  2.2 Update and run the request json data as and when needed 
