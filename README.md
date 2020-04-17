# Used Car Price Prediction System - Necessary Code Files 

## This repository comprises all the necessary code file of the project.
<p align = "center">
  
  <img src = "https://i.imgur.com/aJMp43P.png" width = "500">
</p>

<b align = "justify"> The whole project is based and follows the data-analytic life cycle shown above.</b>


# Installation tools

### Below are some tools that you can download, now it’s a preference, so download whichever that fits the best for you.

| Name of the tools | 
| ------------- |
|[Python download](https://www.python.org/downloads/)|
|[Pycharm download](https://www.jetbrains.com/pycharm/download/#section=windows)|
|[Jupyter Notebook](https://jupyter.org/install)|
|[Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb)|
|[Visual Studio IDE](https://code.visualstudio.com/)|
|[Django](https://www.djangoproject.com/)|



<p align="justify"> For those of you who aren't aware of Pycharm: PyCharm is an integrated development environment used in computer programming, specifically for the Python language. It is developed by the Czech company JetBrains (Psss, copied from Wikipedia).</p>

<p align = "justify">I personally use Google Colab for python programming. It's one of the best interactive tool in the world. I like it because I can provide more documentation to the code and write some quality tutorials.</p>

<b>Also, you might wanna install the necessary libraries in your terminal (Command Prompt), because you need to manually install them<b>
There are two ways you can do this
1. Download from the [requirements.txt](https://github.com/Tanu-N-Prabhu/Used_Car_Price_Prediction_System1/blob/master/requirements.txt) file 
  
2. Manually install them from below:

    `Django==3.0.3`
    
    `googletrans==2.4.0`
    
    `gunicorn==20.0.4`
    
    `matplotlib==3.1.3`
    
    `numpy==1.18.1`
    
    `pandas==1.0.1`
    
    `scikit-learn==0.22.2.post1`
    
To install any of the above library navigate to your command prompt and then tell `pip install library-name`. If you don't have `pip` installed already then you might see a error. Download it [here](https://pypi.org/project/pip/)



# Repository Contents

<b>This repository comprises all the necessary code files</b>

1. Project Code and all necessary files for verification
   
   1.1 Data
    
      a. Raw data set (Uncleaned Data) --> Click [here](https://drive.google.com/open?id=10uHx8frC71x5cpAPEcyUwjRzW5fJe4GU) to download 
      > Since the size of the dataset was very large it was unable to store it on GitHub, this is why I have provided the google drive link
      
      b. Raw data set (Uncleaned Data) --> Click [here](https://drive.google.com/open?id=10uHx8frC71x5cpAPEcyUwjRzW5fJe4GU) to download
      > Since the size of the dataset was very large it was unable to store it on GitHub, this is why I have provided the google drive link

      c. Cleaned data set --> Click [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Cleaned%20Dataset)
      > This the cleaned data used in the data exploration, model building phase. 

      d. Training data set --> Click [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Testing%20set)

      e. Testing data set --> Click [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Testing%20set)

      f. Vaidation data set --> Click [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Validation%20set)
      
    1.2 [Self-contained Setup Guide](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/SetUp%20file): Click [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/SetUp%20file) to view it. All the requirements to run the code.
    
    1.3 Code/Set Up files
    
    Below are the interactive python notebooks

      1.3.1 [Data Discovery](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Discovery.ipynb)

      1.3.2. [Data Preparation](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Data_Preparation.ipynb)

      1.3.3. [Model Planning](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Model_Planning.ipynb)

      1.3.4. [Model Building](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Model_Building.ipynb)

      1.3.4.1 [Manuall Hyper Parameter Tuning](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Random_Forest_Manual_tuning_of_parameters.ipynb)

      1.3.4.2 [Grid Search CV](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Random_Forest_Using_Grid_Search_CV.ipynb)

      1.3.5. [Model Saving](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Model_Saving.ipynb)
      
      1.3.6 [Deployment](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Operationalize/Django%20Application)
      
    1.4 [Documentation](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Documentation) (with full Screenshots)
    
      1.4.1 [User-guide for engineers](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/User_Guides.pdf)
      
      1.4.2 [User-guide for analysts](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/User_Guides.pdf)
      
      1.4.3 [User-guide for executives](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Documentation/User_Guides.pdf)
      

2. Presentation

    2.1 Powerpoint, PDF or another format of slides (for this course/ analysts) can be found [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Communicate%20Results)
    
    
   2.2 Recorded Presentation (12-15 minutes) video on [YouTube](https://www.youtube.com/watch?v=4aAHyhvNJUc&t=757s)
   
   2.3 Project report (all sections of the proposal + data analytics lifecycle with screenshots) can be found [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/blob/master/Communicate%20Results/Data_Science_Final_Report.pdf)
   
   2.4 Powerpoint, PDF, or another form of slides for executives can be found here
      
      
      
     

# Nbviewer

<b align = "justify">If the jupyter notebook doesn't load. Don't worry just copy and paste the link to [nbviewer](https://nbviewer.jupyter.org). Because most of my jupyter notebooks are not loading.</b>

# Deployment code
 
The deployment code requirements can be found [here](https://github.com/Tanu-N-Prabhu/Used_Car_Price_Prediction_System1) or [here](https://github.com/Tanu-N-Prabhu/UsedCarPricePredictionSystem-Files/tree/master/Operationalize/Django%20Application)
  
# Steps to run the notebooks

Below are the steps to execute the notebooks

Step 1: Download the data raw or cleaned data sets to your local system from above

Step 2: Install [Jupyter Notebook](https://jupyter.org/) or use [Google Colab](https://colab.research.google.com/).
> Note: Use anaconda jupyter notebook while building the model. Because this is much faster than google colab. Also make sure you install all the necessary libraries shown above. Also make sure your system RAM and disk space is free.

Step 3: Download the notebooks to execute

    3.1: Download the data preparation notebook to perfrom data exploration
    
    3.2: Download the model building notebook to run the model or open directly from GitHub in a colab environment.
    
    3.3: Download the model saving notebook to save the model to your local system

Step 4: Run all the cells of the desired notebooks.

To execute in google colab, copy the google drive dataset and export it to your own drive.

# Contributors

<p align="justify"> Tanu Nanda Prabhu : I'm doing my Master's in Computer Science, at University of Regina, Canada. Although I'm good at programming, definitely not a code monkey. I like to document each and every line of code and help others understand it. It is very important to document the code.</p>


# Contact for help

| Contact        | Info           | 
| ------------- |:-------------:|
| Mail id      | tanuprabhu96@gmail.com  | 
| Phone number        | +1 306-737-9073              |   
| Facebook       | Tanu N Prabhu      |    
| Instagram      | tanunprabhu   |

# Version

<b> Version 10.0 - Last Updated on April 17 2020 - 3:09 PM <b>



