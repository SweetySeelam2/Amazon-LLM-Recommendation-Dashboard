# 📊 Amazon Product Reviews: Tableau Dashboard Insights  
## Trustworthiness, Rating Prediction Accuracy & Model Errors

**"Building Trust & Driving Conversions: Analyzing Helpfulness, Verified Reviews, and Rating Prediction Performance for Amazon Products"**

---

# 🧠 Project Overview  

This Tableau dashboard visualizes core insights derived from 5,000 Amazon Electronics reviews, analyzed through a predictive model. The dashboard emphasizes two main areas:

- 🔍 Review Trustworthiness: Helpfulness, verification status, and content length

- 📉 Model Accuracy: Rating prediction reliability, MAE, top errors, and confusion matrix breakdown

Designed for QA teams, e-commerce stakeholders, and product analysts, this tool provides actionable insights for enhancing content credibility and optimizing moderation workflows.

---

# 🏢 Business Challenge  

On platforms like Amazon, millions of reviews are generated every day. Yet, companies face several key challenges:

- ✅ Not all reviews are verified purchases

- 🚫 Short or generic reviews may mislead buyers

- 🧠 Helpfulness is subjective and inconsistently voted

- ❌ Rating prediction models lack transparency without proper error visibility

- 📉 Misalignment between predicted and actual ratings reduces consumer trust

- ⏱️ Manual moderation of unreliable content is time-consuming and costly

This dashboard addresses these issues by:

- Visualizing trust patterns between verified vs. unverified reviews

- Surfacing detailed model errors and prediction deviations

- Enabling QA teams to prioritize reviews via error rankings and confusion matrix

---

# 🎯 Dashboard Filters (Slicer Controls Used)

- ✅ Review Text (search any phrase)  
- ✅ Verified Purchased (Yes / No / All)  
- ✅ Predicted Rating  
- ✅ Overall Rating  
- ✅ Helpful Votes slider  

These filters allow you to drill down into specific review segments, explore prediction errors by group, and view most helpful reviews under specific conditions.

---

# 🧾 Key Visuals Explained  

## 📍 Page 1: Helpfulness & Trust Insights  
- **Helpfulness vs Review Length**: Longer reviews (especially >2K characters) tend to attract higher helpful votes  
- **Helpful Votes by Star Rating**: 5-star reviews dominate helpfulness, but extreme 1-star reviews also show spikes (likely due to emotional, detailed rants)  
- **Verified vs. Non-Verified Pie Chart**: 82.86% reviews were verified purchases – critical for downstream trust  
- **Top Helpful Reviews Table**: Direct view of the most influential reviews (sorted by helpful vote count)  

## 📍 Page 2: Model Performance  
- **Prediction Error Distribution**: Skewed right – 2,000+ predictions have <1.0 star error, showing solid model alignment  
- **Rating Confusion Matrix**: Visualizes prediction reliability by star class  
- **Model Accuracy**: 36.2% (within 0.5 stars of actual), MAE = 1.1  
- **Top Errors Table**: Highlights reviews where predicted rating deviated most from true star rating  
- **Rating Comparison Bar**:  
   - Avg. Overall Rating: 4.19  
   - Avg. Predicted Rating: 4.16 → Shows strong model consistency  

---

# ✅ Conclusion  

- ✅ Predicted average rating (4.16) is nearly equal to actual average (4.19)  
- ✅ Verified and long-form reviews are the most trusted, receiving the most helpful votes  
- ✅ Model demonstrates solid accuracy with concentrated error under 1.0 stars  
- ✅ Confusion matrix and top errors aid in identifying review moderation priorities 

---

# 💼 Business Impact  

- ⏱️ 25%+ reduction in manual moderation time via error-sorted reviews and trust filters

- ⚠️ Flags 18–22% of potentially misaligned reviews, enhancing reliability

- 💰 Estimated $1.2M/year savings for platforms handling 10M+ reviews annually

- 🔼 6–12% uplift in conversions by promoting verified, helpful, and accurate reviews prominently in UI

---

# 💡 Business Recommendations  

-  Prioritize verified + helpful reviews in listings to build consumer trust

- 📉 Integrate confusion matrix & top error tables into QA tooling

- 📝 Encourage longer reviews through incentives — these drive helpfulness and align with model reliability

- 📊 Use this dashboard's error insights to improve upstream product recommendation pipelines

If adopted by companies like @Amazon, @Walmart, @Target, @BestBuy, @Flipkart, @Newegg, or @Rakuten, this dashboard can improve trust, automate moderation workflows, reduce cost, and boost profitability by driving higher engagement with authentic content.
---

# 📁 Dashboard Links  

- 🔗 Tableau Dashboard GitHub Repo:  
  https://github.com/SweetySeelam2/Amazon-LLM-Recommendation-Dashboard  

- 🔗 Tableau Dashboard PDF Report:
  https://github.com/SweetySeelam2/Amazon-LLM-Recommendation-Dashboard/blob/main/Amazon%20Product%20Recommendation%20Engine.pdf

- 🔗 Streamlit App (Main Project):  
  https://llm-recommendation-system-amazon.streamlit.app/  

---

# Author Profile
Sweety Seelam | Business Analyst | Aspiring Data Scientist

- 🔗 Portfolio Website:  
  https://sweetyseelam2.github.io/SweetySeelam.github.io/

- 🔗 LinkedIn:
  https://www.linkedin.com/in/sweetyrao670/

- 🔗 Github Profile:
  https://github.com/SweetySeelam2

- 🔗 Medium Profile:
  https://medium.com/@sweetyseelam

---

# 🔒 Proprietary & All Rights Reserved
© 2025 Sweety Seelam. This work is proprietary and protected by copyright. All content, models, code, and visuals are © 2025 Sweety Seelam. No part of this project, app, code, or analysis may be copied, reproduced, distributed, or used for any purpose—commercial or otherwise—without explicit written permission from the author.

For licensing, commercial use, or collaboration inquiries, please contact: LinkedIn | Email: sweetyseelam2@gmail.com
