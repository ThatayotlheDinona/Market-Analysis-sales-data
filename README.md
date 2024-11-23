# SUPERMARKET SALES ANALYSIS REPORT
_Prepared by Thatayotlhe Dinona_  
  _Date: 23/11/2024_

### PROJECT OVERVIEW 
This analysis intends to investigate the market sales of an imaginary supermarket to gain insights and identify areas of improvement and optimize operations to drive growth and profitability. 
### OBJECTIVES
1. To determine the times of the day when sales are highest?
2. To analyse customer ratings to gauge satisfaction levels?
3. To determine the payment methods used by customer?
4. To determine which product line are most profitable?
5. To analyse sales by customer demographic (gender and member)
6. To compare sales performance across branches
7. To determine the total sales revenue over a specific period?


### DATA ANALYSIS METHODOLOGY
This is a systematic process of inspecting ,cleaning, transforming data with the goal of discovering useful information and this was done using python with libraries such as **pandas, matplotlib , seaborn and numpy** imported.
 * ##### DATA COLLECTION 
The dataset used was from [Kaggle](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales) the dataset shape is 1000 rows and 13 columns. Data quality assessment was conducted to ensure the data is accurate, free from null values and consisent and also relevant to the analysis objectives.
* ##### DATA CLEANING
The following common data quality issues were checked with the help of pandas library which is well suited for data manipulation and data cleaning.  
* Missing data
* Inconsistent data formatting
* Outliers
* Duplicates
* Incorrect data type
* Renaming columns
   ![data cleaning](https://github.com/user-attachments/assets/bee20cd2-9875-4332-934c-dee4e39b6723)

 The dataset was further refined by correcting erros of data type mismatches , renamed columns and further removed columns which were not applicable to my analysis. 

* #### DATA EXPLORATION
  Data exploration techinques were employed which involves descriptive statistics to provide summary statistics(mean, mode, median, quartiles,standard deviation,etc) to have a rough understanding of the data before diving deep into earthing insights. Histograms, boxplot/whisker, kernel density were of use to help with identifying outliers,patterns and trends in the dataset.
![heatmap summary stat](https://github.com/user-attachments/assets/d9b9fd11-f6b7-4373-b51b-0f09b4b8575a)
![ratings ditribution](https://github.com/user-attachments/assets/18050c59-0edf-4a36-8e6d-262edd1b5cb3)

  
* #### DATA VISUALISATION
  Visuals were created to support analysis and visualise patterns, trends and insights of the data.

 1.  *Total sales revenue over a specific period?*
    
     The figure below illustrates the sales trends across different months. It shows that sales fluctuated significantly over this period.
![Sales_revenue_over_specific_period](https://github.com/user-attachments/assets/b1ab8975-6741-4e43-8dab-ffbd104725c7)

   
2. *Payment methods used by customer?*
     
   The figure below illustrates the most used payment methods by customers, which are e-wallet and cash. This insight can help us better cater to their preferences.
   ![Payment methods used by customer](https://github.com/user-attachments/assets/734f0e5a-4904-41ca-aa4d-0ca8f9fb9ff7)
3. *Customer ratings to gauge satisfaction levels?*
   
   The figure below depicts customer ratings for different products and services. This can help us understand customer perceptions. Health and beauty products received the lowest ratings, indicating a need for review and improvement to enhance their appeal.
   
  ![Gauge ratings (1)](https://github.com/user-attachments/assets/24de4456-f930-444f-a884-2249e6faebc9)
6. *Sales by customer?*
![Demographics](https://github.com/user-attachments/assets/579fbe4b-31c3-4452-aaaf-e5022502b282)

7. *Most profitable product line ?*![Screenshot 2024-11-23 203136](https://github.com/user-attachments/assets/a5016fbd-33e6-4024-a7f0-047a00287c2d)
8. *Sales by Branch name* ![sales performance](https://github.com/user-attachments/assets/a5b23a43-0124-40c4-9d38-f45c10a6fcd4)


