# Creating and Interpreting a Call Center Performance Dashboard Using Power BI

### Introduction
This Power BI dashboard is designed to provide a comprehensive overview of call center performance. It helps in monitoring various key performance indicators (KPIs) such as average speed of answer, customer satisfaction ratings, the number of calls answered and resolved, and agent performance. The dashboard aids in understanding and improving call center operations through data visualization and analysis.
Here's a detailed explanation of the call center performance dashboard:

# Steps to Create the Dashboard
**1. Data Import**
Import relevant data into Power BI, such as call times, satisfaction ratings, call outcomes, and agent statistics. Use data sources like Excel files, databases, or APIs to gather the necessary data.

**2. Data Transformation**
Use the Power Query Editor to clean and transform the data. Ensure fields are in the correct format and address any missing or inconsistent data. Create calculated columns or measures for specific KPIs if needed.

### Key Sections

#### 1. Average Speed of Answer in Seconds
This section displays the average time taken to answer calls. For this dashboard, the average speed of answer is 67.52 seconds. This metric helps assess the efficiency of the call center in responding to customer inquiries promptly.
Visual Type: Card Visual
Measure: AVERAGE([Speed of Answer])

#### 2. Average Satisfaction Rating
A gauge chart in this section shows the average customer satisfaction rating, which is 3.40 out of 5. This metric indicates the overall satisfaction level of customers with the service provided by the call center.
Visual Type: Gauge Chart
Measure: AVERAGE([Satisfaction Rating])

#### 3. Answered Calls
This donut chart illustrates the proportion of answered and unanswered calls. The data shows that out of a total of 5,000 calls, 4,050 were answered, and 950 were not answered. This metric highlights the call center's ability to handle incoming call volume effectively.
Visual Type: Donut Chart
Fields: CALL STATUS (categorized as Answered/Not Answered)

#### 4. Resolved Calls
Similar to the answered calls section, this donut chart shows the proportion of resolved and unresolved calls. Out of 5,000 calls, 3,650 were resolved, while 1,350 were not resolved. This metric measures the call center's success in resolving customer issues.
Visual Type: Donut Chart
Fields: CALL RESOLUTION STATUS (categorized as Resolved/Not Resolved)

#### 5. Number of Calls Per Month
A bar chart in this section shows the percentage of calls answered and not answered for January, February, and March:
Visual Type: Bar Chart
Fields: MONTH, CALL STATUS (answered/not answered)
- **January**: 82% answered, 18% not answered
- **February**: 80% answered, 20% not answered
- **March**: 81% answered, 19% not answered

This metric provides insights into monthly call center performance trends.

#### 6. Agent Statistics
A table provides detailed statistics for individual agents, including the number of calls answered, resolved, average satisfaction rating, and average speed of answer.
This section allows for performance comparisons between agents and helps identify areas for improvement.
Visual Type: Table Visual
Fields: Agent Name, Calls Answered, Calls Resolved, Avg Satisfaction Rating, Avg Speed of Answer

#### 7. Avg Talk Duration vs Answered
A line chart in this section shows the correlation between the count of answered calls (Y/N) and the average talk duration. This metric helps understand how call duration impacts the likelihood of calls being answered.
Visual Type: Line Chart
Fields: Avg Talk Duration (Y-axis), Call Count (categorized as Answered/Not Answered)

### Insights
- The call center is performing well in terms of answering and resolving calls, with a high percentage of calls being answered and resolved.
- There is room for improvement in the average speed of answer to reduce customer wait times.
- The average satisfaction rating of 3.40 indicates that there is potential for enhancing customer satisfaction.
- Monthly trends suggest consistent performance, with slight fluctuations in call handling efficiency.
- Agent statistics highlight individual performance, with some agents performing better in terms of speed of answer and satisfaction ratings.

### Conclusion
The dashboard provides valuable insights into the call center's performance, highlighting strengths and areas for improvement. By monitoring these key metrics, the call center can take data-driven actions to enhance efficiency, resolve more calls, and improve overall customer satisfaction. The detailed agent statistics enable targeted training and support to boost individual and team performance.
