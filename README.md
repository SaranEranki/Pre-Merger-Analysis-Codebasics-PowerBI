# Pre-Merger Analysis of OTT Platforms (LioCinema & Jotstar)📺🎬

>## 🏆 Achievement
>🥉 **3rd Place Winner** — [Codebasics Resume Project Challenge #14](https://codebasics.io/challenge/codebasics-resume-project-challenge/17)

>This project was awarded **3rd place** in an analytics competition hosted by Codebasics.
>**Recognized for:**
>- Insightful business analysis  
>- Clean and interactive dashboard design  
>- Clear and impactful presentation of findings

>✅ Also featured on [LinkedIn](https://www.linkedin.com/posts/codebasics_codebasics-data-dataanalyst-activity-7334062699586142208-fxf8?utm_source=share&utm_medium=member_desktop&rcm=ACoAABY98NEBQWmpZWTaKmK93m_x2JhKH8bkOO4).
---

## 🎯 Dashboard Preview
![Dashboard page screenshot](https://github.com/SaranEranki/Pre-Merger-Analysis-Codebasics-PowerBI/blob/main/Screenshot%202025-04-21%20212100.png)

---

## 🏢 Project Overview 

🚀 Lio x Jotstar: Paving the Future of Streaming in India

Lio, one of India’s top telecommunications providers, is gearing up for a game-changing merger with Jotstar, a leading streaming platform known for its rich and diverse content. This strategic alliance aims to blend LioCinema’s massive subscriber base with Jotstar’s expansive content library, setting the stage to revolutionize the digital entertainment landscape in India.

As part of the merger preparations, Lio’s management is conducting a comprehensive analysis of both platforms—LioCinema and Jotstar—spanning January to November 2024. The focus is to uncover **insights into**:

Platform performance

Content consumption trends

Subscriber growth patterns

Inactivity behavior

Upgrade/Downgrade movements

🎯 These insights will play a crucial role in guiding post-merger strategies, optimizing content offerings, and positioning Lio-Jotstar as India’s #1 OTT platform.

📈 I, Guru Dayal Saran as a Data Analyst at Lio, lead this analytical initiative to empower smarter, data-driven decisions for a bold new future in streaming.

---

## 🎯 Project Goals  

  - **🔍 Data Understanding & Exploration**:
    - Thoroughly review the dataset and its metadata to understand structure, relationships, and key variables.

  - **📑 Question-Driven Analysis**:
    - Refer to the questions that stakeholders have to guide the core analysis. Use tools like MySQL and Power BI to answer these questions effectively.

  - **📊 Dashboard Development**:
    - Design a comparative and interactive dashboard showcasing critical metrics for both LioCinema and Jotstar. Ensure it is visually intuitive and self-explanatory for non-technical stakeholders.

  - **📈 Executive Presentation**:
    - Develop a compelling presentation that highlights insights, trends, and data-backed recommendations.

  - **💡 Extended Analysis**:
    - Go beyond the given questions by identifying new areas of investigation based on data patterns and business needs.

  - **🎥 Creative Communication**:
    - Present findings through an engaging video presentation to enhance clarity, impact, and stakeholder engagement.



---

## 🛠️ Tools and Technologies Used

- **MySQL**: The main tool utilized for securely storing and delivering platform data from the databases.
- **Power Query Editor**: For data extraction, transformation, and loading (ETL) processes. It helps in cleaning and preparing data from various sources.
- **Power BI Desktop**: For summarizing, analyzing, exploring, and presenting data through creating interactive reports and dashboards that effectively communicate data insights. 
- **Power BI Servie**: To share the reports to stakeholders and embed in MS powerpoint.
- **MS Powerpoint**: To make Presentation with answers and Data-backed recommendations and record video.
- **Canva**: Used for designing logos.
---

## 🔬 Techniques & Process Followed

1. **Data Extraction and Transformation**:
   - Retrieved LioCinema and Jotstar datasets from their respective MySQL databases.
   - Cleaned and transformed the data using Power Query Editor by removing duplicates, addressing missing values, and standardizing fields to maintain data quality and consistency.
   - Loaded all tables into the data model and established relationships to consolidate the datasets for seamless analysis.


2. **Data Modeling**:
   - [Connected dimension tables and fact tables](https://github.com/SaranEranki/Pre-Merger-Analysis-Codebasics-PowerBI/blob/main/Lio_Jotstar%20Data%20Model.png) by implementing snowflake schema.
   - Created calculated columns and DAX measures to derive key metrics and enhance data analysis.

3. **Exploratory Data Analysis (EDA)**:
   - Used different visuals and charts to summarize and analyze the data.
   - Applied drill-down and cross-filtering techniques to uncover deeper, hidden relationships within the data.   
   - Utilized aggregation functions, segmentation, and trend analysis to compare key metrics between LioCinema and Jotstar.
   - Leveraged dynamic field parameters and slicers to enable real-time filtering and customized drill-through insights.

4. **Multiple Views**:
   - Organized visuals into separate view pages to ensure easy navigation and a smoother exploration experience.
   - Incorporated attractive icons for each view page and implemented page navigation actions to enhance user interactivity.


5. **Appealing Design**:
   - Designed reports focusing on business users, making them visually intuitive and easy to understand for non-technical stakeholders.
   - Built a dedicated filter panel to enable seamless self-exploration and improve user experience.


---

## 📑Views and 🔎Insights

<br> 

### 🎞️ Content Library View (Content Library Analysis):
#### Content Comparison: Jotstar vs. LioCinema
  - **Content Volume**: Jotstar offers nearly **double** the content compared to LioCinema.
  - **Genres & Languages**: Jotstar provides a broader selection of genres and languages than LioCinema.
  - **Language Distribution**:
    - **Jotstar**: Predominantly features content in **English**.
    - **LioCinema**: Primarily offers content in **Hindi**.
  - **Content Type**: Both platforms have the highest volume of **movie-type** content.

<br>

### 👥 Subscriber View (Subscriber Insights):  

  - Total users on **LioCinema** and **Jotstar** are **183K** and **45K**, respectively.
  - The growth rate of **LioCinema** is **23 times** that of **Jotstar**.
  - User distribution across different parameters shows:
    - **LioCinema**:
      - 57% are **Free users**
      - 43% are from **Tier 3** cities
      - 44% belong to the **18-24** age group
    - **Jotstar**:
      - 43% are **VIP subscribers**
      - 57% are from **Tier 1** cities
      - 45% belong to the **25-34** age group (i.e., working class)
  - The **current paid user percentage** of **Jotstar (71%)** is **significantly higher** than that of **LioCinema (35%)**.


<br>

### ⛔ Inactivity View (Inactivity Analysis):  

  - Inactive users in **LioCinema (45%)** are significantly higher compared to **Jotstar (15%)**.
  - **Free** users, the **18-24** age group, and **Tier 3** users are the most **inactive** across **both** platforms.
  - However, an **inactivity rate of 18%** among **Premium** users highlights a lack of engaging content on **LioCinema**.
  - Despite having a large user base, the **low watch time** and **inactivity patterns** in **LioCinema** suggest that **less engaged users are more likely to become inactive**.


<br>

### ↕️ Upgrade / Downgrade View (Upgrade & Downgrade Analysis):  

  - The trends clearly indicate that **upgrades** are **higher** on **Jotstar**, while **downgrades** are more **prevalent** on **LioCinema**.
  - **Jotstar** records the **highest upgrade rate** among users in **Tier 2** cities, the **45+** age group, and among **VIP** subscribers.
  - **LioCinema** has the **highest downgrade rate** among users in **Tier 1** cities, the **18-24** and **25-34** age groups, and **Premium** subscribers.

<br>

### ⌚ User Engagement View (Content Consumption Behavior):  

  - The **lower** average watch time on **LioCinema** (60 hours) compared to **Jotstar** (352 hours) suggests that **_LioCinema users are less engaged_**.
  - **Premium** users and users from **Tier 1** cities have the highest content consumption across **both** platforms.
  - **Jotstar** sees the **highest** watch time in the **18-24** age group, while **LioCinema** has the **highest** watch time across both the **18-24** and **25-34** age groups.
  - On **both** platforms, a **significant** majority of users (**50% or more**) **preferred** watching content on **mobile** devices.

<br>

### 💰 Finance View (Revenue Analysis):  

#### I went a step further and analyzed revenue as well by:

  - Creating new tables and appending the updated subscription plan details of the same user as new rows.  
  - Connecting to the date table using the plan change date as the new subscription start date for the new rows, and as the end date for the old rows.  
  - This allowed me to calculate the duration of each plan, multiply it by the respective prices, and then summarize the results to obtain accurate revenue figures.


#### Revenue & Demographics Comparison: Jotstar vs. LioCinema

  - **Revenue Comparison**: Jotstar's revenue is approximately **twice** that of LioCinema.
  - **Revenue Breakdown**:
    - **LioCinema**:
      - **60%** from **Basic** plans
      - **40%** from **Premium** plans
    - **Jotstar**:
      - **68%** from **Premium** plans
      - **32%** from **VIP** plans
  - **Demographic Insights**:
    - **LioCinema**:
      - Majority of revenue from the **18–24 age group** (youngsters or students)
      - Predominantly from **Tier 2 cities**
    - **Jotstar**:
      - Majority of revenue from the **25–34 age group** (earning individuals)
      - Predominantly from **Tier 1 cities**
  - **Average Revenue Per User (ARPU) Analysis**:
    - **Tier 1 city users** contribute more on **both** platforms.
    - **45+ age group users** on **Jotstar** and **34–45 & 45+ age group users** on **LioCinema** are the highest contributors.

---

## 🔗 Important Project Links 

1. 💻 [Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOWUzZTY0NzUtYmYwNi00ZjM2LTkwNGEtNmU2YzA4YTUzOGIzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=036df02ca0a7b6a34164)
2. 🎥 [Video Presentation](https://www.youtube.com/watch?v=Z-kkVwEBCtk) (Here I have given Post-Merger Recommendations)

---

## 🏁 Conclusion

The **pre-merger analysis** of **LioCinema** and **Jotstar** highlights key insights that will drive the success of their union as they aim to become India’s leading OTT platform.

- **User Growth & Engagement**:  
  - **LioCinema** has a larger user base, but **Jotstar** leads in user engagement, higher upgrade rates, and a stronger paid subscriber share.
  - Combining these strengths can help the merged entity expand both its reach and user quality.

- **Inactivity Challenges**:  
  - **LioCinema** faces higher inactivity, particularly among **Free users** and **Tier 3 cities**.  
  - Post-merger strategies must focus on content improvement and user reactivation to reduce churn.

- **Content and Revenue Strengths**:  
  - **Jotstar** offers broader genre and language variety, resulting in higher revenue, while **LioCinema** dominates in **Hindi content** and younger demographics.
  - Together, they can cater to both premium and mass markets effectively.

- **Demographic Synergy**:  
  - The merger balances **young, budget-friendly users** from LioCinema with **working, premium users** from Jotstar, covering a wider audience across age groups and cities.

- **Mobile-First Focus**:  
  - With over 50% of users preferring mobile viewing, enhancing mobile experiences will be critical for future growth.

In short, the merger of **LioCinema** and **Jotstar** offers a powerful opportunity to combine user scale, content diversity, and engagement excellence—paving the way to become **India’s #1 OTT destination**.


---


🚀 Follow me on:   

🔗 [LinkedIn](https://www.linkedin.com/in/guru-dayal-saran-eranki/)   
🐙 [GitHub](https://github.com/SaranEranki)

