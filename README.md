# Data-Job-Market-End-To-End-Analysis-Project

This project analyses roughly 500,000 tech job postings from the 2024 DataNerd.com data job dataset to understand trends within the current data and tech job market. This analysis pipeline combines exploratory data analysis, data cleaning, deep analysis, and dashboard building.

## Project Backgorund / Motivation

I’m currently studying Computer Science and Statistics, and I wanted to move past theoretical learning and see what the market actually demands. This dataset of data and tech job postings gave me a realistic way to investigate questions like:

- How do salaries compare between different roles and locations?
- How available are remote or hybrid positions?
- Which technical skills are most in demand for each role?
- What's the split between junior, mid, and senior roles?

### This project demonstrates the following essential data analytics skills:

- Full technical process explained [here](PROCESS.md)
- **Data Cleaning:** Cleaning & transforming data with Power Query, Excel, and Python (Pandas).
- **SQL (MySQL):** Building a repeatable SQL based workflow.
- **Exploratory Data Analysis:** Performing EDA with Python (Pandas).
- **Visualisations:** Creating interactive visualisations with Power BI that clearly communicates insights for a non-technical audience.


## Database Structure of Cleaned Dataset
My transformed & created database structure as seen below in the Entity Relationship Diagram consists of four tables: job_postings, job_skill_connector, job_skills, and job_skill_categories, with a total of 477,778 job postings.
![alt text](Images/data_jobs_erd.jpg)

Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarization with the dataset.

# Executive Summary
Rather than doing a simple surface level summary, I analysed the data to find answers and insights to the four "Executive Questions" that I designed to help guide my own career path. The full, in-depth analysis with graphs and visualisations can viewed [here](ANALYSIS.md).

## Overview of Findings
- **Technical Depth Rewards:** The data job market heavily rewards techincal depth, where more technical roles like ML and Data Science are offered the highest salaries due to their difficulty. 
- **Data Engineering Paradox:** While the Data Engineering role dominates in volume, it faces a talent shortage due to the steep learning curve that isn't always compensated with proportional pay.
- **Industry Skill Demand:** The industry remains anchored by foundational skills, with Python and SQL required for over 50% of all roles, and a growing emphasis on technical depth over a broad, shallow toolkit.
 especially foundational skills like Python & SQL, which are required for over 50% of all roles.
- **Seniority-Driven Market:** The market is becoming increasingly seniority-driven, favouring experienced professionals (mid-level & senior) 31:1 over juniors.
- **Geographical Education Emphasis:** Geographically, the U.S. acts as a global market distributor with 78% of job postings not requiring a degree, prioritising skill mastery, which contrasts with European job markets like the U.K. and Poland, where over half of roles still require a formal education.



## Deep-dive Analysis Executive Questions' Key Insights:
Each Executive Question has its own interactive dashboard created with Power BI. The entire interactive dashboard along with specific executive question dashboards can be downloaded here.

### Role Comparison Analysis Key Insights Summary:

- **Complexity Premium:** Data Scientists, Software & ML Engineers offer the market's best technical ROI, rewarding professionals who master the industry's most difficult technical skills and concepts the highest compensation in pay. These salaries can dramatically increase as professionals advance in seniority.
- **Data Engineer Volume Trap:** Despite Data Engineering roles having the most market share, it has the lowest total technical ROI. This is due to the role's complexity and requirements. There aren't enough people willing to endure the learning curve, leaving the industry with a shortage of Data Engineers.
- **Analyst Career Pivot:** Between Business & Data Analaysts, Data Analytics yields a higher return on investment when it comes to both salary and job opportunities. But because of these role's low complexity, their base salaries are typically lower. So as analysts progress in their career, many would eventually switch over to Data Science for salary growth.
- **Data Analysts Vs. Data Scientists Skillset:** Roughly 70% of a Data Analyst's technical skillset is applicable to Data Science. The remaining 30% consists of machine learning libraries and advanced statistical modeling. These more technical skills are what differentiates a Data Analyst from a Data Scientist, and is rewarded with a higher salary.
- **Role Remoteness:** Technically heavy roles Engineers have the largest remote market as their roles focus on independent technical execution and involve fewer client-facing meetings. Business intelligence roles like Analysts are responsible for informing stakeholders about insights and presenting strategies, which require in-person collaboration to ensure clear communication. So these roles have a smaller remote market.
- **Remote Vs. Onsite Pay:** The technically heavy roles Engineers have a "Remote Premium" as companies compete globally for technical talent. Analysts, however, are often offered higher onsite salaries, to compensate for cost of living expenses and physical presence requirements for client meetings.
- **Degree Requirement:** Roles that involve heavy theoretical concepts often have a degree as a requirement like ML Engineers & Data Scientists. Having a degree for more applied, practical execution focused roles is a competitive advantage, but these 'applied' skills can often be self taught.


### Job Market Skills Key Inights Summary:

- **Foundational "Must-Have" Skills:** Python & SQL are the two skills that should be considered foundational skills which every candidate should have in their skillset. Lacking either skill effectively disqualifies a candidate from over half of all roles in the data tech field, regardless of seniority.
- **2024 AI Pivot:** Hugging Face emerged as the definitive trending sill of 2024 with a 322.3% growth rate. This indicates a fundamental shift in the data industry's tech stack, now focusing on Generative AI integration and agentic workflows over traditional predictive analytics.
- **Skillset Efficiency:** To to succeed in this job market, the data suggests a depth over breadth approach when it comes to learning technical skills, as 65% of job postings require five skills or fewer. To maximise efficiency, mastering 1-2 in-demand skills yields a 14x higher ROI-per-skill than a broad & shallow skillset.

### Overall Market Trends Key Insights Summary:

- **Volume Vs. Stability:** The data shows that the 2024 data job market that favours Data Science for stability and Data Engineering for sheer volume. Analyst and Engineering roles are the most volatile, meaning their hiring is highly reactive to immediate business needs and seasonal shifts.
- **Seniority Pivot:** The data job market in 2024 was increasingly favouring more experienced workers as the year went on to potentially cut down training & liability costs.
- **Hiring Seasonality:** The market has three distinct phases: a Q1 Peak (Jan-Feb), a Mid-Year Surge (July), and a Pre-hiring Window (December). The 124.7% spike in December indicates companies are preparing a month before budgets officially reset for the next year.


### Geographical Influences Key Insights Summary:

- **Global Tech Hubs:** The U.S. claims the "Global Tech Hub" title due to its sheer volume of job postings and companies. Secondary tech hubs include several European nations, India, and Singapore for East/South East Asia.
- **Global Opportunity Density:** Smaller and emerging markets like El Salvador and Guam have the highest job-per-company density, while more developed job markets (U.S., India, Several European Countries) have a substantially higher volume of job postings and unique companies, despite not having as high of a density.
- **Cultural Adoption Divide:** Asian job markets have lower remote job adoption rates likely due to deeply rooted onsite traditions, while western markets are less conservative and have higher remote adoption rates.
- **Remote Pay Premium:** The average remote salary exceeds the average onsite salary due to senior roles having mroe remote positions and higher pay, skewing those averages.
- **Global Shift to "Skills-First":** Degrees are most prevalent in Europe, but globally, the market is moving towards a skills-first economy, increasingly favouring technical skills competence over holding a formal degree, all without influencing a professional's yearly salary.
- **U.S. favouring Skills over Degrees:** The global tech hub, the U.S. is favouring technical skills over a degree with over 78% of job postings not requiring a degree. Given the U.S. tech industry's market's influence on global hiring trends, this suggests that degrees may become increasingly optional for staying competitive in the data industry.