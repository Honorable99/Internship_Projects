## Internship Projects


### 1. Global Debt Analysis  


Global Debt Analysis Dashboard – Documentation



🔎 Overview
This project explores global debt metrics across three major dimensions: General Government Debt, Household Debt, and Private Sector Debt. Using Power BI, I transformed raw data into a compelling, interactive dashboard that visualizes national debt levels while also uncovering patterns and high-risk zones.

Beyond the visuals, I applied a McKinsey-style business analysis framework to extract deeper insights, understand the implications of debt distribution, and suggest policy-driven recommendations.


📌Dashboard Development Process (Technical Walkthrough)


📥 Step 1: 

Data Acquisition
The dataset was sourced from a reputable financial institution and contained time-series data on national debt levels for over 100 countries. The figures represented percentages of each country’s GDP, categorized under:
	•	General Government Debt
	•	Household Debt
	•	Private Sector Debt

🧹 Step 2: 

Data Cleaning & Preparation
To prepare the dataset for analysis, I first performed an exploratory data review to identify missing values, formatting inconsistencies, and outliers. 

Next, I removed records with significant gaps and imputed missing values using forward-fill logic, particularly where yearly data could be reasonably projected. The data was then transformed from a raw long-form structure into a format suitable for Power BI modeling—allowing for clean filtering by year, region, and debt category.

🧠 Step 3: 

Data Modeling
Within Power BI, I created a simplified star schema to ensure scalability and ease of querying. The model included:
	•	A Fact Table with all debt metrics
	•	Dimension Tables for countries, debt categories, and years
	•	DAX Measures to compute averages and rankings across multiple categories

This structure supported dynamic filtering and drill-downs on visuals while keeping calculations optimized.

📊 Step 4: 

Dashboard Design

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

As both a Business Analyst and Data Analyst, I leveraged McKinsey’s structured problem-solving framework to go beyond visualizations and craft a story around the data. 

This helped identify not just what the numbers say, but why they matter—and what should be done next.


✅ Why Is This Important?
Understanding Global debt patterns is essential for economic planning, risk assessment, and international policy development. 

Debt in any form—governmental, household, or private—affects financial markets, investor confidence, and social development.

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


📥 Step 1: 

Data Sourcing
The dataset was sourced from a U.S. transportation authority and includes:

 •	International flight departures from the U.S.

 •	Monthly scheduling statistics

 •	Airport and carrier data

 •	Passenger averages per flight

 •	Flight counts per carrier and month

It provided a comprehensive look at the air traffic ecosystem from both operational and passenger perspectives.

🧹 Step 2: 

Data Cleaning & Preparation
Using Power Query in Power BI, I began by removing empty rows and irrelevant columns such as placeholder fields and unneeded codes. I standardized column names, parsed date fields, and created new columns for:

 •	Month & Year Extracts

 •	Airport Codes Mapping

 •	Carrier Grouping (Low volume vs. high volume carriers)

Missing carrier codes were excluded from analysis to ensure accurate comparison.

The cleaned dataset was restructured to allow dynamic filtering and relationship modeling based on airports, months, and airline carriers.

🧠 Step 3: 

Data Modeling
I designed a modular data model that supports layered insights:

•	Fact Table: Flight records with counts, passenger averages, airport codes

•	Dimension Tables: Airport names, carriers, months, and traffic types

I also created key DAX measures:
	
 •	Total Departures

 •	Total Scheduled Routes

 •	Average Passengers per Flight

 •	Most Active Airport (by traffic volume)

 •	Monthly Flight Volume Rankings

📊 Step 4: 

Dashboard Visualization
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


📥 Step 1: 

Data Collection & Scope
The dataset contained historical records of airplane crashes and their associated fatalities, including on-ground casualties. Key fields include:
	
 •	Crash location (by region)

 •	Type of aircraft involved

 •	Operator

 •	Total number of fatalities (on board and on ground)

🧹 Step 2: 

Data Cleaning & Preparation
Using Power BI’s Power Query Editor, I cleaned the dataset by:

 •	Removing duplicates and invalid rows

 •	Standardizing region and aircraft names

 •	Creating new calculated columns:

 •	Month of Crash

 •	Year

 •	Fatalities on Ground vs. In-Air

 •	Crash Severity Index (fatalities per crash)

🧠 Step 3: 

Modeling & Analysis
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

📊 Step 4: 

Dashboard Design & Visualization
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


### 4. Hotel Booking Analysis

🏨 Hotel Booking Analysis – 


📍 Project Summary

The objective was to uncover trends in guest behavior, identify key drivers of bookings, and provide actionable insights to optimize customer experience and revenue growth.

The analysis combines technical dashboard development with a strategic business lens using McKinsey’s problem-solving framework to extract meaning from the numbers.


🧩 Dashboard Development Process (Power BI)


📥 Step 1: 

Data Understanding & Scope
The dataset covered thousands of hotel bookings from guests across different countries. Key attributes included:

 •	Booking dates

 •	Number of nights stayed

 •	Country of origin

 •	Daily rates

 •	Market segment

 •	Guest names

🧹 Step 2: 

Data Cleaning & Transformation
To ensure clarity and usability in Power BI, I performed the following:

 •	Removed nulls and duplicates

 •	Converted text-based date columns to datetime

 •	Created calculated columns for:

 •	Length of stay

 •	Guest type

 •	Booking source

 •	Arrival month grouping

 •	Standardized country names for accurate filtering and analysis

 •	Removed outliers in pricing and duration for better data integrity


📊 Step 3: 

Dashboard Creation in Power BI
Using Power BI Desktop, I created an interactive dashboard that displayed key KPIs and breakdowns across country, guest type, and booking behavior.


💡 Key Performance Indicators (KPIs)

 •	Total Country Entries: 119,390

 •	Average Nights per Booking: 0.93

 •	Mean ADR (Average Daily Rate): $101.83

 •	Total Number of Adults: 222,000


🔍 Deeper Insights Uncovered

 •	Top Guest Name: Zoe Wu

 •	Country with the Most Travelers: Portugal — with over 1.33 million entries

 •	High number of bookings involving children & babies — important for marketing family packages

 •	Peak Arrival Month: October — recorded 11.16K bookings

 •	Most active market segment: Corporate bookings via company referrals


🎨 Visual Features

 •	Dynamic slicers to filter by country, guest type, and booking month

 •	Bar and line charts for time-based trend analysis

 •	Matrix visualizations to break down bookings by market segment and room type

 •	KPI cards for fast executive-level summaries


💼 Business Analysis (McKinsey Framework Approach)

As both a Business Analyst and Data Analyst, I used McKinsey’s structured problem-solving methodology to extract strategic business value from the data.


✅ Why Is This Important?

Understanding guest demographics, seasonal behavior, and booking patterns is essential for:

 •	Enhancing hotel revenue strategy

 •	Targeting the right customer segments

 •	Creating better offers and incentives

 •	Managing resources efficiently (rooms, staff, services)

With travelers arriving from all over the world, especially Portugal, this hotel has the opportunity to scale operations, improve customer retention, and maximize occupancy rates year-round.


❌ What Went Wrong / Key Discoveries

 •	Low average stay: Guests are only spending an average of 0.93 nights — indicating either short layovers or lack of long-term value

 •	Country concentration: A massive 1.33M+ bookings from Portugal may suggest untapped potential in other markets like Germany and France

 •	Underutilized off-peak months: Although October was the best performer, other months show clear drop-offs

 •	Website update lag: Potential booking loss due to slow room availability updates


🛠 What To Do – Strategic Recommendations
To improve bookings and extend guest stays, I propose the following actions:

 1.	Introduce Booking Incentives
	•	Example: Offer a “Book 2 nights, get 1 free” promotion to boost the average length of stay.

 2.	Real-Time Website Updates
	•	Ensure that as soon as a room becomes free, it is updated immediately on the booking platform to maximize occupancy.

 3.	Tourism & Experience Bundles
	•	Partner with local tourism boards or government bodies to offer low-cost attraction bundles for hotel guests.
	•	Promote tourist destinations like beaches, museums, and guided tours — incentivizing longer bookings.
	•	Benefits both the local economy and hotel revenue — a win-win.

 4.	Expand Ad Campaigns Globally
	•	Launch strategic digital marketing campaigns targeting other high-interest countries (Germany, France, UK).
	•	Showcase vacation packages with strong visual content around “Experience & Relaxation” themes.

 5.	Build a Vacation Planning Feature
	•	Create an interactive vacation planner on the hotel’s site — helping visitors design their stay with flexible room, activity, and pricing options.
 
### 5. Amazon Sales Analysis

🚀 Amazon Sales Analysis 


🧩 Dashboard Development Process (Power BI)


📥 Step 1: 

Dataset Overview
The dataset contains detailed product-level data across various categories sold on Amazon. This includes:

 •	Product Name & Category

 •	Units Sold

 •	Sales Revenue

 •	Rating & Review Counts

 •	Inventory Metrics

The focus was to identify which products are driving performance and which ones are underperforming despite market potential.

🧹 Step 2: 

Data Cleaning & Preparation
Using Power BI:

 •	I standardized product names and categories

 •	Removed duplicates and zero-sale entries

 •	Created calculated columns for:

 •	Sales per Unit

 •	Review-to-Sale Ratio

 •	Revenue Contribution by Category

📊 Step 3: 

Power BI Dashboard Creation
The dashboard was built to be fully interactive, featuring:

 •	Category-wise performance visualization

 •	Top-performing and underperforming SKUs

 •	Revenue vs. Activity heatmaps

 •	Filterable visuals by product, region, and sales period


📈 Key Dashboard Insights

 •	🖥 Top-selling category: Computers & Accessories led in sales and unit movement, indicating sustained consumer demand in tech.

 •	🛑 Average performer: Zuvexa USB Rechargeable showed decent movement but lacked revenue impact — a classic case of under-leveraged potential.

 •	⚠ Category Concern: Despite high activity in certain categories, overall revenue underperformed — suggesting that visibility and alignment of effort are off-balance.


💼 Strategic Business Analysis (McKinsey-Style)



🎯 Objective
To identify what’s driving sales and where Amazon (or vendors) are leaving money on the table, using data-backed decisions.


✅ Why Is This Important?
Understanding product performance isn’t just about celebrating bestsellers — it’s about:

 •	Knowing which items to promote

 •	Avoiding inventory bloat

 •	Redirecting marketing spend for maximum ROI


❌ What Went Wrong? Key Discoveries

 •	Some average-performing SKUs (e.g. Zuvexa USB Rechargeable) are not well-marketed despite demand signals.

 •	High-performing categories aren’t being scaled effectively.

 •	Revenue and engagement are not aligning — indicating poor visibility or low conversion pathways.


🛠 What To Do? Strategic Recommendations

 1.	Double Down on What Works
	•	Scale inventory and exposure of high performers like Computers & Accessories.
	•	Use Amazon ads and A+ content to keep them at the top of customer consideration.

 2.	Revive Average Performers
	•	For products like Zuvexa USB Rechargeable, introduce:
	•	Sponsored listings
	•	Customer review campaigns
	•	Bundle deals (e.g., sell with laptops)

 3.	Optimize Customer Journey
	•	Review listings with low review-to-sale ratios and adjust descriptions, visuals, or pricing to reduce bounce rate and cart abandonment.


 ### 6. Health Insurance Analysis
 
 
 🧠 Health Insurance Coverage in the U.S. (2010–2015)


Business Intelligence Dashboard + Strategic Analysis using McKinsey Framework

📍 Project Overview
In this project, I worked as a Business Intelligence Analyst to explore the shifts in health insurance coverage across the United States between 2010 and 2015. The goal was to understand where and why coverage gaps persisted, the effectiveness of federal and marketplace plans, and how public policies influenced access to insurance.

The analysis involved combining Power BI dashboards with insights structured through McKinsey’s problem-solving framework, and culminated in a PowerPoint presentation for stakeholder reporting.


🧩 Dashboard Process (Power BI)


📥 Step 1: 

Data Exploration & Understanding
The dataset covered U.S. states over a 6-year period, containing variables like:

 •	Uninsured population by state

 •	Marketplace plan enrollment

 •	Tax credit usage

 •	Employer-sponsored plan metrics

 •	Federal vs state-based plan access

🧹 Step 2: 

Data Cleaning & Preparation
To ensure clean visualization, I took the following steps:

 •	Removed states with missing or incomplete records

 •	Standardized time formats for consistent year-over-year tracking

 •	Created calculated columns for:

 •	Growth Rate of Coverage Types

 •	Uninsured Rate %

 •	Federal vs Marketplace Enrollments

📊 Step 3: 

Visualization in Power BI
Using Power BI, I developed an interactive dashboard that allowed users to:

 •	Filter by state, year, or coverage type

 •	See trends in insurance access and how they correlated with policy changes

 •	Compare marketplace vs employer-sponsored plans

 •	Identify which states struggled most with uninsured rates



📈 Key Findings from Dashboard

 •	States like Wyoming, Virginia, Washington, West Virginia, and Wisconsin consistently had the highest uninsured rates

 •	Employer-sponsored insurance saw a sharp uptick in 2015

 •	Marketplace plan growth stalled in 2016, especially in lower-income states — indicating a setback in expanding coverage to vulnerable populations


💼 Strategic Business Analysis (McKinsey Framework)


🎯 Objective
To assess the success of U.S. healthcare policy reforms by analyzing:

 •	Growth in coverage (Marketplace, Employer, Medicaid)

 •	Uninsured trends at state level

 •	The role of tax credits and plan accessibility




✅ Why Is This Important?
Health insurance coverage directly impacts public health outcomes, poverty levels, and economic productivity. Identifying which states are lagging — and why — helps policymakers and healthcare providers:

 •	Allocate funding more effectively

 •	Improve outreach for underserved populations

 •	Redesign plans to suit income and accessibility barriers


❌ What Went Wrong? Key Discoveries

 •	Marketplace plan growth dropped in 2016, even though uninsured populations remained high in key states — pointing to a mismatch in availability and accessibility.

 •	Tax credits were not fully utilized in states with lower literacy or economic engagement.

 •	High uninsured rates persisted in several states despite national healthcare reforms.

 •	Public awareness campaigns were either ineffective or nonexistent in high-need zones.


🛠 What To Do? (Strategic Recommendations)

To reduce the number of uninsured Americans and revamp stagnant coverage growth, the following actions are necessary:

 1.	Launch Targeted Funding Programs
	•	Federal and state governments should channel more resources into high-risk states like Wyoming and West Virginia.
	•	These programs should focus on outreach, education, and subsidized plan options.

 2.	Revamp Marketplace Health Plan Promotions
	•	Use digital, local, and grassroots campaigns to promote Marketplace awareness in communities where growth has stalled.

 3.	Annual State-Level Coverage Reviews
	•	Set up an accountability loop by conducting yearly performance reviews of insurance uptake, accessibility, and satisfaction — tied to improvement funding.

 4.	Enhance Tax Credit Accessibility
	•	Simplify eligibility checks and documentation required to apply for premium tax credits, increasing coverage among low-income citizens.

 ### 7. Car Insurance Policy Analysis
 
 
 🚗 Car Insurance Policies Analysis | Power BI Dashboard

This one focuses on identifying patterns in car insurance claims using real-world data. I handled everything from data preparation to visual storytelling using Power BI and Power Query Editor.


⚙ DASHBOARD PROCESS
Tools & Technologies Used:
🛠 Power BI – For creating dynamic and interactive dashboards
🧼 Power Query Editor – For cleaning and transforming raw data


Step-by-Step Workflow:
	1.	Data Cleaning & Transformation

• Removed missing and inconsistent values

• Standardized car make, region, and education data

• Converted date formats and numerical columns

• Created custom columns for segmentation (e.g., usage type by gender)

 2.	Data Modeling

• Built relationships across tables (car details, claims, policyholder info)

• Defined calculated columns and measures using DAX (e.g., claim totals, % share)

 3.	Dashboard Design

• Used card visuals for KPIs (Total Claims, Total Income, Total Payouts)

• Clustered bar charts to compare car makes, education levels, and coverage zones

• Slicers for dynamic filtering by gender, region, and car color

• Pie and donut charts to show distributions (ownership type, claim frequency)

• Tooltip-enabled visuals for deeper drill-down insights


📊 ANALYSIS PROCESS & INSIGHTS

1. Most Frequent Car Make & Model
🔧 Acura led with 25.51% of total claims, followed by BMW, Ford, and Lincoln. These models should be considered high-risk for pricing adjustments.

2. Education Level vs. Claim Frequency
🎓 Surprisingly, individuals with a Bachelor’s degree filed the most claims—outpacing High School, Master’s, and PhD holders. Could link to lifestyle and car usage intensity.

3. Coverage Zones vs. Claim Amounts
📍 Urban zones had the highest average claim amount—20.14% higher than suburban, rural, and highly rural areas. Suggests higher accident rates in congested areas.

4. Car Usage by Gender & Family Composition
👨‍👩‍👧‍👦 Private ownership dominated, with over 12,500+ claims—vastly exceeding commercial use. Indicates a need to reevaluate risk models for personal-use vehicles.

5. Car Color & Claim Risk
🎨 Turquoise, Violet, Teal, Red, and Yellow topped the list of most-claimed colors—suggesting color psychology or risk perception may influence claims.

6. Household Income vs. Claims
💸 Households had a combined income of ₦5B+, while total claim payouts were around ₦1.5B. This gives a socio-economic view of risk and policy sustainability.


🔍 BUSINESS ANALYSIS (Using McKinsey’s MECE Framework)


Why Is This Important?

Understanding trends in claims helps insurers:

• Redesign premium pricing models

• Promote safer driving practices

• Manage risk based on customer segmentation

• Reduce fraudulent claims


What Went Wrong?


• Urban areas showed the most claims—linked to driver recklessness & traffic density

• Most claims came from Bachelor’s degree holders—raising behavioral questions

• Car maintenance not enforced—may increase accident frequency


What Can Be Done?

✅ Enforce car servicing policies—require proof of regular maintenance

✅ Require safety equipment checks (fire extinguishers, spare tires) before policy renewal

✅ Partner with state traffic agencies to reduce urban accidents via safety campaigns

✅ Re-evaluate pricing models for popular makes/models with high claim rates


### 8. Retail Sales & Customer Demographics Analysis

In this project, I explored a retail dataset to uncover customer behavior patterns, demographic influences, and product category trends. The goal: translate raw data into actionable insights that inform smarter inventory, marketing, and sales decisions.


⚙ DASHBOARD CREATION PROCESS

🔧 Tools Used:

• Power BI – For developing interactive visualizations and KPIs

• Power Query Editor – For data preparation and transformation


🔄 Workflow:

	1.	Data Cleaning & Preparation

 •	Removed duplicates, handled missing values

 •	Formatted dates for monthly/quarterly trend analysis

 •	Split categorical columns (e.g., product category)

 •	Grouped customer data by age, gender, and purchase history

	2.	Data Modeling & DAX Measures

 •	Created calculated columns for total sales, product count, and age brackets

 •	Used DAX for KPIs like Average Age, Total Sales by Quarter, and Gender Split

	3.	Dashboard Design

 •	KPI cards for average customer age and total purchases

 •	Column charts for monthly and quarterly sales patterns

 •	Stacked bar charts for gender-based purchase behavior

 •	Pie/donut charts for product category share

 •	Heat maps to show age vs. spending patterns by product


📊 ANALYSIS & INSIGHTS


📈 Key Performance Indicator:

 •	Average Customer Age: 41.39 years – signaling a mature, working-age consumer base



🔍 What Did I Discover?

1. Gender Influence on Purchasing

👩‍🦰 Females slightly edge males in total purchases with 50.96%, confirming their strong influence on retail spending.

2. Monthly Sales Trends

📅 May recorded the highest single-month sales, reaching 21,255 units—suggesting strong mid-year promotions or seasonal triggers.

3. Seasonal Purchase Behavior

🗓 Quarter 4 (Q4) saw the highest customer activity—likely driven by holidays, Black Friday, and end-of-year discounts.

4. Product Category Distribution

🛒 Clothing had the highest number of purchases (894 units), while

💰 Electronics accounted for the highest product price value (₦62K)—signifying big-ticket transactions.

5. Age, Spending, and Product Relationship

📌 Customers spent the most on Clothing (₦15K), followed by Electronics (₦14K) and Beauty products (₦12K).
This confirms that while electronics are expensive, clothing drives more frequent purchases.



🧠 BUSINESS ANALYSIS (McKinsey Framework)


Why Is This Important?

Analyzing customer demographics and preferences helps retailers:

• Predict peak seasons and prepare inventory accordingly

• Understand which gender and age group to target

• Optimize pricing strategies for high-performing product categories

• Boost conversion through personalized marketing



What Went Wrong / Key Findings


• Female customers dominate sales—yet current inventory may not fully reflect that.

• Most purchases happened in May and Q4, but campaigns may not be aligned with these high-demand periods.

• While Electronics top by value, Clothing dominates in volume and consistent spending.

• Failure to align stock with demand across high-performing categories and seasons could result in missed revenue.



✅ What Should Be Done?


🔹 Prioritize female-targeted inventory – Trendy, high-demand women’s clothing should be increased


🔹 Leverage Q4 seasonality – Stock up on electronics ahead of Q4 and plan promotions accordingly


🔹 Run gender-targeted campaigns – Tailor marketing content to match the leading demographic (female, mid-40s)


🔹 Bundle value deals in May & Q4 – Use historic peak data to trigger seasonal offers that convert


### 9. Tata Retail Sales Analysis

Tata Retail Sales Analysis 

When the data speaks, we listen. And this time, it had a lot to say.

Tata didn’t ask for insights.
But the data wouldn’t stay quiet — so I stepped in to make sense of it.

What began as a simple sales report turned into a deep dive into product movement, customer activity, and seasonal demand. 

Here’s what I uncovered using Power BI:


⚙ DASHBOARD CREATION PROCESS

🔧 Tools Used:

• Power BI – Visual storytelling and dashboard development

• Power Query Editor – Data cleaning, preparation, and transformation

🔄 Process Overview:

 1.	Data Cleaning & Transformation

 •	Cleaned inconsistent stock codes and missing values

 •	Extracted date features: Month, Year, Quarter

 •	Created custom columns (e.g., revenue per product, total orders)


 2.	Data Modeling & DAX Measures

 •	Built relationships between transactions, products, and customer tables

 •	Used DAX to compute total revenue, units sold, customer count, and top-performing stock codes


 3.	Dashboard Design & UX

 •	KPI Cards for: Total Revenue, Products Sold, Unique Customers

 •	Time-based visuals: Line & column charts for monthly and yearly revenue

 •	Bar charts for top stock codes and customer activity

 •	Slicers for dynamic filtering by product type, date range, or customer ID



📊 ANALYSIS & INSIGHTS

💰 Core Metrics Uncovered:

• $9.75M in total revenue

• 5 million products sold

• 4,373 unique customers

🔥 Revenue Peak:

• November 2011 emerged as the highest revenue month and year combo

• Stock Code “DOT” was the best performer, generating over ₦206M in revenue



🧠 BUSINESS ANALYSIS (McKinsey-Style Framework)

Why Is This Important?

Analyzing Tata’s sales data helps to:

• Understand revenue trends across time

• Identify high-performing products and customer segments

• Optimize inventory planning for peak periods

• Uncover underperforming months that need strategic marketing boosts



What Was Discovered?


🔍 Key Findings:


 •	Stock Code “DOT” drove the most revenue: ₦206,245,480+

 •	November 2011 was the revenue peak — indicating seasonal demand or successful campaigns

 •	Most revenue was clustered toward the end of the year, while other months saw slower performance



✅ What Should Be Done?


📦 Pre-Holiday Stock Planning


Ensure that November to December is supported with full inventory for high-demand products


📢 Targeted Campaigns in Low-Performing Months


Use data-driven ads and customer retargeting to boost sales during slower periods (January to September)


📨 Customer Re-Engagement


Update and reconnect with previous buyers leading into peak seasons for repeat business


📈 Product-Level Promotion


Double down on high-performing stock codes like “DOT” through bundles, discounts, or featured listings



### 10. Supply Chain Greenhouse Emission Analysis


🌍 Supply Chain Greenhouse Emissions Analysis


🚀 An environmental data analysis project focused on Greenhouse Gas (GHG) Emissions across various supply chain activities.

The goal? Go beyond carbon counts — and uncover which industries contribute the most, how margins affect reporting, and where businesses can optimize for sustainability.



⚙ ANALYSIS & DASHBOARD CREATION PROCESS

🛠 Tools Used:

• Microsoft Excel – Data aggregation and emission calculations

• Power Query Editor – For data cleaning, merging datasets, and restructuring for analysis

🔄 Process Overview:

 1.	Data Cleaning & Pre-Processing

 •	Removed irrelevant/duplicate entries

 •	Formatted NAICS titles and codes for consistency

 •	Segregated datasets into “with margin” and “without margin” categories


 2.	Calculation of Emission Factors

 •	Applied formulas to compute total emissions with and without margin adjustments

 •	Used lookups to merge industry-specific data (NAICS codes) with emission values


 3.	Visualization & KPI Design

 •	Developed Excel dashboard with clear KPI summaries, margin difference visuals, and top emission contributors

 •	Built pivot tables to segment emissions by NAICS titles and categories



📊 KEY FINDINGS & INSIGHTS


🔑 Key Performance Indicators (KPIs)


• Total Emission Factors (without margin): 361.89

• Total Emission Factors (with margin): 390.49

• Margin Difference: 28.62



🔍 What Did I Discover?


📌 Top NAICS Industry by Total Emission Factor

 •	Photofinishing Laboratories recorded the highest total emissions, followed closely by Pet Care Services


📌 Highest Emission Contributor (without & with margin)

 •	Solid Waste Landfill led in both categories, contributing 10.898 units, highlighting it as a significant source of supply chain emissions


📌 Impact of Margins

 •	Adding margins to the emission calculation increased the total emissions by 28.62 units, demonstrating the importance of buffering in sustainability metrics



🧠 BUSINESS ANALYSIS 

1. Why Is This Important?

In today’s ESG-conscious world, understanding the environmental impact of a company’s supply chain is essential for:

 •	Ensuring compliance with emission regulations

 •	Making informed decisions for green procurement

 •	Prioritizing high-emission sectors for sustainable transformation

 •	Identifying where margins may be inflating perceived impact



2. What Was Discovered?

 •	Emission spikes are heavily concentrated in sectors like photofinishing and solid waste management

 •	Even without margins, these industries still top the emissions list, proving the underlying environmental risk is structural, not just accounting-based

 •	Emission factors increase significantly when margin buffers are introduced — reflecting cautious or conservative reporting by some industries



3. What Should Be Done?

✅ Target High-Impact Industries First

 •	Prioritize sustainability interventions in sectors like waste management, photofinishing, and pet care


✅ Review Margin Policies

 •	Conduct audits to determine if margins used in emissions reporting are realistic or inflated, especially in sensitive industries


✅ Partner with Cleaner Suppliers

 •	Shift procurement toward lower-emission NAICS categories, aligning with long-term ESG goals


✅ Sustainability Reporting Integration

 •	Integrate this type of emissions analysis into quarterly sustainability reports and executive dashboards


 
 ### 11. Mental Health Analysis

 
🧠 Mental Health Analysis 


I’m excited to share another impactful project from my ongoing internship journey — this time, I dove deep into a Mental Health Dataset spanning multiple years and regions.

The goal? Go beyond statistics and uncover the true weight of anxiety, depression, drug use, and other disorders on human lives — and what the numbers reveal about global health trends.



⚙ DASHBOARD & ANALYSIS PROCESS

🛠 Tools Used:

• Microsoft Excel – Data prep, transformation, and KPI setup

• Power Query Editor – For cleaning and reshaping time-series and categorical data

• Power BI – Visualization, slicing by disorder types, years, and regions


🔄 Process Workflow:

 1.	Data Cleaning & Preparation

 •	Removed duplicates and handled null values

 •	Standardized disorder naming and aligned regional entries

 •	Extracted year, disorder type, region, and prevalence metrics


 2.	Data Modeling & KPI Development

 •	Developed time-series trend lines across disorders

 •	Created DAX-based KPIs to aggregate total cases per disorder

 •	Segmented visual breakdown by disorder, year, and region


 3.	Dashboard Design

 •	KPI summary cards for total cases by disorder

 •	Year-on-year trend lines for depression, drug use, bipolar, and eating disorders

 •	Highlight visuals for peak years and top suffering regions



📊 KEY METRICS & INSIGHTS


🔑 Core KPIs:

• Total Alcohol Use: 1,641.87

• Total Depression Cases: 3,421.94

• Total Drug Use: 898.51

• Total Anxiety Cases: 4,020.33

• Total Eating Disorders: 287.12



🔍 What Did I Discover?


🧩 Top Mental Health Disorder:

• Anxiety leads globally — highest reported condition with 4,020+ cases


🕰 Historical Peaks:

• 2009 marked the highest spike in Bipolar Disorder cases

• 2017 saw a massive surge in drug use (33.2% of total cases) and the highest prevalence of eating disorders across all years


📌 Sustained Trends:

• From 1999 to 2003, Depression maintained an average rate of ~20% — indicating a consistent burden over time


🌍 Top Region by Suffering:

• Australasia had the highest prevalence across multiple mental health issues



🧠 BUSINESS ANALYSIS (McKinsey-Style Framework)

1. Why Is This Important?

Mental health is no longer a silent crisis — it’s a global business and policy priority.

This analysis reveals:

• Which disorders are most common globally

• When and where spikes happen — guiding healthcare policy

• How substance use correlates with mental health patterns

• The urgency for preventive action and awareness programs



2. What Went Wrong / Was Discovered?


🚩 Critical Observations:

 •	Anxiety disorders dominate — revealing a growing global stress crisis

 •	Substance abuse (drugs & alcohol) continues to fuel comorbid disorders like depression and bipolar

 •	2017 emerged as a year of global mental health crisis — across drug use, eating disorders, and general case spikes

 •	Australasia had one of the highest mental health burdens, indicating regional vulnerability



3. What Should Be Done?


✅ Global Policy Action

 •	Stakeholders (governments, NGOs, mental health organizations) must focus more on anxiety, drug use, and youth-targeted interventions


✅ Regional Resource Allocation

 •	Allocate more support to high-burden regions like Australasia, which face disproportionate mental health challenges


✅ Early Intervention Campaigns

 •	Use insights from high-risk years (like 2017) to build proactive campaigns around schools, digital detox, and mental wellness


✅ Integrated Data Monitoring

 •	Encourage governments and agencies to adopt real-time mental health dashboards for better responsiveness and prevention


 ### 12. Supply Chain Analysis

 🚀 Supply Chain & Sales Analysis 


The aim? Uncover actionable insights to boost product delivery, reduce costs, and enhance customer experience in the supply chain.



⚙ DASHBOARD & ANALYSIS PROCESS

🛠 Tools Used:

• Excel – for data wrangling and pivot summary

• Power Query Editor – to clean and transform product, carrier, and pricing data

• Power BI – for dashboard development and insight visualization



🔄 Process Breakdown:

 1.	Data Cleaning

 •	Removed duplicates, standardized product names and shipping carriers

 •	Handled missing transport cost and defect values


 2.	KPI Formulation

 •	Computed total revenue and average product pricing

 •	Defined product defect rate and transport mode cost metrics

 •	Created dynamic slicers by carrier and product type


 3.	Dashboard Design

 •	Revenue and volume performance by product type

 •	Carrier usage frequency and shipping volume metrics

 •	Average transport cost by mode

 •	Defect rate heatmap per product type



📊 CORE METRICS & KEY INSIGHTS


🔑 Key Performance Indicators (KPIs):


• Total Revenue: $4,960

• Average Product Price: $49.46

• Total Products Sold: 46,000 units



🔍 Deep Dive Insights:


🧴 Top Product Type by Sales & Revenue:

• Skincare dominated both in units sold and revenue contribution


🚚 Most Used Shipping Carrier:

• Carrier B was the top performer — highest in both frequency and volume


⚠ Product Type with Highest Defect Rate:

• Hair Care Products — indicating potential production or packaging issues


💸 Most Expensive Transport Mode:

• Road Transport recorded the highest logistics cost, more than air, rail, or sea



🧠 BUSINESS ANALYSIS (McKinsey Framework)


1. Why Is This Important?

This project answers the big operational questions:

• Which products and carriers drive the most sales and revenue?

• Where are we losing value — through defects or high transport cost?

• What strategic shifts are needed in carrier selection, inventory planning, or logistics budgeting?



2. What Went Wrong? / What Was Discovered?


🚩 Problem Areas Identified:

 •	Hair care products had the highest average defect rate, affecting customer satisfaction and returns

 •	Road transport, though widely used, proved to be costly, affecting logistics margins

 •	Carrier B, while highly utilized, could be over-relied on — risk if it underperforms or faces disruption



3. What Should Be Done?


✅ Defect Control on Hair Products

• Implement quality assurance reviews specifically for hair care SKUs — from packaging to storage


✅ Cost Review on Road Transport

• Analyze whether rail or sea can be used more in non-urgent deliveries to cut down logistics cost


✅ Diversify Carrier Dependence

• While Carrier B is reliable, it’s essential to build backup logistics partnerships to reduce operational risk


✅ Double Down on Skincare

• As the best-performing product category, optimize inventory for skincare lines and run targeted campaigns to scale revenue


### 13. Women E - Commerce Clothing Analysis


👗 Women’s Clothing E-Commerce Analysis



Each dataset tells a different story—and this one was all about what women love to wear. 

In this 6th project of my internship journey, I focused on analyzing customer preferences, product engagement, and age-based shopping behavior in the women’s fashion space.



⚙ DASHBOARD & ANALYSIS PROCESS

🛠 Tools Used:

• Power BI – to design dynamic dashboards for trend visualization

• Power Query Editor – for cleaning, filtering, and transforming raw customer and rating data



🔄 Process Breakdown:

 1.	Data Cleaning & Preparation

 •	Removed null values in rating and department fields

 •	Converted age and rating fields into usable numeric formats

 •	Standardized department and class names for clarity


 2.	KPI Development

 •	Built measures for average rating, average age, total rating count

 •	Segmented rating by department and class name


 3.	Dashboard Design

 •	Created bar charts and heat maps to highlight trends in rating, age distribution, and feedback positivity
 

 •	Enabled interactive filtering by department and age range



📊 CORE METRICS & INSIGHTS


🧮 Key Performance Indicators (KPIs):


• Total Ratings: 4,194

• Average Rating: 4.194

• Total Age Sum: 43,502

• Average Customer Age: 43.502



🔍 Deeper Insights:


👚 Department with Highest Engagement:

• Tops led the way — over 2,000 customer ratings, showing strong interest and feedback volume


👵 Age Distribution Insights:

• Bottoms attracted the highest total age sum, revealing preference from older customer segments


💃 Most Loved Product by Feedback:

• Dresses received the highest positive feedback count (650+), reflecting consistent customer satisfaction



🧠 BUSINESS ANALYSIS (McKinsey Approach)

1. Why Is This Important?

This analysis helps e-commerce fashion businesses answer key questions like:

• Which product categories generate the most customer interest and loyalty?

• How does customer age affect purchasing preferences?

• Where should we invest more in product development and marketing?



2. What Was Discovered?


📌 Customer Engagement Patterns:

 •	Tops received the most ratings, showing popularity and repeat interest

 •	Dresses had the highest satisfaction levels, as seen in positive feedback volume

 •	Bottoms saw interest from older customers, an untapped market for age-specific styles



3. What Should Be Done?


✅ Double Down on Dresses

• Capitalize on customer satisfaction by promoting and upselling dress collections through targeted campaigns


✅ Segment Campaigns by Age

• Since Bottoms appeal to older shoppers, develop age-tailored messaging and fit guides for that segment


✅ Expand Topwear Range

• With high engagement, introducing new styles and color variants in Tops can sustain momentum and boost conversion


✅ Introduce Review Incentives

• Encourage customer feedback across less-engaged departments to balance data and product insights



### 14. Investment Preference Analysis


💼 Investment Preference Analysis



Another one wrapped up ✅ — this time, I explored where people invest, why they invest, and what drives their decisions.



⚙ DASHBOARD & ANALYSIS PROCESS

🔧 Tools Used:

• Power BI – for clear, interactive data visualizations

• Power Query Editor – for transforming raw data into clean, structured formats



🔄 Process Workflow:

 1.	Data Cleaning & Transformation

 •	Removed null entries in investment type and reason fields

 •	Categorized investment vehicles: Equity, Debentures, Mutual Funds, Fixed Deposits

 •	Segmented age groups: Youth, Young Adults, Established Adults, Seniors


 2.	Dashboard Development

 •	Visualized investment distribution via bar/column charts

 •	Mapped investor age groups to preferred investment types

 •	Highlighted reasons for investment and return expectations using pie charts & KPI cards


 3.	Insight Extraction

 •	Interactively filtered investment behaviors by age group

 •	Measured volume of investments across categories and their motivating factors



📊 KEY METRICS & INSIGHTS


📌 Investment Distribution (by count):


• Debentures – 230

• Equity Market – 139

• Mutual Funds – 102


👥 Investor Age Group Analysis:


• Established Adults dominate the investor base

• Their top choices: Mutual Funds, Fixed Deposits, and Equities


💡 Primary Motivation to Invest:

• The leading driver? Returns — it wasn’t even close


💰 Why Mutual Funds?

• Investors were especially attracted to 20–30% return brackets, explaining their popularity



🧠 BUSINESS ANALYSIS (Using McKinsey’s Framework)


1. Why Is This Important?

Understanding investment behavior by age and decision-making factors can help financial institutions:

• Build tailored investment products

• Improve marketing campaigns by segment

• Align offers with investor priorities like return expectation, risk appetite, and investment goals



2. What Was Discovered?


🔍 Demographic Patterns:

 •	Established Adults are the core investment demographic

 •	Their preferred vehicles include Mutual Funds and Fixed Deposits


💹 Investment Type Preferences:

 •	Debentures saw the highest total count — possibly due to perceived security and fixed returns

 •	Mutual Funds gained traction where expected returns hit 20–30%


🎯 Investor Motivation:

 •	Across all investment types, high returns were the primary driver—showing a risk-reward mindset among most groups




3. What Should Be Done?


✅ Target Established Adults Strategically

• Offer more return-focused marketing for Mutual Funds

• Introduce hybrid investment plans combining security + moderate return potential


✅ Position Debentures for Conservative Segments

• Highlight stability and long-term performance for older or risk-averse investors


✅ Educate on Risk & Returns

• Since high returns are a key motivator, provide transparent breakdowns of risk-reward tradeoffs to build long-term investor trust


✅ Create Personalized Investor Journeys

• Use demographic segmentation to customize onboarding, newsletters, and investment advice tools


### 15. Digital Marketing Analysis

📊 Digital Marketing Performance Analysis



🚀 Just completed a deep-dive project focused on Digital Marketing Analysis — and I built an interactive dashboard that connects cost, performance, and profitability into one compelling story.



⚙ DASHBOARD & ANALYSIS PROCESS

🔧 Tools Used:

• Power BI – for advanced visual analytics

• Power Query Editor – to clean, merge, and prepare the marketing dataset



🧩 Process Workflow:

 1.	Data Preparation & Cleaning

 •	Standardized columns (date format, campaign types, performance metrics)

 •	Removed duplicates and null values across cost and revenue indicators

 •	Engineered key metrics: CAC, AOV, CPL


 2.	Dashboard Development

 •	Built visuals for CAC, CPC, AOV, Gross Profit, and campaign performance

 •	Time-series line charts for order trends

 •	Bar/stacked charts for campaign ROI and channel breakdowns

 •	Drill-through filters for campaign and platform-level insights


 3.	Insights & Trend Discovery

 •	Identified most cost-efficient channels and campaigns

 •	Analyzed daily vs cumulative metrics to flag performance peaks and gaps

 •	Connected campaign types to profitability and lead generation strength



📈 KEY KPIs & INSIGHTS


💰 Performance Metrics:

• Cost Per Click (CPC): ₦673.32 billion

• Cost Per Lead (CPL): ₦17.68 billion

• Customer Acquisition Cost (CAC): ₦2.49 billion

• Average Order Value (AOV): ₦26.11

• Gross Profit: ₦13.54 trillion


🔎 Campaign Highlights:

• 📅 Peak Sales Day: February 20th recorded the highest number of orders

• 📹 Best Campaign: YouTube Blogger – generated the highest revenue

• 🌐 Most Leads Generated: The Social category led in lead volume



🧠 BUSINESS ANALYSIS (Using McKinsey’s Framework)


1. Why Is This Important?

Marketing budgets are massive — but without analysis, companies could be spending more to earn less. 

This project helps decision-makers:

 •	Optimize ad spend

 •	Identify high-performing campaigns and channels

 •	Improve cost efficiency and customer targeting



2. What Was Discovered?


📊 Strong Performance Metrics:

 •	Despite high CPC and CPL, gross profit remains robust, signaling strong ROI in specific channels


📈 Top Campaign:

 •	YouTube Blogger outperformed all others in revenue generation — showing the power of influencer-led video marketing


🌐 Lead Source Insights:

 •	Social platforms generated the most leads — an opportunity to further optimize targeting and creatives for conversion


📆 Temporal Insight:

 •	February 20th showed an order surge, suggesting campaign timing, audience intent, or seasonal behavior influenced buying patterns



3. What Should Be Done?


✅ Double Down on High-Performing Campaigns

• Scale YouTube Blogger and similar influencer-driven campaigns

• Consider reallocating budget toward high-ROI channels like YouTube and Social


✅ Optimize CPC and CPL

• Evaluate underperforming campaigns with high cost and low conversion

• Improve audience segmentation and ad creatives to reduce lead cost


✅ Maximize Q1 Conversions

• Leverage the February spike to build seasonal campaigns or early-year promos


✅ Experiment with A/B Testing

• Run controlled tests across platforms to refine messaging and offer structures

• Measure real-time shifts in CAC and AOV


✅ Balance Profitability with Reach

• High CPC doesn’t always mean low ROI — identify which audience cohorts drive the highest gross profit per order
