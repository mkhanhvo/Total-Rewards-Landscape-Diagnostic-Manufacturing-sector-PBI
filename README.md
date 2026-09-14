<img width="1024" height="926" alt="image" src="https://github.com/user-attachments/assets/0428c5b4-649e-4e90-876e-1c7c459f9711" />

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

#### Table relationship

<img width="769" height="491" alt="image" src="https://github.com/user-attachments/assets/5f9ed9e9-f611-4fd3-8c78-2368a57d85f7" />

#### Table 1: Payroll & KPI

<img width="1064" height="601" alt="image" src="https://github.com/user-attachments/assets/1e10394a-805d-4d37-a6b8-e90003b3ef23" />

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

#### *2024 Snapshot*

<img width="632" height="542" alt="image" src="https://github.com/user-attachments/assets/bfe8dafb-589f-4907-851d-8ad4edf27602" />

#### *2025 Snapshot*

<img width="633" height="542" alt="image" src="https://github.com/user-attachments/assets/597a6791-5f4e-44d8-a484-b419ee11b3e0" />

#### 📌 Analysis 1. Compensation Mix Shifts Steadily Toward Fixed Pay
Total compensation structure comprises base salary, allowance, KPI bonus, employer side statutory insurance contributions, 13th salary overtime and leave pay . Base salary's share of the mix has risen from 33.43% in 2022 to over 54% in 2024 while KPI bonus has contracted correspondingly, from 27.22% to approximately 21 - 24%. In absolute terms, total compensation per employee is materially unchanged between 2024 (62.10M) and 2025 (60.96M), following a 40.4% decline from 2023 to 2024. Given the substantial net headcount growth that year (268 new hires), this decline is most plausibly attributable to a dilution effect - employees joining mid year are counted as full headcount despite receiving only partial year pay rather than a genuine reduction in individual compensation

#### *2024 context*

<img width="867" height="230" alt="image" src="https://github.com/user-attachments/assets/0f43352a-0d00-4ebd-beff-e68d2305f775" />

#### *2025 context*

<img width="868" height="394" alt="image" src="https://github.com/user-attachments/assets/6d327ea5-fb6f-49f9-a6d4-be0ea41791a8" />

#### 📌 Analysis 2. Core Production Function Under Weighted on Variable Pay
At  organization level, fixed pay & variable pay ratio is healthy and stable at approximately in both years. By job family, however, Production & Operations which is the core output generating function carries the lowest variable pay share of any family in 2024 at 35.53%, trailing functions such as Finance & Accounting and Engineering/Technical (both nearly 40%). This is inconsistent with conventional incentive design, under which output linked roles typically warrant a heavier variable weighting. The gap narrows in 2025 as Production rises to 38.24%, while HR & Admin/Support declines sharply to 31.74%, a shift meriting further review

#### *2024 context*

<img width="434" height="168" alt="image" src="https://github.com/user-attachments/assets/08282347-19b5-4bd1-90f2-75281444b751" />

#### *2025 context*

<img width="434" height="167" alt="image" src="https://github.com/user-attachments/assets/9fa398de-5262-4cd7-a0bd-809daa87e3e2" />

#### 📌 Analysis 3. Payout Ratios Show Seasonal Timing Distortion
Every job family recorded a sharp payout spike in March 2024 (115 - 178%), a pattern sufficiently uniform across unrelated departments to suggest a shared timing event, likely Tet related adjustment rather than genuine overperformance. Outside of March, most job families held a healthy 85 - 100% range but Production & Operations was the exception, ranging from 178.4% to 60.5% within the same year with the widest swing observed across all families. In 2025 the same spike is absent and replaced instead by a broad dip across February - March that recovers by June

#### *2024 context*

<img width="896" height="177" alt="image" src="https://github.com/user-attachments/assets/67edf7ac-c4b4-42b8-b178-451904d75f31" />

#### *2025 context*

<img width="895" height="175" alt="image" src="https://github.com/user-attachments/assets/f5e6e25d-77fc-48a6-90a3-2c518c3d9ad3" />

#### 📌 Analysis 4. Bonus System Fails to Differentiate Performance
Every job family in 2024 & 2025 falls below the 1.5x threshold that denotes effective differentiation between high and low performers. The trend is deteriorating that five of six families sit below 1.0 in 2025, indicating bottom quartile performers receive higher median bonus than top quartile performers compared with four in 2024. Read against KPI Distribution which shows an extreme concentration near 100% achievement in both years, this lack of differentiation is partly structural with the workforce clustered almost entirely at a single performance level, little genuine variance remains for any bonus formula to act on

Besides that, a comparison of median bonus against median base salary reveals mechanism underlying the low differentiation observed above: in most job families, bottom KPI quartile group holds a higher median base salary than top KPI quartile group (Engineering/Technical: 11M vs 9M in 2024, HR & Admin: 10M vs 8M) and frequently receives comparable or greater bonus as well. This indicates that both salary positioning and bonus payout are governed by tenure and internal seniority rather than by performance in the current review cycle

#### *2024 context*

<img width="898" height="190" alt="image" src="https://github.com/user-attachments/assets/a0eaf72b-3fc8-403d-9e2c-038c5034783c" />

#### *2025 context*

<img width="899" height="188" alt="image" src="https://github.com/user-attachments/assets/fe506f0f-035f-4c35-bc6c-6ab16f353f9a" />

### 2️⃣ From Reward Structure to Retention Impact

#### *2024 snapshot*

<img width="943" height="478" alt="image" src="https://github.com/user-attachments/assets/c98baa02-b322-4c96-bcaa-418a25f4e2dc" />

#### *2025 snapshot*

<img width="945" height="485" alt="image" src="https://github.com/user-attachments/assets/1924edc4-45a9-4719-ab52-39585350ed8a" />

#### 📌 Analysis 5. Turnover Concentrated Among Well Paid Staff

#### *2024 Production & Operations snapshot*

<img width="946" height="488" alt="image" src="https://github.com/user-attachments/assets/52a9dc75-9d4d-4841-8370-f310df07c3ae" />

#### *2025 Production & Operations snapshot*

<img width="942" height="485" alt="image" src="https://github.com/user-attachments/assets/c0e5ed15-8da9-4ec6-ae5e-e99dcbca3745" />

#### *2024 Engineering/Technical snapshot*

<img width="947" height="490" alt="image" src="https://github.com/user-attachments/assets/de4e3682-8c93-4de0-b403-39b22ba89e5f" />

#### *2025 Engineering/Technical snapshot*

<img width="945" height="492" alt="image" src="https://github.com/user-attachments/assets/e7d2e0c5-5e21-4ed4-8aa1-144b010e5e64" />

Voluntary turnover peaks first in lower half compa ratio band (80 - 100%) and second in high compa ratio band (> 120%) in both 2024 & 2025 - segments already compensated at or above their internal salary range position. In Production & Operations, this pattern holds across both years and intensifies markedly in 2025 (lower half compa ratio band: 2.2% to 39.2%; high compa ratio band: 1.0% to 31.5%). Engineering/Technical exhibits the inverse trajectory: turnover was concentrated in the low compa ratio band in 2024, a pattern consistent with underpaid staff exiting before converging by 2025 onto the same well compensated segments observed in Production. Once departures shift from underpaid to well paid, tenured staff, compensation level no longer functions as an effective retention lever

#### 📌 Analysis 6. Underperformance Rising in High Turnover Segments
Within Production & Operations, the share of Below Expectation ratings has risen in exactly the compa ratio bands where voluntary turnover is highest - from 22.97% to 31.03% in lower half compa ratio band and from 12.5% to 13.01% in high compa ratio band while a previously clean low compa segment, at 100% Meets Expectation in 2024, developed a 19.79% Below Expectation share by 2025. Taken together with the 1 - 3 year tenure band standing out as the peak of voluntary attrition across every cut examined, the evidence points to a self reinforcing cycle: the absence of meaningful bonus differentiation erodes engagement, the erosion of engagement manifests as declining performance and the organization's most capable employees choose to exit rather than remain and underperform

### 🔎 Recommendation
- Address recalibrate KPI ratings since redesigning the bonus formula alone will not produce differentiation while ratings remain compressed
- Decouple bonus calculation from tenure and salary band position - a performance linked bonus requires its own calculation logic, independent of an employee's existing position within the pay structure
- Rebalance variable pay weighting for Production & Operations against manufacturing sector benchmarks, given its combination of the lowest variable share and the highest payout volatility across job families
- Verify March 2024 payout spike with the payroll function before attributing it to performance, given the likelihood of a scheduled adjustment rather than genuine overperformance
- Prioritize retention interventions in Production & Operations and Engineering/Technical, specifically among 1–3 year tenure cohort and the 80 - 100%/above-120% compa ratio segments, the precise profile of employees currently exiting despite competitive pay.
