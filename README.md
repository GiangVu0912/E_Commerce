# Online Retailer
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
- Business Performance:\
KPI\
![image](https://user-images.githubusercontent.com/56812443/142840974-1d4a6876-85f5-44d9-8d3a-7fa34c6f0610.png)\
Revenue & Quantity by Month\
![image](https://user-images.githubusercontent.com/56812443/142840850-0c5077f2-0cb7-4b62-bcec-8ba0f23cae07.png)\
Total Order by Month\
Average Value & Average Quality per Order by Month
![image](https://user-images.githubusercontent.com/56812443/142875372-6cd5abf6-1396-4462-9279-f56567e82549.png)
- Trend:\
Do customers tend to buy more on certain weekday?\
![image](https://user-images.githubusercontent.com/56812443/142876755-55fc6056-3c97-4b1d-b243-c4b450d2e794.png)
Do customers buy more at the start of the month?\
![image](https://user-images.githubusercontent.com/56812443/142875785-066e1d27-8609-42ad-8bfd-bde544f43d24.png)
Do customers tend to buy more at a specific hour of the day?\
![image](https://user-images.githubusercontent.com/56812443/142876861-6b96ec84-cec9-4db2-b9ef-075989b6c141.png)
- Country:\
Ranking\
![image](https://user-images.githubusercontent.com/56812443/142877046-0046ec9b-50c5-4d79-9df0-63e3719511e2.png)
Total Revenue contribution by Country\
![image](https://user-images.githubusercontent.com/56812443/142877098-3dfbbb05-e4c4-4ddb-b582-5f3b030898a8.png)\
Average Order value by Country\
![image](https://user-images.githubusercontent.com/56812443/142877122-a22f064e-337d-48f9-abf7-6789a5fe0648.png)\
Revenue Monthly compare to Revenue of First Month by Country\
![image](https://user-images.githubusercontent.com/56812443/142877243-7f700e66-da1a-4e23-8e90-dacff9d4f1d7.png)
- Customer:\
Customer by Time & New Customer by time\
![image](https://user-images.githubusercontent.com/56812443/142877938-9e00bb3c-e20f-4b2a-8d2d-5a1d8545ca83.png)\
Revenue Made By New vs Existing Users\
![image](https://user-images.githubusercontent.com/56812443/142878003-96434b63-19e8-4e5f-8e02-eee4361f19d8.png)\
Customer Retention & Customer Retention Rate\
![image](https://user-images.githubusercontent.com/56812443/142878061-a8cc0b73-6bef-419c-86d2-0ce7a8b9842a.png)\
Revenue Contribution by First Order Date\
![image](https://user-images.githubusercontent.com/56812443/142878148-9dbe6b3b-729e-45eb-8a86-9dc1c53c94fc.png)\
Customer Segmentation\
![image](https://user-images.githubusercontent.com/56812443/142878213-9c88e634-c39a-462b-9c7a-18fe929e11ec.png)\

