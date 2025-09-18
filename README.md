# 📊 Market Sentiment & Trader Performance Analysis

**Author:** Ishita Jaiswal  

## 🔎 Overview
This project analyzes how trader performance (PnL, trade volume, win rates) relates to market sentiment, using the **Fear & Greed Index**.

## 📂 Repository Structure
- `Market_Sentiment_Analysis.ipynb` → Main Colab notebook
- `Market_Sentiment_Analysis.pdf` → Report version (optional)
- `data/` → Input datasets (historical trades + sentiment index)
- 📂 Full dataset (~XX MB): [Download here](https://drive.google.com/file/d/1-fgDzU9vtvZBJ1rblqjaaP_4jSYpkOX2/view?usp=sharing)


## 🚀 How to Run
1. Open `Market_Sentiment_Analysis.ipynb` in **Google Colab**.  
2. Upload the raw datasets (`historical_data.csv`, `fear_greed_index.csv`).  
3. Run all cells step by step.  

## 📊 Key Results
- Daily PnL varies significantly across sentiment categories (Kruskal-Wallis p < 0.05).
- Some accounts perform better in **Greed conditions**, while others thrive in **Fear conditions**.
- Trader activity levels (trade count, volume) also shift with sentiment.

---
