![SURVEY ANALYSIS DASHBOARD SLIDES BANNER](https://github.com/user-attachments/assets/48c9a737-cc98-4ae1-a198-ed92a7c200e6)
# 1.Overview

This Power BI project analyzes responses from a structured survey to extract key insights and visualize participant feedback across various dimensions. The goal was to identify patterns in participant satisfaction, engagement, and demographics to support data-driven decision-making.

# 2. Data Preparation
The columns Email (has only one value), Browser, OS, City, Country, and Referrer were empty, so they were removed from the CSV file.

Column names were originally survey questions and have been shortened using keywords. For example: "Q1 - Which Title Best Fits your Current Role?" was renamed to "Current Title" (as was done for most columns).

The column "Q1 - Which Title Best Fits your Current Role?" contained values like "Other (Please Specify): Manager, Business Intelligence Developer" and "Other (Please Specify): Business Analyst", which made the data unstandardized. I split these entries and created a new column for "Other" (as this was user-inputted text), then merged all values into a standardized format.This process was applied to several other columns where users could choose the 'Select' option from a dropdown list in the survey and enter custom text

Entries in "Q11 - Which country do you live in?" have been corrected,using find and replace feature of Power BI, as some were entered incorrectly.

# 3.Challenges&TakeAways during Analysis
* Many user-submitted entries required standardization. However, performing thesedata cleaning steps within Power BI posed significant challenges, particularly due to its limited capabilities for large-scale text normalization. 
* In future projects, I would likely use SQL for data cleaning to streamline the process and improve efficiencyFor instance, salary ranges had to be converted into discrete numeric values to enable the use of DAX formulas in visualizations. Having precise numerical data instead of ranges is far more beneficial for efficient and accurate data analysis.
* The dataset is relatively small, which highlighted the importance of working with larger, more balanced datasets. I also realized how data imbalance can easily lead to misleading insights. For instance, Vietnam ranked as the top country in overall happiness—but this was based on just one respondent, making the result statistically unreliable.
# 4. Conclusion & Recommendations
Success in data analytics isn’t defined solely by technical ability — career satisfaction stems from culture, balance, and opportunity for growth. To thrive, professionals (or those entering the field) should:

* Develop Python proficiency(Its the most commonly used tool)
* Target roles that offer meaningful, high-impact work (Data Scientist's average salary and salary happinnes is more than DataBase Developer)
* Prioritize companies with strong work culture and flexibility (Highest-rated dimensions: Coworkers (5.86) and Work/Life Balance (5.75))
* Leverage non-traditional backgrounds — it’s a strength, not a barrierr(A majority of professionals didn’t start in data analytics — they came from other fields.Formal * e* education beyond a bachelor’s isn’t required in most cases.
Feel free to reach me at;
Linkedin:www.linkedin.com/in/alp-tuna

My Website:https://alptheanalyst.wixsite.com/alptuna

My E-Mail:alptuna.professional@gmail.com

Colab paid products - Cancel contracts here
