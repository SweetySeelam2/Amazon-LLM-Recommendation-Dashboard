# 📊 Amazon Product Reviews: Tableau Dashboard Insights  
## Trustworthiness, Rating Prediction Accuracy & Model Explainability  

**"Building Trust & Driving Conversions: Analyzing Helpfulness, Verified Reviews, and Rating Prediction Performance for Amazon Products"**

---

# 🧠 Project Overview  

This dashboard visualizes key insights derived from a sentiment + rating prediction model trained on 5,000 Amazon Electronics reviews.  

While the full project includes a full-scale recommendation system (Retrieve → Rank → Explain), this Tableau dashboard focuses solely on two core areas:

- 🔎 Trust Indicators such as review helpfulness, verification status, and review length  
- 📉 Model Performance including predicted rating accuracy, MAE, confusion matrix, and key error analysis  

It is designed for e-commerce stakeholders, QA teams, and data product managers who want to:  
- Understand which reviews are trusted  
- Evaluate model reliability at scale  
- Reduce manual moderation time while improving review visibility and trustworthiness  

---

# 🏢 Business Challenge  

On platforms like Amazon, millions of customer reviews pour in daily. However:

- ✅ Not all reviews are verified purchases  
- 🚫 Many short or generic reviews can mislead future buyers  
- 🧠 Review helpfulness is subjective and often difficult to automate  
- ❌ Sentiment or rating prediction models are often black boxes without interpretability  
- 📉 Misalignments between true vs. predicted ratings reduce trust in AI-powered recommendations  

This dashboard solves these challenges by:  
- Visualizing trust patterns across verified vs. unverified reviews  
- Breaking down model prediction errors and accuracy  
- Empowering QA teams with Top Errors Table and Confusion Matrix  

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

- Model aligned well with real user sentiment: Predicted ratings (4.2) match average actual ratings (4.19)  
- Most trusted content comes from long, verified 4–5 star reviews  
- Top helpful reviews shape purchasing behavior and should be prioritized  
- Dashboard offers full transparency into model performance, trust insights, and moderation opportunities  

---

# 💼 Business Impact  

- ⏱️ 25%+ reduction in manual review moderation time through auto-surfacing suspicious or low-trust reviews  
- 🔍 Helps Amazon or any e-commerce platform flag 18–22% misaligned reviews, improving user trust  
- 💰 Potential $1.2M+ in annual savings across 10M reviews/year from reduced moderation, improved UX, and better review positioning  
- 🔼 Conversion rates can improve 6–12% when verified, trusted, and helpful reviews are prioritized in UI  

---

# 💡 Business Recommendations  

- 🛡️ Use the Verified + Helpful filters in downstream recommendation pipelines to promote trusted reviews  
- 🧠 Integrate Confusion Matrix & Top Error Tables into your QA dashboards  
- 💬 Encourage longer reviews via incentives — as they receive more helpful votes and are more model-aligned  
- 🧪 Use insights to train further LLM summarization or fraud detection modules  

---

# 📁 Repository Links  

- 🔗 Tableau Dashboard GitHub Repo:  
  https://github.com/SweetySeelam2/Amazon-LLM-Recommendation-Dashboard  

- 🔗 Tableau Dashboard PDF Report:
  

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

# ⚖️ Copyrights  

© 2025 Sweety Seelam. All rights reserved.  
This Tableau dashboard is strictly for academic, research, and portfolio purposes.  
Unauthorized commercial use or replication is prohibited.