# MIMIC to OMOP: CONDITION_OCCURRENCE Mapping

This project demonstrates the transformation of MIMIC-III clinical data (`DIAGNOSES_ICD` table) into the OMOP `CONDITION_OCCURRENCE` format.

## Files

- `condition_occurrence_transformation.sql`: SQL code for profiling, mapping, and data quality assessment
- `condition_occurrence_presentation.pdf`: Slide deck presentation

## Summary

The assignment includes:

- **Source profiling** of MIMIC-III diagnoses_icd
- Mapping of `subject_id`, `hadm_id`, `icd9_code` to `person_id`, `visit_occurrence_id`, `condition_source_value`
- Use of CTEs for safe transformation
- Data quality checks for NULLs and uniqueness
- Commented SQL code for clarity

## Data Source

- MIMIC-III Public Dataset (https://mimic.mit.edu/)
