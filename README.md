# employee-attrition (HR Analytics project)

## File documentation

|File Name|Description|
|:-|:-|
|`employee-attrition.xlsx`|Excel workbook of compiled datasets used for report building. Original datasets from [HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/mahmoudemadabdallah/hr-analytics-employee-attrition-and-performance?resource=download) uploaded by Mahmoud Emad Abdallah on Kaggle.|
|`employye-attrition-report.pbix`|Microsoft Power BI file of resulting interactive data dashboard report. Can be downloaded and opened using Microsoft Power BI Desktop (free).|
|`employee-attrition-report.pdf`|pdf version of above file. No interactive functions, but still helpful in terms of understanding the report results and aesthetics.|

## The why behind this project
During my job search, I came across a LinkedIn post describing Intuit's most recent wave of layoffs. While this wouldn't usually catch my eye, what was significant about this instance was the fact that Intuit very publicly described 1,050 out of 1,800 total layoffs as "low performers". Understandably, this led to outrage as (1) these public statements can have detrimental effects on the career of the now unemployed job searcher, (2) low employee performance can be due to many interlaced factors such as poor project management, excessive workloads, unclear direction, etc., and (3) low employee performance can be addressed several time prior to immediate layoff.

Regardless of the questionable management methods of Intuit's recent fumble, layoffs are undoubtably becoming a more and more aggressive cycling season in the tech industry. In order to mitigate the need for aggressive and inhumane layoffs, assessing the natural employee attrition behaviors within a company can aid in mitigating the intensity of layoff cycles. Honest and transparent employee peformance and HR analytics to assess employee attrition is evermore needed to have a good control of the hiring periods for a company, especially in the current corporate climates.

## Motivating research questions
1. How can employee performance be assessed based on different factors?
2. How does employee performance and other factors affect employee attrition?
3. Can forecasting of employee attrition inform hiring practices?


#### Technology used
Excel, Power BI


## Results and meaningful insights

The final Power BI data dashboard report is in pdf and pbix file format. If you wish to experience the interactivity of the dashboard please download the pbix file and explore with the free application Microsoft Power BI Desktop. Otherwise, the pdf file has sufficient insights and aesthetics.

Some final results, especially regarding the original motivating questions and curiosities, are listed here:

1. How can employee performance be assessed based on different factors?

   First of all, employee performance rating can vary depending on whether it is rated by the employee themselves or their manager. For analysis purposes, we continued with the managers' ratings for clarity and less bias. Company-wide-wise, average employee performance over time does not change. However, performance ratings can have a higher variance depending on job role and attrition. When exploring job roles with low attrition, there are more employees not meeting expectations as opposed to the job roles with high attrition. This may indicate for more analysis and exploration needed to understand why people are leaving the company even when they are highly rated in performance. This may be due to reasons unincluded in the data, such as more promising outside opportunities, unsupportive work enviroment, etc.
   
2. How does employee performance and other factors affect employee attrition?

   Like mentioned prior, job roles with more varying performance ratings can indicate lower attrition counts within that job role. It is important to note that this company is in a growth period. They are hiring at very high numbers, so much so that they've grown from 0 to about 1200 employees in ten years. So, first and foremost, the company's rapidly rising head count is increasing their attrition rate. Some specific job roles that have the most attrition are data scientists, sales executives, software engineers, and sales representatives. Another factor that may indicate attrition is whether or not an employee works over time. Out of all attrition counts, 53.59% of them worked over time and 46.41% didn't.

3. Can forecasting of employee attrition inform hiring practices?

   As we can see on the Overview of Company Behavior and Trajectory report page, employee attrition is not frequent and/or seasonal enough to provide insightful forecasting results. The attrition is very close to zero and very minimally increased over the ten years the company has existed. So, unfortunately forecasting is not feasible or reliable in this situation. On the other hand, simply looking at the company-wide attrition rate over time on the Employee Attrition and Performance report page can tell us more. A good attrition rate should be under 10%. With the growth period of the company, the attrition rate is at a good place. As the head count increases in the future, attrition rate should be expected to increase as well, but preventative measures should be taken to keep attrition rate under 10%. These preventative measures will relate to the factors mentioned before that can impact attrition.

## Potential actions to manage and work with the attrition rate can include:

- exploring possible incentives for employees in job roles with the most attrition (data scientists, sales executives, software engineers, and sales representatives)
- dispersing workload so that employees are not working over time
- introducing a ceiling/cap for hiring rates so that head count can maintian and level out (also leveling out attrition rate) once attrition rate approaches 10%

Utilizing this discovered knowledge can help in efforts to retain employees and manage attrition.
