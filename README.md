**Pharmaceutical Supply Chain Analytics: Analyzing Raw material delivery performance**

**SITUATION:** Raw material delivery issue mitigation data is extracted from Devonway application, manually updated with new data and delivery performance is visualized in MS Excel. The visualizations are slow to load and limited in extracting insights

**TASK**: There is a need to implement an automated methodology to update the data and enable efficient extraction of advanced insights to upper management

**ACTION**:
1. Exported Closed delivery issues with required fields in Excel from **Devonway** application
  ![image](https://github.com/user-attachments/assets/6698e7b9-9ba9-4c31-8615-7b47eaa7cd33)

2. The Power BI's "Closed Alerts" table takes this data as the source to eliminate 2021 data which is not needed for analysis.

3. Created SharePoint Excel sheet that replicates same data and allows users to  update the needed fields. The "Closed Alerts" table has transformations to merge this table to include the updated information. This is used for visualizations.
   ![image](https://github.com/user-attachments/assets/23401a3f-5872-40f1-9ab7-b436062f7bcd)

4. The exported data is also used in Power BI to generate No of initiated alerts every month, No of closed alerts every month, No of open alerts from the first month.
   ![image](https://github.com/user-attachments/assets/5628b16c-d06e-493d-94ca-6e8cce350857)

**RESULT:**
**PRIMARY MITIGATION ANALYSIS:**
![image](https://github.com/user-attachments/assets/403dc69a-a97f-49f7-875b-a8104e8019d0)
**Insights extracted:** We have closed delivery issues 39% through Order expedition from supplier, 37.4% through using alternate item number. Almost 75% of our closed delivery issues belong to these two categories. We have been closing alerts at a rapidly fluctuating level through the years by order expedition. Drug Substance site is a major contributor of delivery issues by order expedition. Single sourced suppliers contribute to majority of our issues managed by order expedition.

**ROOT CAUSE SPLIT UP**
![image](https://github.com/user-attachments/assets/26f166b1-5059-4aa1-9d8a-6ecbff05c552)
**Insights extracted:** Majority of our delivery issues are caused by capacity constraint from supplier - end.

**ROOT CAUSE ANALYSIS:**
![image](https://github.com/user-attachments/assets/9acd0593-d680-45a0-933f-48ed75e84f63)
**Insights extracted:** The delivery issues caused by capacity constraint from supplier-end has decreased over time and is lowest during July 2023. Majority of it is sourced from Single Supplier. We have managed the majority of this cause by using alterate item numbers. Drug Substance site needs to be focused to resolve this cause.

**SOURCING TYPE ANALYSIS:**
![image](https://github.com/user-attachments/assets/f63edbb6-4f5d-46cd-96da-b19921b6e514)
**Insights extracted:**  Since majority of the issues are caused by single sourcing type, this is analyzed further. Through this sourcing type, we have managed most of the issues by Order expedition. The number of issues have been decreasing over the years. During the second half of 2022, there was a sudden increase in the issues.

**SITE ANALYSIS:**
![image](https://github.com/user-attachments/assets/cec9329b-7d95-4650-a69e-51551846da9e)
**Insights extracted:** Since majority of issues are caused by Drug Substance Site, it is analyzed further. Through this site, order expeditions form majority. In this site, July 2022 to October 2022 was the period in which we faced high number of delivery issues. We can infer that second half of 2022 is the time when we faced higher challenges in material delivery.

**SUPPLIER WISE SPLIT UP:**
![image](https://github.com/user-attachments/assets/595d05cd-d2b4-4f0c-98c0-dd6e5866b56e)
**Insights extracted:** We know that Single Sourced Supplier items caused majority of delivery issues caused by capacity constraint. According to the analysis, the Supplier "Thermofisher" caused majority of delivery issues, followed by "MilliporeSigma".

**SUPPLIER ANALYSIS:**
![image](https://github.com/user-attachments/assets/4ed1d98f-99d4-4cfe-9a58-530604828d7b)
**Insights extracted:** We know that Thermofisher supplier caused majority of delivery issues as per our analysis. Major chunk of delivery issues caused by Thermofisher are managed by looking for alternate item number. 

**SUPPLIER WISE ROOT CAUSE ANALYSIS:**
![image](https://github.com/user-attachments/assets/a441457c-73a9-4217-830d-e0968cf2ceaa)
**Insights extracted:** For issues caused by Capacity constraint at Supplier end, a major contributor is Thermofisher supplier. It is followed by Millipore Sigma.

**NUMBER OF OPEN, CLOSED, INITIATED ALERTS:**
![image](https://github.com/user-attachments/assets/b50a3553-5808-422a-a618-fb6584203dac)
**Insights extracted:** For second half od 2022 where most of the delivery issues happened, we can observe how many issues were initiated and closed every month. We can infer that we were closing issues at a higher rate than the rate at which new issues occured. 














