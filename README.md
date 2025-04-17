# Bellabeat Spring: Smart Water Bottle Analysis & Dashboard
![DashboardScreenshot](https://github.com/user-attachments/assets/2e95aea3-a4c6-4bfa-bd50-f388ddb7c276)


This project explores user data from non-Bellabeat smart devices to provide **data-driven insights** and **marketing recommendations** for the Bellabeat product called **Spring** — a smart water bottle that tracks daily hydration using smart technology and syncs with the Bellabeat app.

The goal is to identify patterns in **hydration-related behavior** using weight and BMI data, among other wellness metrics, and present actionable insights in an interactive Excel dashboard.

---

## Tools Used

- **Microsoft Excel** (Power Pivot, Slicers, Pivot Tables, Charts, Dashboard Design)
- **GitHub** (for project documentation and sharing)
- **Data Modeling** in Excel using a User Lookup Table

---

## Data Processing Workflow

1. **Combined Data from Different Time Periods**  
   - Merged multiple Excel files to create one master workbook.  
   - Cleaned columns, fixed formatting, and standardized date fields.

2. **Loaded Datasets into the Excel Data Model**  
   - Added individual datasets: `Activity`, `Weight`, `Sleep`, etc.  
   - Ensured consistent formatting (ID, Date fields).

3. **Created a User Lookup Table**  
   - Generated a `UserLookup` table with unique `Id`s.  
   - Used as the central key for building relationships across all datasets.

4. **Linked All Tables in the Data Model**  
   - Connected each dataset to the `UserLookup` using the `Id` field.  
   - Built one-to-many relationships to enable unified slicer filtering.
     ![TablesRelationship](https://github.com/user-attachments/assets/5fd5d32a-bd74-45b4-9d43-4a942eee79f4)

5. **Built Pivot Tables**  
   Created custom pivot tables for key wellness metrics:
   - **Calories Burnt by Weekday**
   - **Average Steps by Weekday**
   - **Sleep Duration per Day**
   - **Weight vs. BMI Comparison**
   - **Steps vs. Calories**
   - **Activity Type Percentages**
     
   NB: To prepare the data for visualization and analysis, I also created the following helper pivot tables:
- **helperWeightLog Pivot**
- **helperMinuteSleep Pivot**
- **helperDailyActivity pivot**
  
All pivot tables are connected to a universal slicer for user-level filtering and interactivity across the dashboard.


6. **Designed an Interactive Dashboard**  
   - Slicer-enabled, user-specific dashboard.
   - Calories Burnt by Weekday chart
   - Average Steps by Weekday chart
   - Sleep Duration per Day chart
   - Side-by-side line charts for Weight and BMI.
   - Steps vs. Calories chart
   - Activity Type Percentages chart  

---

## Key Insights (Spring Product)

- Users with consistent weight and BMI data tend to show **stable hydration habits**.  
- **Low sleep duration** may correlate with higher BMI for some users — a potential sign of poor hydration or recovery.  
- **Activity levels drop on weekends**, suggesting a need for hydration reminders on those days.  
- **Hydration tracking could benefit from real-time alerts** during low-activity periods.
- Users with high step counts do not necessarily have higher water intake, showing a disconnect that **Spring can fill** via smart tracking and app nudges.

---

## Recommendations for Bellabeat (Spring)

1. **Promote Personalized Hydration Goals**  
   - Use weight/BMI trends to suggest daily water intake targets.

2. **App Notifications Based on Inactivity**  
   - Remind users to hydrate during long sedentary periods.

3. **Weekend Wellness Campaigns**  
   - Encourage consistent Spring usage during low-activity days.

4. **Gamify Hydration**  
   - Offer badges or streaks for meeting daily hydration targets synced with the Spring bottle.

5. **Use Sleep Patterns to Drive Messaging**  
   - Target users who sleep less with wellness reminders about the link between hydration and rest.

---

## Files in This Repository

| File | Description |
|------|-------------|
| `Bellabeat_Spring_Analysis.xlsx` | Main Excel file with all datasets, model relationships, pivot tables, and dashboard |
| `DashboardScreenshot.png` | Static preview image of the final dashboard |
| `TablesRelationship.png` | Preview image of the tables relationship |
| `README.md` | Documentation of the project |

---

## Next Steps
 
- Collect feedback on dashboard usability and insights clarity.  
- Explore building the dashboard in **Power BI or Tableau** for web-based interactivity.

---

> Created by **Rosemary Ojwang** as part of a case study inspired by the Google Data Analytics Capstone project.
