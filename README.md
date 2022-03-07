# Sales-Predictions

The project is a sales prediction for food items sold at various stores. The goal of this is to help the retailer better understand the properties of products and outlets that play crucial roles in increasing sales.

**Data Dictionary for this dataset**


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

**Key Questions**

**Which items generate the greatest amount of sales?**
- Some Items sell significantly more than others.
- Item FDY55 is the top selling item with $42,662 in sales.

**Which Item Type has the highest sales?!**
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

**Key Insights*
- Current consumers tend to eat healthier. 
> - They tend to buy significantly more low fat items than regular items.
> - They also tend to spend more on Fruits and Vegetables than any other category of item.
- Outlet Type contributes greatly to sales.
> - Type 3 Outlets contribute significantly more than Types 1 or 2.

**Recommendations**
- Future Outlet expansion should consider prioritizing:
> - Healthy low fat item categories and convenience items
> - Tier 3 Outlet Location Types





