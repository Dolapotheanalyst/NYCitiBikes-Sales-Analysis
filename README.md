# NYCitiBikes-Sales-Analysis
As someone passionate about data analysis, I decided to explore the NYC Citi Bikes dataset to uncover key insights about bike rental patterns. This project involved cleaning, filtering, and analyzing the dataset using pivot tables, descriptive statistics, and data visualization techniques.
Throughout this analysis, I focused on answering key questions such as:

✔ Which locations are the most popular for pickups?

✔ How does trip duration vary across different age groups?

✔ Which age group rents the most bikes?

✔ How do bike rentals vary between one-time users and long-term subscribers across different days?

By addressing these questions, I was able to identify patterns in bike rental behavior and user preferences.
# Data Source:
https://docs.google.com/spreadsheets/d/1D7y7LfBG-owIkXOiabRfFG0XcEzQS_8Lz5BsnRkVT3E/edit#gid=845159259
# Data Cleaning Process
## Removing Duplicates
When I first loaded the dataset, I noticed the presence of duplicate values, which could have skewed my analysis. To resolve this:
I identified and removed 1,950 duplicate values, reducing the dataset to 18,450 unique records.
After removing duplicates, I checked for empty rows caused by missing values and deleted them to maintain a clean dataset.
## Handling Missing Values
While exploring the dataset, I discovered that some "End Station Name" entries were missing, particularly in five locations, including Corners Library.
Since these missing values could lead to inconsistencies, I removed incomplete rows to ensure data integrity.
## Detecting and Removing Outliers
To ensure that my analysis was not affected by extreme values, I performed a descriptive statistics analysis on Trip Duration and Age.
I discovered an unrealistically high trip duration of 6,515 minutes, which I considered an outlier and removed.
After filtering outliers, the new maximum trip duration was 3,693 minutes, making the data more realistic.
These steps were essential in ensuring that my analysis was based on accurate and meaningful data.

# Data Analysis Using Pivot Tables
## Question 1: What are the most popular pickup locations for Citi Bikes?
 How I approached this question:
I created a pivot table with "Start Station Name" as both row labels and values.
I sorted the count to determine the most frequently used pickup stations.
 Key Findings:
The top 3 most popular stations were PATH Exchange Place, Hamilton Park, and Grand Central.
These stations likely experience high demand due to their proximity to business hubs and transit points.
This insight could be valuable for bike-sharing companies to optimize bike distribution and availability.

## Question 2: How does average trip duration vary across different age groups?
 How I approached this question:
I created a pivot table with "Age Group" in rows and "Trip Duration (minutes)" in values.
This helped me calculate the average trip duration per age group.
 Key Findings:
The 75+ age group had the longest average trip duration (48 minutes).
However, this group had one of the lowest rental counts, indicating that while they ride for longer periods, they rent bikes less frequently.
This insight highlights a potential market segment for Citi Bikes, where they could introduce senior-friendly bike programs to encourage more rentals among older users.

## Question 3: Which age group rents the most bikes?
How I approached this question:
I created a pivot table with "Age Group" in both the row and value sections to count total rentals per age group.
 Key Findings:
The 35-44 age group rented the most bikes.
Interestingly, this differs from the 75+ age group, which had the longest trip durations but the lowest rental frequency.
This suggests that middle-aged individuals are the primary users of Citi Bikes, possibly due to commuting needs.

## Question 4: How does bike rental vary across the two user groups (one-time users vs. long-term subscribers) on different days of the week?
How I approached this question:
I created a pivot table with:
"Weekdays" in the row section
"User Type" (One-Time Users vs. Long-Term Subscribers) in the column section
"Bike ID" in the value section
I applied conditional formatting to visualize rental trends more clearly.
Key Findings:
One-time users rent bikes the most on Saturdays and Mondays.
Long-term subscribers rent bikes mostly on Wednesdays and Thursdays.
Subscribers rent the least on Saturdays, while one-time users rent the most on that day.
This suggests that subscribers use Citi Bikes more for weekday commuting, while one-time users are more likely to use bikes for leisure or weekend activities.

# Conclusion
After cleaning and analyzing the data, I gained valuable insights into NYC Citi Bike rental patterns:

✔ The most popular pickup locations are PATH Exchange Place, Hamilton Park, and Grand Central.

✔ Age groups differ in rental behavior—35-44-year-olds rent the most, while 75+ riders take the longest trips.

✔ One-time users are weekend riders, while long-term subscribers use Citi Bikes for weekday commutes.

✔ Data cleaning is crucial to remove duplicates, handle missing values, and detect outliers for accurate analysis.

✔ Pivot tables and visualization techniques helped uncover these insights effectively.

This analysis not only helped me hone my data analysis skills but also provided actionable insights that Citi Bike operators could use to improve bike distribution, pricing, and user engagement strategies.
