# Action Choice and Agency Judgment – Project Repository

This repository contains all materials related to the project titled:  
**"The impact of action choice on simultaneity and causality judgments: comparing free choice, direct order, and posthypnotic suggestion"**

---

## 📁 Repository Structure

### `AgencyRDM/`
Contains MATLAB code used to run the experimental task using Psychtoolbox.

- `myfunc/`: Custom MATLAB functions used within the task
- `images/`: Instruction and message screens (in Persian) used in the task as images
- `mydata/`: Automatically stored participant data during the task
- `meandata/`: Files that store mean reaction times for each participant
- `main3cond.m`: Full task script (12 blocks × 24 trials = 288 trials)
- `train2cond.m`: Training task script (2 blocks × 24 trials = 48 trials; only Free/Force conditions)

### `dataset/`
Separate folder containing the cleaned or raw datasets used for analysis. May include CSV, MAT, or processed versions.

### `R_analysis/`
Contains statistical analysis scripts written in R for post-experiment analysis.

### `Hypnosis_Script_Translated.docx`
The English translation of the hypnosis induction script used during the experiment (outside of `AgencyRDM/`).

---

## ▶️ How to Run the Experiment

1. Open MATLAB.
2. Navigate to `AgencyRDM/`.
3. Run `train2cond.m` for the training phase, or `main3cond.m` for the full experiment.
4. Data will be saved to `mydata/`.

---

## 📋 Requirements

- MATLAB R2021a or later
- Psychtoolbox 3.x
- R (optional, for statistical analysis)

---

## 🧠 Citation

> A full citation will be added once the related manuscript is published.

---

## 📎 Notes

- All participant-facing Persian text is shown using images due to MATLAB’s limited RTL support.
- Folder structure may grow as the project develops.

