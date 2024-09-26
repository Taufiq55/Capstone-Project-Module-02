# Discount Effect on AWS SaaS Profitability Analysis

![AWS-SaaS-Factory-2019](https://github.com/user-attachments/assets/9a50e40e-e098-4af2-a183-e357a208873d)

## Overview

This repository contains the analysis of AWS SaaS sales data with a focus on understanding the impact of discount strategies on profitability and customer segmentation. The analysis leverages RFM (Recency, Frequency, Monetary) analysis to segment customers and assess the effectiveness of discount strategies across different regions and customer segments.

## Business Understanding

SaaS (Software as a Service) is a rapidly growing business model, where software is delivered over the internet. AWS (Amazon Web Services) plays a crucial role in providing the infrastructure for many SaaS businesses. In an increasingly competitive market, companies often use discounts to attract and retain customers. However, while discounts may drive short-term sales, they can also negatively impact profit margins if not strategically managed.

To optimize marketing efforts and customer engagement, businesses employ RFM analysis to segment customers based on their purchase history. This segmentation allows for more targeted marketing and provides insights into how discount strategies impact different customer segments.

## Stakeholders

**Sales and Marketing Directors**: Responsible for overseeing the sales and marketing functions, ensuring alignment with company goals, and making high-level decisions on resource allocation, sales planning, and marketing strategies.

## Problem Statement

As the SaaS market becomes more competitive, the use of discounts has increased. However, without a clear understanding of their impact on different countries and customer segments, these discounts can erode profit margins. The challenge is to balance the need for competitive pricing with maintaining healthy profit margins while optimizing customer retention and lifetime value.

### Business Questions

1. How do discounts affect the profits generated from different countries?
2. How can customer segmentation through RFM Analysis be used to assess the sales and profit performance for each customer segment?
3. What recommendations can be made to maximize profit and retention for each customer segment?

## Goal

The primary goal of this analysis is to assess **the impact of discount strategies on the profitability of SaaS sales through AWS**. This involves:

- Quantifying the impact of discounts on profit margins, particularly identifying instances where discounts result in negative profits.
- Segmenting customers using RFM analysis to gain insights into customer behavior and engagement.
- Developing actionable insights to inform future discount strategies that drive sales without compromising profitability.
- Recommending strategies to optimize customer retention and lifetime value through targeted discount offers.

## Analysis Insights

### Discounts and Profitability
- Discounts generally lead to a significant decrease in profit across various regions and customer segments, often resulting in negative profitability despite increased sales.
- Certain regions, such as APJ and EMEA, see a shift from positive to negative profit due to discounts, indicating that current discount strategies may be detrimental.
- The NAMER region, however, shows that while discounts decrease profit, they remain positive, suggesting a more balanced market response to discounts.

### Regional Insights
- Countries like Argentina, Chile, and Mexico experience negative profits when discounts are applied, indicating that discounts are reducing profit margins rather than driving profitable sales.
- Brazil, Canada, and the United States perform well both with and without discounts, demonstrating a balanced approach where discounts effectively drive additional sales without severely impacting profitability.
- Markets such as Australia and Japan show no transactions without discounts, indicating high price sensitivity or unappealing full-price offerings.

### Customer Segmentation
- High-value customer segments like "Champions" and "Loyal Customers" may not require discounts, as offering them could be detrimental to profitability.
- Segments such as "Promising" and "New Customers" show negative profits when discounts are applied, indicating that discounts might not be the most effective strategy for these groups.
- "Need Attention" and "At Risk" segments show some responsiveness to discounts, suggesting that discounts could be strategically used to re-engage these customers and prevent churn, albeit at a cost to profitability.

### Statistical Analysis
   
The Kruskal-Wallis test reveals no significant difference in median sales and profit across different customer segments, suggesting consistent performance across segments regardless of discount strategies.

## Recommendations
- **Reevaluate Discount Strategies**: Given the negative impact of discounts on profitability, refine discount strategies, particularly in regions and customer segments where they currently lead to losses.
- **Targeted Discounting**: Focus on segments that respond positively to discounts, such as those "At Risk" of churning or in markets like NAMER where discounts yield positive profits.
- **Alternative Engagement Strategies**: For high-value customers who are already loyal, explore non-discount-based engagement strategies, such as loyalty programs, exclusive offers, or personalized experiences.
- **Personalization**: Use RFM analysis insights to tailor communication, promotions, and services to each segment.
- **Customer Feedback**: Regularly gather feedback from segments like "At Risk," "Hibernating," and "Need Attention" to understand their needs and challenges.
- **Loyalty Programs**: Consider implementing or enhancing loyalty programs for "Champions," "Loyal Customers," and "Potential Loyalists."

## Conclusion

This analysis provides critical insights into the effects of discount strategies on profitability and customer behavior. By leveraging RFM analysis and regional insights, we can optimize discount strategies to maximize profit while maintaining customer satisfaction and loyalty.

## 
For further visualization here is the tableau dashboard : https://public.tableau.com/views/CapstoneProject02_17229993915800/AmazonAWSSaaSSalesDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
