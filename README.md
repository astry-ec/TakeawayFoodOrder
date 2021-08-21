# EDA Practice - Personal Task

EDA for Takeaway Food Order. Sourse of Dataset is from Kaggle with URL as belows

[Takeaway Food Order](https://www.kaggle.com/henslersoftware/19560-indian-takeaway-orders)

Raw Data consist of Order ID, Order Date, Item Name, Quantity, Product Price and Total Product started from 2015 - 2019 (5 years data)

Business Questions for this data as follows :

1. Which the busiest week in month and which the busiest day based on quantity sold ?
2. Which the busiest hour based on quantity sold ?
3. What are the most popular takeaway dishes based on quantity sold ?
4. What is the correlaction between Top 10 Dishes and its Price per Product ?
5. What are the most expensive dishes and its popularity for being takeaway ?
6. Which dishes with the highest revenue ?
7. What is the best Menu Package Recommendation combining the most popular food main dish with the least popular food as side dish in the package menu - enhance revenue from the least popular foods

Data insight above help food business industry to understand their past data of Takeaway food order and help them to efficient their business from several aspects such as number of shift/worker at peak time, stock of raw material based on popularity dish, creating menu bundled for menu package to ease customer on choosing food combination.

1. We're identified that Friday, Saturday and Sunday on Third Week and Fourth Week of the month also the peak time for the restaurant takeaway order
2. The peak hour of restaurant (at takeaway order) is between 17.00 - 20.00. 
3. Top 10 Dish based on Quantity Sold

![Screenshot](https://github.com/astry-ec/TakeawayFoodOrder/blob/main/Top%2010%20DIsh.PNG)

4. Top 10 Food doesn't affected by its price
5. The Top 10 most expesinve food being takeaway order is having popularity less than 0.1%
6. Chicken Tikka Masala, Pilau Rice are the highest revenue food over year
7. For menu package recommendation :

  - Combination of Plain Papadum and Pilau Rice, or Combination of Chicken Tikka Masala and Naan, are the perfect combination as every meal time, these items is being ordered.
  - Onion Bhaji and Mango Chutney might be added in number 1 menu package as this side dish always orderd every meal time
  - Mint sauce might as well added in menu package
  - The least favorite food : Saag, Saag Bhaji, Vegetable Bhuna, Vegetable Korma are good to be added in menu package to serve as vegetables dish
  - For Breakfast special menu, we can combine Meat Samosa + Mint Sauce + Saag in one package.
