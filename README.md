# Data_analysis
<p>Airport survey analysis using Pandas and Sklearn machine learning tools: Random Forest, Support Vector Machines, Decision Tree, KNN, Logistic Regression, Linear SVC, Sthocastic Gradient Descent, Gaussian Naive Bayes and Perceptron.</p>

<p><b>My goal is to find the best machine learning tool that can predict the variable "Airport Rating" based on other variables.</b></p>

<p>Basic steps I followed:</p>

## 1. Survey
<ul>
  <li>Import survey (.csv file)</li>
  <li>Check data (1400 rows, 47 columns/variables):</li>
</ul>
<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32989191-b9b638ea-cd4c-11e7-836f-cbf78b9f5032.PNG" width="700"></p>

## 2. Data processing
<ul>
<li>Data processed using <b>Pandas</b></li>
<li>Check correlation between variables:</li>
</ul>
<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32992023-a16bf3a4-cd80-11e7-9b0e-456c0705e1ef.png" width="700"></p>

## 3. Machine learning models
<ul>
<li>Train <b>sklearn</b> maching learning models</li>
<li>Test models (= predict <b>airport_rating</b>)</li>
<li>Compare prediction's accuracy:</li>
</ul>
<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32992042-c98dfad0-cd80-11e7-94bf-777e47385255.png" width="700"></p>

## 4. Conclusions
<b>Random Forest</b> is the best model predicting airport_rating with <b>63% accuracy</b>
