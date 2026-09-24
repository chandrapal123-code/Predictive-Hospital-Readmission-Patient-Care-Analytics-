# Predictive-Hospital-Readmission-Patient-Care-Analytics-
An end-to-end healthcare analytics project focused on understanding 30-day hospital readmission patterns, patient characteristics, admission/discharge operations, medication patterns, and predictive readmission risk.

 # 1.Project Overview

Healthcare organizations generate large amounts of patient, admission, treatment, medication, and discharge data.
One important operational challenge is understanding 30-day hospital readmissions.

This project analyzes historical hospital encounter data to identify:
  * Patient characteristics associated with 30-day readmissions
  * Admission and discharge patterns
  * Medication-related patterns
  * Diagnosis-level readmission patterns
  * Hospital stay and treatment patterns
  * Previous healthcare utilization
  * Predicted high-risk encounters
  * Operational areas where readmission patterns can be monitored

# 2.Business Problem :-

 Which patient characteristics and healthcare utilization patterns are associated with higher 30-day readmission risk, and how can analytics help                   prioritize patients for post-discharge follow-up review?

# 3. Business Objectives

The primary objective of this project is to use healthcare data to understand **30-day hospital readmissions, patient characteristics, healthcare utilization, medication patterns, and hospital operations**, and convert these findings into actionable insights for hospital management.

### 1. Measure and Monitor 30-Day Readmissions

Measure the overall level of hospital readmissions by tracking:

* Total hospital encounters
* Number of 30-day readmissions
* 30-day readmission rate

**Business Value:**
Helps hospital management monitor readmission performance and identify the overall scale of the readmission problem.

---

### 2. Understand Patient Profiles and Readmission Patterns

Analyze how readmission patterns differ across patient characteristics such as:

* Age
* Gender
* Race
* Number of diagnoses
* Hospital stay
* Medication count

**Business Value:**
Helps identify patient segments with different readmission patterns and supports more focused patient-level analysis.

---

### 3. Analyze Healthcare Utilization Patterns

Evaluate patients' previous healthcare utilization through:

* Previous outpatient visits
* Previous emergency visits
* Previous inpatient visits

**Business Value:**
Helps understand how previous healthcare utilization is related to patient encounters and readmission patterns.

---

### 4. Evaluate Medication and Treatment Patterns

Analyze medication-related information, including:

* Diabetes medication
* Insulin changes
* Medication status
* Medication count

**Business Value:**
Helps identify differences in readmission patterns across medication and treatment categories and highlights areas for further clinical investigation.

---

### 5. Analyze Admission Operations

Analyze hospital admission patterns based on:

* Admission type
* Admission source
* Admission volume

**Business Value:**
Helps management understand where patients are coming from, how patients are being admitted, and which admission channels contribute to overall hospital volume.

---

### 6. Evaluate Discharge and Post-Discharge Patterns

Analyze:

* Discharge location
* Readmission rate by discharge location
* 30-day readmission patterns

**Business Value:**
Helps identify differences in readmission patterns across discharge destinations and supports further investigation of post-discharge care and follow-up processes.

---

### 7. Analyze Diagnosis and Patient Complexity

Compare diagnosis categories based on:

* Number of encounters
* Average hospital stay
* Readmission rate
* Number of readmissions

**Business Value:**
Helps hospital management understand which diagnosis groups contribute to patient volume, hospital utilization, and readmission activity.

---

### 8. Support Risk-Based Prioritization

Use available predictive outputs to identify encounters classified as **higher risk for 30-day readmission**.

Analyze:

* Predicted high-risk encounters
* Prediction probability
* Actual vs predicted readmission outcomes

**Business Value:**
Provides a risk-oriented view that can support patient prioritization, follow-up planning, care coordination, and resource allocation.

---

# 4. Dataset

* The project uses a historical hospital encounter dataset stored in a SQLite database.
### Main Dataset
   * diabetic_data
 * The analyzed main dataset contains:

   * 71,518 hospital encounters
   * Patient information
   * Hospitalization information
   * Diagnosis information
   * Medication information
   * Healthcare utilization information
   * Readmission information
---
# 4. Analytical Methodology
### Phase 1 — Data Understanding
   *The dataset was inspected to understand:
     * Table structures
     * Column names
     * Data types
     * Patient attributes
     * Hospital attributes
     * Clinical variables
     * Medication variables
     * Readmission fields
### Phase 2 — Data Preparation
   *The preparation process included:
       * Identifying relevant fields
       * Reviewing missing values
       * Checking duplicate records
       * Understanding categorical variables
       * Mapping numeric IDs to descriptive categories
       * Preparing analytical fields
       
### Phase 3 — SQL Analysis

* SQL was used to calculate:
   * Encounter counts
   * Readmission counts
   * Readmission rates
   * Average hospital stay
   * Average medication count
   * Admission patterns
   * Discharge patterns
   * Diagnosis-level patterns
   * Medication-level patterns
     
### Phase 4 — Exploratory Data Analysis

  * Python/Pandas was used to explore:
     * Patient demographics
     * Age groups
     * Hospital stay
     * Medication count
     * Diagnosis count
     * Healthcare utilization
     * Readmission patterns

### Phase 6 — Power BI Dashboard

 * The final analytical results were transformed into an interactive Power BI dashboard.
      * Page 1:Executive Overview
      * Page 2:Clinical Risk & Medication Analysis
      * Page 3:Admission & Discharge Operations
