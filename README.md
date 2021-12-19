# Machine Learning and Statistics
***
![Machine_Learning](img/ml.jpg)
<br>

## Project Overview
In this project contains two jupyter notebooks and some other files what are relevant to the project . The first is the "scikit-learn.ipynb" notebook where I use different machine learning techniques to investigate different data sets to make predictions for future outcomes.<br>
The second is the "scipy-stats.ipynb" notebook where I do hypothesis testing on two data sets. I use two statistical test methods t-testing and ANOVA testing. <br>

## What is Machine Learing?
Machine learning is the study of computer algorithms that can improve automatically through experience and by the use of data. It is seen as a part of artificial intelligence AI.<br>

## What is Statistics?
Statistics is the study and manipulation of data, including ways to gather, review, analyse, and draw conclusions from data. 
***
<br>

## Project Installation
The project uses the Python package [Python](https://www.python.org/downloads/). It can run on different operation systems. Some additional python packages and libraries are required to run the notebook. The best way to install the python packages using "pip". Please find a list of additional packages and libraries on the requirements.txt file. The notebook is running in any web browser.
***
<br>

## How to run this notebook

you have three options to run this notebook
* Option 1 from your local machine
    1. Download and Install [Anaconda](https://www.anaconda.com/) or install [Python](https://www.python.org/downloads/) with<br>
    additional packages listed in the reqirement.txt file.
    2. Download and Install [Commander](https://cmder.net/) for your Operation System
    3. Insert the path where the notebook files are located
    4. Run notebook by typing jupyter lab or jupyter notebook into the Commander command line
    5. Pick the `scikit-learn.ipynb` or the `scipy-stats.ipynb` file
    6. When notebook file is open<br>
        Click on "Kernel" tab<br>
        Click on "Restart" Button<br>
        Click on "Cells" tab<br>
        Click on "Run All"  
    7. Alternative Click on each cell and use the keyboard keys "Shift + Enter"       
    <br/>
    
* Option 2 view the notebooks in static format

    View the notebook "scikit-learn" from this link <br/>
    [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/Silvio622/Machine-Learning-Scikit-Learn/blob/main/scikit-learn.ipynb)

    View the notebook "scipy-stats" from this link <br/>
    [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/Silvio622/Machine-Learning-Scikit-Learn/blob/main/scipy-stats.ipynb)  

* Option 3 view notebooks in interactive format  

    View the notebook "scipy-stats" from this link <br/>
    [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Silvio622/Machine-Learning-Scikit-Learn/HEAD?labpath=scikit-learn.ipynb)

    View the notebook "scipy-stats" from this link <br/>
    [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Silvio622/Machine-Learning-Scikit-Learn/HEAD?labpath=scipy-stats.ipynb)
***
<br>

## Creating Machine Learning Scikit-Learn Notebook
<br>
<p>In this notebook I use the Classification and Regression Machine learning techniques with the Scikit-Learn package. The data sets I using for the Classifications is the “Iris data set”. The “KNeighborsClassifier” method is used to find the correct Iris flower. The “KNeighborsClassifier” predicts the right iris flower based on random selected values or measured values taken from the iris flower for the features Sepal length, Sepal width, Petal length and Petal width. The three Iris flower species are Setosa, Versicolor and Virginica. The accuracy for the prediction is 98%.
<p>On the second data set the Portuguese red wine data set I try to predict the quality of the red wine based on the attributes citric acid and sulphates. I used three different techniques the “Two Dimensional Logistic Regression”, “linear Logistic Regression” and the “KNeighborsClassifier”. The prediction results are very similar between the three different techniques. The prediction result or score is around only 50%. It is a disappointing result. 
<p>The third data set is the “Hungarian chicken pox”. The data set contains the weekly chicken pox cases over period of 10 years in different cities in Hungary. With the “Multiple Regression” method I try to predict the chicken pox cases for the capital and biggest city in Hungary Budapest. The prediction result or the score is around 57%. I thought I could archive a better prediction.
<br><br>

## References


https://medium.com/analytics-vidhya/exploration-of-iris-dataset-using-scikit-learn-part-1-8ac5604937f8

https://medium.com/@jalalmansoori/lets-apply-our-first-machine-learning-model-part-2-8357952dc5c3

https://medium.com/@jalalmansoori/how-to-evaluate-and-improve-knn-classifier-part-3-62d72fd17eec 

https://datatofish.com/multiple-linear-regression-python/
https://www.youtube.com/watch?v=dQNpSa-bq4M

<br>

***
## Creating Machine Learning Scipy-Stats Notebook
<br>
<p>In the Scipy-Stats Notebook I carry out a t-test on the famous Iris data set and an ANOVA test on a Diet data set. A t-test can only be used when comparing the means of two groups a pairwise comparison. If you want to compare more than two groups, or if you want to do multiple pairwise comparisons, use an ANOVA test or a post-hoc test. ANOVA stands for Analysis of Variance. One-way ANOVA is the most basic form.
<p>The Iris data set contains four features Sepal length, Sepal width, Petal length and Petal width for three different Iris flower species Setosa, Versicolor and Virginica. For the Iris data set the null hypothesis H0 (no difference between two possibilities) is that the Setosa Iris flower Sepal length is the same as the Versicolor Iris flower Sepal length. The t-test shows that both Iris flowers have the same average Sepal length. The p or probability value was much lower than 0.05 or 5%. The null hypothesis was accepted. 
<p>On the Diet data set I carry out an ANOVA test and a Post hoc test for three different types of Diets. The Diet’s been called Diet 1, Diet 2 and Diet 3. They are no statistically difference between Diet 1 and Diet 2 but statistically difference between Diet 1 and Diet 3 as well between Diet 2 and Diet 3. 
<br><br>

## References

https://www.scribbr.com/statistics/t-test/

https://www.qualtrics.com/uk/experience-management/research/anova/

https://statistics.laerd.com/spss-tutorials/one-way-anova-using-spss-statistics.php

https://www.youtube.com/watch?v=EWYzeZbchR0

https://www.youtube.com/watch?v=BOGCsSzQNR4