## Customer Satisfaction and Service Quality in Canadian Retail – Topic Modeling & Sentiment Analysis

## 📌 Overview:
This project investigates the relationship between customer satisfaction and service quality in the Canadian retail sector by applying **Natural Language Processing (NLP)** techniques on user-generated reviews collected through web scraping. The focus was to uncover key discussion themes and understand how they correlate with customer sentiments to support actionable improvements in service delivery.

## 🎯 Objective

- To collect and clean customer review data from online sources.
- To perform sentiment analysis and understand the emotional tone of customer feedback.
- To apply topic modeling and identify common themes across reviews.
- To explore word frequency patterns and highlight key issues and strengths mentioned by customers.

## 🔍 Methodology:
1. Data Collection:
Customer reviews and retail-related feedback were scraped from blogs and websites using Python libraries (Requests, BeautifulSoup).

2. Data Preprocessing:
Cleaned and prepared text data using Pandas and NLTK—this involved removing duplicates, handling missing values, tokenization, lemmatization, and stopword removal.

3. Sentiment Analysis:
Applied VADER and TextBlob to classify reviews into positive, neutral, and negative sentiment categories based on polarity thresholds.

4. Topic Modeling:
Employed Latent Dirichlet Allocation (LDA) to uncover five dominant themes in the reviews:

 - E-Commerce Services

 - Delivery Issues

 - Product Quality

 - Customer Support

 - Pricing and Offers

5. Visualization:
Generated word clouds and stacked bar charts to visualize sentiment distribution across identified topics. Most feedback was neutral , with positive insights on pricing and support, and negative feedback primarily on delivery and product quality.

![image](https://github.com/user-attachments/assets/ff387878-11d4-48fe-912d-6ab37a9b3bc1)

![image](https://github.com/user-attachments/assets/c3053bca-2a41-442e-ab6d-510e0713033e)

![image](https://github.com/user-attachments/assets/7ba166fc-9aa8-440b-b1d0-f4c24baf4d9d)


## 🛠️ Tools & Libraries

- Python, pandas, NumPy  
- BeautifulSoup, requests  
- NLTK, VADER 
- Matplotlib, Seaborn, WordCloud

  
## 📊 Key Insights:
  1. Neutral Sentiment Dominance: Most reviews were descriptive rather than emotionally charged.

  2. Delivery & Product Issues: Frequent sources of customer dissatisfaction.

  3. Positive Drivers: Competitive pricing and responsive customer support were well-received.

  4. Emotional Triggers: Anger and sadness were tied to late deliveries and poor product quality, while joy stemmed from good deals and helpful service.

## ✅ Outcome & Recommendations:
This analysis highlighted critical service areas that influence customer loyalty and provided data-backed recommendations such as improving delivery systems, enhancing product quality control, and leveraging positive customer stories in marketing. The findings support retailers in building trust, increasing retention, and creating a more satisfying shopping experience.

## Author 
**Pavithra Pillappa**

📧 pavithra2749@gmail.com  
🔗 www.linkedin.com/in/pavithra-pillappa
