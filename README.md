
# Social Media Ad Optimization

This project analyzes social media ad campaign performance using a dataset of user interactions. It uncovers which platforms, ad categories, and user segments drive the highest engagement, conversions, and simulated revenue.

---

## Problem Statement

In digital advertising, understanding which ads perform best across devices, platforms, and times is critical. This project aims to surface performance insights using CTR, CVR, engagement, and revenue simulation metrics.

---

## About the Dataset

- **Format**: CSV file  
- **Records**: User-level interaction data  
- **Key Features**:
  - Demographics: Age, gender, interest
  - Ad metadata: Platform, category, type
  - Performance: Impressions, clicks, conversions
  - Temporal: Day of week, timestamp
  - Device used: Desktop, Mobile, Tablet

---

## Project Structure

```
📁 social-media-ad-optimization/
├──  social_media_ad_analysis.ipynb   # Python notebook
├──  README.md                         # Project overview
├──  data/
│   └── social_media_ad_optimized.csv   # Cleaned dataset
├──  requirements.txt                 # Required libraries
```

---

##  Techniques & Models Used

- Data preprocessing & cleaning
- Metric engineering (CTR, CVR, Engagement Score)
- Aggregation & temporal analysis
- Revenue estimation (using fixed CPC)
- KMeans clustering for user segmentation
- Data visualization with matplotlib & seaborn

---

##  Visual Insights

- **CTR Analysis**: Instagram outperforms Facebook in click-throughs  
- **CVR by Category**: Food & Beverage shows highest conversion rates  
- **Revenue Insights**: Electronics and Gadgets generate top revenue  
- **Device & Day Impact**: Desktop performs well midweek; mobile varies  
- **Clustering**: User segments with high engagement vs low performance  

---

##  Key Results

- Instagram yields ~55% CTR vs Facebook's ~52%  
- Wednesday sees highest engagement and conversions  
- Electronics category leads in revenue simulation  
- Segment 0 users are highly engaged; Segment 2 least responsive  

---

##  How to Run This Project

```bash
git clone https://github.com/YOUR_USERNAME/social-media-ad-optimization.git
cd social-media-ad-optimization
pip install -r requirements.txt
jupyter notebook social_media_ad_analysis.ipynb
```

---

##  Tools & Libraries

- **Python**: pandas, numpy, seaborn, matplotlib, scikit-learn  
- **Jupyter Notebook**  
- **CSV**: Structured data input

---

##  Use Cases

- Improve ad engagement and ROI through data-backed decisions  
- Identify high-performing ad combinations and user segments  
- Optimize ad spend across platforms and timing windows  
- Simulate revenue potential for different categories

