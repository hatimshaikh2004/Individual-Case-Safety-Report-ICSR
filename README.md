# Individual-Case-Safety-Report-ICSR
# Pharmacovigilance Task 5: Individual Case Safety Report (ICSR) Assessment
**Author:** Mohammed Hatim Shaikh  
**Task ID:** task5  
**Role:** Drug Safety Associate (PV Assessment)  
**Organization:** VirtualWorks Internship Program  
**Domain:** Pharmacovigilance & Drug Safety Management  
---
## Executive Summary
An **Individual Case Safety Report (ICSR)** is an itemized format used in pharmacovigilance to document and report suspect adverse drug reactions (ADRs) occurring in a single patient[span_2](start_span)[span_2](end_span). This capstone project integrates the end-to-end evaluation workflow performed by a Drug Safety Associate, including ADR identification, ICSR documentation, causality testing, and safety classification[span_3](start_span)[span_3](end_span).
---
## Primary Deliverables Overview
1. **ADR Identification:** Extraction of essential safety data from clinical case narratives[span_4](start_span)[span_4](end_span).
2. **ICSR Form Documentation:** Structuring data into standardized ICH E2B-compatible safety report fields[span_5](start_span)[span_5](end_span).
3. **Causality Assessment:** Determining the strength of association using the Naranjo Algorithm and WHO-UMC scale[span_6](start_span)[span_6](end_span).
4. **Severity & Expectedness Classification:** Classifying case seriousness and regulatory reporting urgency[span_7](start_span)[span_7](end_span).
---
## Section 1: Clinical Case Narrative & Identification
* **Patient Demographic:** 32-year-old Male | Weight: 65 kg | Patient Initials: `RP`
* **Indication:** Acute Bacterial Sinusitis
* **Suspected Drug:** Amoxicillin 500 mg (Oral, TID)
* **Start Date:** 01st March 2026
* **Reaction Onset:** 03rd March 2026 (3 days post-initiation)
* **Observed Symptoms:** Generalized cutaneous itching (pruritus) and erythematous skin rash over the chest.
* **De-challenge Outcome:** Amoxicillin discontinued on 03rd March 2026; complete resolution of symptoms on 06th March 2026.
---
## Section 2: ICSR Data Entry Breakdown

| ICSR Section | Parameter | Recorded Value |
| :--- | :--- | :--- |
| **Primary Reporter** | Type / Source | Healthcare Professional / Clinical Study |
| **Patient Info** | Initials / Age / Gender | `R.P.` \ | `32 Years` \ | `Male` |
|  | Weight | `65 kg` |
| **Suspected Drug** | Active Ingredient | Amoxicillin |
|  | Dose / Route / Freq | `500 mg` \ | `Oral` \ | `Three times daily (TID)` |
|  | Treatment Dates | `01/03/2026` to `03/03/2026` |
| **Adverse Reaction** | Event Term | Cutaneous Erythematous Skin Rash & Pruritus |
|  | Onset Date | `03/03/2026` |
|  | Outcome | Fully Recovered (`06/03/2026`) |
| **Action Taken** | Drug De-challenge | Drug Withdrawn (`Yes`) |

---
## Section 3: Causality Assessment Analysis
### 1. WHO-UMC Scale Classification
* **Temporal Relationship:** Plausible time interval between administration and event onset.
* **De-challenge:** Positive (symptoms resolved upon drug withdrawal).
* **Confounders:** No concurrent medical condition or concomitant drug explained the event.
* **WHO Result:** **Probable / Likely**
### 2. Naranjo Probability Scale
* **Total Score:** **+7**
* **Naranjo Classification:** **Probable**
---
## Section 4: Severity & Expectedness Classification
* **Seriousness Assessment:** **Non-Serious** (Does not meet ICH E2A criteria for death, life-threatening condition, or hospitalization).
* **Expectedness Status:** **Expected** (Skin rashes and hypersensitivity reactions are listed in the official Amoxicillin package insert / SmPC).
* **Reporting Timeline:** Routine aggregate safety database documentation (PSUR/PBRER entry).
---
## Project Structure
```text
├── README.md                 # Complete ICSR end-to-end evaluation report
└── ICSR_Data_Form.txt        # Structured data export for safety database entry
