# 🌟 PWD-DTI-Batam-DatSci-Final-Project 🌟

## Main Idea: 
Pareto's principle, a commonly accepted rule of business, states that roughly 20 percent of your customers provide 80 percent of your profits. Therefore, it makes sense for small businesses to focus much of their spending and attention on their core customers. The next tier of customers should also get some marketing attention. However, customers that do not offer much lifetime potential should not be the target of marketing investments.

## Research on Business Metrics & Marketing Efficiency Improvement (post RFM & MBA):

### How RFM Customer Segmentation and Product Recommendations Impact Business Metrics:
**Business Metrics Improvement: Percentage Increases:**
- **CLV**: Increasing customer retention by 5% can result in a 25-95% increase in profits .
- **ACL**: Personalization strategies can extend customer lifespans by up to 20% .
- **AOV**: Product recommendations, especially upselling and cross-selling, can boost AOV by 10-30% .
- **APF**: Cross-selling and upselling efforts can increase purchase frequency by 15-20% .
- **Sales Volume**: Effective segmentation and recommendation systems can lead to a 10-20% increase in sales volume .
- **Revenue**: Personalization through RFM segmentation and product recommendations can increase overall revenue by 10-15% .

### How Customer Segmentation (RFM) and Product Recommendations (Upselling & Cross-Selling) Impact Marketing Efficiency Metrics for E-Commerce Businesses
**Business Metrics Improvement: Percentage Increases:**
- **CAC**: Targeted segmentation can reduce CAC by 20-40% .
- **ROMI**: Personalization strategies can boost ROMI by 10-30% .
- **Conversion Rates**: Product recommendations increase conversion rates by 20-50% .
- **Customer Retention Rate**: Segmentation and recommendations improve retention rates by 5-10% .
- **CTR**: Personalized recommendations boost CTRs by 25-50% .
- **ARPU**: Upselling and cross-selling increase ARPU by 10-20% .
- **CPA**: Proper segmentation can decrease CPA by 15-30% .


## Business Narrative:

### Background:
E-commerce businesses often face challenges in understanding their customer base, tailoring marketing strategies, and optimizing product offerings. By the Implementation of an **ML clustering model for customer segmentation using Recency, Frequency, and Monetary (RFM) analysis. Enhanced by a product recommendation system (RecSys) using Market Basket Analysis (MBA)**. This project aims at providing valuable insights that can enhance marketing effectiveness, increase customer retention, and boost overall revenue through tailored and targeted (per Segment) Upselling and Cross-selling of listed products.

### Stakeholder: Olist Marketing Division

### Problem:
Stakeholders have a harder time categorising their customers into meaningful segments, making their marketing campaigns less personalised, thus leading to lower campaign effectiveness and overall customer engagement. Stakeholders wants to save their time (lower man hours) and lower operational costs through more effective Marketing campaigns, at the same time also increasing the company’s Total Product transaction volume and AOV (average order value) and most importantly, their CLV (customer lifetime value)

### Objectives:
help the Stakeholders better understanding their customer base/segments as to be able to increase campaign effectiveness and customer engagement (for increased Transaction Volume, AOV, & CLV) by providing tailored marketing strategies through optimized product offerings on a segment-by-segment basis.

### Project Goals:
1. **Olist Marketing Division:**
    1. Increased Customer Segmentation nuance and understanding (due diligence on which to invest in)
    2. More personalised and effective marketing campaigns tailored to each Segment
    3. A more effective approach to a Product Recommendation System that increases sales numbers through Upselling & Cross-selling
2. **Marketplace Seller’s Perspective:**
    1. Increased Sales numbers from Cross-selling
    2. Increased AOV (average order value) from Upselling
3. **Marketplace Buyer’s Perspective:**
    1. More engaged with the brand through more relevant product offerings 
    2. Increase satisfaction through better product recommendations

### Project Implementation:
1. **Customer Segmentation:** Tailored UX experience aimed at increasing spending through tailored segment-specific triggers (promotions, bundles, timely deals, etc)
2. **Product Upselling & Cross-selling:** UI elements that emphasize Product Offerings front-and-center. These offerings would not just be attention-grabbing visually, but by context as well (products that have high association to each other)

### Key Guiding Questions (GQs):
1. **Marketing Analytics Combination:** How effective can the combination of RFM Analysis & Market Basket Analysis provide the stakeholders with the desired result? How would the 2 methods synergise and complement each other?
2. **RFM Considerations:** Why an RFM Analysis be the combined-best solution to address the Stakeholder's Customer Segmentation concerns?
3. **MBA Considerations:** Why a Market Basket Analysis be the combined-best solution to address the Stakeholder's Customer Personalisation concerns?
4. **Main Goal:** How can the proposed ML approach holistically address Customer Segmentation & Personalisation marketing-related issues?

### Key Proposed Solutions (PSs):
1. **Method Combination:** By combining results from Marketing Analytic Methods: Customer Segmentation (RFM | Clustering) and Product Recommendations (MBA | FP-Growth) on the dataset provided (2016-2018)
2. **RFM:** Recency-Frequency-Monetary analysis will identify the customer segments whom are most desirable to the company's business goals
3. **MBA:** Market-Basket analysis will help identify ancillary products these highly desirable customer segments are most likely to buy in addition to the primary product (their current purchase behaviour)
4. **The Ultimate Goal:** targeted Marketing campaigns through Product Recommendation Systems (Upselling and Cross-selling) of listed products that are tailored for each Customer Segments
    
## Business Arguments:

1. **Argument-1**: **Revenue Growth**:
By using insights from MBA for Optimized Product Recommendations, the business can implement recommendation engines that suggest products frequently bought together, leading to increased AOV (average order value), and thus increased revenue growth rate
2. **Argument-2**: **Increased Customer Lifetime Value (CLV)**:
Targeting high-value customers (e.g., "Champions" and "Loyal Customers") with personalized offers will encourage repeat purchases, thus increasing CLV.
3. **Argument-3**: **Enhanced Marketing Efficiency**
By segmenting customers based on RFM analysis and using MBA for product affinity, marketing campaigns can be more personalized and targeted. This will increase the relevance of marketing messages, improving open rates, click-through rates (CTR), and conversion rates.

## Business Implementation (+ Technical Insights):

- **<<< RFM Analysis >>>**
    - **Customer Segmentation**: The effective segmentation of customers allows for targeted marketing strategies, increasing the likelihood of customer engagement and conversion. This is reflected in improved sales figures and customer retention.
    - **Clustering Metrics**: The high silhouette score and low Davies-Bouldin index indicate that the customer segments are distinct and meaningful. This means that marketing strategies tailored to each segment are likely to be effective.
- **<<< Market Basket Analysis >>>**
    - **Product Recommendations**: Strong association rules enable personalized recommendations that can boost average order value and sales. Implementing these recommendations effectively translates to higher revenue and improved customer satisfaction.
    - **MBA Metrics**: High confidence and lift for product recommendations suggest strong relationships between items, which can be leveraged to enhance cross-selling and upselling opportunities.

## Stakeholder Presentation:
By applying RFM customer segmentation and MBA in an e-commerce context, the company can expect to see tangible business benefits such as higher CLV, increased revenue, and improved marketing ROI. The key is to bridge technical improvements—like better customer segmentation and product recommendations—with core business metrics such as revenue growth, profitability, and the long-term value of customers. **(that C-suite stakeholders care about)**
When presenting to C-suite stakeholders, the focus should be on how technical improvements from RFM and MBA directly impact business outcomes:
    1. **Revenue Growth**: By identifying high-value customer segments and leveraging MBA for product recommendations, revenue increases through higher AOV and repeat purchases. These insights help optimize marketing spend, targeting the right customers with the right products.
    2. **Increased CLV**: The improved targeting through RFM increases the retention of at-risk customers, while MBA drives upsell and cross-sell opportunities, thereby boosting the average CLV of each customer.
    3. **Marketing Efficiency**: With RFM segmentation, marketing efforts become more personalized and effective, leading to better ROI on marketing campaigns. By focusing resources on high-potential segments (e.g., Champions, Loyal Customers), campaigns are more likely to result in conversions.


**Sources (Notion - Holistic):** https://endurable-sand-5da.notion.site/Business-Narrative-Calculations-5559b5d8950d493b81256b120c2ead9e?pvs=4 
* contains Machine Learning RFM-CLusteirng & MBA-RecSys business calculation details
