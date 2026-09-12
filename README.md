## 📊 Total Rewards Landscape & Diagnostic | Manufacturing sector | PBI

### Author: Vo Tran Mai Khanh
### Date: 09/2026

## 📌 Background & Overview

### 📖 Objective
- Examine internal compensation landscape and surface underlying signals within it
- Determine whether current pay and bonus practices produce meaningful differentiation between performance levels
- Assess whether these practices have measurable effect on employee retention and motivation
- Establish whether reward system is functioning as intended before recommending structural changes

### 👤 Who is this project for?
- HR leadership and Total Rewards function, responsible for design, calibration and governance of the reward system
- Business unit leaders overseeing Production & Operations and other core job families, where the findings carry most direct operational implications
- Decision makers evaluating compensation structure, bonus formula design and retention strategy

### 👤 Client Background
The Vietnam based manufacturing company operates a domestic production facility manufacturing industrial and construction materials. This workforce is organized across job families including Production & Operations, Engineering/Technical, Finance & Accounting, Supply Chain/Logistics and HR & Admin/Support, with Production & Operations serving as the core department directly tied to output. Performance is tracked at individual employee level through compensation, KPI achievement performance rating and tenure, giving visibility into how pay and performance dynamics vary across departments and drive workforce outcomes such as retention

### 📊 Data Structure & Relationships

#### 1️⃣ Tables Used:
- Payroll & KPI table: contains over 4,000 rows, structured as a per pay period snapshot for each employee. Each row captures full compensation details, KPI achievement, performance rating, tenure and core employee attributes for that period. 
- Dimensions tables: Date, Job Family and related reference tables which provide the categorical and time based context needed to slice the analysis across years, job families and performance/compensation bands

#### 2️⃣ Table Schema & Data Snapshot

#### Table 1: Payroll & KPI
<img width="856" height="593" alt="image" src="https://github.com/user-attachments/assets/33b2786c-f0d2-4ef1-bc21-43a070f9a580" />

<img width="877" height="91" alt="image" src="https://github.com/user-attachments/assets/cb346378-9bb3-42c7-ab9e-ffcac9f9a2d0" />

<img width="890" height="110" alt="image" src="https://github.com/user-attachments/assets/3a2b70a2-ddb2-4ef3-8788-2ad03d99ffed" />

#### Table 2: Dim date

<img width="515" height="595" alt="image" src="https://github.com/user-attachments/assets/36359275-3f77-4c1d-94be-f290e3647381" />

#### Table 3: Dim job family

<img width="338" height="595" alt="image" src="https://github.com/user-attachments/assets/04f3725e-50e1-49ac-b665-02710e08809c" />

#### Table 4: Dim title

<img width="282" height="479" alt="image" src="https://github.com/user-attachments/assets/c7a9a01e-acee-4eb5-99b7-4233eb743767" />

#### Table 5: Dim position

<img width="415" height="594" alt="image" src="https://github.com/user-attachments/assets/7c195bae-2836-4d68-9dba-86c9e7908b0e" />

## 📊 Key Insights & Visualizations

### 1️⃣ Total Rewards Landscape & Diagnostic (2024 vs 2025)

#### 2024 Snapshot

<img width="632" height="542" alt="image" src="https://github.com/user-attachments/assets/bfe8dafb-589f-4907-851d-8ad4edf27602" />

#### 📌 Analysis 1. Compensation Mix Shifts Steadily Toward Fixed Pay
Total compensation structure includes SI salary (base), employer SI contribution, OT + Leave bonus, 13th salary and KPI bonus. Total comp per employee has grown from 33.43% of the mix in 2022 to over 54% in 2024, while KPI bonus has steadily shrunk from 27.22% to around 21 - 24%. In absolute terms, total comp per employee is essentially flat between 2024 (62.10M₫) and 2025 (60.96M₫) but fell 40.4% from 2023 to 2024. Given the large net headcount increase that year (268 new hires), this is most likely a dilution effect since new hires joining mid year are counted as full headcount despite earning only partial year pay rather than a real cut to individual compensation

#### 📌 Analysis 2. Core Production Function Under Weighted on Variable Pay
Company-wide, fixed & variable pay ratio split is healthy and stable (~62% / ~38%) in both years. By job family, however, Production & Operations which os the core output generating function carries the lowest variable share of any family in 2024 (35.53%), trailing back office functions like Finance & Accounting and Engineering/Technical (~40%). This is the inverse of typical incentive design, where output linked roles usually warrant heavier variable weighting. 2025 shows partial correction (Production rises to 38.24%), while HR & Admin/Support drops sharply to 31.74%

