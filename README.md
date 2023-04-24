# OS Collection Performance
##. Dataset
### 1. Introduction about dataset
The dataset of Bank X includes a table containing debt collection information of partners by month in 2020 and 2021 (The detailed file with the name _"1. OS_Collection_Dataset.xlsx"_ can be downloaded from the above location)
### 2. Data Dictionary
![image](https://user-images.githubusercontent.com/129883764/233991260-6f6ac9a3-5e54-4a4a-a399-9414bfdf7279.png)
## II. Requirement of the Project
Analyzing debt recovery efficiency so that the Head of Collection of Bank X can see the debt recovery efficiency of its partners. Based on the findings, informed decisions can be made regarding the allocation of debt portfolios for the upcoming quarter, as well as the development of a suitable cooperation strategy.
## III. Design Thinking Method
Before developing solutions and visualizing data related to the problem, I will undertake a deep understanding of the problem through the application of the five primary stages of the design thinking process.
![image](https://user-images.githubusercontent.com/129883764/233991659-f9535e5a-9412-4cec-a12e-903f3ef0d1b5.png)
## VI. Visualization in Power BI
![image](https://user-images.githubusercontent.com/129883764/233992042-ead7f7c8-8f87-460d-b38b-0f1d249444d7.png)
## V. Insight
### Overview:
* Most of the debt is in the DPD 1080+ range, accounting for about 37% of the total debt. The 720-1080 group makes up about 29% of the debt, and the dead loan group accounts for approximately 7%.
* Credit card and overdraft products have the highest recovery rates, at 0.17% and 0.01%, respectively.
* The secured loan product has the lowest payment rate (0.02%) and the third-highest outstanding balance, worth 41T. NDC is the top-ranked company in terms of debt recovery for this product, with a recovery rate of 0.03%. In December 2020, this product had the best debt collection, with payments totaling 1.3bn. In October 2020, NDC collected debt payments for this product worth over 950 million, and in December 2020, the FBI collected debt payments worth over 1.1 billion.
* The unsecured loan product has the highest outstanding balance among all products, accounting for nearly 50% of the debt (worth 136T). The average debt recovery rate for this product is 0.07%, and it is well-recovered by ASA, HMK, and GLX. <br>
##### The top 3 partners with the highest recovery rates are ASA, GLX, and HMK.<br>
### Top 1: ASA
* Average debt recovery rate: 0.11%
* ASA has an unstable debt collection rate compared to the same period last year:<br>
   ** January and February: The debt recovery rate in 2021 is much lower than in 2020. Specifically, the rate in January 2020 was 0.2%, while in January 2021 it was 0.14%. The rate in February 2020 was 0.28%, while in February 2021 it was 0.06%.
   ** March, April, and May: The debt recovery rate in 2021 is higher than in 2020. Specifically, the rate in March 2021 was 0.17%, while in March 2020 it was 0.15%. The rate in April 2021 was 0.12%, while in April 2020 it was 0.08%. The rate in May 2021 was 0.11%, while in May 2020 it was 0.06%.
 * The strength of this company is the Overdraft product, with a recovery rate of 0.26%.
### Top 2: GLX
* Average debt recovery rate: 0.11%
* GLX experienced a sharp decrease in their recovery rate in 2021 compared to 2020.:: 
* The strength of this company is their Overdraft and HHB products, with a recovery rate of 0.13% and 0.12%, respectively.
### Top 3: HMK
* Average recovery rate: 0.10%
* Although the recovery rate of HMK in 2020 was not consistent, it has slightly increased from the beginning to the middle of 2021.
* The strongest product for HMK is Overdraft, with a recovery rate of 0.34%, which is 1.8 times higher than the second strongest product, Credit card, with a recovery rate of 1.9%.
### NDC
NDC is a notable partner company, although the recovery rate is not in the top 3 companies with the highest recovery rate.
* First balance 45T billion
* Average recovery rate: 0.09%
* From October 2020 (0.15%, up 0.06% compared to September 2020), NDC has had a breakthrough in the ratio of payment to the total balance.
* As a result, from March to May 2021, NDC ranked first in the amount of collected and paid nearly 5.5 billion (March 2021).
* Products that this company can collect are Other (0.32%) and Credit Card (0.26%)
* Ability to recover dead loan debts, continuously ranked in TOP in terms of ability to recover bad loan debts (59.7%) 2.6 times larger than FBI in second place in terms of ability to recover dead loan debts (22.93%)
## VI. My Recommendation
1. Allocate debt portfolios based on each company's strengths, and focus on companies that achieve high debt collection efficiency.
* NDC: Other, Credit Card, Overdraft
* ASA: Overdraft, Credit Card, Unsecured Loan
* GLX: Overdraft, HHB, Credit Card
* HMK: Overdraft and credit card
2. Focus on the NDC partner, particularly for the DPD range, which is the dead loan group.
3. Implement a ranking policy that allocates better portfolios to partners with a good recovery rate. This could involve a ranking system or scoring mechanism that takes into account the recovery rate or other metrics related to debt recovery for each partner.
