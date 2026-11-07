# HEOR-ICER-Markov-Model-Project-
# Health Economics & Markov Modeling Project (HEOR/ICER)

This repository contains a comprehensive Health Economics and Outcomes Research (HEOR) project developed for ReDI School, focusing on the cost-effectiveness analysis of a new therapeutic intervention compared to standard care.

## Project Structure & Methodology
- **Modeling Approach:** A 10-year cohort Markov model featuring three health states (Healthy/Stable, Progressed, Dead) with annual cycles.
- **Economic Standards:** Applied a 3% annual discount rate to both costs and QALYs in accordance with international HEOR guidelines (NICE/ISPOR standards).
- **Uncertainty Analysis:** Implemented a Probabilistic Sensitivity Analysis (PSA) via Monte Carlo simulation (1,000 iterations) utilizing Beta distributions for transition probabilities and Gamma distributions for state costs.

## Key Visualizations & Outputs
- **Markov Trace Plot (`markov_trace_plot.png`):** Visualizes the long-term cohort progression across health states over 10 years.
- **Cost-Effectiveness Plane (`cost_effectiveness_plane.png`):** Illustrates the joint distribution of incremental costs and QALYs.
- **Cost-Effectiveness Acceptability Curve (`ceac_curve.png`):** Evaluates the probability of cost-effectiveness across varying Willingness-to-Pay (WTP) thresholds.
- **Tornado Diagram (`tornado_diagram.png`):** Demonstrates the impact of parameter variations on the ICER.
- **Reports:** Includes final discounted Markov model reports and PSA summaries (`discounted_markov_report.txt`, `psa_summary_report.txt`).

## Author
Developed as part of the ReDI School Data Analytics / HEOR curriculum.
