# Project Background
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geo-tracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system at any time. The company has a significant amount of data on its clients' trips, marketing efforts, product offerings. The project thoroughly analyzes and synthesizes this data in order to uncover critical insights that will improve company's commercial success. 


Insights and recommendations are provided on the following key areas:

📣 Marketing & Outreach
- Promote membership benefits to casual riders who may be unaware of long-term advantages.
- Run targeted ad campaigns at high-traffic casual rider stations to raise awareness and boost engagement.
- Launch seasonal marketing campaigns focused on increasing member activity during less popular months, with incentives or rewards for continued use.

🧩 Product & Membership Strategy
- Introduce a weekend-only membership at a lower price point to attract occasional riders.
- Provide coupons or discounts bundled with both annual and weekend-only memberships to encourage the use of electric bikes.

🚲 Operations & Fleet Management
- Increase the number of electric bikes and reduce classic bikes to match current usage trends and consumer preferences.
- Leverage pricing strategies if electric bikes are more profitable, ensuring fleet allocation supports business goals.


The SQL queries used to inspect and clean the data for this analysis can be found [here.](https://github.com/nourlybeque/Cyclistic-Bike-Share-Project/blob/34c9359674a6806a3e6eab5cbbbd535032b41e54/Cyclistic%20Bike-Share%20Project/sql_cyclistic/sql_key_findings_cyclistic.docx)

The worksheet with the pivot report that provides statistical analysis can be found [here.](https://github.com/nourlybeque/Cyclistic-Bike-Share-Project/blob/7883c8bbb0bce3346259e3c0208c4f9edc7627fc/Cyclistic%20Bike-Share%20Project/excel_cyclistic/excel_pivot_cyclistic.xlsx)

In addition, provided a complete analysis of R syntax can be found [here.](https://github.com/nourlybeque/Cyclistic-Bike-Share-Project/blob/7883c8bbb0bce3346259e3c0208c4f9edc7627fc/Cyclistic%20Bike-Share%20Project/rstudio_cyclistic/rscripts_cyclistic.Rmd)



# Data Structure & Initial Checks

The company's main database structure as seen below consists of 12 similar tables (as for 12 months) joined with **UNION ALL** function.

![ERD](https://github.com/nourlybeque/Cyclistic-Bike-Share-Project/blob/37616e801edb905edbc1c835465f6b9c559d3bce/Cyclistic%20Bike-Share%20Project/sql_cyclistic/ERD_cyclistic.png)

Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarization with the dataset. The SQL queries utilized to inspect and perform quality checks can be found [here.](https://github.com/nourlybeque/Cyclistic-Bike-Share-Project/blob/3b2642a0e4c54fc5a8a94f92a857ddb579f50d3c/Cyclistic%20Bike-Share%20Project/sql_cyclistic/1_Prepare_phase(Union_All_SQLquery).sql)



# Executive Summary

### Overview of Findings

- Members holds the biggest proportion of the total rides, ~30% bigger than casuals riders.
- In all months we have more members than casual riders.
- For casual riders the biggest volume of data is on the the weekend.
- There is a bigger volume of bikers in the afternoon.

This could be possible that member use bikes for work purpose, this information can be backed by their bike usage in colder months, where there is significant drop in casual members in those months.

![diagram](https://github.com/nourlybeque/Cyclistic-Bike-Share-Project/blob/3036dcc3d9ecb8109f9708b445bbd86bd0278f9e/Cyclistic%20Bike-Share%20Project/excel_cyclistic/diagram_cyclistic.png)





### How casual riders differs from annual membership riders ? :

- Members have the bigger volume of data, except on saturday and sunday. On the weekend, casuals riders have the most data points.
- Casuals riders have more ride length (ride duration) than members. Average ride time of member are mostly same slight increase in end of week.
- We have more members during the morning, mainly between 7am and 9am. And more casuals between 3pm and 2am. Actually this figure is applicable for both types of riders.
- Members have a bigger preference for classic bikes, followed by electric bike.
- Members have a more fixed use for bikes for routine activities. Where as casual rider's usage is different, mostly all activiy in the weekend.
- Casual member spend time near the center of the city or the bay area, where as member are scattered throughout the city.


<p align="center">
  <img src="https://github.com/nourlybeque/Cyclistic-Bike-Share-Project/blob/4e0a7321e7b5510c655d73cd65e8440bf46ec271/Cyclistic%20Bike-Share%20Project/rstudio_cyclistic/Rplot9.jpeg" width="300"/>
  <img src="https://github.com/nourlybeque/Cyclistic-Bike-Share-Project/blob/4e0a7321e7b5510c655d73cd65e8440bf46ec271/Cyclistic%20Bike-Share%20Project/rstudio_cyclistic/Rplot10.jpeg" height="250"/>
</p>



# Recommendations:

Based on the insights and findings above, we would recommend the stakeholder team to consider the following: 

- Educate casual riders on the perks of memberships as a lack of knowledge can be the reason for the long usage by casual riders
- An ad campaign at the popular start stations for casual riders can increase engagement or interest in memberships
- A campaign to increase the usage by members especially in the less popular months could increase the number of trips. This campaign should provide benefits or rewards for continued usage with a focus on the less popular months.
- Offer a weekend-only membership at a different price point than the full annual membership.
- Coupons and discounts could be handed out along with the annual subscription / weekend-only membership for the usage of electric bikes targeting casual riders. Also increasing the number of electric bike while reducing classic bikes if electric bike costs more for the pass, this can be beneficial for the company. (As electric bike are already in trend and usage is good as per member and ride type data.
