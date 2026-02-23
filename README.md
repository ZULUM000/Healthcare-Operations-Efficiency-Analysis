# 🏥 Healthcare Benchmark Dashboard (Power BI)

## Purpose

This dashboard benchmarks hospital performance using three core dimensions that matter to healthcare decision-makers:

1. **Cost efficiency** – Average Cost per Discharge
2. **Care efficiency** – Average Length of Stay (LOS Days)
3. **Operational scale** – Total Discharges (patient volume)

The goal is to help stakeholders:

* Understand how hospitals perform **relative to state and regional benchmarks**
* Identify **high-impact hospitals** where improvement efforts will matter most
* Distinguish between **case-mix driven outcomes** and **operational inefficiency**

---

## Key Definitions 

* **Average Cost per Discharge**
  The typical cost incurred for a patient episode ending in discharge.

* **Average LOS Days**
  The average number of days a patient stays in hospital before discharge.

* **State / Regional Average (ALL)**
  A benchmark calculated across all hospitals in the selected context, independent of the chosen facility.

* **% Variance vs Benchmark**
  Shows how far a hospital deviates from the benchmark:

  * **Positive (%)** → higher cost or longer stay than benchmark
  * **Negative (%)** → lower cost or shorter stay than benchmark

---

## Page 1 — Home
<img width="1737" height="806" alt="Screenshot 2026-02-23 091110" src="https://github.com/user-attachments/assets/e4e687d9-909d-4e52-b4bd-5fd85539d1e3" />

*(Navigation page)*

This page provides structured navigation to:

* LOS benchmarking
* Cost benchmarking
* Hospital-level performance profiles

No analytical conclusions are drawn here.

---

## Page 2 — LOS Comparison (Capital/Adiron)
<img width="1743" height="807" alt="Screenshot 2026-02-23 091202" src="https://github.com/user-attachments/assets/80e05140-a283-4ffa-9aef-a18d3cfb211a" />

### Headline KPIs

* **Average LOS Days:** **2.39**
* **Total Hospitals:** **15**
* **Total Discharges:** **2,542**
* **Total Surgeons:** **49**

---

### What the visuals show

* Hospitals ranked by **total discharges** (volume)
* A line overlay showing **Average LOS Days**
* Identification of **highest and lowest LOS performers**
* Key Influencers explaining **what drives longer stays**

---

### What the data is saying

* **High-volume hospitals** (e.g., Albany Medical Center, St. Peter’s Hospital) handle the largest share of discharges **without exhibiting excessive LOS**.
* Hospitals with the **highest LOS** include:

  * Aurelia Osborn Fox Memorial — **3.6 days**
  * Glens Falls Hospital — **3.5 days**
  * Nathan Littauer Hospital — **3.3 days**
* Hospitals with the **lowest LOS** include:

  * Alice Hyde Medical Center — **1.7 days**
  * St. Peter’s Hospital — **2.0 days**
  * Albany Medical Center — **2.1 days**

---

### Key influencer insight

LOS increases most strongly when:

* **Illness severity is Extreme** → **+8.96 days**
* **Mortality risk is Extreme** → **+6.09 days**
* **Mortality risk is Major** → **+2.48 days**

> Case severity, not staffing or volume alone, is the dominant driver of long hospital stays.

---

### What this means for stakeholders

* Longer LOS is often **clinically justified**, not operational failure.
* Penalizing hospitals without accounting for **severity and mortality risk** would be misleading.
* High-volume hospitals maintaining average LOS represent **strong operational performance**.

---

### Recommended actions

* Segment LOS reviews by:

  * Severity of illness
  * Risk of mortality
* Focus process improvements on:

  * **Moderate and Major cases**, where LOS is most controllable
* Avoid targeting hospitals primarily treating **extreme-acuity patients**

---

## Page 3 — Cost Comparison (Capital/Adiron)
<img width="1741" height="810" alt="Screenshot 2026-02-23 091405" src="https://github.com/user-attachments/assets/d9fbec63-141a-48c3-9b9d-601f136c67ff" />

### Headline KPIs

* **Average Cost per Discharge:** **$14K**
* **Average LOS Days:** **2.39**
* **Total Hospitals:** **15**
* **Total Discharges:** **2,542**

---

### What the scatter plot shows

* Each dot represents a hospital
* **X-axis:** Average LOS Days
* **Y-axis:** Average Cost per Discharge
* **Bubble size:** Total Discharges
* Dashed lines indicate **regional averages**

---

### What the data is saying

* Most hospitals cluster between:

  * **LOS:** ~2–3 days
  * **Cost:** ~$10K–$17K
* A small number of hospitals fall **above both LOS and cost benchmarks**, indicating potential inefficiency.
* **High-volume hospitals** tend to cluster **at or below the cost benchmark**, which is a positive efficiency signal.

---

### Key influencer insight

Average cost per discharge tends to be **lower** when hospitals operate in:

* **Capital/Adiron** → ~$9.33K
  Compared with higher-cost regions such as:
* Southern Tier (~$8.58K)
* Central NY (~$7.83K)
* Finger Lakes (~$7.78K)

> Geography and service area materially influence cost outcomes.

---

### What this means for stakeholders

* Not all high-cost hospitals are high-impact.
* The **greatest opportunity for cost reduction** lies where:

  * Cost variance is high **and**
  * Discharge volume is high

---

### Recommended actions

* Prioritize cost reviews for **high-volume, above-benchmark hospitals**
* Avoid blanket cost-cutting across regions
* Evaluate cost and LOS **together**, not in isolation

---

## Page 4 — Hospital Profile (Dynamic)
<img width="1739" height="806" alt="Screenshot 2026-02-23 091502" src="https://github.com/user-attachments/assets/cb4e08c7-6e2a-41c6-a426-65fa177acf35" />

### Example: Memorial Hospital for Cancer and Allied Diseases

### Key metrics shown

* **Average LOS:** **9.10 days**
* **Average Cost per Discharge:** **$64K**
* **State upper reference LOS:** **18.2 days**
* **State upper reference Cost:** **$128K**

---

### What the data is saying

* This hospital exhibits **longer stays and higher costs** than general hospitals.
* Discharges are concentrated in:

  * **Moderate and Minor illness severity**
  * **Moderate and Minor mortality risk**
* Patient disposition is primarily:

  * Home / Self-care
  * Home with Home Health
  * Smaller share to inpatient rehabilitation

---

### What this means for stakeholders

> The performance profile reflects **case-mix complexity**, not operational inefficiency.

This is a **specialized oncology facility**, and direct comparison to general hospitals would be inappropriate.

---

### Recommended actions

* Benchmark this hospital against:

  * Other specialty cancer centers
  * High-acuity facilities only
* Monitor:

  * Growth in major / extreme cases
  * Discharge destination trends

---

## Executive Summary (For Leadership)

* **$14K average cost per discharge** and **2.39-day LOS** define the Capital/Adiron regional baseline.
* High-volume hospitals generally demonstrate **strong efficiency**.
* LOS is driven primarily by **clinical severity**, not hospital size.
* Cost improvement efforts should focus on **high-volume outliers**, not specialty or high-acuity providers.

---

## How to Use This Dashboard

1. Start with **LOS Comparison** and **Cost Comparison** to identify outliers.
2. Use **Total Discharges (bubble size)** to prioritize impact.
3. Drill into **Hospital Profile** for context-specific interpretation.
4. Use variance metrics to guide **targeted, fair interventions**.

---

### Final note (portfolio-level quality)

This dashboard demonstrates:

* Benchmark-driven analysis
* Proper use of context-aware DAX
* Responsible interpretation of healthcare performance data
* Stakeholder-ready storytelling

---

## 📬 Contact

**Enoch Chukwuebuka**
Data Analyst | Power BI | Healthcare Analytics

