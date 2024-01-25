# Superstore Sales Analysis

**Goal**

To examine sales order data from a big-box store and develop conclusions based on various factors such as item geographical location and customer loyalty.

**Analysis Process**

-	Imported dataset from Excel spreadsheet into Pandas using a Jupyter notebook. 
-	Manipulated data to obtain the desired findings.
-	Used Matplotlib to create visualizations as needed.
  
**About the Data**

This dataset was taken from Kaggle.com: https://www.kaggle.com/datasets/ishanshrivastava28/superstore-sales/data

It contains 9994 rows of sales transactions between **2011** and **2014**.

**Annual Profit**

-	The store experienced increased growth in each year.

![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/fdddf457-a777-433b-bed5-8b7bbc2b1148)
 
![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/b2ee384b-aee3-4c22-84d1-316463b99a64)

**Geographical**

-	California and New York were the most profitable states, making over double the revenue of every other state.
  
![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/4a300d1c-afb4-4f58-8f86-011927c693da)

-	10 states experienced a net loss. The state with the biggest loss was Texas with $25,729.44.
    
![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/cc76f4e0-1b71-4d10-a7d6-9c0786f078f2)

- Regionally, the West generated the most profit in the country. Conversely, the Central region generated the least amount.

![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/950c0fdd-0232-434d-8e80-cf699c617210)

**Items**

-	The Canon imageCLASS 2200 Advanced Copier was the store’s most profitable item. At $25,199.94, it is more than triple the revenue of the 2nd most profitable item.

![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/9e1d9120-02a2-4584-9605-bdf775d9e3a8)

-	The Cubify CubeX 3D Printer Double Head Print was the store's least profitable item, with a net loss of $8,879.97.

![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/6f420fbf-ccf0-46eb-a53f-24e4b5e3fcbf)

-	A total 301 items (16%) resulted in a net loss.
  
![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/737eee57-6bd7-4c66-9eb3-ae263306da53)
 
**Discounts**

-	A discount was applied to 52% of all 9994 transactions.

![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/b74bf827-3146-4dec-a371-76b969120db8)

- The average amount of discounts per year gradually dropped from 2011 to 2013, but increased in 2014.

![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/5d5cc64c-da38-4637-8ac9-ea6a0c8a0ccb)

**Shipping**

-	Shipping times saw a spike in 2012, but dropped significantly in the following years. 

![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/ebda42e9-fa83-454d-b46e-5d2298ff3e9d)

**Customers** 

-	A total of 44 customers purchased items from 2011 to 2013, but not in 2014. The screenshot below shows those customers with the highest sales from 2011 to 2013.
  	
![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/ef0b42ac-e29e-4c42-9d31-a1391ffaf757)

**Conclusion**

- With a significant net loss, removing the Cubify CubeX 3D Printer from the store's catalog would likely make a large impact on their overall profit.
- By taking a closer look at the negative profits in the Central region, we can determine that the biggest loss is in the furniture category:
  
![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/1aef855d-5c1c-499d-9d3f-d88dc0ccf77a)

- The ship time directly correlates with the annual profit. Specifically, as ship times decreased, the profits grow higher.
- The steady decrease in discounts from 2011 to 2013 may have had an impact on the 44 customers the store lost in 2014.
-	By contacting the list of customers who left in 2014, we can gain more insight into their departure.

For more information, please see the Jupyter notebook and XLSX spreadsheet included in this repository.  
