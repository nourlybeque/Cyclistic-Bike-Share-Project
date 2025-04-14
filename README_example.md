Welcome to the sample GitHub ReadME! Use this template as an outline for your data analytics projects. Include one ReadME per repository, with each repository storing one project. Remember, it's better to have quality over quantity - having 2 stellar business-relevant projects stands out much more than 3+ mediocre projects. Feel free to make a copy of this or fork this repository and make it your own. Happy portfolio-ing :) 




# Project Background
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geo-tracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system at any time. The company has a significant amount of data on its clients' trips, marketing efforts, product offerings. The project thoroughly analyzes and synthesizes this data in order to uncover critical insights that will improve Lily Moreno's commercial success. 


Insights and recommendations are provided on the following key areas:

- **Category 1:** Recos for marketing campaign
- **Category 2:** Recos for pricing strategy
- **Category 3:** 
- **Category 4:**

Recommendations:
- Educate casual riders on the perks of memberships as a lack of knowledge can be the reason for the long usage by casual riders
- An ad campaign at the popular start stations for casual riders can increase engagement or interest in memberships
- A campaign to increase the usage by members especially in the less popular months could increase the number of trips. This campaign should provide benefits or rewards for continued usage with a focus on the less popular months.

Recommendations 2:
- Offer a weekend-only membership at a different price point than the full annual membership.
- Coupons and discounts could be handed out along with the annual subscription / weekend-only membership for the usage of electric bikes targeting casual riders. Also increasing the number of electric bike while reducing classic bikes if electric bike costs more for the pass, this can be beneficial for the company. (As electric bike are already in trend and usage is good as per member and ride type data.
- Create marketing campaigns which can be sent via email, or advertisement in the docking stations explaining why annual member is beneficial. Campaigns should be placed at the peak months of the year.


The SQL queries used to inspect and clean the data for this analysis can be found [here.](https://github.com/nourlybeque/Cyclistic-Bike-Share-Project/blob/34c9359674a6806a3e6eab5cbbbd535032b41e54/Cyclistic%20Bike-Share%20Project/sql_cyclistic/sql_key_findings_cyclistic.docx)

The R report can be found here

The excel report can be found here



# Data Structure & Initial Checks

The company's main database structure as seen below consists of 12 similar tables (as for 12 months) joined with **UNION ALL** function.

![ERD](https://github.com/nourlybeque/Cyclistic-Bike-Share-Project/blob/37616e801edb905edbc1c835465f6b9c559d3bce/Cyclistic%20Bike-Share%20Project/sql_cyclistic/ERD_cyclistic.png)

Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarization with the dataset. The SQL queries utilized to inspect and perform quality checks can be found [here.](https://github.com/nourlybeque/Cyclistic-Bike-Share-Project/blob/3b2642a0e4c54fc5a8a94f92a857ddb579f50d3c/Cyclistic%20Bike-Share%20Project/sql_cyclistic/1_Prepare_phase(Union_All_SQLquery).sql)



# Executive Summary

### Overview of Findings

Explain the overarching findings, trends, and themes in 2-3 sentences here. This section should address the question: "If a stakeholder were to take away 3 main insights from your project, what are the most important things they should know?" You can put yourself in the shoes of a specific stakeholder - for example, a marketing manager or finance director - to think creatively about this section.

[Visualization, including a graph of overall trends or snapshot of a dashboard]



# Insights Deep Dive
### Category 1:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 1]


### Category 2:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 2]


### Category 3:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 3]


### Category 4:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 4]



# Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)
  
* Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)
  
* Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)
