# E_Commerce 
Link to report: https://datastudio.google.com/reporting/d030f9d8-c7bf-491e-b63f-ff38163155d5
## Tool used:
- Pandas
- Matplotlib
- Seaborn
- Google Data Studio
## Dataset:
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered online retail store. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
![image](https://user-images.githubusercontent.com/56812443/142798049-c246a1e0-6794-4b84-8f13-3bb61621808b.png)
Link to dataset:
https://drive.google.com/file/d/1uY2B7YfdE3iFERc1W09a2tNwpoE3KLaQ/view?usp=sharing
## Online Retailer Store Analysis:
![](https://maas.vn/wp-content/uploads/2021/04/How-to-Perform-Content-Analysis-1.jpg)
### Step 1: Clean Data
- Remove unecessary rows (Quantity <=0)
- Change type of Invoice Date from string to datetime
- Make new column name Revenue = Quantity * UnitPrice
- Remove all transaction before 1st Dec 2011 (Cause there are only transaction till 9/12/2011)
- Remove all duplicated rows 
### Step 2: EDA
- Overview: Total revenue, Total quantity, Total order, Total Customer, Total Country
- Business Performance: 
