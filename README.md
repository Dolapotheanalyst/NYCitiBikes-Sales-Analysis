# NYC Citi Bikes Sales Analysis  
A Data-Driven Exploration of Urban Mobility Patterns

As a passionate data analyst, I carried out a comprehensive analysis of the NYC Citi Bikes dataset to uncover patterns in user behavior, trip characteristics, and rental trends across the city. This project involved a full workflow—cleaning the dataset, removing duplicates, handling missing values, detecting outliers, and applying pivot-table–based analysis to derive insights.

The analysis was guided by four key questions:

- **Which locations are the most popular pickup points?**  
- **How does trip duration differ across age groups?**  
- **Which age group records the highest rental frequency?**  
- **How do rental patterns differ between one-time users and long-term subscribers across the week?**

Through these questions, I was able to reveal meaningful trends in bike usage across NYC.

---

##  Data Source  
The dataset used for this analysis is available here:  
**Google Sheets:**  
[[`https://docs.google.com/spreadsheets/d/1D7y7LfBG-owIkXOiabRfFG0XcEzQS_8Lz5BsnRkVT3E/edit#gid=845159259`
#  Data Cleaning Process

## 1. Removing Duplicates  
During initial inspection, the dataset contained **1,950 duplicate rows**, which could distort results.  
- These duplicates were removed, reducing the dataset to **18,450 unique records**.  
- Additional empty rows caused by missing values were removed to maintain dataset reliability.

## 2. Handling Missing Values  
Several entries under **"End Station Name"** were missing—5 rows, including locations such as **Corners Library**.  
- All incomplete rows were deleted to preserve the accuracy of station-based analysis.

## 3. Detecting and Removing Outliers  
Using descriptive statistics:  
- An abnormally high trip duration of **6,515 minutes** was detected.  
- This value was removed as an outlier.  
- The adjusted maximum duration became **3,693 minutes**, aligning with realistic trip ranges.

These steps ensured the analytical results were both accurate and meaningful.

---

#  Data Analysis Using Pivot Tables

## **Question 1: What are the most popular pickup locations?**  
**Approach:**  
- Pivot table with *Start Station Name* as rows and values.  
- Sorted by rental count.

**Key Findings:**  
Top 3 pickup stations:  
1. **PATH Exchange Place**  
2. **Hamilton Park**  
3. **Grand Central**

Their proximity to business districts and transport hubs explains the high demand.

---

## **Question 2: How does average trip duration vary across age groups?**  
**Approach:**  
- Pivot table with *Age Group* and average *Trip Duration*.

**Key Findings:**  
- The **75+ age group** recorded the **longest average trip duration (48 minutes)**.  
- Despite this, they ranked among the lowest in overall rentals.  

This suggests potential for targeted senior-based programs.

---

## **Question 3: Which age group rents the most bikes?**  
**Approach:**  
- Pivot table with *Age Group* and rental counts.

**Key Findings:**  
- **35–44 age group** recorded the highest number of rentals.  
- This contrasts with the 75+ group, who ride longer but rent less frequently.  

Commuting patterns likely drive the high usage among middle-aged adults.

---

## **Question 4: How do rentals differ between one-time users and subscribers across the week?**  
**Approach:**  
- Pivot table with:
  - *Weekday* as rows  
  - *User Type* in columns  
  - *Bike ID* counts as values  
- Conditional formatting applied to highlight peaks.

**Key Findings:**  
- **One-Time Users:** Peak on **Saturdays** and **Mondays**.  
- **Subscribers:** Peak on **Wednesdays** and **Thursdays**.  
- Subscribers rent the least on Saturdays, while one-time users rent the most.

This shows a clear difference between **leisure riders (weekend)** and **commuters (weekday)**.

---

#  Conclusion  
The analysis provided valuable insights into Citi Bike usage:

- **Most popular pickup stations:** PATH Exchange Place, Hamilton Park, Grand Central.  
- **Age-driven behavior differences:**  
  - 35–44-year-olds rent the most frequently.  
  - 75+ users record the longest trip durations.  
- **User-type patterns:**  
  - One-time users dominate on weekends.  
  - Long-term subscribers dominate weekday rentals.  
- **Importance of data cleaning:** Removing duplicates, missing values, and outliers ensured credible results.  
- **Pivot tables and visualizations** uncovered critical behavioral patterns across demographics and user types.

---

#  Recommendations for Future Planning and Program Growth  
Based on the insights from this analysis, the following recommendations can support planning for future Citi Bike programs, station distribution, and service optimization:

### **1. Increase Bike Availability at High-Demand Hubs**
Stations such as **PATH Exchange Place**, **Hamilton Park**, and **Grand Central** should have:  
- More bikes allocated during peak commuting periods.  
- Additional docking points installed if feasible.  
- Real-time rebalancing strategies to prevent shortages during rush hours.

---

### **2. Develop Senior-Friendly Riding Programs**
Since the **75+ age group** takes the longest rides but rents the least:  
- Introduce **discounted senior plans** to boost usage.  
- Provide **comfort bikes**, such as bikes with better seats and step-through frames.  
- Offer **guided safety sessions** to make older riders more comfortable.

---

### **3. Target the 35–44 Age Group With Commuter-Focused Initiatives**
This group is the highest renter and likely driven by work commutes.  
- Expand weekday subscription packages.  
- Introduce loyalty bonuses for repeat weekday riders.  
- Add more bikes near office complexes and business corridors.

---

### **4. Tailor Weekend Strategies for One-Time Users**
Since one-time users peak on **Saturdays**:  
- Increase inventory near parks, tourist areas, and recreation zones.  
- Offer weekend promo codes or flexible 24-hour passes.  
- Deploy mobile maintenance teams to minimize downtime from wear and tear.

---

### **5. Optimize Distribution Based on Day-of-Week Patterns**
Subscriber activity peaks mid-week, while casual riders peak on weekends.  
- Weekday: Prioritize commuter hotspots.  
- Weekend: Shift bikes toward leisure and tourist locations.  
- Use predictive analytics to forecast daily bike demands.

---

### **6. Improve Marketing Campaigns Using Behavioral Trends**
- Promote weekday commuter plans to subscribers.  
- Use weekend-focused ads for one-time users, tourists, and families.  
- Highlight long-distance ride features for older adults.

---

### **7. Prepare Inventory Planning for Upcoming Programs**
If Citi Bike plans to **host new events or mobility programs**, they should:  
- Position bike stations near event venues.  
- Provide extra temporary bike racks if crowds are expected.  
- Monitor real-time demand during events for rapid bike redistribution.

---

### **8. Expand Data Monitoring and Reporting**
To support continuous improvement:  
- Track rental patterns monthly.  
- Add dashboards showing age-group usage, station demand, and user-type trends.  
- Use the insights to support future funding and expansion decisions.

---

# Author  
**Adewumi Dolapo**  
*Data Analyst | Excel | Power BI | SQL | Visualization*  
