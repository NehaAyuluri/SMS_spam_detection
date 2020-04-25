# SMS spam detection

This project involved detection of  spam SMS using Machine Learning. Dataset is available in Kaggle.
<br>Link: https://www.kaggle.com/uciml/sms-spam-collection-dataset

**Steps involved:**
  <li>  Loading data and importing necessary text analytics packages
  <li>  Check word counts of spam and non spam SMS <li>
        <img width="379" alt="spam1" src="https://user-images.githubusercontent.com/47410643/79669585-841a2f80-818a-11ea-8c70-23eac0d3fb9c.PNG">
    
   <img width="384" alt="spam2" src="https://user-images.githubusercontent.com/47410643/79669595-9bf1b380-818a-11ea-926d-1a80949f9f90.PNG">
   <li>Top words in spam messages </br>
  
<img width="461" alt="spam3" src="https://user-images.githubusercontent.com/47410643/79669607-ae6bed00-818a-11ea-814f-cdad17eb0771.PNG">

<li>  Perform required text cleaning
<li>  Modelling: Uses Keras for Deep Learning
<li>  Obtained a test accuracy of 98%  
  
 ## Cloud deployment
 
The model was deployed in cloud using the following steps:

<li> A flask application was created in cloud9 environment
<li> Required HTML and CSS files were loaded in place to provide a simple user interface
<li> Once the flask application was tested locally it was containerized and pushed into Dockerhub
<li> To test the application, a new environment was created and file was pulled from DockerHub and tested
  
![image](https://user-images.githubusercontent.com/47410643/80268600-8b53a880-8676-11ea-8f68-aa7cf2b571f2.png)

<li> User can enter the text and predict weather its a spam or not
  
![image](https://user-images.githubusercontent.com/47410643/80268631-cf46ad80-8676-11ea-9df2-d78de0d495ea.png)
  
![image](https://user-images.githubusercontent.com/47410643/80268638-ee453f80-8676-11ea-8334-3092c33cb513.png)  
  
  
  
  
  
  
  
          
