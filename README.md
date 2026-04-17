**#🏥 Insurance Claims & Fraud Analysis**
- 
Diagnosing Profitability Decline in a General Insurance Portfolio

**📌 Overview**
- 
This project analyzes a general insurance portfolio experiencing declining profitability despite 18% premium growth, with claim payouts rising by 31%.
The objective is to identify whether losses are driven by fraud, pricing inefficiencies, customer risk, or operational costs.

**📊 Dashboard**
- 
- Interactive Power BI dashboards include:
- Claim Behavior Overview
- Fraud Analysis
- Policy-wise Performance
- Cost & Settlement Analysis


<img width="891" height="497" alt="Image" src="https://github.com/user-attachments/assets/a836f39e-20d2-4726-b98f-640983a95d9d" />


**📂 Dataset Summary**
- 
- ~2000 records (3 years)
- Policy Types: Auto, Health, Property, Travel, Life
- Premium Range: 2,000 – 50,000
- Claim Range: 1,000 – 50,000
- Data Preparation
- Retained missing values to avoid bias
- Created age buckets (18–30, 31–45, 46–60, 60+)
Standardized schema

**📈 Key Metrics**
- Total Claims: $38M
- Total Settlements: $31M
- Loss Ratio: 88.17%
- Combined Ratio: 137.57% ⚠️
- Fraud Rate: 4.95%
- Service Cost Ratio: 49.40%
- Combined ratio >100% → business is structurally unprofitable

**🔍 Key Insights**
- 
- 💰 Structural Profitability Issue
Loss driven by high service costs (~49%) + claims
- Indicates operational inefficiency, not just claims pressure
- 🚗 Auto Insurance Risk - 
Highest claims, frequency, and settlements
Suggests underpricing or high-risk customer inflow
- ✈️ Travel Insurance Leakage - ~6% premium contribution → ~20% claims share
- Higher fraud and claim size
→ Indicates mispricing and weak underwriting

** 🕵️ Fraud Analysis**
- Fraud rate ~5% (not primary driver)
- Concentrated in:
  60+ age group
  North region
  Specific agents
→ Localized risk, not systemic
- ⚙️ Service Cost Inefficiency
Increases with age and claim size
- Suggests:
  Manual processing
  Operational inefficiencies

**🧑‍💼 Agent Risk Concentration**
- Certain agents linked to:
  High fraud counts
  High claim exposure
 → Indicates adverse risk selection
**⚖️ Settlement Gap**
- Settlements ~20% lower than claims
- High approval rate + rising complaints
→ Trade-off between cost control vs customer satisfaction

**🧠 Final Diagnosis**
- 
- Profitability decline is driven by a combination of:
  Mispricing (Auto & Travel)
  High service costs
  Agent-driven risk exposure
  Localized fraud clusters

**🚀 Recommendations**
- 
- Immediate
- Implement agent risk scoring
- Reprice Travel insurance
- Audit service cost drivers
- Mid-Term
- Segment-based pricing (age, region)
- Risk-based claim approvals
- Long-Term
- Targeted fraud detection
- Align incentives (sales vs risk vs claims)

**⚠️ Limitations**
- Missing Claim IDs (~25%)
- Partial fraud reporting
- Correlation limitations

*🛠️ Tools Used* : 
- Power BI → Dashboard & visualization
- Excel → Data cleaning
- DAX → KPI calculations

**✨ Conclusion**
- 
The issue is not fraud alone—it is a system-level inefficiency involving pricing, operations, and incentives.
