# **Wizard Apprentice Potion Revenue Simulation**

## **Overview**
This repository contains a Monte Carlo simulation model designed to optimize revenue for a wizard apprenticeship program focused on potion production. The simulation accounts for production boosts, randomized spell effects, and conditional weekend work, with an emphasis on achieving high revenue targets over different operational durations.

## **Features**
- **Dynamic Production Modeling**:
  - Milestone-based production boosts (+7% every 10 potions).
  - Spell effects including:
    - Haste (+18% production).
    - Empower (+$100 potion price).
    - Lady Luck (12% chance to double production).
- **Weekend Work Decision**:
  - Weekend overtime work is enabled only when cumulative revenue exceeds a threshold ($800,000 or $900,000).
- **Flexible Simulation Parameters**:
  - Adjustable operation durations (e.g., 90 days, 180 days).
  - Configurable thresholds for weekend work and spell allocation strategies.
- **Monte Carlo Simulation**:
  - Simulates production and revenue over thousands of iterations for robust statistical analysis.

## **Requirements**
- Python 3.7+
- Required Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`

## **Output**

### **Simulation Results**
- **Total Revenue Distribution**:
  - A detailed histogram showing the frequency of total revenue outcomes across simulations.
- **Probability of Reaching Revenue Targets**:
  - Calculates the likelihood of achieving specific revenue milestones, such as $1,000,000.
- **Daily Metrics**:
  - Potion-making rates for each apprentice.
  - Sale prices influenced by spell allocation.
  - Cumulative potion production over the operation duration.

### **Visualization**
- **Revenue Distribution Histogram**:
  - Graphical representation of the revenue outcomes to analyze variability and trends.
- **Comparative Analysis**:
  - Comparison of revenue distributions and probabilities across different operation durations (e.g., 90 days vs. 180 days).
