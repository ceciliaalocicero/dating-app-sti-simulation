# Beyond Random Pairing: Modeling Assortative Matching and Hub Formation

Agent-based simulation of online dating networks and STI diffusion using real-world OKCupid profile data.

---

## Overview

This project investigates how dating applications reshape sexual contact networks and influence the spread of sexually transmitted infections (STIs).

Using approximately 60,000 OKCupid profiles, we developed an agent-based simulation in which:

- Users exhibit assortative matching preferences
- Popular users become hubs
- Dynamic contact networks emerge endogenously
- STI diffusion is simulated using a SEIS epidemiological framework

The model is calibrated using empirical evidence from online dating research and network science.

---

## Research Question

How do assortative matching and hub formation influence STI transmission dynamics in online dating networks?

---

## Dataset

Source:

https://www.kaggle.com/datasets/andrewmvd/okcupid-profiles

The dataset contains approximately 60,000 OKCupid user profiles including:

- Age
- Gender
- Education
- Ethnicity
- Religion
- Smoking habits
- Drinking habits
- Drug use

---

## Methodology

### Exploratory Data Analysis
Cleaning, filtering and preprocessing of OKCupid user data.

### Assortative Matching
Partner selection based on demographic and behavioral similarity.

### Hub Formation
Highly visible users accumulate disproportionately many matches.

### Epidemiological Layer
SEIS simulation for:

- Chlamydia
- Gonorrhea
- Syphilis

---

## Main Findings

- Hub users act as transmission amplifiers.
- Assortative matching creates clustered communities.
- Network structure strongly affects STI spread.
- Moderate homophily can reduce large-scale diffusion compared to random matching.

---

## Files

| File | Description |
|--------|--------|
| `Ciapparelli_Lo_Cicero_Pulidori_Sharuda.ipynb` | Main simulation model |
| `Ciapparelli_Lo_Cicero_Pulidori_Sharuda_EDA.ipynb` | Exploratory data analysis |
| `project report.pdf` | Final report |

---

## Authors

Anna Ciapparelli  
Cecilia Lo Cicero  
Sara Pulidori  
Alissa Sharuda
