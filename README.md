# **Sales Predictions Project**

The goal of this is to help the retailer better understand the properties of products and outlets that play crucial roles in increasing sales.

## **Data Dictionary for this dataset**

|**Variable Name**|	**Description**|
| ----- | ----- |
|Item_Identifier|	Unique product ID|
|Item_Weight|	Weight of product|
|Item_Fat_Content|	Whether the product is low fat or regular|
|Item_Visibility|	The percentage of total display area of all products in a store allocated to the particular product|
|Item_Type|	The category to which the product belongs|
|Item_MRP|	Maximum Retail Price (list price) of the product|
|Outlet_Identifier|	Unique store ID|
|Outlet_Establishment_Year|	The year in which store was established|
|Outlet_Size|	The size of the store in terms of ground area covered|
|Outlet_Location_Type|	The type of area in which the store is located|
|Outlet_Type|	Whether the outlet is a grocery store or some sort of supermarket|
|Item_Outlet_Sales|	Sales of the product in the particular store. This is the target variable to be predicted.|

## **Key Questions**

**Which items generate the greatest amount of sales?**
(https://github.com/YBilodeau/Sales-Predictions/blob/main/Images/Top%20Selling%20Items.png?raw=true)
- Some Items sell significantly more than others.
- Item FDY55 is the top selling item with $42,662 in sales.

**Which Item Type has the highest sales?**
- The Fruits and Vegetables category is the highest selling category and makes up 16% of total sales.
Convenience food categories come in at 2nd and 4th place with Snack Foods at 14% and Frozen Foods at 10%.
- Household Items came in 3rd place with 10%.

**Are consumers health conscious?**
- Consumers tend to buy significantly more low fat items than regular items.
65% of all sales are low fat items.

**Does Outlet Size affect sales?**
-The Medium size outlets contributed to 33% of sales, however as 28% of the Outlets had an 'Unknown' size we can not make any assumptions based on this feature.

**Does Outlet Location Type affect Sales?**
- Tier 3 Outlet Location Type did contribute the most with 39% sales.

## **Key Insights**
- Current consumers tend to eat healthier. 
> - They tend to buy significantly more low fat items than regular items.
> - They also tend to spend more on Fruits and Vegetables than any other category of item.
- Outlet Type contributes greatly to sales.
> - Type 3 Outlets contribute significantly more than Types 1 or 2.

## **Recommendations**
- Future Outlet expansion should consider prioritizing:
> - Healthy low fat item categories and convenience items
> - Tier 3 Outlet Location Types


## **Prediction Model Comparison**

| Model | R^2 Training Score | R^2 Test Score | RMSE Training Score | RMSE Test Score |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| Baseline | 0.00 | -0.00 | 1720.31 | 1664.98 |
| Linear Regresion | 0.5615438029098283 | 0.5671535903394698 | 1139.1188233294758 | 1092.8007198762534 |
| Decision Tree | 0.6039092654846363 | 0.594954272967407 | 1,082.69 | 1,057.12  |

**R^2 (Coefficient of Determination)**
- The Decision Tree Model has the highest R^2 Test Score of 0.594954272967407.

**RMSE (Root Mean Square of Errors)**
- The Decision Tree Model has the lowest RMSE Test Score of 1057.12 

**The Decision Tree Model is the reccomended model due to having the highest R^2 Test Score and the lowest RMSE Test Score.**
- While whithin the scope of this analysis the Regression Decision Tree Model does have the highest R^2 Test Score and the lowest RMSE Test Score, it is reccomended that additional models be explored, such as Bagged Trees or Random Forests.



