# Black-Friday-Data-Set-Analysis
A sample analysis of Black Friday data set is presented in this repository.

A retail company “ABC Private Limited” wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month.

The data set also contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category) and Total purchase_amount from last month.

Now, they want to build a model to predict the purchase amount of customer against various products which will help them to create personalized offer for customers against different products.

Data Set Description:-
  1) Variable: Definition
  2) User_ID: User ID
  3) Product_ID: Product ID
  4) Gender: Sex of User
  5) Age: Age in bins
  6) Occupation: Occupation (Masked)
  7) City_Category: Category of the City (A,B,C)
  8) Stay_In_Current_City_Years: Number of years stay in current city
  9) Marital_Status: Marital Status
  10) Product_Category_1: Product Category (Masked)
  11) Product_Category_2: Product may belongs to other category also (Masked)
  12) Product_Category_3: Product may belongs to other category also (Masked)
  13) Purchase: Purchase Amount (Target Variable)

## Hypothesis Generation
  1) 26-35 age group people are more likely to spend more as compared to any other age group.
  2) 0-17 and 55+ age group people are least likely to spend much as compared to other age groups.
  3) Assuming high 'Occupation' level means high salary, then
  
      - People with low 'Occuaption' levels contribute to majority of sales.
      - People with high 'Occupation' levels contribute much less to the total sales.
  4) Unmarried people spend more than their counterparts.
