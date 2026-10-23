# gujarat-tourism-investment-analysis
Power BI analysis of Gujarat tourism and hotel supply to support investment prioritisation and regional development recommendations.

A proposed ₹6,500 crore investment framework for inclusive tourism development
Developed for QUB GIFT City Datathon 2026 - Data for Good, this team project combines hospitality analysis with a proposed investment strategy for Gujarat tourism. The final presentation examines 2,364 hotel listings across 24 destinations and recommends allocating investment across three tiers.

Tools: Power BI · Excel
Focus: Business analysis · Investment prioritisation · Regional development
Business problem
Where should Gujarat direct tourism investment to support destinations with limited accommodation supply, improve existing infrastructure and distribute development opportunities more widely?

The project assesses differences in hotel availability, guest ratings, prices and regional coverage. These insights inform a proposed allocation of a ₹6,500 crore case budget.
Objectives
- Compare accommodation supply and quality across destinations.
- Identify destinations for further investment assessment.
- Consider affordability and regional inclusion when prioritising interventions.
- Translate findings into a tiered investment proposal.
- Communicate the analysis through a four-page Power BI report and a strategy presentation.
Data and project scope
Component	Coverage
Hotel analysis	2,364 listings across 24 destinations, as reported in the final presentation
Regional framework	Six region types
Hotel attributes	Ratings, listed and discounted prices, facilities and location information
Supporting context	Tourism statistics and 2011 district census data
Deliverables	Four-page Power BI report and final team presentation


The supplied workbook includes hotel, tourism and census sheets. Historical census figures provide demographic context rather than current population estimates.
Methodology
1. Data preparation and enrichment
The presentation describes 21 derived columns, including price tiers, value scores, facility tiers, regional classifications, distance parsing and data-quality flags.
2. Supply-Quality Mismatch Index
The team used a Supply-Quality Mismatch Index (SQI) to compare average hotel ratings with listed accommodation supply:
SQI = Average hotel rating / log10(Hotel count)
A higher score highlights destinations with relatively strong ratings and fewer listed hotels. The index supports initial prioritisation; further demand and feasibility analysis is necessary before investment.
3. Regional analysis
The framework compares regional accommodation availability and budget hotel coverage, using district census information as additional context.
4. Investment recommendations
The final presentation groups destinations into investment tiers and proposes different interventions for infrastructure development, upgrades and maintenance.
Findings highlighted in the final presentation
Destination	Hotel count	Average rating	SQI	Interpretation
Surendranagar	7	3.59	4.24	High priority for further assessment under the SQI framework
Patan	10	3.92	3.92	Strong ratings with limited listed accommodation
Saputara	28	3.81	2.63	A candidate for additional accommodation assessment
Ahmedabad	480	—	1.29	Substantially greater existing listed supply


The central recommendation is to direct a larger share of the proposed budget towards destinations with limited accommodation supply, while improving and maintaining established locations.
Proposed allocation
Investment tier	Recommended intervention	Budget share	Allocation
Tier 1 — Invest	Develop accommodation and supporting tourism infrastructure in 14 priority destinations	55%	₹3,575 crore
Tier 2 — Upgrade	Improve existing infrastructure across seven destinations	30%	₹1,950 crore
Tier 3 — Maintain	Maintain infrastructure, support digitisation and encourage visitor dispersal from three metros	15%	₹975 crore
Total		100%	₹6,500 crore


This allocation is a team recommendation developed for the datathon case. It does not represent funds actually deployed.
Illustrative impact scenarios
The presentation explores potential outcomes under the proposed strategy:
- 300 new hotels: a proposed Tier 1 development target.
- 2,400+ direct hospitality jobs: based on the assumption of eight jobs per proposed hotel.
- Approximately ₹8,937 crore in gross economic output: the presentation's scenario applying a 2.5× multiplier to Tier 1 investment.
These figures are projections based on assumptions, not achieved results. Gross economic output should be interpreted separately from financial profit or investor ROI. The multiplier's source, applicability and time horizon require validation before practical use.
Power BI report
The report contains four pages covering:
Page	Analytical coverage
1	Hotel supply, destination mapping, ratings and prices
2	Price comparisons, literacy context and tier distribution
3	Infrastructure gaps, population and geographic prioritisation
4	Population versus hotel supply, with priority scores


Open the PBIX in Power BI Desktop to explore the report. Updating the Excel source path may be necessary before refreshing the data.
Repository contents
File	Description
[Power BI report](PowerBI_Dashboard.pbix)	Editable four-page report
[Final presentation](Summary_PPT.pptx)	Team findings and investment proposal
[Source workbook](hotels_gujarat.xlsx)	Hotel data and supporting tourism/census context, if redistribution is permitted
images/	Dashboard screenshots for viewing directly on GitHub


Project attribution
This is a team datathon project. Amrita Kumari served as team lead. Findings and recommendations presented here reflect the team's final presentation.
Limitations
- Hotel listings may not represent the complete accommodation market or unique properties.
- Ratings and listing counts do not establish occupancy, room capacity or unmet demand.
- SQI is sensitive to small hotel counts and does not directly estimate investment returns.
- Price discounts alone do not prove market distress or seasonality.
- The investment proposal requires additional demand, cost, environmental and feasibility assessment.
- Dataset provenance and redistribution terms should be confirmed before sharing source data publicly.
Business analysis relevance
The project demonstrates how descriptive analysis can support a structured investment discussion: define the decision, compare destinations, develop a prioritisation framework and communicate recommendations with explicit assumptions.
