# CapstonProject

Energy Products In KSA
Data Insight Group
Capstone project report



Introduction and problem statement:

Oil and natural gas are major industries in the energy market and play an influential role in the global economy as the world's primary fuel sources. The processes and systems involved in producing and distributing oil and gas are highly complex, capital-intensive, and require state-of-the-art technology. 

Consequently, The Joint Organizations Data Initiative Oil (JODI-Oil) was first launched in 2002, the main goal was not to build a database but to raise the awareness of all oil market players to the need for transparency in oil market data. So, more than 90 countries/economies, Members of the six pioneer organizations (APEC, EUROSTAT, IEA, OLADE, OPEC and UNSD) participate in JODI Oil, representing around 90% of global oil supply and demand. But in our case, we used the date that related to GCC countries.


About the dataset:

The dataset consists of 955500 rows and seven columns TIME_PERIOD, AREA, ENERGY_PRODUCT_NAME, FLOW_BREAKDOWN, UNIT_MEASURE, OBS_VALUE and ASSESSMENT_CODE.  For the time period it contains data from 2002 till 2021. Moreover, Product categories: crude oil, LPG, gasoline, kerosene, diesel oil, fuel oil and total oil products. Eight flows: production, demand, refinery intake and output, imports, exports, closing stock levels and stock change.

The explanation of plots:

<img width="435" alt="image" src="https://user-images.githubusercontent.com/105698551/189083943-d953be21-b4f1-43f7-b676-438a68f49f99.png">

This plot shows the total number of demands, exports, and imports over the years starting from 2002 till 2022, it clearly shows that the exports number starts with more than 60K .
<img width="429" alt="image" src="https://user-images.githubusercontent.com/105698551/189084001-1f1406e9-ab1e-4aee-bdac-22c2389fdb99.png">
This bar plot represents the counts of demands, exports, and imports that depend on the flow of breakdown. So, imports are close to 700 but for both demands and exports look like the same nearly equal to 1200.

<img width="381" alt="image" src="https://user-images.githubusercontent.com/105698551/189084050-f6bd3a46-9fc8-4866-85a6-7169680124f2.png">
This bar plot shows the total number of the six products: crude oil, liquefied petroleum gasses, motor and aviation gasoline, kerosene, diesel or gas oil, and fuel oil. so that crude oil has the lowest number of products whereas motor and aviation gasoline have the highest number of products compare to others.  
<img width="374" alt="image" src="https://user-images.githubusercontent.com/105698551/189084100-3aa8a4cd-d814-4168-911c-b4152303ede4.png">

For this plot, it shows the OBS value of the imports, exports and demands over the years, so that in 2008, the exports had the most value compared to other years by 7000.

<img width="468" alt="image" src="https://user-images.githubusercontent.com/105698551/189084152-3d456d58-c7f6-440c-8f6a-d298a5acc0ea.png">
This box plot shows the import in Saudi Arabia for different types of product such as: Fuel Oil, Gas/diesel oil, Kerosenes, Liquefied petroleum gasses and Motor and aviation gasoline. However, it seems that the Fuel Oil has the maximum value with more than 400 thousand, Gas/diesel oil with maximum value near to 390 thousand, Motor and aviation gasoline value is 320 thousand, Kerosenes and Liquefied petroleum gasses these products have less than 100 thousand.


<img width="468" alt="image" src="https://user-images.githubusercontent.com/105698551/189084253-e2a1ffe2-3ea2-4536-8c62-cf261a2bea10.png">
This box plot shows as the previous plot but it investigates the demand products  in Saudi Arabia which are: Fuel Oil, Gas/diesel oil, Kerosenes, Liquefied petroleum gasses and Motor and aviation gasoline.  However, it seems that the Gas/diesel oil has the highest demand over other products with value near to 900 thousand. 

The next four plots show the total number of demands, exports, and imports over the years of some of the Gulf Cooperation Council countries.
<img width="468" alt="image" src="https://user-images.githubusercontent.com/105698551/189087117-00977699-2ca1-45cb-9aca-a33e0664624d.png">

So, this plot represents the Kuwait country's total number of demands, exports, and imports. As shown, the total number of exports will suddenly decrease by nearly 23k in 2020. 
<img width="468" alt="image" src="https://user-images.githubusercontent.com/105698551/189087231-1f055ba0-2cad-458c-af52-ca6462730e1a.png">

This plot represents the Oman country, which clearly shows the unstable total of exports over the years, in 2005 the total of exports increased from 0 to 8k.  



The total number of demands, exports, and imports over the years for Qatar country
<img width="467" alt="image" src="https://user-images.githubusercontent.com/105698551/189087308-394ad003-d8a5-4ba0-87fe-c6526faf802a.png">

Findings and results:

 We use three different models for example: Random Forest, Multiple linear Regression and Polynomial Regression. However, the evaluation for these models is 95% for random forest and 69% and 30% for Polynomial Regression and Multiple linear Regression, respectively.  To improve the models and achieve high scores we change the degree parameter for Polynomial Regression from 2 to 4 this modification improves the model to 86%.  On the other hand, for Random Forest we use parameter tuning using Grid Search which is a popular technique to enhance the model and achieve 91%.



This box plot shows as the previous plot but it investigates the demand products  in Saudi Arabia which are: Fuel Oil, Gas/diesel oil, Kerosenes, Liquefied petroleum gasses and Motor and aviation gasoline.  However, it seems that the Gas/diesel oil has the highest demand over other products with value near to 900 thousand. 
