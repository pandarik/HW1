# HW1
Crowdfunding Assignment

Background
Crowdfunding platforms like Kickstarter and Indiegogo have experienced significant growth and popularity since the late 2000s. These platforms provide a space for a diverse range of individuals, from independent creators to well-known celebrities, to seek funding for their innovative projects. However, not every project achieves success.

To secure funding, a project must either meet or surpass its initial funding goal. Consequently, many organizations invest substantial resources in examining past projects, hoping to uncover the elusive “secret” to achieving success. In this week’s Challenge, you will delve into a database of 1,000 sample projects, aiming to reveal any hidden trends that could shed light on the keys to crowdfunding triumph. 🚀🌟

Objective
The goal of this assignment is to explore the dataset, identify patterns, and gain insights into what factors contribute to a successful crowdfunding campaign. By analyzing project attributes such as funding goals, categories, and campaign duration, we aim to provide recommendations for future project creators.

Dataset
The dataset contains information on 1,000 crowdfunding projects, including details such as project name, funding goal, campaign duration, category, and outcome (successful or not). We will use Python and data analysis techniques to extract meaningful information from this dataset.

Tasks
Data Cleaning: Prepare the dataset by handling missing values, outliers, and any other data quality issues.
Exploratory Data Analysis (EDA): Explore the dataset to understand its distribution, correlations, and trends.
Feature Engineering: Create relevant features that may impact project success.
Modeling: Build predictive models to determine factors that contribute to a successful campaign.
Recommendations: Provide actionable insights for project creators based on the analysis.

Deliverables
Excel workbook and word doc with the solutions, visualizations, and explanations as outlined in each tab/sheet(refer to solution file links below)
README summarizing the analysis, findings, and recommendations.
Solution File: The dataset for this assignment can be found here.
https://github.com/pandarik/HW1/blob/main/CrowdfundingBook.xlsx
https://github.com/pandarik/HW1/blob/main/HW1%20Create%20a%20report%20in%20Microsoft%20Word.docx

Data Solution and Recommendations
Based on the analysis of the data as presented in the CrowdfundingBook.xlsx and HW1 Create a report in Microsoft Word.docx documents/solutions, it is evident that the presence of a category with an extremely high number of backers (theater with 74,601 backers) is an outlier. Outliers can significantly affect the mean (average) because they pull the value toward extreme ends. The median is less sensitive to such extreme values and provides a more representative summary of the central tendency for this dataset.

The mean number of backers is 26,646, which is heavily influenced by the theater category. The median number of backers is 17,750, which represents the middle value when all categories are sorted. Since the median is less affected by outliers, it better reflects the typical number of backers across categories.

In conclusion, the median provides a more accurate summary of the central tendency of the data. This insight can be used to guide future project creators in setting realistic funding goals and expectations.
