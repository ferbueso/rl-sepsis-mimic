# Offline RL for Safe Clinical Decision Support in Sepsis

## Datasets

This project evaluates the **generalizability of offline reinforcement learning (RL) models for sepsis management** using two intensive care unit (ICU) datasets.

### 1. MIMIC-III (Adult ICU Dataset)

The **Medical Information Mart for Intensive Care (MIMIC-III)** database is a large, publicly accessible dataset containing clinical data from **over 61,000 ICU stays** at Beth Israel Deaconess Medical Center.

In this project, MIMIC-III was used as a **benchmark dataset** to validate the modeling pipeline and ensure the correctness and consistency of the reinforcement learning implementation.

Although widely used in research, **MIMIC-III is not directly downloadable without authorization**. Access must be requested through PhysioNet after completing the required data use training.

Access information can be found here:

🔗 https://physionet.org/content/mimiciii/1.4/

---

### 2. Great Ormond Street Hospital (GOSH) Pediatric ICU Dataset

The core focus of this work is a **pediatric intensive care unit (PICU) cohort** from **Great Ormond Street Hospital (GOSH)** in London.

This dataset contains **2,229 pediatric sepsis patient trajectories** and enables the study of reinforcement learning for **pediatric sepsis management**, a setting that has received far less attention compared to adult ICU populations.

Due to **institutional governance, ethical approvals, and patient privacy regulations**, the GOSH dataset **cannot be publicly shared**.

---

## Data Availability

Because of the restrictions described above:

- **MIMIC-III** can be accessed by credentialed researchers through PhysioNet.
- **GOSH data is not publicly available** due to hospital data governance policies.

## Disclaimer

This repository is intended for **research purposes only**.  
The models implemented here are **not designed for clinical deployment** and should not be used for medical decision making without proper validation and regulatory approval.
