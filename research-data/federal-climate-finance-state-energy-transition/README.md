# Federal Climate Finance and State Energy Transition in the United States

## Research data repository

This folder contains the research data package for the manuscript:

**Federal Climate Finance and State Energy Transition in the United States: The Allocation-Conversion Wedge**

Author: **Bright Akwasi Gyamfi**

Version 1.0 - 29 September 2026.

The study uses a balanced panel of all 50 U.S. states for 2017-2024 (400 state-year observations) to examine the geographic allocation of federal climate finance and its association with renewable-energy deployment, renewable share, and carbon intensity.

## Data files

### data/analysis_ready_2017_2024.csv
Primary balanced state-year panel. It contains federal climate-grant obligations and the principal EIA energy, emissions, population, and GDP variables used in the study.

### data/advanced_derived_2017_2024.csv
The analysis-ready panel augmented with transformed variables, lags, leads, first differences, standardized exposure components, baseline exposure, and variables used in robustness and heterogeneous-conversion analyses.

### data/state_spatial_exposure_summary.csv
State-level file used for the Spatial Exposure Atlas and descriptive transition diagnostics, including baseline exposure, cumulative grants per capita, transition progress, residual exposure, finance-need classifications, and model-implied renewable-share conversion slopes.

## Principal public data sources

- U.S. Energy Information Administration, State Energy Data System (SEDS): https://www.eia.gov/state/seds/
- USAspending: https://www.usaspending.gov/
- USAspending API: https://api.usaspending.gov/

Federal climate finance is measured using a strict taxonomy of qualifying federal grant and cooperative-agreement obligations, assigned by primary place of performance. The main treatment is the natural logarithm of one plus federal climate grants per capita.

The principal transition outcomes are renewable-energy consumption (trillion Btu), renewable share of total state energy consumption (%), and energy-related CO2 intensity (metric tons per million 2017 USD of real GDP).

Baseline transition exposure is fixed using 2017 conditions and combines standardized CO2 intensity, energy use per capita, and the inverse of renewable share.

## Analytical boundary

The data are observational. Federal climate finance is strategically allocated rather than randomly assigned. The accompanying manuscript therefore interprets finance-outcome estimates as conditional within-state associations rather than causal treatment effects.

## Integrity checks

SHA-256 checksums for this release:

- analysis_ready_2017_2024.csv: 65c333e7e2eb19c5e965a7f94e43a68438177ea829c2b753cf2bf5a692d92b1d
- advanced_derived_2017_2024.csv: 8600c4596850e0f8049b503c36b26946a246337e2d02d4eedd78fe34bc26507a
- state_spatial_exposure_summary.csv: 8916d29ffd1a249c59d6ee304be01204874c620bbef2b1c662e0216b7ad4d034

## Suggested citation

Gyamfi, B. A. (2026). *Research data for Federal Climate Finance and State Energy Transition in the United States: The Allocation-Conversion Wedge* [Data set]. GitHub.

Please also cite the underlying EIA SEDS and USAspending sources.

## Related subnational climate-finance research

The study acknowledges the measurement contributions and public materials of:

- Gilmore, E. A., & St.Clair, T. (2018). Budgeting for climate change: Obstacles and opportunities at the US state level. *Climate Policy, 18*(6), 729-741. https://doi.org/10.1080/14693062.2017.1366891
- Gilmore, E., & St.Clair, T. (2026). Tax expenditures as tools for state-level climate action in the U.S. *Climate Policy, 26*(1), 65-76. https://doi.org/10.1080/14693062.2025.2482111

Their public replication/supplementary materials were consulted as background for subnational climate-finance measurement. The principal 2017-2024 federal-grant panel in this folder is constructed from EIA SEDS and USAspending.
