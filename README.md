# 🌟 PWD-DTI-Batam-DatSci-Final-Project 🌟

# ☁️ Click, Cluster, Convert - Big, Basket, Buy: The ML Blueprint for Olist’s E-Commerce RFM & MBA Revolution 🗑️

🏹 AssaultGroup_DTI_01_FinalProject <br>
👥 [Muhammad Difagama Ivanka](https://github.com/zeenfts), [Rizqi Ahmad Kurniawan](https://github.com/Rizqi-Ahmad-Kurniawan), [Tio Syaifuddin](https://github.com/tio14)

* [Tableau Story](https://public.tableau.com/app/profile/rizqi.ahmad.kurniawan/vizzes) 🎀
* [Tableau Dashboard](https://public.tableau.com/views/FINALDTI-DSFinalProjectOlistE-CommerceDB/HomeDashboard?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) 📈
* [Main Notebook File](https://github.com/PurwadhikaDev/AssaultGroup_DTI_01_FinalProject/blob/main/notebook.ipynb) 📝
* [Olist Brazilian E-commerce Datasets](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data?select=olist_order_payments_dataset.csv); [Geolocation](https://www.kaggle.com/code/zeeniye/geolocation-workaround-mapping-solved/notebook) 🗄
---

## Main Idea: 
Pareto's principle, a commonly accepted rule of business, states that roughly 20 percent of your customers provide 80 percent of your profits. Therefore, it makes sense for small businesses to focus much of their spending and attention on their core customers. The next tier of customers should also get some marketing attention. However, customers that do not offer much lifetime potential should not be the target of marketing investments.

## Project Overview

In today’s highly competitive e-commerce landscape, understanding customer behavior is paramount to driving success. For Olist, the primary hurdle had been a lack of meaningful customer segmentation, which made it difficult for the marketing division to personalize campaigns. This resulted in lower customer engagement, reduced marketing campaign effectiveness, and missed revenue opportunities. 

Our project centered around the implementation of machine learning (ML) models for Olist's e-commerce marketing division using Recency, Frequency, and Monetary (RFM) analysis, enhanced by a product recommendation system (RecSys) based on Market Basket Analysis (MBA). Our project utilized two core methodologies: **RFM Analysis** for Customer Segmentation (ML Clustering) and **FP-Growth algorithm** for (MB Analysis) for the task of product recommendation.

The primary goal was to enable the stakeholders to better understand their customer base and optimize their marketing strategies by addressing critical challenges in customer segmentation, marketing personalization, and product offering optimization, ultimately leading to increased transaction volumes, Average Order Value (AOV), and Customer Lifetime Value (CLV).

## Scope of the Project

The project employed RFM (Recency, Frequency, Monetary) analysis to categorize customers into 10 distinct segments based on their purchasing behavior. These segments ranged from high-value customers such as **Champions** and **Loyal Customers** to lower-value segments such as **Hibernating** and **Lost Customers**. Machine Learning clustering models, such as k-means, were NOT applied due the “Manual Binning’s” more appropriate and advanced business interpretation, hence further refining these segments, providing a clearer, data-backed picture of customer behaviors. Additionally, the **FP-Growth algorithm** was implemented to identify associations between products, enabling more personalized and effective product recommendations tailored to each segment.

The project’s **focus** was twofold:
1. **Revenue Growth:** Emphasizing marketing efforts on the top six customer segments, including Champions, Loyal Customers, Potential Champions, Can’t Lose Them, Recent Users, and Needs Attention → a.k.a. maximizing revenue by concentrating on high-value customer segments)
2. **Cost Savings:** Reducing marketing spend on the bottom four customer segments—Price Sensitive, About to Sleep, Hibernating, and Lost Customers → a.k.a. reducing costs by scaling back efforts on low-performing segments.


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

## Stakeholder Point-of-View:
By applying RFM customer segmentation and MBA in an e-commerce context, the company can expect to see tangible business benefits such as higher CLV, increased revenue, and improved marketing ROI. The key is to bridge technical improvements—like better customer segmentation and product recommendations—with core business metrics such as revenue growth, profitability, and the long-term value of customers. **(that C-suite stakeholders care about)**

1. **Revenue Growth**: By identifying high-value customer segments and leveraging MBA for product recommendations, revenue increases through higher AOV and repeat purchases. These insights help optimize marketing spend, targeting the right customers with the right products.
2. **Increased CLV**: The improved targeting through RFM increases the retention of at-risk customers, while MBA drives upsell and cross-sell opportunities, thereby boosting the average CLV of each customer.
3. **Marketing Efficiency**: With RFM segmentation, marketing efforts become more personalized and effective, leading to better ROI on marketing campaigns. By focusing resources on high-potential segments (e.g., Champions, Loyal Customers), campaigns are more likely to result in conversions.


============================================================================================================================================
## POST-PROJECT REVIEW (result interpretation)

### Impact on Stakeholders

The results of this ML implementation were profound. For the **Olist Marketing Division**, the nuanced customer segmentation provided insights that allowed for more targeted and effective marketing campaigns driven by a more tailored customer experience and optimized product offerings suited to each segments, further enhancing “Individual Personalisation”.

From the **Marketplace Sellers' perspective**, the enhanced product recommendation system has the potential to foster increased cross-selling and upselling, directly contributing to higher sales volumes and an elevated AOV. Sellers benefited from a clearer understanding of which customer segments were most likely to convert and make additional purchases, resulting in more effective promotional efforts and higher revenues.

For the **Marketplace Buyers**, the improvements led to a more engaging shopping experience. The use of personalized product recommendations increased customer satisfaction and loyalty by ensuring that they received relevant and appealing offers, thereby reinforcing their connection with the Olist brand. This ultimately resulted in higher customer retention rates and an increase in CLV.

### Impact on Business (Financial)

The results from this ML implementation yielded substantial financial benefits, most notably in terms of both revenue growth and cost savings. By focusing on high-value customer segments, the project achieved a total revenue increase of **R$3,128,320.85**. The segments that contributed the most to this growth were **Needs Attention** (R$2,437,345.64) and **Recent Users** (R$388,499.11), emphasizing the importance of nurturing emerging customers and providing them with targeted product recommendations.

Simultaneously, the project identified significant cost-saving opportunities by strategically limiting investments in the lower-value segments. This resulted in a total cost savings of **R$1,289,345.17**, driven mainly by reduced marketing spend on the **Price Sensitive** (R$327,109.53) and **Hibernating** (R$614,030.65) segments. The dual approach of increasing revenue while cutting costs resulted in an overall financial impact of **R$4,417,666.02**, underscoring the effectiveness of the ML models in enhancing business profitability.

### Future Prospects

Moving forward, the application of these Machine Learning models can be expanded to other aspects of the business. For instance, further refinement of the FP-Growth algorithm can improve cross-selling and upselling strategies by dynamically updating recommendations as customer preferences evolve. Additionally, there is also potential to explore deep learning techniques to uncover more complex patterns in customer behavior, which could lead to even more granular segmentation and better targeting. 

### Conclusion

The implementation of Machine Learning models for customer segmentation and product recommendation systems, leveraging RFM analysis and clustering techniques, helps our stakeholders in fine-tuning their respective marketing strategies, leading to significantly increased revenue and reduced operational costs, creating a positive feedback loop between customer engagement and profitability. The ability to focus marketing efforts on the most promising customer segments while reducing costs in less responsive areas offers a sustainable path for growth. As these models evolve and adapt, the future prospects for Olist’s e-commerce business look more promising, setting the stage in enhancing Olist’s marketing effectiveness, improving customer engagement, and driving overall financial growth, laying a sustainable path for future advancements.



============================================================================================================================================
## ADDITIONAL: Research on Business Metrics & Marketing Efficiency Improvement (post RFM & MBA):

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


**Sources (Notion - Holistic):** 
1. [https://endurable-sand-5da.notion.site/Business-Narrative-Calculations-5559b5d8950d493b81256b120c2ead9e?pvs=4]
2. 2. (https://endurable-sand-5da.notion.site/Biz-Data-Understanding-ipynb-Tableau-UPDATE-FINAL-Calcs-fdb7301fc7534a49a1f8e2ebc48e9014?pvs=4) (contains Machine Learning RFM-CLusteirng & MBA-RecSys business calculation details)
