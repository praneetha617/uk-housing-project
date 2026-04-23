# UK Housing Project

This project explores UK housing data using Azure Data Factory, data cleaning workflows, star schema modelling, and Power BI reporting.

## Project Overview

The project was developed to build a simple end-to-end housing data workflow:

- raw housing data ingestion
- movement of data through Azure Data Factory
- cleaned and curated dataset creation
- modelling for analytics
- dashboard reporting in Power BI

## Repository Structure

- `data/` - curated dataset, Azure Data Factory assets, cleaned data, and star schema files, scripts or notebook-based processing logic
- `docs/` - project documentation
- `screenshots/` - screenshots for Azure, pipeline runs, and dashboards

## Azure Data Factory Pipeline

The Azure Data Factory pipeline was created to move housing data from the raw layer into the processed layer.

Pipeline name:
`pl_combine_housing_data`

Main activity:
`copy_raw_to_processed`

Datasets used:

- `ds_raw_housing`
- `ds_processed_housing`

## Curated Dataset

The repository includes a curated master dataset:

`data/uk_housing_master_dataset_curated.csv`

This dataset is used as the final prepared dataset for downstream analysis and reporting.

## Data Engineering Components

This repository currently includes:

- Azure Data Factory pipeline JSON files
- linked service configuration
- dataset definitions
- cleaned data notebook
- star schema notebook
- curated housing dataset

## Next Steps

Planned additions:

- Power BI dashboard screenshots
- architecture diagram
- pipeline execution screenshots
- project documentation with workflow explanation
