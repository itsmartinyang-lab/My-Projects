# Pfizer Vaccine Event Study

This project analyzes the stock market reaction to Pfizer's
November 9, 2020 COVID-19 vaccine announcement.

## Research Question
How quickly did financial markets incorporate the information,
and did related firms experience spillover effects?

## Methodology
Event study using the market model.

- Estimation window: [-250, -11]
- Event window: [-10, +10]
- Data source: CRSP

Firms analyzed:
- Pfizer (PFE)
- Moderna (MRNA)
- AstraZeneca (AZN)

## Key Findings
Pfizer’s stock increased approximately 13% within the first hour
of trading following the announcement, indicating rapid market
information incorporation.

Moderna experienced a gradual increase in cumulative abnormal
returns over the following days, suggesting technology spillover
effects for mRNA vaccine developers.

## Paper
See the full paper: `paper.pdf`