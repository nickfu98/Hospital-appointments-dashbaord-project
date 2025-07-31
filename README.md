# Hospital Appointment Dashboard - Excel Project
This interactive Excel dashboard provides insights into hospital appointment performance and operational trends. Stakeholders can filter data based on appointment dates, hospital branch, insurance provider, appointment status, and individual doctors. This dashboard allows stakeholders to monitor patterns in revenue, treatment breakdowns and no-show rates.

<img width="1292" height="749" alt="Hospital_dashboard_overview" src="https://github.com/user-attachments/assets/bae1c3de-9bd0-4ca2-b664-779d3009df1e" />

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
    - Appointment Status Breakdown

---

## Tools Used
  - **Microsoft Excel**
    - Pivot Tables
    - Xlookup(), Index(), Match()
    - Slicers & Timelines
    - Combination charts & stacked visuals
  - **Synthetic Hospital Data**

---

## Questions Answered
  - Which treatments are the highest earning over time?
      - MRIs, X-Rays, and Chemotherapies were the highest earning treatments overall.
  - Which doctors or hospital branches have the highest no-show rates?
    - Central Hospital (31%) had the highest no-show rate, whereas Eastside Clinic (21%) had the lowest.
    - The doctors with the highest no-show rates were David Jones (36%) and Sarah Smith (35%), whereas Jane Davis (5%) and Robert Davis (15%) had the lowest.
  - How do no-shows trend over time?
    - There is no clear pattern throughout the year however the average no-show rate for the year is 26%. February (40%), October (36%), and June (33%) have the highest no-show rates while March (16%), December (17%), April (20%), and August (20%) have the lowest.
  - Which hospital branches are generating the most revenue and from which treatments?
    - Westside Clinic generates the most revenue ($47,981) on **completed** appointments, primarily from Physiotherapy appointments. Central Hospital ($40,257) and Eastside Clinic ($35,861) generate less revenue overall, with ECGs (Central) and MRIs (Eastside) being their top grossing treatments. Chemotherapy is the 2nd highest grossing treatment for Eastside and Westside Clinics, but the lowest for Central Hospital. 
<img width="1290" height="746" alt="top_grossing_hospital_branch" src="https://github.com/user-attachments/assets/24c09097-232d-4d2a-bb39-ddd5705f4ec9" />


  
--- 

## Key Takeaways and Recommendations
  1. Westside Clinic is the top revenue generating branch, especially from ECGs and the least amount from Chemotherapies
    - Continue to invest in equipment and staff capacity at Westside Clinic to maintain growth.
    - Replicate successful treatment practices and offerings at Central Hospital and Eastside Clinc to balance load and increase revenue at those branches as well.
    - Prioritize ECGs and Physiotherapy across the board for marketing campaigns and monitor demand to reduce issues providing these treatments.
  3. February, October, and June have the highest no-show rates. Urgency in reducing no-show rates is a must
    - Introduce automated reminder systems (text messages, emails, and calls) 24-72 hours before appointments to ensure patients are being notified of upcoming. appointments
    - Create standby waitlists for doctors with high no-show rates to fill cancellations and no-show openings.
    - Identify reasons for no-show rate spikes in February, October, and June (seasonal, staffing gaps, location-based factors, etc).
  4. David Jones and Sarah Smith have the highest no-show rates amongst doctors
    - Reinforce automated reminder systems stated above, especially for these doctors.
    - Provide training to front desk staff and use patient surveys to increase patient commitment and understanding.

