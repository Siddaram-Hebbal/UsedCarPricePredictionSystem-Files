# Documentation (with full screenshots)
<p align = "center">
  <img src = "Img/user-manual.jpg">
  </p>

## Data Analytic Life Cycle

Data Science is an emerging interdisciplinary field. Altogether, data science is the science involved in studying the data. Data Analysis which is a part of data science has a life cycle composed of 6 phases. These phases include: Discovery, Data Preparation, Model Planning, Model Building, Communicate Results and Operationalize. The detailed data analytic life cycle can be found below:
<p align = "center">
<img src = "Img/lifecycle.PNG">
</p>
This project completely follows the data analytic life cycle. All the 6 phases can be seen above. These phases must be thoroughly understood by all the executives, engineers and analysts before moving to the user guide.

1. <b>Discovery</b>: In this phase the introduction followed by problem statement along with the current situation and the desired situation was drafted. All this detailed information can be found [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Discovery.ipynb).

2. <b>Data Preparation</b>: In this step all the necessary steps taken to prepare the data such as extraction,transformation,  loading  the  data  would  be  performed.   Further  the  data  was  be explored and conditioned by visualizing the results. The details of the data preparation can be found [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Data_Preparation.ipynb)

Shown below is the data set and its details.
<p align = "center">

<img src ="Img/access1%20(1).PNG">

</p>

<p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/detailsoffeatures%20(1).PNG">
</p>

3. <b>Model Planning</b>: In this phase all the variables were selected by performing the Chi-squared test and heat maps were used to select the most important variables. Also the model selection, category of techniques were performed. For more details visit [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Model_Planning.ipynb)

4. <b>Model Building</b>: In this phase splitting the data sets into 3 sets, choosing the model, checking for overfitting and underfitting conditions and the hyperparameter tuning were performed. For more details visit [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Model_Building.ipynb)

5. <b>Communicate Results</b>: In this phase all the findings, necessary steps to enhance the model along with the technical documentation, tool and users of the application was discussed. For more details visit [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Communicate\%20Results)

6. <b>Operationalize</b>: In this phase the django web application was built to predict the price was built. All the process details was given along  with elucidating the prominent features and working of the application. For more details visit [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Operationalize/Django\%20Application)



## Source Code User Guide for Engineers and Analysts

### Prerequisites
Below are some of the basic prerequisites that must be followed or being aware of:

1. <b>Required Hardware Configuration</b>: You don't need a computer with super-high specifications to run this project. But the higher the better. For example my system specifications is as shown below. Make sure your system meets these requirements. Keep your RAM as free as you can. 
<p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/system.PNG" width="500">
</p>

After having a look at the specifications it's now time to run the code. Follow the steps below for successful execution

1. Install Jupyter Notebook or Google Colab. If the code takes a lot of time to execute in Google Colab then user Jupyter Notebook instead. 
<p align = "center">

<img src="https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/JN.png" width="200"/> <img src="https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/GC.png" width="300"/>
</p>

Below are the download links

1. <b>Jupyter Notebook</b>: [Download](https://jupyter.org/install) or run this on your command prompt `pip install notebook`

Congratulations, you have installed Jupyter Notebook! To run the notebook, run the following command at the Terminal (Mac/Linux) or Command Prompt (Windows) `jupyter notebook`

2. <b>Google Colab</b>: [Download](https://colab.research.google.com/). Here you can open, upload or create a new notebook.
 <img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/new.png">
 
3. Clone or download my GitHub repository manually or from the command line. 

(Clone): [https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files.git](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files.git)
        
   <p align = "center">
     
<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/updategit.png" width="500">
</p>


Below are the folders that you can have a look after you clone or download

<p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/folder.PNG" width="500">

</p>

4. Navigate to the cloned folder from your command prompt using the following command:

`cd UsedCarPricePredictionSystem-Files-master`

Also, install all the required libraries and dependencies from the [requirements.txt file](https://github.com/Tanu-N-Prabhu/Used_Car_Price_Prediction_System1/blob/master/requirements.txt). You can do this using pip install command `pip install -r requirements.txt`

5. Open the individual jypyter notebook (.ipynb) on Jupyter notebook or Google colab. And then start running each and every cell. You can manually open and load all the notebooks on Google Colab. But to open specific notebooks in Jupyter Notebooks use: `jupyter notebook notebook.ipynb`

The jupyter notebook file in this case would be [Data Discovery](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Discovery.ipynb),[Data Preparation](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Data_Preparation.ipynb), [Model Planning](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Model_Planning.ipynb), [Model Building](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Model_Building.ipynb), [Model Saving](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Model_Saving.ipynb), [Random Forest Manual Tuning of Parameters](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Random_Forest_Manual_tuning_of_parameters.ipynb), [Random Forest Using Grid Search CV](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Random_Forest_Using_Grid_Search_CV.ipynb).

## Data Set Preparation

Here the data set was not created from the scratch. The data-set was retrieved from [data.world](https://data.world/data-society/used-cars-data). Then all the splitting of data was done as shown below:

1. To access the raw data set please visit [here](https://drive.google.com/open?id=10uHx8frC71x5cpAPEcyUwjRzW5fJe4GU). Since the raw data set was very larger I stored it in my drive. First please all the four sets of data sets from my repository and store it on your google drive. 

    1. Raw Data set: Download [here](https://drive.google.com/open?id=10uHx8frC71x5cpAPEcyUwjRzW5fJe4GU)

    2. Cleaned Data Set: Download [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Cleaned\%20Dataset)

    3. Training Data Set: Download [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Testing\%20set)

    4. Testing Data Set: Download [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Testing\%20set)

    5. Validation Data Set: Download [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Validation\%20set)
  
 After downloading all the data set, don't forget to mount your drive from Google Colab and then you will need to provide a access key which will be prompted on your screen. 
 
 
 <p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/mount.png" width="300">
    
  </p>
For any data set to covert and load it as a pandas data frame please use the following code.

```
# Import the packages
import pandas as pd

# Storing the dataset (CSV file) as a pandas dataframe

df = pd.read_csv("/content/drive/My Drive/Dataset/CleanedData.csv")   

df.head(5)
```

Don't forget to add the path of the dataset from your drive. Similarly there is two way you can load the data sets. One is shown above just loading it manually. Other is using the `scikit-learn` library to split and load the data set as training, testing and validation. 

```
# Import the packages
import pandas as pd
from sklearn.model_selection import train_test_split

# Storing the dataset (CSV file) as a pandas dataframe

df = pd.read_csv("/content/drive/My Drive/Dataset/CleanedData.csv")   

selectedFeatures = ['yearOfRegistration','powerPS','model','kilometer','monthOfRegistration','fuelType','brand','postalCode','vehicleType_0','vehicleType_1','vehicleType_2','vehicleType_3','vehicleType_4','vehicleType_5','vehicleType_6','vehicleType_7','gearbox_0','gearbox_1']

X = df[selectedFeatures]
y = df['price']

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.1, random_state=1)
X_train, X_val, y_train, y_val = train_test_split(X_train, y_train, test_size=0.15, random_state=1) 

```

Make sure you load the [cleaned data set](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Cleaned\%20Dataset), because the [Raw data set](https://drive.google.com/open?id=10uHx8frC71x5cpAPEcyUwjRzW5fJe4GU) needs to be explored. Details of this can be found [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Data_Preparation.ipynb)

## Model Planning and Building

Below are the necessary notebooks that performs the above phases. Since this category of the data set falls under supervised machine learning algorithm,the regression estimator was applied on this dataset.  Out of the four regression algorithms namely:  Linear Regression, Decision Tree Regression, Random Forest  Regression  and  Support  Vector  Regression,  the  Random  Forest  Regression gave  better  results  in  terms  of  prediction  accuracy,  mean  squared  error  and  mean absolute error.  More details of the performance can be found in the above chapter5 under model performance assessment.  Before applying the regression algorithms,the  correlation  between  two  variables  (independent  and  dependent  variables)  were detected and then the dependent variables which are the price of the used car was later predicted.  Basically, the categorization of the variables which is the dependent are the price and the independent variables are the features of the used car except the price was done in this stage.  And then the regression algorithms were applied until a good accuracy score which was presentable.  In this case, Random Forest Regression gave an accuracy score of around 86.019%


1. Random Forest Regression: The necessary notebooks are:
    
    1. [Model Planning](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Model_Planning.ipynb)
        
    2. [Model Building](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Model_Building.ipynb)
     
    3. [Manual Tuning of Hyper Parameters](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Random_Forest_Manual_tuning_of_parameters.ipynb)
    
    4. [Tuning using Grid Search CV](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Random_Forest_Using_Grid_Search_CV.ipynb)
    
    5. [Model Saving](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Model_Saving.ipynb)
    
    
Make sure all the path of the data sets are correct. And also while executing these notebooks please change my path location to your path stored location. Other you will get a path error. In google colab as you mount your drive where the data sets are stored, you can then right-click to get the path location and then paste it in the `read_csv()`.
    <p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/path.png" width="300">
</p>
To reduce the execution time, you can visit the [Model Saving](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Model_Saving.ipynb) and try to save your model as a .sav file. The advantage of this is that the model would run faster then ever before. This is because the model is already loaded and saved by me.


## Operationalize User Guide for Executives, Engineers and Analysts

### Django Web Application Hosted on Heroku Cloud Platform

If you only want to execute the application and not worry about running the model files. Then you are in the right place. Just ignore all the above steps and start following the new steps to successfully execute the application. But there is one important point, make sure that you have installed the necessary libraries from the [requirements.txt](https://github.com/Tanu-N-Prabhu/Used_Car_Price_Prediction_System1/blob/master/requirements.txt). You can just use

`pip install -r requirements.txt` or `pip install library_name`

There are two ways you can execute the application: Manually deploy the application from scratch or just opening the website link to.

#### Manually deploying the application from GitHub

1. This is a pretty long and straight forward process. Because here you need to create a new profile on Heroku, connect your GitHub Repository to it and then deploy the code. Please visit the [setup guide](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/SetUp\%20file/SetUp\%20Guide.pdf) to get more details about this process. 
    
2. For this process your main key repository would be [Operationalize](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Operationalize/Django\%20Application). First clone or download the folder to your local system and then follow the [setup guide](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/SetUp\%20file/SetUp\%20Guide.pdf) to get more details about this process. 
    <p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/deploy1.PNG" width="500">
</p>

#### Opening the web application link via browser

This is a pretty much one of the easiest steps to execute a application. Now you don't have to worry about installations. All you need here is a browser and a fairly good internet connection. Because at the end of the day this is what matters (The final product). Since this is deployed on the Heroku cloud this link can be accessed from anywhere(from earth). Open the below given link from your browser:

Website application link: [Link](https://ucpps.herokuapp.com/ucpps_app/home.html)

The moment you open the application just feed the value of your car and get to how much your car is worth from the predict button. If you are not satisfied from the results then you have an option to give feedback (to me).

## Application Screenshots

The application has two types of input options: Number field, where the user has to enter the desired number of their choice with respect to their used car and drop down menu where the user has to select a provided option given in the menu. Later when the user clicks on the submit button the model predicts the price based on the values given by the user and then displays underneath the submit button.

<p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/finalwebsite.PNG" width="500">
</p>


## Working of the application

The working of the application is pretty trivial. First, the user must enter all the desired feature values of their used car as inputs to the form field as shown below:
<p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/working.PNG" width="300">
</p>


As seen above the predicted price for the Mercedes Benz B class model is about 6387 euros where the original price was 6500 shown below. Just for comparison from this we can see that the prediction rate of the model is quite accurate.
<p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/original.PNG" width="500">
</p>

## Features of the application
1. Secure link: Firstly the application is secure. [Heroku Cloud application platform](https://www.heroku.com/) by default provides SSL certificate, issued by DigiCert. The application uses HTTPS instead of HTTP, so data sent through our application will be safe. Below figure indicates the secure connection of our application and the certificate information is also depicted.
    
    <p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/secure.png" width="500">
</p>

<p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/digi.PNG" width="300">
</p>

2. The application is very roboust


    1.   Incomplete form submission is not allowed: All the values in the forms (textfields, dropdown) must be entered. Skipping the forms will lead to a warning (Please Fill this field). A user cannot submit a empty form or a incomplete form. To allow smooth performance of the application all the values has to entered only then the form can be submitted. Show below are the use cases for the both conditions.
    
    <p align = "center">

    <img src="https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/rob1.PNG" width="200"/> <img src="https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/rob2.PNG

</p>

    2. Character values cannot be entered in the interger fields: In some of the forms such as kilometer the user has to enter the numeric values, other than numeric the user cannot enter any values. This is the speciality of Django's integer field method which only accepts integers. Since the model accepts only numeric values this feature was very helpful.


<p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/rob3.png" width="500">
</p>


3. Responsive: The whole application is mobile-friendly. The application adjusts itself to different aspect rations. This is the functionality of using bootstrap. Below is the screenshot take from my mobile phone (One Plus 6T).

<p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/Screenshot_20200407-185348%20(1).jpg" width="300">

</p>
 4. Feedback option: This application has a feedback option. The user if they are not satisfied with the resuts or they wanted the application to be improved then they can give the feedback which is located below the submit button. The feedback form was not design from scratch, meanwhile it was extended from [jotform.com](https://www.jotform.com/).
    
 <p align = "center">

<img src = "https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/Img/feedback.PNG" width="500">
</p>    

## Maintenance User Guide for Engineers and Analysts

There is always scope for improvement. Since there are many different car brands and model, new model or used car model keep increasing every month. In the future if there is an addition of a new car with respect to brand or model or in other words you need to update the data set follow the below steps to have code up and running.


1. Visit the [Data Preparation]({https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Data_Preparation.ipynb) notebook and change the path of the old data set to the new data set. You need to again perform all the operations on the existing data sets like exploration, conditioning. Follow the same steps given in the notebook. 
    
2. After successfully cleaning the data, now you have to plan and build the model. Now you can change or remove the features in the [Model Planning phase](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Model_Planning.ipynb). But in the model building phase split the new cleaned data set into three set, and execute all the given cell. As normal compare the results of all the models and then choose the best one for operationalize. You can also add any learning algorithm if you think it gives good results in this phase.
    
3. Finally when it comes to deploying on Heroku. Make sure you commit all the files on GitHub and deploy the branch. The place where you need to put the main code is the [views.py](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Operationalize/Django\%20Application/ucpps_app/views.py) file. If at all you need to update the UI don't worry navigate to the [template folder](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Operationalize/Django\%20Application/template) and do the changes. Once all is done, don't forget to commit and deploy the changes on the Heroku cloud.


        
        

