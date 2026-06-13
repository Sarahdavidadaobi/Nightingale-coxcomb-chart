# Nightingale Coxcomb Chart

A Python recreation of Florence Nightingale's iconic 1854–1856 Crimean War polar area (coxcomb) diagram — one of the most influential data visualisations in history.

## Overview

Nightingale used this chart to argue that preventable diseases (not battle wounds) were the leading cause of soldier deaths. This project recreates her original diagram using Python's polar projection capabilities.

## Tools & Libraries

- Python
- Matplotlib (polar projections)
- NumPy
- Pandas

## Key Techniques

- Polar bar chart using `ax = plt.subplot(projection='polar')`
- Square-root scaling to preserve area proportions
- Manual angle calculation for wedge positioning
- Colour-coded causes: Preventable disease, Wounds, Other

## Data

1854–1856 Crimean War monthly mortality data, sourced from Nightingale's original publication.

## Output

![Coxcomb Chart](output.png)

---

*Project completed as part of the She Code Africa Data Science Programme, 2026.*# Nightingale-coxcomb-chart
Recreating Florence Nightingale's 1854-1856 Crimean War polar area diagram in python.
