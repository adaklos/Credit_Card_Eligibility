# Credit Card Eligibility


## **About the project**


*The goal was to create model capable of establishing if client applying for creadit card is credible or not. 
Prediction were based on Default Payments of Credit Card Clients in Taiwan from 2005 dataset.*

*Project consist of data cleaning, exploaratory data analysis, data preparation for machine learning algorithms, modeling, models evaluation and final conclusions.*


**Libraries used:** 
*  *pandas*
* *numpy*
* *matplotlib.pyplot*
* *seaborn*
* *sklearn*

**Techniques used:** 
* *binary classification modeling*
* *grid search* 
* *stratify shuffle split*
* *recursive feature elimination*
* *piepelines*
* *one hot encoder*
 </br> 

## **Exploratory Data Analysis**
 </br> 
 
![sum](https://user-images.githubusercontent.com/109808438/208154569-73897b38-7d8c-4b10-b446-df95ca42c8ce.png)
 </br> 
 </br>
    
![2](https://user-images.githubusercontent.com/109808438/208154529-7e1463e1-572a-4f91-8459-0d370ea62d74.png)
 </br> 
 </br> 
  </br> 
 
![3](https://user-images.githubusercontent.com/109808438/208154534-3e017377-aa10-46c1-bf0e-87501c8bad8a.png)
     
 </br> 

## **Comparsion of used models**
 
 *This project was a binary classification problem. Therefore Logistic Regresssion, Decision Tree Classifier, Random Forrest Classifier, KNeighbors Classifier and AdaBoost Classifier were trained.*
  </br>  
  
  ![pobrane](https://user-images.githubusercontent.com/109808438/208158004-76261f30-6d22-4ccf-8eb9-6b253723d57b.png)
   </br>
*AdaBoost got the best AUC score, however recall score wasn't satisfactory. Therefore some changes in threshold for non credible clients classification in Logistic Regression model were taken under consideration to improve recall score.*

</br>

>**You'll find the full report here:** [Credit Card Eligibility](https://github.com/adaklos/Credit_Card_Eligibility/blob/master/Credit_Card_Eligibility.ipynb)
  
