# NeoBank

Project Objective:
Elevate NeoBank's customer support capabilities by implementing a sophisticated dashboard for monitoring customer churn rate and satisfaction levels. We've devised strategic metrics that comprehensively cover various aspects, including monthly active user numbers, user demographics, age group distributions, transaction frequencies, average transaction amounts, notification engagement rates, and average churn rates per month. To enhance fraud detection capabilities, we've incorporated advanced analytics, including Z-score analysis, enabling the proactive identification of potential outliers in transaction patterns.

Analysis & Conclusion:
The data reveals that the majority of customers are from the UK (35%), followed by Ireland (11%) and Poland (9%). Despite a growing customer base, the observed average monthly churn rate of approximately 6.72% aligns favorably with industry benchmarks, indicating a healthy retention rate. Notably, baby boomers exhibit the highest monthly churn rate at 10.6%, while millennials boast the lowest at 5.89%. The inverse relationship between churn rates and notification success rates suggests a positive impact on user retention. Enhanced analytics related to suspicious transactions could aid the customer support team in reaching out to users, investigating failures, and providing assistance. Proactive measures, such as user verification and enhanced monitoring for specific MCCs, can be implemented to detect anomalies effectively. Flagging accounts for additional scrutiny or fraud prevention measures, coupled with notifying users about observed patterns, can enhance overall security.

Customer Engagement Metrics and Segmentation:
- Active customer: Last transaction within 30 days
- Inactive customer: Last transaction between 30 and 60 days
- Churned customer: Last transaction beyond 60 days

Churn Rate Definition:
Percentage of users remaining active from one period to the next, indicating user retention effectiveness over time.

Customer Age Group Definitions:
- GenZ: 18 to 25
- Millennials: 25 to 40
- GenX: 40 to 55
- Baby boomers: 55 and above

Additional Metrics Definitions:
- Monthly Active User (MAU): Count of unique users with at least one transaction in a month, offering an overview of user activity.
- Transaction Frequency: Average number of transactions per user within a specific time period, reflecting user engagement.
- Average Transaction Amount: Average amount transacted by users, providing insights into financial activity.
- Notification Engagement Rate: Percentage of users accepting marketing push and email notifications.

Fraudulent-Related Analysis:
1. Unusual Frequency of Failed Transactions: Identifying higher-than-average frequencies of 'DECLINED/FAILED' transactions.
2. Unusual Transaction Amounts by Merchant Category: Detecting transactions with significantly higher amounts compared to the average within the same Merchant Category Code (MCC).
3. Unusual Transaction Amount: Recognizing transactions where the amount_usd deviates significantly from the user's typical transaction amount.
4. Unusual Transaction Frequency: Identifying transaction frequencies significantly higher than the average daily transaction frequency.

