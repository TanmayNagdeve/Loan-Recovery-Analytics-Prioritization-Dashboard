# Loan-Recovery-Analytics-Prioritization-Dashboard
Data analytics project to optimize loan recovery using segmentation and scoring. Built a Power BI dashboard and rule-based strategy using DPD, payment behavior, and customer data to prioritize accounts and improve recovery outcomes.
This project focuses on improving recovery rates for non-performing loans (NPLs) by applying data-driven analysis and prioritization strategies.
The goal was to identify high-impact factors affecting recovery and design an efficient approach to maximize collections.
Problem Statement :
Financial institutions often struggle to recover outstanding amounts efficiently due to:
Lack of prioritization
Inefficient resource allocation
Over-reliance on single metrics like DPD
This project addresses these challenges using analytics.
Key Insights : 
~71% accounts fall into low recovery probability (90+ DPD)
₹866M total outstanding amount
₹652M concentrated in medium recovery segment (highest opportunity)
Even customers with good history showed low recovery probability.


Approach : 
1. Segmentation
Accounts were segmented into:
High Recovery (1–30 days)
Medium Recovery (31–90 days)
Low Recovery (90+ days)
2. Scoring Model
A rule-based scoring system was designed using:
Days Past Due (DPD) – 40%
Last Contact Outcome – 20%
Payment History – 20%
Income Band – 20%
This helped rank accounts based on recovery likelihood.
3. Strategy Design
High Recovery: Calls, SMS, WhatsApp
Medium: Early intervention to prevent slippage
Low: Field visits and legal action
4. Resource Optimization
Expensive actions (legal/field) reserved for high-risk accounts
Soft channels used for recoverable segments

Dashboard :
Built an interactive Power BI dashboard to:
Track recovery rates
Segment accounts dynamically
Support decision-making

Business Impact :
Focus on ₹652M segment → highest ROI potential
Prevent transition to NPAs
Even a 5% improvement can significantly increase recovery

 AI Applications (Conceptual) : 
Predict recovery likelihood using historical data
Recommend next-best action
Automate follow-ups using AI agents
Generate personalized communication strategies


Tools Used : 
SQL
Power BI
Excel
Key Takeaway :
Data is not just for reporting—it is a tool for prioritization and decision-making.
