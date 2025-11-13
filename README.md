# Workforce-intelligence-burnout-analysis
Power BI and SQL project analyzing workforce productivity, wellness, and burnout risk.
# Strategic Workforce Intelligence Report  
### Productivity, Wellness, and Burnout Risk  
**by Pranitha Sree**

---

## Project Overview  
This project focuses on understanding how workforce productivity connects with employee well-being and burnout risk.  
It demonstrates an end-to-end analytics workflow — from data generation in Python to SQL integration and Power BI dashboarding — to simulate a realistic HR analytics environment.  

The aim was to identify measurable patterns behind employee stress, engagement, and performance, and to translate them into actionable insights for decision-makers.  

---

## Objective  
To analyze and visualize **workforce productivity and burnout risk** using HR-related data.  

Specific goals included:  
- Identifying the factors influencing **employee stress, well-being, and performance**  
- Quantifying burnout risk using a **probabilistic Python model**  
- Developing a **Power BI dashboard** that presents clear, actionable insights  

---

## Project Workflow  

### Phase 1: Data Generation (Python)  
- Created a **synthetic HR dataset** of 800 employees using NumPy and Pandas  
- Developed four structured CSV files:  
  - `employee_info.csv` – Employee demographics  
  - `workload_metrics.csv` – Hours, projects, remote days  
  - `performance_metrics.csv` – Performance score, goals, training  
  - `wellness_survey.csv` – Stress, sleep, work-life balance, burnout risk  
- Applied a custom formula to calculate burnout probability based on stress level, work-life balance, and working hours  

### Phase 2: Database Integration (SQL)  
- Designed a **MySQL database** named `burnout_analysis`  
- Imported the four datasets into relational tables linked by `EmployeeID`  
- Verified data consistency, joins, and record counts  
- Prepared the final dataset for Power BI connection  

### Phase 3: Dashboard Development (Power BI)  
- Built a **three-page interactive dashboard** with professional visuals and navigation  
- Added **DAX measures** for metrics such as Burnout Index, Burnout Rate, and High-Risk Count  
- Used conditional formatting and interactive slicers for clarity and analysis depth  

---

## Dashboard Structure  

### 1️⃣ Executive Overview  
Presents organizational health indicators and summary KPIs:  
- Burnout Rate: **2.75%**  
- Average Burnout Index: **25.9**  
- Average Stress Level: **3.3 / 10**  
- Wellness Score: **86**  
- High-Risk Employees: **22**
(Visuals/Executive overview.png)


### 2️⃣ Workforce Productivity & Burnout Analysis  
Examines how workload factors relate to burnout:  
- Scatter: Average Weekly Hours vs Burnout Index  
- Heatmap: Stress vs Sleep Quality  
- Bar: Work-Life Balance vs Burnout Index  
- Line: Training Hours vs Burnout Rate  

### 3️⃣ Department & Performance Insights  
Highlights departmental and role-level variations:  
- Marketing, Finance, and HR show the highest burnout levels  
- R&D and Finance maintain strong performance despite moderate burnout  
- Technical roles (Engineers, Analysts) show lower burnout risks  

*(Visuals can be inserted here)*  

---

## Key Insights  

1. **Overall Workforce Health**  
   - Burnout rate of 2.75% with moderate burnout intensity (avg index 25.9)  
   - Balanced stress (3.3/10) and wellness (86) scores  

2. **Department-Level Trends**  
   - Marketing, Finance, and HR show the highest burnout risk  
   - IT, Operations, and Sales departments demonstrate better balance  

3. **Burnout Drivers**  
   - Stress > 4.0, Sleep < 8.5, and Work Hours > 45 strongly correlate with burnout  
   - Training hours improve engagement and don’t contribute to burnout  

4. **Role-Based Insights**  
   - HR Managers, Finance Managers, and Sales Executives show the highest risk  
   - Technical roles (Analysts, Engineers) remain more resilient  

5. **Performance Observations**  
   - R&D and Finance show strong performance despite moderate burnout  
   - Persistent burnout-performance gap may lead to long-term fatigue  

---

## Strategic Recommendations  

- **Target High-Risk Departments:** Focus wellness and workload initiatives in Marketing, Finance, and HR  
- **Promote Healthy Work Hours:** Implement flexible schedules for employees exceeding 45 hours per week  
- **Strengthen Engagement:** Conduct regular surveys and workshops on stress and sleep management  
- **Continuous Monitoring:** Track burnout and performance metrics quarterly to identify early warning signs  

---

## Tools & Technologies  

| Category | Tools Used |
|-----------|-------------|
| Data Generation | Python (NumPy, Pandas) |
| Database Management | MySQL |
| Visualization | Power BI |
| Data Modeling | DAX |

---

## Author  
**Pranitha Sree**  
Business Analyst | HR Analytics | Data Visualization  
> Focused on transforming complex workforce data into insights that support people-first decision-making.  

---

## Files Included  
- `Strategic_Workforce_Intelligence_Report_Pranitha_Sree.docx`  
- Power BI dashboard visuals (screenshots)  


---

*This project represents a complete HR analytics workflow — combining technical skills with business interpretation to deliver actionable workforce intelligence.*  

