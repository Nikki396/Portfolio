# Quantium Virtual Internship - Data Analytics Simulation (R)

This project is a high-fidelity simulation of a retail consulting engagement. Acting as a Data Analyst, I used **RStudio** to deliver actionable business insights for a major supermarket client, bridging the gap between raw transactional data and strategic decision-making.

---

## Technical Workflow
The analysis was conducted entirely in **RStudio**, focusing on three core data engineering pillars:
* **Data Cleaning:** Handled large-scale datasets by resolving date format inconsistencies, removing outliers (e.g., bulk commercial purchases), and imputing missing values.
* **Data Restructuring:** Merged transactional data with customer demographic profiles to create a unified analysis dataset. Engineered new features like `Price per Unit` and `Pack Size` to identify purchasing patterns.
* **Data Visualisation:** Developed comprehensive charts using `ggplot2` to illustrate customer distribution, sales trends, and trial performance comparisons.

---

## Project Structure & Task Details

### Task 1: Category Review & Customer Analytics
* **Objective:** Understand the "Chips" category's performance and customer purchasing drivers.
* **Key Findings:** Identified that **175g and 150g pack sizes** contribute nearly 40% of revenue, reflecting a "moderate consumption" mindset.
    * Discovered that **99.35% of transactions involve a single item**, indicating highly mission-driven shopping behavior.
    * Segmented the customer base into three tiers: **Premium** (Middle-aged/older), **Mainstream** (Younger singles/couples), and **Value** (Families/Budget-conscious).

### Task 2: Trial Analysis & Uplift Testing
* **Objective:** Evaluate the impact of new marketing/layout strategies in trial stores.
* **Methodology:** Used statistical matching (correlation and magnitude similarity) to select Control Stores for unbiased comparison.
* **Results:** All trial stores showed significant growth. **Store 77** achieved a peak monthly customer growth of **56.14%**.
    * **Store 86** was the most consistent performer with an average growth of **13.68%**.
    * Validated results using t-tests (t-values > 1.943 at 95% confidence level), ensuring both statistical and commercial significance.

### Task 3: Strategic Reporting
* **Deliverable:** A professional executive summary and data-backed recommendation report.
* **Conclusion:** The trial was highly successful. Recommended a **broader rollout** of the strategy to stores sharing similar demographic characteristics.

---

## Tech Stack
* **Software:** RStudio
* **Key Libraries:** `tidyverse` (dplyr, ggplot2), `data.table`, `lubridate`.
* **Methodologies:** A/B Testing, Uplift Modeling, Customer Segmentation (Demographic & Behavioral).

---

## 📄 Usage Note
This repository contains my personal solution to the Quantium simulation. While the insights are based on provided datasets, the analytical frameworks and R scripts are my original work.
