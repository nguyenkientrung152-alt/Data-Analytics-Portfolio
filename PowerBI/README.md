Hi, I'm Kien Nguyen. I'm an aspiring Business Analyst / Supply Chain Analyst based in Australia with a background in Economics and Supply Chain Management.

Insurance Premium & Payout KPI Dashboard
A Power BI dashboard analyzing a portfolio of 7,000 insurance policies, tracking premium collection, payout obligations, ROI performance, and sales agent productivity through a fully modeled star schema — built for the Data Analytics unit at Macquarie University.

Dashboard Screenshot

Business Questions Answered
What is the total premium book size, and how much has been collected vs. is still payable?
Which policy types, states, and sales agents generate the most premium revenue?
How has portfolio ROI trended over time, and how does that vary by tenure?
What does the future premium payment/maturity schedule look like (cash flow forecasting)?
How is sales performance structured across the Sales Agent → Regional Manager → Zonal Manager hierarchy?
Key Metrics (Portfolio Overview)
Metric	Value
No. of Policies	7,000
Total Premium Amount	39,097M
Total Annual Premium	2,162M
Total Premium Paid	10,686M
Total Premium Payable	28,410M
Underwriting Expense	39M
Key Metrics (Payment Bucket: Payable in 10 Years)
Metric	Value
Total Premium Amount	6,505M
Total Premium Paid	2,116M (32.52%)
Total Premium Payable	4,390M (67.5%)
Key Insights
Whole and Endowment policies dominate the annual growth-rate mix, together accounting for the large majority of fixed-rate policy growth, with Universal policies a smaller share.
Revenue is geographically concentrated in Delhi (271M) and Uttar Pradesh (239M), together outpacing the next 8 states combined — a useful signal for regional resource allocation.
Top sales agent Baiju Singh generated 273M in annual premium, roughly 14% more than the next-highest agent (Divij Malhotra, 239M), out of 20+ tracked agents — highlighting concentration risk in a small group of top performers.
Portfolio ROI has climbed sharply, from 3.25% (2016) to 19.13% (2024), while total premium and maturity amounts have stayed relatively flat (~3.6–4.7B) — indicating improving capital efficiency rather than book growth.
For 25-year tenure policies specifically, ROI grew from 4.48% to 14.67% over the same period, tracked alongside coverage (sum assured) amounts reaching 192M by 2024.
The premium payable schedule (2032–2036) shows maturity payouts growing from ~2.0B to ~5.0B, useful for cash flow and reserve planning.
The sales hierarchy view (Sales Agent → Regional Manager → Zonal Manager) enables profit/gain tracking at the individual agent level — e.g. Baiju Singh's book shows 411M in profit/gain against 4.6B in premium amount.
Data Model
Built as a star schema in Power BI with:

Fact table: FCT Insurance_Policy_Transaction
Dimension tables: DM Customer_Detail, DM Insurance_Agent, DM Policy_Protection, DM Policy_Type, DM Regional_Manager, DM Zonal_Manager
Parameter tables: Visual Parameter (toggles chart measures), Parameter - Selection (drives dynamic filtering)
This structure supports the slicers across Policy Type, Policy Name, Sales Agent, Year, State, Occupation, and Tenure seen throughout the report.

Tools Used
Microsoft Power BI (DAX, star schema data modeling, what-if parameters, drill-through, matrix/hierarchy visuals)
Files
Insurance_Premium_and_Payout_KPI_Dashboard.pbix — full interactive dashboard file
screenshot.png — dashboard preview image
LinkedIn:(https://www.linkedin.com/in/nguyen-kien-trung/)
Email: nguyenkientrung152@gmail.com
Thank you for visiting my portfolio!
