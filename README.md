# New Jersey COVID-19 Analysis

A Stat 310 course project examining COVID-19 outcomes and county-level demographic, socioeconomic, and transportation characteristics across New Jersey's 21 counties.

**Authors:** Camila Nunez Polanco and Sarah Suratt

## Project Materials

- [Final project report](reports/project-report.pdf): research questions, exploratory figures, statistical methods, results, and references.
- [Presentation](reports/presentation.pdf): a slide-based overview of the project.
- [Data source notes](docs/data-sources.md): sources cited in the original materials.

## Repository Status

This repository currently preserves the final report and presentation. The original R code has not yet been recovered, and the original analysis datasets are not included. The analysis cannot currently be rerun from this repository.

No replacement analysis, synthetic data, or reconstructed R code has been added. Original code and data may be added later if recovered, with their provenance and reproducibility status documented.

## Research Focus

The project explored how county characteristics were associated with the speed and severity of COVID-19 spread. Topics included commuting patterns, population density, health insurance coverage, demographic composition, and geographic differences.

## Methods Documented in the Original Materials

- County-level data preparation and joins in R.
- Exploratory plots and summary statistics.
- Permutation testing for associations involving commuting, early case growth, uninsured percentage, and mortality.
- Bootstrap confidence intervals for the correlation between uninsured percentage and deaths per 100,000 residents.
- Multiple linear regression of deaths per 100,000 residents using uninsured percentage and log population density.

These descriptions summarize the submitted documents; they have not been verified against the missing source code or rerun.

## Selected Reported Results

The report describes a positive correlation between uninsured percentage and deaths per 100,000 residents (approximately 0.662), with a permutation-test p-value of 0.004 and a bootstrap 95% confidence interval of 0.252 to 0.914 (report, page 10).

The presentation reports an association between commuter percentage and days to 100 COVID-19 cases, with an observed linear-model slope of -0.695 and a permutation-test p-value of 0.0034 (presentation, slide 13).

These are results reported in the original coursework, not independently reproduced results.

## Interpretation and Limitations

The study is observational and includes only 21 counties. County-level associations do not establish causation or individual-level effects. Case reporting, testing, and the timing of source data may affect comparisons.

The PDFs are preserved as submitted and may contain inconsistencies. For example, the report identifies the South region as reaching 100 cases faster (page 8), while the presentation identifies the Central region (slide 18). This discrepancy remains unresolved without the original data and code.

## Repository Layout

```text
new-jersey-covid-analysis/
|-- README.md
|-- .gitignore
|-- docs/
|   |-- data-sources.md
|   `-- provenance.md
`-- reports/
    |-- project-report.pdf
    `-- presentation.pdf
```

## Future Recovery

If the original materials are recovered, add the R scripts or notebooks, document their input files and package requirements, and check their outputs against the submitted report. Any corrections or later reanalysis should be clearly distinguished from the original coursework.

## Attribution

This was a joint project by Camila Nunez Polanco and Sarah Suratt. The repository does not assign individual responsibility for particular analyses. See the original report and presentation for the submitted work and references.
