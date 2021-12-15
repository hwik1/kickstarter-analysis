# Kickstarter Campaign Analysis
Analysis of Kickstarter Campaigns for proposed project funding, completed December 2021 for Louise
## Overview
* This project was completed for Louise to provide insights on prior Kickstarter campaigns in order to have the best chance of succcess of creating her own campaign to fund her play _Fever_, which has an estimated budget over $10,000.
* This dataset covered 4,115 Kickstarter campaigns, featuring a wide range of subjects, time, periods, locations, and funding requets, including:
  * 21 different countries
  * 9 unique sectors (i.e. theater) with an additional 41 subcategories (i.e. plays)
  * Campaign dates ranging from 2009-2017
  * Funding goals ranging from $1 to $100M, while actual pledges ranged from $0 to $2.3M
  * 53% of campaigns were successful, 37% failed, 8% were canceled, and 1% are still live
 ---
 ## Findings
 * Within the US, theater is the most common campaign subject on Kickstarter, ahead of music, film & video, and technology.
   * With a 58% success rate, theater is the third most likely category to have a successful campaign, behind music (77%) and film & video (62%).
   
![Parent Category Outcomes Picture](https://user-images.githubusercontent.com/93058069/145688031-1e698abf-060d-4455-91d1-e2dff0c8e2f1.png)
   
 * Of the 912 US theater campaigns, 314 or 34% were specifically for plays.
   * Plays tend to be even more successful than the average for theater - 76% were successful.
 * When examining all theater campaigns (agnostic of country), the most successful campaigns were launched in May, with a decline in success rate through the rest of the year.
 
![Success by Month](https://user-images.githubusercontent.com/93058069/145688155-bf26d5a2-d944-4d59-9a33-83f7e4311c79.png)
 
 * For play campaigns that were successfully funded, the mean goal was $5,049 and mean pledged was $5,602, but that is skewed by outliers that had goals/funding up to $100,000.
   * The median goal for a successful play was $3,000. The median pledged was $3,168.
   * 75% of goals were $5,000 or less and only 25% of plays raised pledges above $5,699.
   * Failed Kickstarter campaigns for plays tended to have higher goals (mean of $10,554 and median of $5,000), but raised significantly less than successfully funded plays.
   
![Success vs Failed US Play Goals](https://user-images.githubusercontent.com/93058069/145688571-8437de61-3da9-4a1f-a999-45a1a64c770e.png)

---
## Recommendations
To set-up Louise for the best chance of a success Kickstarter campaign, I recommend she adhere to the following guidelines:
  1. **Timing** - If possible, launch the campaign in May.
  2. **Goal** - Don't ask for too much money. The initial budget of $10,000 is likely too high because it would be an outlier based on goals and funding in the past.

---
---
# Kickstarting with Excel
Analysis of Kickstarter campaign results for proposed project funding, completed December 2021 by Hannah Wikum for Louise
---
## Overview of Project
Louise is trying to raise funds on Kickstarter to cover the $10,000 estimated budget for her new play _Fever._ The results of previous Kickstarter campaigns were analyzed to set her up for the best chance of a successful campaign.

### Purpose
This analysis specifically focused on using the data of previous Kickstarter campaigns to answer two questions:
 1. How does the timing of the launch date impact the outcome of the campaign?
 2. How does the funding goal impact the success of the campaign?
---

## Analysis and Challenges
This Excel-based dataset covered 4,114 Kickstarter campaigns, featuring a wide range of subjects, time, periods, locations, and funding requets, including:
  * 21 different countries
  * 9 unique sectors (i.e. theater) with an additional 41 subcategories (i.e. plays)
  * Campaign dates ranging from 2009-2017
  * Funding goals ranging from $1 to $100M, while actual pledges ranged from $0 to $2.3M
  * 53% of campaigns were successful, 37% failed, 8% were canceled, and 1% were still live at time of data collection

### Analysis of Outcomes Based on Launch Date
When looking at the outcomes for theater campaigns based on launch date, May was the month with the greatest volume of campaigns launched, as well as the highest percent successfully funded. The amount successfully funded declines for the rest of the year. (See chart below)

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/93058069/146106432-e0be2ad0-3c6c-4503-aa9a-ddaf8bf82dac.png)

### Analysis of Outcomes Based on Goals
When looking at the outcome of completed campaigns for plays based on different ranges of fundraising goals, 69% of campaigns asked for less than $5,000 as a goal. The most successful campaigns asked for less than $1,000 where 76% were successfully funded. Six plays with goals between $35,000 - $44,999 were successfully funded, but those were outliers in the data. (See chart below)

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/93058069/146107003-f8bb7997-ed6b-477f-8dfb-3e7d59ac3c5d.png)

### Challenges and Difficulties Encountered
* Although theater was the most common category of Kickstarter campaigns (1,393 out of 4,114 total campaigns), and plays were the most common subcategory (1,066 out of 4,114 total campaigns), the data is skewed right with 17% of data points being outliers (using median/IQR range calculation.)
* Amount of publicity, fame of associated playwright, or virality of Kickstarter campaigns was not examined.
* Given the ongoing pandemic, using data from 2009-2017 is unlikely to accurately represent people's willingness to fund or attend plays in current times.
---

## Results
To set-up Louise for the best chance of a successful Kickstarter campaign for her play _Fever_, I recommend she adhere to the following guidelines based on the results of the data analysis:
1. Using the outcomes based on launch date, the most theater campaigns are launched in May, as well as the highest percent of successfully funded campaigns. Launch in May if possible and avoid launching later in the year when volume and success rates decline.
2. Using the outcomes based on goals, aim for a lower funding goal for a better chance of success, ideally under the mean of successful plays of $5,049. Successfully funding the campaign with a goal of $10,000 would be an outlier.
3. The limitations of this dataset include old data that doesn't represent current market conditions for plays (last data from 2017) and the fact that the data for plays is skewed with many outliers.
4. Other tables or graphs that could be used to improve the analysis, include length of campaign (days) versus outcome, average number of donors or average donation based on campaign subtype, etc.
