# Employee Sentiment Analysis

## Key Findings

### Top Performers
**Most Positive Employees:**
1. eric.bass@enron.com (Consistently positive communication)
2. patti.thompson@enron.com (High positive score)
3. kayne.coulter@enron.com (Frequent positive engagement)

**Most Negative Employees:**
1. sally.beck@enron.com (Multiple urgent negative messages)
2. lydia.delgado@enron.com (Consistent negative tone)
3. johnny.palmer@enron.com (Severe negative content)

### Flight Risks Identified
1. johnny.palmer@enron.com (Urgent negative messages)
2. patti.thompson@enron.com (Frequent negative pattern)
3. sally.beck@enron.com (Severe negative content)

## Key Insights
- 74.6% of communications are neutral, 20.3% positive, and only 5.1% negative
- Positive sentiment correlates with company events
- Negative communications often contain urgent language ("issue", "concern")
- Gradient Boosting model achieved best prediction (R² = 0.42)

## Recommendations
1. **Immediate Action:** HR should contact the 3 flagged flight risks
2. **Recognition Program:** Reward top positive communicators
3. **Process Improvement:** Analyze negative message triggers
4. **Ongoing Monitoring:** Implement quarterly sentiment reviews

## How to Use These Results
1. Review `/kaggle/working/top_positive_employees.csv` for recognition candidates
2. Check `/kaggle/working/flight_risks.csv` for intervention priorities
3. See `/kaggle/working/model_results.csv` for predictive model details
