# Olist Data Warehouse: Preprocessing Pipeline
This repository contains the Python/Pandas preprocessing pipeline for the Olist E-commerce Data Warehouse project.

Key operations performed in this notebook:
- Data Quality Assessment: Identification of chronological anomalies.
- Vectorized Category Mapping: Safe translation of Portuguese product categories to English using .map().
- Type Casting & Decimal Elimination: Resolving structural IDE parsing bugs by enforcing .astype(int) on physical measures (weight, length, width, height).
- String Standardization: Padding ZIP codes and standardizing anagraphic text fields.
