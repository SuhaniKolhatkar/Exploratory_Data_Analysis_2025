# Exploratory_Data_Analysis_2025
This file provides a Python code for analyzing student study data, with a focus on understanding individual study habits and preferences. 
![compPT](https://github.com/user-attachments/assets/9414ca9f-36f4-4864-8c6e-92e7ba6aef57)


**The code processes and analyzes a CSV file named 'timeSheet.csv', which contains information about student study sessions, including the subject, start and end times, and a Rate of Perceived Exertion (RPE) value**. The code utilizes the Pandas, NumPy, Matplotlib, and DateTime libraries to perform various data manipulations, calculations, and visualizations. 

**Key Features:**

*   **Data Cleaning and Preprocessing:** The code starts by cleaning the data by removing unnecessary columns and converting timestamps to appropriate date and time formats.
*   **Duration Calculation:** It calculates the duration of each study session based on the start and end times.
*   **Average RPE and Duration Calculation:**  The code then calculates the average RPE and duration for each student and subject.
*   **Prime Time Analysis:**  It analyzes study durations and RPE across different times of the day (dawn, morning, afternoon, evening) to identify individual prime study times.
*   **Session-Wise Analysis:** The code allows for an examination of session durations and RPE values together to understand student productivity and focus.
*   **Subject-Specific Insights:** The code creates separate dataframes and visualizations for each subject, providing insights into subject-specific study patterns.
*   **Comparative Analysis:**  It includes code for creating combined plots that compare study durations and RPE across students for each subject and time slot. 

**Visualizations:**

*   Bar plots are used to visualize average study durations and RPE values.
*   Grouped bar plots provide a comparative view of study metrics across students and subjects. 
*   Overlapping bar plots with maximum value bars as background effectively highlight prime time analysis for each student.

**Key Insights:**

The analysis reveals distinct study patterns for each student. **Swara demonstrates the highest average study duration overall, followed by Jui, while Jui consistently reports higher RPE scores**.  **Nupur exhibits a more balanced approach with variations depending on the subject and time of day.** 

**Prime study times also vary, with Nupur excelling in the evening, Swara preferring mornings and dawn, and Jui showing consistency across time slots**.  The analysis highlights subject preferences, with **Swara focusing on Maths-I, Nupur showing a preference for English, and Jui dedicating significant effort to Chemistry.**

**By combining these insights, educators and students can work together to develop personalized study plans that optimize learning effectiveness, time management, and overall academic success.** 



