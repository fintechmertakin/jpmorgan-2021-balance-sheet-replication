# jpmorgan-2021-balance-sheet-replication
This project reproduces JPMorgan Chase’s 2021 balance sheet and income statement using WRDS data. It merges FR Y-9C Bank Regulatory data and CRSP/Compustat Fundamentals to align regulatory and accounting figures, verifying totals against the official 2021 JPMorgan annual report.
This project replicates JPMorgan Chase & Co.’s 2021 balance sheet and income statement, following the official figures published in its Annual Report
 (see pages 10–11).

The analysis uses two WRDS databases:

Bank Regulatory – FR Y-9C (RSSD ID 1039502): Consolidated financial data for JPMorgan Chase Bank Holding Company, December 2021.

CRSP/Compustat Merged – Fundamentals Annual (PERMNO 47896): Supplemental firm-level accounting data for cross-validation.

The code retrieves FR Y-9C data, selects key balance-sheet and income-statement variables, aggregates subaccounts to match the structure reported in the annual report, and verifies totals. Where necessary, Compustat data are merged to confirm asset, equity, and income components.

Outputs include:

Replicated simplified balance sheet and income statement for 2021

Comparison table versus reported values from JPMorgan’s 2021 Annual Report

Log of data sources, adjustments, and validation checks

The project demonstrates proficiency in financial data extraction, reconciliation, and regulatory reporting analysis using WRDS and Stata.
