# 💬 Text Analysis for Caregiver Hiring MVP Development
 **🛠️ Python (PRAW, pandas, text analysis)**  
 
As part of an early-stage MVP ideation for a caregiver hiring platform, this project explores Reddit discussions related to caregiving to uncover key user pain points, unmet needs, and regional demand patterns.

Using web scraping and text analysis techniques, I collected and analyzed posts from both caregiver-focused subreddits and Canada-specific communities. The goal was to extract raw, unfiltered insights to guide product direction and validate market needs for CareCarry, a caregiver hiring and tax compliance platform. Key methods include keyword filtering, sentiment analysis, and regional segmentation.
<br>

📎 Rachel Kim  
📅 Date: 2025.08 (Completed - 2025.08.05)  
📚 Hackathon Project
<br>

---

### 📂 Project Objective  
- To identify caregiver-related user pain points, emotional burdens, and regional service gaps by analyzing Reddit posts.  
Findings were used to inform MVP ideation for a caregiver employment and tax support platform.

### 📂 Data Collection  
- Source: Reddit (via PRAW)  
- Subreddits: caregiving, caregivers, CaregiverSupport, PersonalFinanceCanada, etc.  
- Keywords: “caregiver”, “home care”, “caregiver tax”, “PSW”, “no benefits”, “overworked”, etc.  
- Datasets:  
  1. `keyword_tagged_posts.csv` – keyword-tagged posts (incl. duplicates)  
  2. `unique_posts.csv` – deduplicated version for analysis  

### 📂 Key Analyses Performed  
- Complaint keyword frequency & sentiment analysis  
- Comparative analysis between employer and caregiver pain points  
- Sample emotional sentences extracted via keyword filtering  
- Regional discussion distribution across Canada-based subreddits  
- Strategic implications for MVP feature development and positioning

### 🛠️ Tools & Technologies  
Python (PRAW, pandas, matplotlib, wordcloud, etc)  
Text cleaning, keyword extraction, user insight mining
