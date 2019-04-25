## Graduate Admission Predictor for student and University

<b> Goal</b><br>
The goal of the model is to cover two aspects of Graduate Admission:<br>
 - Students : Building a Machine Learning model to help the aspiring graduate students to narrow down the universities choices in Computer Science in USA<br>
 - University: Building a Machine Learning model to assist the university in selecting suitable candidates for the CS Program<br>

<b> Approach </b><br>
- Data Gathering : Scraped the dataset from Yocket, Edulix which consists of 9 columns and 9351 for 29 universities in USA<br>
- Data cleaning, Data Processing feature Engineering<br>
- Data Models for students and University : Classification Models<br>
- Error metrices calculation: Using confusion metrix to calculate Accuracy,F1 score and AUC curve<br>
- Pipeling: Using Dask for Pipelining<br>
- Dockerizing: Dockerizing the environment<br>
- Deployment: deploying the code on Heroku and Amazon AWS S3<br>

<b> DataSet Used</b><br>
 - Assisting Student Model : Dataset for 29 colleges across USA ranging from Rank 1 to Rank 130 in computer science department<br>
 - Assidting University Model: Dataset for Northeastern University, Boston<br><br>

<b>Using our Application</b><br><br>

#### Assisting Student Model :<br>
<b>URL for the application:</b> https://grad-school-predictor.herokuapp.com/ <br>
Steps to reproduce:<br> Covers 2 functionality of showing acceptance.rejection of the college <br> Also displaying him with the list of 5 colleges where they will be likely to get most admits
![image](https://user-images.githubusercontent.com/37238004/56715198-ff2a4080-6704-11e9-9e65-6cef85daefbb.png)

##### Assisting University Model :<br>
Steps to reproduce:<br> This is for the Northeastern University to admit or reject a candidate based on the model prediction
![image](https://user-images.githubusercontent.com/37238004/56716147-92fd0c00-6707-11e9-8e26-caaa72edd874.png)






