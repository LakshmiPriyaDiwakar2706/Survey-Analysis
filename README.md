# Survey-Analysis
## 1.	Background and Overview
CodeX is a German beverage company that recently launched its energy drink in 10 cities across India. The goal of this project was to analyze the results of a consumer survey conducted in those cities with 10,000 respondents. As a Marketing Data Analyst, I aimed to convert these survey results into meaningful insights that the marketing team can use to enhance brand awareness, increase market share, and refine product development strategies.
The analysis focuses on three main areas:
1.	Consumer Behavior/Preferences
2.	Competitor Analysis
3.	Brand Analysis
________________________________________
## 2.	Project Files and Resources
1.	Cleaned Survey Data: The cleaned and pre-processed data [here](https://github.com/LakshmiPriyaDiwakar2706/Survey-Analysis/blob/main/fact_survey_responses_%20cleaned_data.csv)
2.	City Data: The city respondents belong to data can be found [here](https://github.com/LakshmiPriyaDiwakar2706/Survey-Analysis/blob/main/dim_cities.csv)
3.	Respondents Data : The data regarding to respondents like (age, gender etc) can be found [here](https://github.com/LakshmiPriyaDiwakar2706/Survey-Analysis/blob/main/dim_repondents.csv)
4.	Interactive Tableau Dashboard: The interactive dashboard visualizing key findings is available [here](https://public.tableau.com/app/profile/lakshmi.priya.diwakar7591/viz/ConsumerAnalysisDashboard_17293052726020/Story2)
5.	Metadata Documentation: Detailed metadata about the survey and dataset can be found [here](https://github.com/LakshmiPriyaDiwakar2706/Survey-Analysis/blob/main/Metadata.txt)
________________________________________
### 3.	Data Structure and Initial Checks
Dat Structure: Being survey data, all the data were qualitative with categorical values in it.
Key Steps in the Data Cleaning Process:
1.	Handling Inconsistent Responses:
   
   Heard Before = ‘No’ and Tried Before = ‘Yes’: Consumers who reported not knowing the brand but claimed to have tried it were flagged for removal as this was deemed inconsistent.

   Brand Perception: Dropped rows where respondents who had never heard of the brand rated its perception as "Positive" or "Negative," as their responses would be unreliable.
   
   Consume Frequency = ‘Rarely’: Responses indicating that consumers rarely consume energy drinks were removed, as they may not recall the brand or provide valuable insights.
   
2.	Data Dropped:
   
   Approximately 600 responses were excluded from the analysis based on the criteria mentioned above to ensure data consistency and improve reliability.
  	
•	The goal was to remove responses that could introduce bias or skew results. The cleaned data now reflects more reliable insights about consumer behavior, perceptions, and purchasing decisions.

Data Modeling:

![Data Model In Tableau - 1](https://github.com/LakshmiPriyaDiwakar2706/Survey-Analysis/blob/main/image.png)

![Data Model In Tableau - 2](https://github.com/LakshmiPriyaDiwakar2706/Survey-Analysis/blob/main/image%20(1).png)

________________________________________
## 4. Insights Deep Dive
1. Demographic Distribution:
   
•	Delhi: Despite being a major metropolitan city, the number of survey respondents from Delhi was surprisingly low. This may indicate a need for targeted marketing efforts in the region to increase brand visibility.


![City](https://github.com/LakshmiPriyaDiwakar2706/Survey-Analysis/blob/main/Untitled%20design%20(3).png)

3. Consumer Behavior:
   
•	Energy Drink Consumption: Around 30% of respondents reported consuming energy drinks frequently, indicating a strong potential market for energy drink brands.

•	Purchase Behavior: 35% of respondents purchase energy drinks from local supermarkets, with most purchases falling in the 50-150 INR price range. This suggests that affordability and availability in supermarkets are key factors driving purchasing decisions.

![Frequency](https://github.com/LakshmiPriyaDiwakar2706/Survey-Analysis/blob/main/image%20(2).png)
![Price](https://github.com/LakshmiPriyaDiwakar2706/Survey-Analysis/blob/main/image%20(3).png)

5. Brand Perception:
   
•	Respondents who have heard of the brand showed positive trends in terms of willingness to purchase and brand perception, with many associating it with energy and refreshment.
________________________________________
## 5. Recommendations
1. Product Development:
   
•	Focus on Caffeine: Based on consumer preferences, a key ingredient for energy drinks is caffeine. However, the R&D team should also consider other improvements such as adding more natural ingredients, reducing the sugar levels and coming up with wide range of refreshing flavors to differentiate the product from competitors.

![Product Development](https://github.com/LakshmiPriyaDiwakar2706/Survey-Analysis/blob/main/Untitled%20design%20(2)%20(1).png)

2. Distribution Strategy:
   
•	Supermarkets Over Malls: Since 35% of respondents buy energy drinks from local supermarkets and around 78% spend anywhere between Rs. 50 and 150 , it’s recommended to prioritize distribution in local supermarkets with multiple price ranges rather than large malls.

![Distribution Strategy](https://github.com/LakshmiPriyaDiwakar2706/Survey-Analysis/blob/main/image%20(4).png)

•	Increased Availability in Delhi: The low number of respondents from Delhi suggests a gap in brand awareness. Focused campaigns or sampling strategies in Delhi should be implemented to improve reach.

3. Marketing Strategy:

•	Targeted Surveys in Key Cities: Conduct follow-up surveys in cities like Delhi, Jaipur, and Kolkata to understand deeper market insights and address regional preferences.

•	Product Visibility: Increase the product's visibility and accessibility in areas where consumers frequently buy energy drinks, focusing on local supermarkets and retail chains.
________________________________________
## 6.	Next Steps
1.	Further Analysis of Excluded Responses: The 645 responses excluded due to inconsistencies may be revisited for secondary analysis if needed, especially to explore niche consumer behavior.
2.	Competitor Analysis: Benchmark the product against competitors in the energy drink market to identify areas of improvement in pricing, taste, and branding.
3.	Expansion to New Cities: Based on insights from the next phase of surveys, expand the brand presence in additional cities with high potential.
________________________________________
## 7.	Tools Used

•	Data Analysis & Processing: Excel

•	Data Visualization: Tableau
________________________________________
## 8.	Conclusion
This analysis provides actionable insights into the preferences, behaviors, and perceptions of Indian consumers towards CodeX’s energy drink. By addressing distribution, product development, and marketing strategies, the company can make informed decisions to enhance its market presence and growth in India.

