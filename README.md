# Global-Shark-Attack-Analysis
Uncovering the Data Behind the Bites (1900 - 2017)

Project Overview

The goal of this project is to analyze historical shark attack data from 1900 to the present day. Using Power BI, I transformed a highly unstructured, messy dataset into an interactive executive dashboard. This project answers key questions about global shark attack trends, the most dangerous locations, and the typical profile of an incident.

Data Cleaning & Transformation

Real-world data is messy, and a century's worth of handwritten shark attack records is no exception. Before building any visuals, I used Power Query to clean and structure the data aggressively:

 * Standardizing Text: Columns like Injury and Species contained thousands of unique, handwritten descriptions (e.g., "2m raggedtooth", "blacktip or spinner"). I forced these columns to lowercase and built custom Conditional Columns to group them into clean, broad categories (like "Leg," "White Shark," and "Bull Shark").
   
 * Handling Blanks & Errors: Historical data has a lot of missing information. I replaced null values and query errors with "Unknown" so the final charts wouldn't break or display blank categories.
   
 * Fixing Data Type Clashes: I caught and resolved step-breaking data type errors, such as changing time entries like "1300" into Text format so they wouldn't break lowercase formatting rules.
   
 * Categorizing Time: I grouped highly varied time formats (like "08h30" and "Late afternoon") into four clean buckets: Morning, Afternoon, Evening, and Night.
   
Key Insights

After cleaning the data and building an interactive dashboard with drill-down capabilities, here is what the numbers actually show:

 * The Historical Trend: Reported attacks stayed relatively flat through the early 1900s, peaked sharply around 2015, and then dropped. This massive spike aligns with global population growth, the rise of surfing, and better internet reporting, not necessarily more aggressive sharks.
   
 * The Danger Zones: The USA and Australia report the highest number of attacks. Drilling down into the USA, Florida and California take the lead, with New Smyrna Beach, Florida, standing out as the top specific location globally.
   
 * The Attack Profile: If an attack occurs, the data shows it is most likely to happen in the Afternoon, the White Shark is the most common species involved, and the most frequently injured body part is the Leg.

Dashboard Preview

   
Tools Used
 * Microsoft Power BI (Data Visualization, Drill-downs, Slicers)
   
 * Power Query (Data cleaning, conditional logic, error handling)
