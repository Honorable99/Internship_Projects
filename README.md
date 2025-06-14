## Internship Projects

### 1. Global Debt Analysis  
Global Debt Analysis Dashboard – Documentation

🔎 Overview
This project explores global debt metrics across three major dimensions: General Government Debt, Household Debt, and Private Sector Debt. Using Power BI, I transformed raw data into a compelling, interactive dashboard that visualizes national debt levels while also uncovering patterns and high-risk zones.

Beyond the visuals, I applied a McKinsey-style business analysis framework to extract deeper insights, understand the implications of debt distribution, and suggest policy-driven recommendations.

📌Dashboard Development Process (Technical Walkthrough)
📥 Step 1: Data Acquisition
The dataset was sourced from a reputable financial institution and contained time-series data on national debt levels for over 100 countries. The figures represented percentages of each country’s GDP, categorized under:
	•	General Government Debt
	•	Household Debt
	•	Private Sector Debt

🧹 Step 2: Data Cleaning & Preparation
To prepare the dataset for analysis, I first performed an exploratory data review to identify missing values, formatting inconsistencies, and outliers. 

Next, I removed records with significant gaps and imputed missing values using forward-fill logic, particularly where yearly data could be reasonably projected. The data was then transformed from a raw long-form structure into a format suitable for Power BI modeling—allowing for clean filtering by year, region, and debt category.

🧠 Step 3: Data Modeling
Within Power BI, I created a simplified star schema to ensure scalability and ease of querying. The model included:
	•	A Fact Table with all debt metrics
	•	Dimension Tables for countries, debt categories, and years
	•	DAX Measures to compute averages and rankings across multiple categories

This structure supported dynamic filtering and drill-downs on visuals while keeping calculations optimized.

📊 Step 4: Dashboard Design
I designed the dashboard for clarity, interactivity, and insight delivery. It includes:
	•	KPI Cards: Showcasing average debt percentages by category
	•	Top 10 Country Bar Charts: Highlighting nations with the highest debt levels
	•	Map Visualizations: Revealing regional debt concentration patterns
	•	Slicers: For users to explore by year, region, and debt type

💡 Key Dashboard Insights:
	•	Average General Government Debt: 6,095.28%
	•	Average Household Debt: 3,480.42%
	•	Average Private Sector Debt: 6,651.42%

🌍 Top 10 Countries with Highest General Government Debt:
Türkiye, Turkmenistan, Ukraine, United Arab Emirates, United Kingdom, United States of America, Uzbekistan, Venezuela, Vietnam, Israel

🏠 Top 10 Countries with Highest Household Debt:
South Africa, Spain, Sweden, Switzerland, Thailand, Türkiye, Ukraine, United Arab Emirates, United Kingdom, United States of America

📌 Business Analysis (McKinsey Framework)
As both a Business Analyst and Data Analyst, I leveraged McKinsey’s structured problem-solving framework to go beyond visualizations and craft a story around the data. This helped identify not just what the numbers say, but why they matter—and what should be done next.

✅ Why Is This Important?
Understanding Global debt patterns is essential for economic planning, risk assessment, and international policy development. Debt in any form—governmental, household, or private—affects financial markets, investor confidence, and social development.

This project allows decision-makers to visualize debt distribution globally and assess where vulnerabilities lie. Whether you’re a policymaker, economist, or business leader, having access to this data can guide smarter fiscal interventions.

❌ What Went Wrong?
The analysis revealed alarming average debt levels across all categories:
	•	General Government Debt – 6,095.28%
	•	Household Debt – 3,480.42%
	•	Private Sector Debt – 6,651.42%

These figures far exceed what many economies can sustainably carry. Notably, many countries appeared in multiple top-10 lists—indicating cross-sector debt exposure. This signals that financial stress isn’t isolated, but structural.

Red Flags by Debt Category:
	•	General Government Debt Top 10: Türkiye, Turkmenistan, Ukraine, UAE, UK, USA, Uzbekistan, Venezuela, Vietnam, Israel
	•	Household Debt Top 10: South Africa, Spain, Sweden, Switzerland, Thailand, Türkiye, Ukraine, UAE, UK, USA

Such overlap highlights systemic risks across both emerging and developed economies.

🛠 What Should Be Done – Strategic Recommendation

To address unsustainable debt levels, I propose the following steps:
	1.	Implement National Debt Recovery Frameworks
Each country should develop a realistic repayment strategy with periodic milestones. These frameworks must be transparent and tailored to the unique financial structure of the country.
	2.	Enforce Compliance Mechanisms
If terms of repayment are not met, enforcement measures or financial consequences should follow. This includes interest penalties, reduced international credit access, or limitations on new borrowing—forcing debt management to be treated as a priority.
	3.	Incentivize Fiscal Responsibility
Through global financial institutions (IMF, World Bank), offer relief or restructuring benefits only to countries that meet specific reform benchmarks. This would encourage governments to adopt responsible debt practices proactively.

### 2. US International Air Traffic Analysis  
📌 Dashboard Development Process (Technical Walkthrough)

📥 Step 1: Data Sourcing
The dataset was sourced from a U.S. transportation authority and includes:
	•	International flight departures from the U.S.
	•	Monthly scheduling statistics
	•	Airport and carrier data
	•	Passenger averages per flight
	•	Flight counts per carrier and month

It provided a comprehensive look at the air traffic ecosystem from both operational and passenger perspectives.

🧹 Step 2: Data Cleaning & Preparation
Using Power Query in Power BI, I began by removing empty rows and irrelevant columns such as placeholder fields and unneeded codes. I standardized column names, parsed date fields, and created new columns for:
	•	Month & Year Extracts
	•	Airport Codes Mapping
	•	Carrier Grouping (Low volume vs. high volume carriers)

Missing carrier codes were excluded from analysis to ensure accurate comparison.

The cleaned dataset was restructured to allow dynamic filtering and relationship modeling based on airports, months, and airline carriers.

🧠 Step 3: Data Modeling
I designed a modular data model that supports layered insights:
	•	Fact Table: Flight records with counts, passenger averages, airport codes
	•	Dimension Tables: Airport names, carriers, months, and traffic types

I also created key DAX measures:
	•	Total Departures
	•	Total Scheduled Routes
	•	Average Passengers per Flight
	•	Most Active Airport (by traffic volume)
	•	Monthly Flight Volume Rankings

📊 Step 4: Dashboard Visualization
The Power BI dashboard was built with simplicity and interactivity in mind. Components include:
	•	KPI Tiles:
	•	39 million total international departures
	•	883 scheduled international flight routes
	•	Average of 42.87 passengers per international flight
	•	Bar and Line Charts:
	•	Monthly traffic volume
	•	Carrier activity comparisons
	•	Top 10 busiest airports
	•	Map Visualization: Showcasing airport-specific departures across the U.S.
	•	Slicers: Allowing dynamic filtering by month, airport, and carrier

💡 Key Insights From the Dashboard:
	•	The U.S. recorded over 39 million international departures, emphasizing its dominance in global air transport.
	•	A total of 8,983 international routes were scheduled, providing insight into route density and planning.
	•	The average passenger load per international flight is 42.87, helping airlines evaluate capacity planning.
	•	July recorded the highest number of flights with 3,547,269—the peak traffic month.
	•	MIA (Miami International Airport) was the busiest airport with 133,820 arrivals and departures combined.
	•	Least active carriers included O2Q, O4Q, O5Q, O7Q, and O9Q, which had significantly low flight frequencies.

📌Business Analysis (McKinsey Framework)
As both a Business Analyst and Data Analyst, I applied McKinsey’s structured problem-solving framework to give meaning to the data beyond numbers—identifying bottlenecks, risks, and recommending action for improvement.

✅ Why Is This Important?
Understanding the total number of international departures and scheduled routes is key to tackling air traffic challenges like congestion, flight delays, and airport resource allocation.

Insights from this project help:
	•	Airlines optimize scheduling and aircraft load
	•	Airport authorities distribute air traffic more efficiently
	•	Policy makers design strategies to support infrastructure growth

❌ What Went Wrong? – Discovery
	•	Overloaded Peak Month: July had the highest recorded flight volume (3.54 million), indicating possible seasonal congestion.
	•	Airport Congestion: MIA handled the most international air traffic with 133,820 flights, creating potential delays.
	•	Underutilized Carriers: Airlines such as O2Q, O4Q, O5Q, O7Q, and O9Q had minimal usage, pointing to market inefficiencies or licensing limitations.

These findings highlight a critical imbalance in how flight operations and infrastructure are currently distributed.

🛠 What To Do? – Solution
To improve efficiency and avoid congestion-related delays:
	1.	Distribute Traffic Across More Airports
Encourage use of underutilized airports through subsidies, upgraded infrastructure, or new international route licenses.
	2.	Standardize Airport Capabilities
Improve facilities at regional airports so they can accommodate more international departures and reduce over-reliance on major hubs.
	3.	Incentivize Carrier Diversity
Support smaller or low-volume carriers to operate on less crowded routes, which can reduce pressure on dominant airlines and create better passenger distribution.

By diversifying the use of airspace and airport capacity, the U.S. can ensure faster, smoother international travel while maintaining safety and efficiency.

### 3. Airplane Crashes & Fatalities Study  
✈ Global Airplane Crashes & Fatalities – Dashboard & Business Insight

🔍 Overview

This Power BI project explores the patterns, fatalities, and impact of global airplane crashes across major geographic zones. From data cleaning to visual storytelling, this project not only uncovers where and how aviation accidents occur—but also aims to provide actionable insight for aviation safety stakeholders.

In addition to building interactive dashboards, I applied the McKinsey problem-solving framework to interpret the data and recommend strategies to mitigate future disasters.

📌 Dashboard Development Process (Technical Breakdown)

📥 Step 1: Data Collection & Scope
The dataset contained historical records of airplane crashes and their associated fatalities, including on-ground casualties. Key fields include:
	•	Crash location (by region)
	•	Type of aircraft involved
	•	Operator
	•	Total number of fatalities (on board and on ground)

🧹 Step 2: Data Cleaning & Preparation
Using Power BI’s Power Query Editor, I cleaned the dataset by:
	•	Removing duplicates and invalid rows
	•	Standardizing region and aircraft names
	•	Creating new calculated columns:
	•	Month of Crash
	•	Year
	•	Fatalities on Ground vs. In-Air
	•	Crash Severity Index (fatalities per crash)

🧠 Step 3: Modeling & Analysis
With a clear data structure, I created a relational model that allowed for cross-filtering by:
	•	Crash date
	•	Location
	•	Aircraft type
	•	Operator
	•	Fatality type

DAX measures were created to track:
	•	Total fatalities
	•	Fatalities on ground
	•	Crashes per month
	•	Average fatalities per crash
	•	Top aircraft models involved in crashes

📊 Step 4: Dashboard Design & Visualization
Using Power BI, I built an interactive and visually intuitive dashboard. Key insights include:
	•	Total Fatalities (on board + ground): ~105,000
	•	Fatalities on ground: ~8,440
	•	Average fatalities per crash: 27.44
	•	Crash volume by region: With visuals illustrating hotspots and trends
	•	Crash timeline: Monthly and yearly breakdowns to identify peak crash periods
	•	Most involved aircraft & operators: For safety trend evaluation

Slicers allow stakeholders to filter by region, year, operator, and crash type for deeper insight.

💡 Key Insights From the Dashboard
	•	Total human loss: 105,000 fatalities paints a sobering picture of aviation safety challenges.
	•	Ground fatalities (8.44k) show the collateral impact of aviation crashes beyond just those in the aircraft.
	•	Average fatalities per crash: 27.44, reflecting how deadly the average incident is.
	•	December emerges as the most dangerous month with 491 recorded crashes—suggesting seasonal or operational strain.
	•	Aircraft frequently involved in fatal crashes include:
	•	Zeppelin L-59
	•	Zeppelin L-70
	•	Zeppelin L-8
	•	Zeppelin LZ-129
	•	Top 6 crash-prone aircraft operators:
	•	Zakava
	•	Zanex
	•	Zantop Air Transport
	•	Zantop Airways
	•	Zantop International
	•	Zennipon

📌 Business Analysis (McKinsey Approach)

As a Business Analyst and Data Analyst, I applied McKinsey’s issue-based problem-solving framework to interpret the crash data and propose evidence-based solutions to improve global aviation safety.

✅ Why Is This Important?
Understanding the causes and outcomes of aviation crashes is critical for:
	•	Enhancing passenger safety
	•	Reducing fatalities (both in-flight and on-ground)
	•	Improving airline compliance and maintenance routines
	•	Guiding aviation policy and investment decisions

The goal is to move from reactive accident response to proactive crash prevention.

❌ What Went Wrong? – Discoveries
	•	December is the riskiest month, with 491 crashes—potentially due to poor weather, increased travel, or maintenance lag.
	•	Older aircraft models, such as the Zeppelin series, repeatedly appear in the data, indicating poor retirement policies.
	•	Some operators (Zakava, Zanex, Zantop brands, Zennipon) are heavily linked to high crash frequencies.
	•	Operator oversight and aircraft conditions are major risk contributors.

🛠 What To Do? – Recommendations
To significantly reduce fatalities and crash frequency:
	1.	Rigorous Pre-flight Aircraft Checks
Ensure comprehensive inspection protocols before every takeoff, especially in high-risk months.
	2.	Limit Overload Flights
Impose strict penalties for flights exceeding weight and passenger capacity.
	3.	Upgrade Pilot Standards
	•	Employ only certified and experienced pilots
	•	Enforce regulations around rest time, alcohol monitoring, and cognitive performance
	4.	Decommission Old Aircraft
Mandate retirement of aged models, especially those with repeated safety incidents.
	5.	Boost Safety Equipment
	•	Increase survival kit availability
	•	Provide mandatory pre-flight training on their usage for all passengers and crew
	6.	Audit High-risk Operators
Conduct frequent audits and safety checks for airlines with poor crash records.

### 4.  Women’s Clothing E-Commerce Analysis
Diving into customer behavior and preferences in women’s fashion through an e-commerce lens.

[View Project Repository](https://www.linkedin.com/posts/badmus-ibraheem-b7576635b_powerbi-powerquery-ecommerceanalytics-activity-7331757354889195521-gCjg?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFmimQkBYBgh5-xqpPIdw5INl85e3sQ6kAU)

### 5. Investment Preference Analysis

I dove deep into what drives people to invest and where they prefer to put their money.

[View Project Repository](https://www.linkedin.com/posts/badmus-ibraheem-b7576635b_powerbi-powerquery-investmentanalysis-activity-7331756914491482112-zt90?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFmimQkBYBgh5-xqpPIdw5INl85e3sQ6kAU)

### 6. Car Insurance Policies Analysis
This one dives deep into the world of car insurance

[View Project Repository](https://www.linkedin.com/posts/badmus-ibraheem-b7576635b_powerbi-powerquery-dataanalytics-activity-7331756152109559808-kTkd?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFmimQkBYBgh5-xqpPIdw5INl85e3sQ6kAU)

### 7. Global Debt Analysis

[View Project Repository](https://www.linkedin.com/posts/badmus-ibraheem-b7576635b_im-excited-to-present-my-first-live-analysis-activity-7327743691886936064-Ihym?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFmimQkBYBgh5-xqpPIdw5INl85e3sQ6kAU)

### 8. Amazon Sales Analysis

[View Project Repository](https://www.linkedin.com/posts/badmus-ibraheem-b7576635b_im-excited-to-share-my-projects-on-amazon-activity-7338597943123316736-pPue?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFmimQkBYBgh5-xqpPIdw5INl85e3sQ6kAU)

### 9. Tata Online Retail Sales Analysis

[View Project Repository](https://www.linkedin.com/posts/badmus-ibraheem-b7576635b_im-excited-to-share-my-tata-online-retail-activity-7338599547469762561-Ez3E?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFmimQkBYBgh5-xqpPIdw5INl85e3sQ6kAU)

### 10. Health Insurance Analysis
Using data from all 51 states, here’s what caught my attention

[View Project Repository](https://www.linkedin.com/posts/badmus-ibraheem-b7576635b_im-excited-to-share-my-9th-project-out-of-activity-7338600082042195970-PbT3?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFmimQkBYBgh5-xqpPIdw5INl85e3sQ6kAU)

### 11. Digital Marketing Analysis
I recently completed a data analysis project focused on Digital Marketing Performance, and I’m excited to share the interactive dashboard I built to visualize key insights and performance metrics that drive marketing decisions.

[View Project Repository](https://www.linkedin.com/posts/badmus-ibraheem-b7576635b_unveiling-insights-from-my-digital-marketing-activity-7338600425610194946-SfJD?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFmimQkBYBgh5-xqpPIdw5INl85e3sQ6kAU)

### 12. Supply Chain Dataset Analysis
This project focused on analyzing product sales, pricing, and logistics performance — and the insights were revealing

[View Project Repository](https://www.linkedin.com/posts/badmus-ibraheem-b7576635b_excited-to-share-my-11th-data-analysis-activity-7338606478821384193-wVsj?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFmimQkBYBgh5-xqpPIdw5INl85e3sQ6kAU)

### 13. Supply Chain Greenhouse Emissions Analysis.

[View Project Repository](https://www.linkedin.com/posts/badmus-ibraheem-b7576635b_im-thrilled-to-share-one-of-the-key-projects-activity-7338967609268236288-q3Pq?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFmimQkBYBgh5-xqpPIdw5INl85e3sQ6kAU)

### 14. Hotel Booking Analysis

[View Project Repository](https://www.linkedin.com/posts/badmus-ibraheem-b7576635b_im-excited-to-share-the-14th-project-activity-7338968810839863296--OkC?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFmimQkBYBgh5-xqpPIdw5INl85e3sQ6kAU)

### 15. Retail Sales & Customer Demographics

[View Project Repository](https://www.linkedin.com/posts/badmus-ibraheem-b7576635b_im-excited-to-share-my-final-project-activity-7338972736188231680-x31n?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFmimQkBYBgh5-xqpPIdw5INl85e3sQ6kAU)
