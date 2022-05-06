# EXPLORATORY-DATA-ANALYSIS-AND-VISUALIZATION-IN-EXCEL
Preliminary cleaning, descriptive statistics, visualization, and insights into housing prices in the city of Windsor, ON, Canada.

![image 2](https://user-images.githubusercontent.com/20278806/167128265-d75b8590-8a28-44c8-ab91-834cdef65cda.png)

Exploratory data analysis is the first step in any data analysis project, it involves getting to know the data by exploring it for any potential research questions before confirming the answers with hypothesis testing and inferential statistics.


**Imaginary situation;** I work in a real estate development agency, and my manager, who is not a data practitioner would like to predict the price of houses in Windsor, ON, Canada.


**Scope of the analysis;** for this project, I will be carrying out exploratory data analysis on the housing dataset to summarize the main characteristics by providing different perspectives using descriptive statistics and visualization to quickly spot trends and determine the relationship between the price of houses (Dependent variable) and features/amenities of the house  (independent variable) 


**Layering out the process**

Step 1: Gathering the data.

Step 2: Cleaning and drug data in excel.

Step 3: Classifying variable.

Step 4: Exploring variables.

Step 5: Insights and conclusion.



**Gathering the data**


This project was inspired by George Mount in his book Advancing into Analytics and he already provided the datasets. The datasets as imported into excel has 546 observations in 12 columns and each column refers to one variable.


_The variables are defined as follows:
Price: the sale price of a house
Lotsize: the lot size of a property in square feet
Bedrooms: the number of bedrooms
Bathrms: the number of full bathrooms
Stories: the number of stories excluding basements
Driveway: yes, if the house has a driveway
Recroom: yes, if the house has a recreational room
Fullbase: yes, if the house has a full finished basement
Gash: yes, if the house uses gas for hot water heating
Airco: yes, if there is central air conditioning
Gaaragepl: the number of garage places
Prefarea: yes, if the house is located in the preferred neighborhood of the city
_



**Cleaning the data in excel** 


Created a new working sheet so that the original data set remains unchanged.
Deleted any duplicates available in the datasets. 
Added an index column called ID to datasets. The index column makes it easier to analyze data by group and count frequencies.
Converted the working sheets into a table.


![dataset](https://user-images.githubusercontent.com/20278806/167133265-0b38503b-2f58-444e-a9e2-08f5e74f2e7d.jpg)

 
 
**Classifying variables**


It is important that I classify the variables to know the kind of questions to ask of the dataset and the different kinds of analysis that can be carried out.


|Variable  |Categorical or Quantitative?	|Type       |
|----------|------------------------------|-----------|
|id	       |categorical	                  |nominal    |
|price	   |quantitative	                |continuous |
|lotsize   |quantitative	                |continuous |
|bedrooms	 |quantitative	                |discrete   |
|bathrms   |quantitative                  |	discrete  |
|stories 	 |quantitative	                |discrete   |
|driveway	 |categorical                   |	binary    |
|recroom   |	categorical                 |	binary    |
|fullbase	 |categorical                   |	binary    |
|gashw	   |categorical                   |	binary    |
|airco     |	categorical                 |	binary    |
|garagepl  |	quantitative                |	discrete  |
|prefarea	 |categorical                   |	binary    |



**Exploring the variables**


After classifying the variables, I started to explore them. At this point, I had to reiterate the scope of this analysis Which is exploring the relationship between housing price (dependent variable) and features /amenities of the house (independent variable).
The price being a dependent variable which value depends on the changes in independent variables.



**Price analysis**


Calculated descriptive statistics using excel data analysis tool Pak.
Visualized the distribution of housing price using a histogram and boxplot.

 
 ![price analysis](https://user-images.githubusercontent.com/20278806/167133441-42b99199-e114-49f2-8da1-95d387311e4d.jpg)

 
_Observations: The distribution of housing price shows that a lot more houses are being sold between 47000 and 58000 with 141 houses selling at that price. On the boxplot, our interquartile range falls within 60000 and 80000 and that there are several outliners especially on the high side.		
Both the visualization using histogram and boxplot indicate similar results_



**Lotsize analysis**


Calculated descriptive statistics using excel data analysis tool Pak.
Visualized the distribution of lotsize using a histogram and explored the relationship between lotsize and price using pivot tables and charts._

 
![Lotsize analysis](https://user-images.githubusercontent.com/20278806/167133546-d08bdda7-3629-4910-a3e7-0424027724bb.jpg)


_Observations: The greatest number of houses have a lotsize of 3510 to 4440 but the houses with a lotsize of 15650 to 16649 have a higher average selling price. This indicates that there is a relationship between housing price and the lotsize of a poperty. The lotsize should be a good predictor of housing price in Windsor, Ontario, Canada._



**Driveway analysis**


Inserted a pivot table and pie chart to compare the houses that have a driveway and the houses that do not.
Inserted another pivot table and a clustered column to explore the relationship between driveway and the housing price.


 ![driveway analysis](https://user-images.githubusercontent.com/20278806/167138690-45363748-0d05-4e51-80f4-c310e89ab819.jpg)


_Observations: Most houses in Windsor, Ontario, Canada have a driveway and the houses with a driveway command a higher price._



**Recreational room analysis**


Inserted a pivot table and pie chart to compare the houses that have a recreational room and the houses that do not.
Inserted another pivot table and a clustered column to explore the relationship between recreational room and the house price.

 
 ![rereational room analysis](https://user-images.githubusercontent.com/20278806/167138862-634b7f30-bdb0-4112-b04e-72f330124198.jpg)


_Observations: Most houses in Windsor, Ontario, Canada do not have a recreational room. The houses that do have a recreational room have a higher average price._



**Basement analysis**


Inserted a pivot table and pie chart to compare the houses that have a full basement and the houses that do not.
Inserted another pivot table and a clustered column to explore the relationship between full basement and the housing price.


 ![Basement analysis](https://user-images.githubusercontent.com/20278806/167138952-b4bba24c-f8f4-4b91-9a3d-708967cd2917.jpg)


_Observations: More houses in windsor, Ontario, Canada have a full basement. Houses with a full basement command a higher price. The basement should be a good predictor of housing price in Windsor, Ontario, Canada._



**Gas analysis**


Inserted a pivot table and pie chart to compare the houses that use a gas for hot water heating and the houses that do not.
Inserted another pivot table and a clustered column to explore the relationship between gas for hot water heating and the house price.


 ![Gas analysis](https://user-images.githubusercontent.com/20278806/167139160-eb030bf3-4ebf-4e0b-b8d8-b7925b7d76df.jpg)


_Observations: Almost every house does not use a gas for hot water heating, except 25 houses from a total of 546. Houses that use a gas for hot water heating command a higher price.
The gas analysis should be a good predictor of housing price in Windsor, Ontario, Canada._



**Air-condition analysis**


Inserted a pivot table and pie chart to compare the houses that a central air-conditioning and the houses that do not.
Inserted another pivot table and a clustered column to explore the relationship between central air-conditioning and house price.

 
 ![Aircondition analysis](https://user-images.githubusercontent.com/20278806/167140011-b4bd637c-79e4-4836-90ea-0715c0d15528.jpg)


_Observations: More houses in Windsor, Ontario, do not use a central air condition. Of 546 houses, 373 do not use a central air-condition and 173 do. Houses with a central air condition command a higher price._



**Preferred area analysis**


Inserted a pivot table and pie chart to compare the houses in a preferred neighborhood of the city with the houses not in a preferred neighborhood.
Inserted another pivot table and a clustered column to explore the relationship between preferred area and house price.


![Preferred area analysis](https://user-images.githubusercontent.com/20278806/167148104-6c6489bd-10f6-4b3c-954b-8199db884ef8.jpg)


 
_Observations: Of 546 houses, 128 are in a preferred neighborhood of the city and 418 houses are not. Houses that are in a preferred neighborhood of the city command a higher price. The prefarea analysis should be a good predictor of housing price in Windsor, Ontario, Canada._



**Bedroom analysis**


Inserted a pivot table and pie chart to spot the number of bedrooms which was most popular in Windsor, Ontario, Canada.
Inserted a pivot table and line chart to determine the relationship between bedrooms and house price.


 ![Bedroom analysis](https://user-images.githubusercontent.com/20278806/167148243-213976e2-8e1b-4a61-93b7-e849e7a7d247.jpg)

 

_Observations:	The maximum number of houses are with 3 bedrooms. The maximum average price is for 5 bedrooms. As the number of bedrooms increase, price of house also increases but starts to decrease after 5 bedrooms. The number of bedrooms should be a good predictor of housing price in Windsor, Ontario, Canada._



**Bathroom analysis**


Inserted a pivot table and pie chart to spot the number of bathrooms which was most popular in Windsor, Ontario, Canada.
Inserted a pivot table and line chart to determine the relationship between bathrooms and house price.

 
 ![Bathroom analysis](https://user-images.githubusercontent.com/20278806/167148317-9808d4e7-afdd-4764-afe1-0f1852641381.jpg)



_Observations:	The maximum number of houses have 1 bathroom. The maximum average price is for 4 bathrooms. As the number of bathrooms increase, price of house also increases. The number of bathrooms should be a good predictor of housing price in Windsor, Ontario, Canada._



**Stories analysis**


Inserted a pivot table and pie chart to spot the number of stories which was most popular in Windsor, Ontario, Canada.
Inserted a pivot table and line chart to determine the relationship between stories and house price.


 ![stories analysis](https://user-images.githubusercontent.com/20278806/167148387-16f8b687-cb42-43c1-b265-3e63d7ce1bcb.jpg)

 
_Observations: The maximum number of houses have 2 stories followed by 1 story. The maximum average price is for 4 stories. As the number of stories increase, price of house also increases. The number of stories should be a good predictor of housing price in Windsor, Ontario, Canada._



**Garage places analysis**


Inserted a pivot table and pie chart to spot the number of garage places which was most popular in Windsor, Ontario, Canada.
Inserted a pivot table and line chart to determine the relationship between sand garage places and house price.


 ![Garage places analysis](https://user-images.githubusercontent.com/20278806/167148518-4915b6d4-4fbf-4db8-afa3-81a3e9e4edf5.jpg)


_Observations:	Most houses have no garage place. Of the houses that have a garage place most had 1 or 2. The maximum average house price has 2 garage places. As the number of garage places increase, price of house also increases but starts to decrease after 2 garage places. The number of garage places should be a good predictor of housing price in Windsor, Ontario, Canada._



**Insights and conclusion**


A large number of houses in Windsor ON Canada sells for approximately 60,000 to 80,000.
Most of these houses have a lotsize between 2518 and 4440. The more expensive houses have a larger lotsize.


Apparently, all the other variables affect the price of houses in Windsor ON Canada.


From the exploratory data analysis, I can already spot trends of housing price in Windsor ON Canada but the analysis should not stop there.


Further analysis like hypothesis and inferential statistics can be carried out to further predict the price of house in Windsor ON Canada. it is also possible that more variables can be added to the dataset to further strengthen the analysis.


If you were a top manager looking to invest in real estate development in the Windsor area of Ontario Canada and you were presented with this exploratory data analysis.


Would you understand the analysis?

Do you think you can somewhat have a general idea of the price of a house in Windsor?

These are the questions I asked myself when carrying out this analysis.
