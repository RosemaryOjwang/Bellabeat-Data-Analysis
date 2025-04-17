# Bellabeat Spring: Smart Water Bottle Analysis & Dashboard
![DashboardScreenShot](https://github.com/user-attachments/assets/2e95aea3-a4c6-4bfa-bd50-f388ddb7c276)


This project explores user data from Bellabeat smart devices to provide **data-driven insights** and **marketing recommendations** for the Bellabeat product called **Spring** — a smart water bottle that tracks daily hydration using smart technology and syncs with the Bellabeat app.

The goal is to identify patterns in **hydration-related behavior** using weight and BMI data, among other wellness metrics, and present actionable insights in an interactive Excel dashboard.

---

## Tools Used

- **Microsoft Excel** (Power Pivot, Slicers, Pivot Tables, Charts, Dashboard Design)
- **GitHub** (for project documentation and sharing)
- **Data Modeling** in Excel using a User Lookup Table

---

## 🧹 Data Processing Workflow

1. **Combined Data from Different Time Periods**  
   - Merged multiple Excel/CSV files to create one master workbook.  
   - Cleaned columns, fixed formatting, and standardized date fields.

2. **Loaded Datasets into the Excel Data Model**  
   - Added individual datasets: `Activity`, `Weight`, `Sleep`, etc.  
   - Ensured consistent formatting (e.g., ID, Date fields).

3. **Created a User Lookup Table**  
   - Generated a `UserLookup` table with unique `Id`s.  
   - Used as the central key for building relationships across all datasets.

4. **Linked All Tables in the Data Model**  
   - Connected each dataset to the `UserLookup` using the `Id` field.  
   - Built one-to-many relationships to enable unified slicer filtering.

5. **Built Pivot Tables**  
   Created custom pivot tables for key wellness metrics:
   - **Calories Burnt by Weekday per User**
   - **Average Steps by Weekday per User**
   - **Sleep Duration per Day**
   - **Weight vs. BMI Comparison**
   - **Steps vs. Calories**
   - **Activity Type Percentages**

6. **Designed an Interactive Dashboard**  
   - Slicer-enabled, user-specific dashboard.  
   - Side-by-side line charts for Weight and BMI.  
   - Custom colors:
     - Weight: RGB(242, 126, 110)
     - BMI: RGB(58, 58, 58)  
   - Key metrics section to summarize user health behavior.

---

## 📊 Key Insights (Spring Product)

- Users with consistent weight and BMI data tend to show **stable hydration habits**.  
- **Low sleep duration** may correlate with higher BMI for some users — a potential sign of poor hydration or recovery.  
- **Activity levels drop on weekends**, suggesting a need for hydration reminders on those days.  
- **Hydration tracking could benefit from real-time alerts** during low-activity periods.
- Users with high step counts do not necessarily have higher water intake, showing a disconnect that **Spring can fill** via smart tracking and app nudges.

---

## 📢 Recommendations for Bellabeat (Spring)

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

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `Bellabeat_Spring_Analysis.xlsx` | Main Excel file with all datasets, model relationships, pivot tables, and dashboard |
| `Dashboard_Screenshot.png` | Static preview image of the final dashboard |
| `README.md` | Documentation of the project |

---

## 📌 Next Steps

- Expand analysis by comparing seasonal trends in hydration and activity.  
- Collect feedback on dashboard usability and insights clarity.  
- Explore building the dashboard in **Power BI or Tableau** for web-based interactivity.

---

> Created by **Rose** as part of a case study inspired by the Google Data Analytics Capstone project.
# Bellabeat-Data-Analysis
## Project Overview
This case study explores how Bellabeat, a high-tech manufacturer of health-focused products for women, can utilize fitness data from non-Bellabeat smart devices to identify new business opportunities.
## Results & Visualizations
View the full presentation here: [Bellabeat Smart Device analysis](https://docs.google.com/presentation/d/1tuwBoV5vEnYOqb0ykqGRgVYJcBSyLUwlN_2ZXNWeyVY/edit?usp=sharing)

## To Do
1. Understand the Key Fitness Metrics from Non-Bellabeat Devices.
Even though you don’t have demographic or feature-specific data for non-Bellabeat devices, you do have fitness activity and user engagement data. By analyzing this data, we can make inferences about what features or user behaviors Bellabeat should target.
- Identify the fitness activities that are most commonly tracked in the non-Bellabeat data:
  - Are users mostly tracking steps, workouts, or sleep?
  - Do users track calories burned, active minutes, or heart rate?
- How frequently do users log their activity data? Understanding this can help assess user retention and engagement over time.

**Actionable Insight:** If non-Bellabeat device users focus heavily on step tracking and running, this indicates that adding advanced features like workout tracking (especially running, cycling, or other cardio) could make Bellabeat more appealing to users of fitness-focused devices.

2. Feature Comparison (Non-Bellabeat Devices vs. Bellabeat Features) Since the device features of Bellabeat are provided, we can compare Bellabeat's existing features with the user activity data from the non-Bellabeat devices. Here’s how to align the insights:
- Feature Usage: Review which features of Bellabeat (e.g., sleep tracking, menstrual cycle tracking, wellness coaching) are similar to features commonly found in non-Bellabeat devices.
  - If non-Bellabeat users engage a lot with heart rate tracking or workout features, it would be beneficial for Bellabeat to ensure it has these features built out fully.
  - If non-Bellabeat users are highly engaged in social features or activity challenges, Bellabeat might want to develop or improve community features.

**Actionable Insight:** Use the available activity data to highlight potential gaps in Bellabeat's features. For instance, if non-Bellabeat devices have strong workout tracking (e.g., Garmin, Fitbit), Bellabeat could explore adding more advanced fitness tracking or integrating social features for users to compete in challenges and share progress.

3. Engagement Patterns in Non-Bellabeat Devices
- Look at how frequently users interact with non-Bellabeat devices. If engagement is high on certain types of data (e.g., tracking daily steps, workouts, sleep), this could indicate a strong user interest in those areas.
- If engagement is low, it may suggest that users are not seeing value in certain features of non-Bellabeat devices (e.g., basic activity tracking), which provides an opportunity for Bellabeat to differentiate itself by offering more valuable features.

**Actionable Insight:** If users of non-Bellabeat devices are not fully utilizing certain features, Bellabeat could target this gap by offering personalized features, such as better sleep analysis or more intuitive workout tracking that encourages user interaction over time.

4. User Engagement and Retention
- Retention Trends: In fitness devices, user retention is often a sign of how well a device meets long-term needs. If the non-Bellabeat data shows declining usage after initial high engagement, Bellabeat could focus on improving retention strategies:
  - Gamify the experience (e.g., offer badges, rewards for continuous tracking).
  - Provide personalized goals (e.g., more tailored fitness plans or reminders).
- Frequency of Activity Logging: Is there a trend in activity logging, such as morning vs. evening usage? Does engagement dip on weekends or holidays?

**Actionable Insight:** High engagement during specific periods could guide Bellabeat in tailoring marketing efforts or adjusting feature timing to ensure higher user retention (e.g., reminders, motivational features for users during weekends or specific times of the day).

5. Actionable Features for Bellabeat Based on Non-Bellabeat Device Insights From the activity data and engagement trends observed in non-Bellabeat devices, you can derive a set of actionable insights for Bellabeat’s features:
- Workout Tracking: If non-Bellabeat devices are being used for detailed workout tracking (running, cycling, HIIT), this feature could be a major opportunity for Bellabeat. Introduce workout modes or fitness challenges that allow users to track different types of exercises, not just steps.
- Social Features: If non-Bellabeat devices have high social interaction (e.g., activity challenges, group sharing), consider integrating a community engagement component into Bellabeat, where users can share their progress and challenge friends.
- Holistic Wellness Focus: Given that Bellabeat is marketed towards women and wellness, it can double down on its holistic wellness features (e.g., mindfulness tracking, nutrition tips, mental health support).
- Integration with Fitness Apps: If users of non-Bellabeat devices use fitness apps to sync their data, Bellabeat could explore integration with third-party fitness apps or create its own ecosystem to increase device utility.


![image](https://github.com/user-attachments/assets/5fd5d32a-bd74-45b4-9d43-4a942eee79f4)


  







