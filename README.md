# Email Marketing Campaign Optimization using Machine Learning

## Objective
- Analyze an email campaign and measure performance
- Build a model to predict likelihood of users clicking the email link
- Optimize future campaigns using ML

## Data
- `email_table.csv`: Info about each sent email
- `email_opened_table.csv`: Emails that were opened
- `link_clicked_table.csv`: Emails that had a clicked link

## What was done
- Data merging and preprocessing
- Campaign performance analysis
- Built a RandomForest and then XGBoost model
- Handled class imbalance using `scale_pos_weight`
- Simulated campaign targeting top 30% likely-to-click users

## Final Results
- Open Rate: ~23.6%
- Baseline Click-Through Rate (CTR): ~2.1%
- Improved CTR with ML (Top 30% users): **~3.83%**
- Recall on clicked class improved from 1% ➝ 52%

## Business Insights
- Evening emails (6–9 PM) have higher CTR
- Users with past purchases are more likely to click
- Short and personalized emails work slightly better

## Tools Used
- Python, Pandas, Matplotlib
- XGBoost, Scikit-learn
- Jupyter Notebook

---

## How to Run
Just open the `.ipynb` notebook and run cells in order.
