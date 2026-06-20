# Beyond Random Pairing

## Modelling Assortative Matching and Hub Formation in Online Dating Networks

### Overview

Online dating platforms do more than connect people—they reshape the structure of social networks.

This project develops an agent-based simulation calibrated using approximately 60,000 OKCupid profiles to investigate how two empirically observed mechanisms:

- Assortative Matching
- Hub Formation

influence diffusion dynamics in evolving contact networks.

The model combines network formation, behavioural matching, and epidemiological simulation to study how platform-driven structures alter transmission outcomes.

---

## Research Question

> How do assortative matching and popularity concentration (hub formation), calibrated from real dating-app behaviour, influence diffusion dynamics within an agent-based network simulation?

---

## Contact Network

![Network Structure](figures/contact_network_hubs.png)

Hub users emerge endogenously through popularity-driven matching and act as bridges between otherwise clustered communities.

---

## Methodology

### Data

- ~60,000 OKCupid profiles
- Demographic and behavioural attributes
- Literature-based calibration

### Network Formation

- Assortative matching based on similarity
- Popularity-driven visibility dynamics
- Dynamic relationship formation and dissolution

### Diffusion Model

Multi-pathogen SEIS simulation:

- Chlamydia
- Gonorrhoea
- Syphilis

---

## Selected Results

### STI Dynamics

![STI Dynamics](figures/sti_compartment_dynamics.png)

---

### Degree Distribution

![Degree Distribution](figures/degree_distribution_diagnostics.png)

---

### Scenario Analysis

![Scenario Analysis](figures/scenario_comparison.png)

---

## Key Findings

- Network topology materially affects diffusion outcomes.
- Hub users emerge as highly influential cross-community connectors.
- Assortative matching and hub formation produce transmission patterns that differ substantially from random mixing assumptions.
- Moderate homophily can partially offset hub-driven amplification.

---

## Project Resources

- [Full Report](report/project_report.pdf)
- [Simulation Notebook](notebooks/Ciapparelli_Lo_Cicero_Pulidori_Sharuda.ipynb)
- [EDA Notebook](notebooks/Ciapparelli_Lo_Cicero_Pulidori_Sharuda_EDA.ipynb)

---

## Technologies

Python • Pandas • NumPy • NetworkX • Agent-Based Modelling • Epidemiological Simulation • Network Analysis
