# Women’s Clothing E-Commerce Review Analysis  

## Introduction  
This project focuses on analyzing customer reviews from a **Women’s Clothing E-Commerce dataset**.  
The goal is to derive insights from review texts, classify them as recommendations or not, and better understand customer preferences and sentiments.  

The dataset comprises **23,486 reviews**, each containing features such as **age, review text, rating, and recommendation status**.  



## Repository Contents  
- **Women Clothing Review Analysis (PDF)**: Business report covering all steps, from data preparation to final business application.  
- **Women_Clothing_Reviews_Code (IPYNB)**: Jupyter Notebook with the complete code for data preparation, modeling, and performance evaluation.  
- **Women Clothing E-commerce Reviews (CSV)**: Raw dataset downloaded from Kaggle.  

---

## Dataset Overview  
The dataset contains **23,486 rows** and **10 feature variables**. Each row represents a customer review.  

### Feature Variables  
- **Clothing ID**: Integer categorical variable referring to the specific product reviewed.  
- **Age**: Positive integer representing the reviewer’s age.  
- **Title**: String variable with the review title.  
- **Review Text**: String variable containing the main review body.  
- **Rating**: Ordinal integer score (1 = Worst, 5 = Best).  
- **Recommended IND**: Binary indicator (1 = Recommended, 0 = Not recommended).  
- **Positive Feedback Count**: Positive integer representing how many customers found the review helpful.  
- **Division Name**: Categorical variable indicating the high-level product division.  
- **Department Name**: Categorical variable indicating the department.  
- **Class Name**: Categorical variable indicating the product class.  

---

## Conclusion  
The project successfully applied **machine learning models** to analyze customer reviews.  
Among them, the **LSTM model** showed strong performance in understanding and predicting customer recommendations.  

This demonstrates the potential of **machine learning for extracting valuable insights from textual data**, enabling businesses to better understand **customer sentiments and preferences**, and ultimately improve decision-making.  
