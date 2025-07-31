# Hospital Appointment Dashboard - Excel Project
This interactive Excel dashboard provides insights into hospital appointment performance and operational trends. Stakeholders can filter data based on appointment dates, hospital branch, insurance provider, appointment status, and individual doctors. This dashboard allows stakeholders to monitor patterns in revenue, treatment breakdowns and no-show rates. 

<img width="1292" height="749" alt="Hospital_dashboard_overview" src="https://github.com/user-attachments/assets/bae1c3de-9bd0-4ca2-b664-779d3009df1e" />

---

## Data Summary
This dashboard uses a synthetic dataset detailing 200 appointment records from 2023 including appointment status, treatment types, doctor, branch, and revenue from the following tables:
  - `appointments`
  - `patients`
  - `doctors`
  - `treatments`
  - `billing`

---

## Goal
Equip hospital administrators and operations stakeholders with a dynamic tool to:

- Track appointments by **hospital branch, provider, appointment status, and doctor**
- Identify **high revenue** treatments and services
- Monitor and reduce **no-show rates**
- Understand patient flow and **appointment status trends**

---

## Dashboard Features

  - **Timeline Filter** for date-based analysis. *This dataset only encompasses 2023*
  - **Slicers** for dynamic filtering based on:
    - Hospital Branch
    - Insurance Provider
    - Appointment Status
    - Doctor
  - **Key visualizations:**
    - Total Revenue by Hospital Branch and Treatment Type
    - Total Revenue by Treatment Type
    - Daily No-Show Rates
      -  *Note: The Daily No-Show Rate chart is based on calculated values outside of the pivot table and is not controlled by slicers. This was chosen to allow for more flexible aggregation at the daily level*
    - Appointment Status Breakdown

---

## Tools Used
  - **Microsoft Excel**
    - Pivot Tables
    - XLOOKUP(), INDEX(), MATCH()
    - Slicers & Timelines
    - Combination charts & stacked visuals
  - **Synthetic Hospital Data**

---

## Questions Answered
**1. Which hospital branches are generating the most revenue and from which treatments?**
  - Westside Clinic generates the most revenue ($47,981) on **completed** appointments, primarily from Physiotherapy appointments. Central Hospital ($40,257) and Eastside Clinic ($35,861) generate less revenue overall, with ECGs (Central) and MRIs (Eastside) being their top grossing treatments. X-Rays generate relatively low revenue for Eastside ($812) and Westside Clinics ($1955).

<img width="1288" height="747" alt="top_grossing_hospital_branch" src="https://github.com/user-attachments/assets/fffdee68-63f3-4c5c-8f05-847fa3e44f80" />



**2. How do no-shows trend over time?**
  - The average no-show rate for the year is 26%. January (40%), October (36%), and June (33%) have the highest no-show rates while March (16%), December (17%), April (20%), and August (20%) have the lowest. January's high no-show rate may be attributed to holiday season disruptions and scheduling conflicts.

<img width="1291" height="744" alt="January_highest_no_show_month" src="https://github.com/user-attachments/assets/bf72ebdf-fc53-4eb3-9576-763d0352919b" />



**3. Which doctors or hospital branches have the highest no-show rates?**
  - Central Hospital (31%) had the highest no-show rate, whereas Eastside Clinic (21%) had the lowest.
  - The doctors with the highest no-show rates were David Jones (36%) and Sarah Smith (35%), whereas Jane Davis (5%) and Robert Davis (15%) had the lowest. David Jones and Sarah Smith are both doctors at Central Hospital, contributing to the top no-show rates among branches and doctors.

<img width="1284" height="746" alt="doctors_highest_no_show" src="https://github.com/user-attachments/assets/84c1e26a-5363-41ce-9815-8d2d7f9fc2fa" />



**4. Which treatments are the highest earning over time on **completed** appointments?**
  - Physiotherapy, Chemotherapy, and MRIs were the highest earning treatments overall.
--- 

## Key Takeaways and Recommendations
  1. Westside Clinic is the top revenue generating branch, especially from Physiotherapy
    - Continue to invest in equipment and staff capacity at Westside Clinic to maintain growth.
    - Replicate successful treatment practices and offerings at Central Hospital and Eastside Clinic to balance load and increase revenue at those branches as well.
       - Drive X-Ray campaigns at Eastside and Westside Clinics to help close the revenue gap with Central Hospital.
    - Prioritize ECGs and Physiotherapy across the board for marketing campaigns and monitor demand to reduce issues providing these treatments.
  2. January, October, and June have the highest no-show rates. Reducing no-show rates should be a top priority
    - Introduce automated reminder systems (text messages, emails, and calls) 24-72 hours before appointments to ensure patients are being notified of upcoming appointments.
    - Create standby waitlists for doctors with high no-show rates to fill cancellations and last-minute openings.
    - Identify reasons for no-show rate spikes in January, October, and June (seasonal, staffing gaps, location-based factors, etc).
  3. David Jones and Sarah Smith have the highest no-show rates among doctors
    - Reinforce automated reminder systems stated above, especially for these doctors.
    - Provide training to front desk staff and use patient surveys to increase patient commitment and understanding.

