# ENTREPRISE RETAIL STORE ANALYSIS

## Objective

The objective of this project is to analyze transactional data for an online store business in an effort to uncover data-driven insights for making informed business decisions. Analysis includes finding  top products, best customers, sales over time and sountries , and overall customer buying behavior. These insights should help the company with making better decisions on  inventory management , marketing strategy, how to keep customers , and maximize profits..

### Skills Learned

- Data Analysis & Interpretation : dentifying trends and patterns in this large dataset.
- Proficiency in analyzing and interpreting data outcomes.
- Data Cleaning & Preparation : Cleaning data , Handling missing values and formating dates.
- Feature engineering by creating a new attributes
- Python Programming : Enhanced profiency in Python , including libraries for data manipulation and analysis(e.g Numpy , Pandas, Sklearn)
- Data Visualization techniques and presenting data insights effective using Matplotlib and Seaborn.
  
### Tools Used

- Xlsx to CSV converter
- Python , Pandas, NumPy, Scikit-learn , Matplotlib and Seaborn

## Key Insights

-Correlation(or lack thereof) of between numerical attributes and between categorical attributes.
-Countries that purchase the most from the store.
-Products that are bought the most.
-The months that have the most sales.

# THE CODE AND KEY FINDINGS 

## Importing the necessary libraries and the dataset
<img width="1179" alt="Screenshot 2025-06-19 at 6 18 15 PM" src="https://github.com/user-attachments/assets/fe26c893-f4eb-4776-9745-4e7578901fc5" />

## Data Cleaning and Preprocessing
<img width="1208" alt="Screenshot 2025-06-19 at 6 20 33 PM" src="https://github.com/user-attachments/assets/893ec63a-ebf4-40eb-b51d-71401d89c22f" />
<img width="1209" alt="Screenshot 2025-06-19 at 6 20 59 PM" src="https://github.com/user-attachments/assets/d38f5af9-5d66-47e5-b1eb-1f9286aa42f1" />
<img width="1206" alt="Screenshot 2025-06-19 at 6 21 24 PM" src="https://github.com/user-attachments/assets/cafc7bec-660c-4cd0-a696-4f6ce4a87ee3" />

## Heatmap for numeric values

-CORRELATION HEATMAP BEFORE DATA CLEANING AND PREPROCESSING
<img width="866" alt="Screenshot 2025-06-19 at 5 35 28 PM" src="https://github.com/user-attachments/assets/39fbaa46-7aa0-4497-b316-e088a1096bbc" />

-As expected it shows that there is zero correlation between any of the attributes. This was actually my output the first time I tried generating the heatmap. When I got these results I went back to the drawing board and found the way I had cleaning the data earlier was wrong(e.g not removing products that had a negative unitprice.)

-CORRELATION HEATMAP AFTER CORRECT DATA CLEANING AND PREPROCESSING
<img width="1202" alt="Screenshot 2025-06-19 at 6 22 55 PM" src="https://github.com/user-attachments/assets/24f0d83f-435c-40f9-9993-b9758545f834" />
 -Findings : This heatmap tells us that there is the biggest/strong correlation between UnitPrice and quanttity. It also tells us that there is a slight/weak correlation between unitprice and total price. And lastly there is a very low , almost no correlation between Customer id and quantity , Unit price or Total price. 

## Heatmap for categorical values 

-Encoding the categorical data , finding the correlation matrix and code to visulize it.
<img width="1192" alt="Screenshot 2025-06-19 at 6 31 26 PM" src="https://github.com/user-attachments/assets/8706e421-a87d-4893-ac29-fdf1b96cd22e" />

-Visual represenattion of heatmap
<img width="1191" alt="Screenshot 2025-06-19 at 6 32 42 PM" src="https://github.com/user-attachments/assets/28c09ad6-989e-4007-be56-caa6c7ffc06c" />
-Findings:This heatmap tells us that overall most correlations are close to zero. Telling us that for the most part these categorical attributes do not affect each other and are independent of each other.

## Finding  top 10 Best Proudcts sold

<img width="1210" alt="Screenshot 2025-06-19 at 7 48 25 PM" src="https://github.com/user-attachments/assets/41da228c-c9c9-46bc-96c6-c4d456275225" />

## Find Monthly Revenue Trend

<img width="1200" alt="Screenshot 2025-06-19 at 7 49 57 PM" src="https://github.com/user-attachments/assets/a304e9a3-20ea-4f5a-8c82-aa5c460b004b" />

## Find customers that bought the most

<img width="1178" alt="Screenshot 2025-06-19 at 7 50 52 PM" src="https://github.com/user-attachments/assets/f4313f2b-95d9-409d-920a-cb965b4c630e" />

## Find top countries that spent the most

<img width="1205" alt="Screenshot 2025-06-19 at 7 52 17 PM" src="https://github.com/user-attachments/assets/8e99399a-6990-4e1d-81d1-3d92ac86428e" />


# MY ADVICE TO THE COMPANY

-Inventory: Prioritize on stocking up more on the goods that were found to be the most bought buy customers.
-Marketing: Focus on marketing ads in The UK and ads that resonate with british most , because they are responsible for the largest portion of people buying from the store.
-Sales Stategy : during low seasons introduces sales and promotions to encourage more people to buy.
-Customer Loyalty : Introduce customer loyalty advantages to keep repeat customers and encourage more company loyalty.













_
