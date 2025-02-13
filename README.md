# aspireindia_assignment

# Methodologies Used
### 1. Data Cleaning and Validation
Why: Before any analysis, it's essential to clean and validate the data to ensure accuracy. This involves identifying missing data, inconsistencies, and outliers.

### 2. Descriptive Statistics
Why: Descriptive statistics (e.g., counts, averages) provide a high-level overview of the data, helping to identify trends and patterns.

### 3. Visualization
Why: Visualizations like bar charts and pie charts make it easier to spot trends and communicate insights effectively.

### 4. Trend Analysis
Why: Analyzing trends over time helps identify patterns in user behavior and engagement.

### 5. Segmentation
Why: Segmenting users based on engagement levels or program preferences allows for targeted actions to improve overall participation.


# Visible Trends/Highlights:
1. *Popular Programs*:
   - Programs like "Cardio Expert" (ID: 10220) and "Guest Happiness Coordinator" (ID: 10168) are frequently updated in the user updates sheet, indicating they are popular among users.
   - Wellbeing programs like "Yoga" (ID: 10023) and "Balanced Diet" (ID: 10030) also show frequent updates, suggesting a focus on health and wellness.

2. *Active Users*:
   - Users like 12240 (Aditi Singh) and 12249 (Rajesh Aggarwal) have multiple updates across different programs, indicating high engagement.
   - Users in the "Operation" department (e.g. Aditi Singh) are highly active, suggesting that operational staff are more engaged in these programs.
   - Also Users in the "F&B" department (e.g. Rajesh Aggarwal) are highly active, suggesting that F&B staff are more engaged in these programs.

3. *Task Engagement*:
   - Tasks related to financial compliance (e.g., "Review TDS and GST compliance for 30 minutes") and project management (e.g., "Update project timelines daily to track progress") are frequently completed, indicating a focus on operational efficiency.
   - Wellbeing tasks like "Meditate for 5 minutes" and "Track your fruit/vegetable intake for the day" are also popular, reflecting a growing interest in personal health.
   
4. *Program Types*:
   - Mastery programs (e.g., "Payment Solutions Expert") are more frequently updated compared to Wellbeing programs, suggesting a stronger focus on skill development.
   - Wellbeing programs, however, show consistent engagement, indicating a balanced approach between professional and personal development.

5. *Department-wise Engagement*:
   - Users from the "Operation" and "F&B" departments are more active in program updates compared to other departments like "IT" or "Security". This could indicate a need to increase engagement in less active departments.
  
# Actionable Insights
#### 1. Actions for Less Engaged Users
*Insight*: Some users have very low level engagement (for eg. 12203-Kiran Srivastava, 12208-Suraj Kumar).

*Action*:
- Conduct surveys to understand why engagement is low. This helps identify obstacles that users face and create targeted solutions.
- Introduce gamification elements (leaderboards, badges, rewards) to motivate users. This makes tasks more interactive and fun.
- Create tutorial videos or knowledge-sharing sessions to increase familiarity and confidence with the platform.
- Offer more relevant tasks or content recommendations based on user interests or past activities. The more aligned the content is with the user’s interests, the more engaged they will be.
- Group activities and collaborative tasks often boost engagement as users feel more involved and connected to others.

#### 2. Actions for Low Performance Programs
*Insight*: Some programs have their performance level very poor. (for eg. 10193-Parking Systems Visionary, 10167-Guest Experience Champion). 

*Action*:
- Evaluate if the goals, processes, and resources are aligned with user capabilities and expectations.
- Adjust the program structure to better suit the needs of participants. For example, add flexibility in deadlines or reduce unnecessary steps.
- Conduct focus groups or individual interviews with users to deeply understand the barriers they face within the program.
- Promote user-generated content where participants can share tips, stories, or strategies that helped them perform better.
- Create a communication plan that keeps participants engaged through regular notifications, email reminders, or app alerts.

#### 3. Boost Engagement in Underperforming Departments 
*Insight*: Users in "IT", "Maintenance", "HR", and "Housekeeping" departments have lower participation compared to "Operation", "F&B", and "Security".  

*Action*:  
- Launch department-specific campaigns (e.g., IT-focused skill challenges, HR focused activities) with rewards like coins or recognition.  
- Assign program ambassadors in these departments to drive participation.  
- Implement transparency in decision-making processes by sharing company goals, results, and how each department contributes to them.
- Provide training and development opportunities (online courses, workshops, mentoring programs).
- Break down large goals into smaller, manageable tasks, and track progress with regular check-ins.

#### 4. Expand Wellbeing Program Offerings  
*Insight*: Wellbeing tasks (e.g., "Meditate for 5 minutes") show consistent engagement, but the current program list is limited.  

*Action*:  
- Introduce new Wellbeing programs (e.g., stress management, fitness challenges) and *gamify tasks* (e.g., streaks, leaderboards) to sustain interest.  
- Highlight top performers in monthly wellness newsletters.

#### 5. Standardize Data Entry Practices  
*Insight*: Inconsistent formats (e.g., taskMinDuration values like "2000" vs. "18") and duplicate user entries reduce data reliability.  

*Action*:  
- Enforce data validation rules (e.g., require units like "minutes" for durations).  
- Run a data cleanup initiative to merge duplicates (e.g., Kartik Bajaj’s two entries) and fix future-dated timestamps.

#### 6. Enhance Mastery Programs with Advanced Tracks  
*Insight*: Mastery programs (e.g., "Payment Solutions Expert") are frequently used but lack progression tiers.  

*Action*:  
- Create certification tiers (Beginner/Expert) for high-demand programs to incentivize skill advancement.  
- Offer bonuses (e.g., extra points, badges) for completing advanced modules.

#### 7. Investigate and Fix Future-Dated Entries 
*Insight*: Entries in user updates with dates in 2025 (e.g., 2025-02-07) suggest system errors or test data contamination.  

*Action*:  
- *Audit timestamp logic* to ensure dates align with actual activity.  
- Implement *automated date validation* to block illogical future entries.  
