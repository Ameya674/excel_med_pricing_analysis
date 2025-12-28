# Project Title: Med B vs Med A – Utilization, Outcomes, and Pricing Analysis

## Question 1
For each calendar month in the dataset (July–December 2012), what is the **total number of units used** for:
- Med A
- Med B  
across **all patients**?

---

## Question 2
For each month from **July through November 2012**, how many **unique patients** received:
- Med A?
- Med B?

---

## Question 3
For each month from **July through November 2012**, and for each medication separately, what is the **average total monthly dose per patient** (i.e., total units for that medication in that month divided by the number of patients receiving that medication in that month)?

---

## Question 4
**(a)** Among patients who **switched from Med A to Med B**, how many patients switched in each month (September–November 2012)? Define the month of switch as the month containing the patient’s **first Med B administration**, where there is evidence of Med A use before that date.

**(b)** Among patients who **started Med B** having **never previously received Med A**, how many such patients initiated Med B in each month (September–November 2012)?

---

## Question 5
For patients who **switched from Med A to Med B**, how long were they on Med A before switching?

For each such patient:
- Calculate the number of **weeks on Med A** from their first Med A administration to their last Med A administration **before** the first Med B date.  
Then report the **average number of weeks on Med A**:
- For patients who switched in **September**
- For patients who switched in **October**
- Overall across all switched patients

---

## Question 6
Focusing **only on patients who switched from Med A to Med B**:

1. For each such patient, calculate their **average total monthly dose of Med A** during the time they were on Med A **before switching**.  
2. For each such patient, calculate their **average total monthly dose of Med B** after switching.  
3. Report the **overall average monthly dose per patient**:
   - For Med A (pre-switch)
   - For Med B (post-switch)

---

## Question 7
Assume that **Med A costs \$1 per 100 units**.

Using the **average monthly doses** from Question 6, what **per-unit price for Med B** would make the **monthly cost per patient** the same for Med A and Med B (i.e., the **breakeven price per unit** for Med B)?

---

## Question 8
Among patients who **switched from Med A to Med B**, how does the **average total monthly dose per patient** change when they move from Med A to Med B?

Report this change **by month of switch** (e.g., patients who switched in September vs October) and comment on how much the total dose decreases when patients move from Med A to Med B.

---

## Question 9
For patients who switched from Med A to Med B, define:

- **First Med B dose** = total Med B units in the **month of the first Med B administration**  
- **Second Med B dose** = total Med B units in the **following calendar month**

For each such patient, compare the **second Med B dose** to the **first Med B dose** and classify them as:
- **Same** (second dose = first dose)
- **Higher** (second dose > first dose)
- **Lower (non-zero)** (0 < second dose < first dose)
- **No second dose** (no Med B use in the month after the first-dose month)

Report, for patients who switched in **September** and in **October**, the **number and percentage** of patients in each category, and the same breakdown for **all switchers combined**.

---

## Question 10
Considering only **LAB B** results and only patients who switched from Med A to Med B:

- Treat LAB B draws **before the first Med B date** as occurring **while on Med A**
- Treat LAB B draws **on or after the first Med B date** as occurring **while on Med B**

For each such patient, compute:
- Their **average LAB B value while on Med A**
- Their **average LAB B value while on Med B**

Then report the **overall average** of these per-patient means:
- Average LAB B while on Med A
- Average LAB B while on Med B

---

## Question 11
Using your results from Questions **7, 9, and 10**:

- How do the observed **changes in dose** and **LAB B values** affect your interpretation of the **breakeven price** for Med B?  
- Would you argue that Med B could be priced **at**, **above**, or **below** the pure cost-equivalence breakeven price? Why?  
- What additional data or analysis would you want to make a stronger recommendation about Med B’s pricing and positioning?
