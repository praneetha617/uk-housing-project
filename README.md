# UK Housing Project

This project explores UK housing data using Azure Data Factory, data cleaning workflows, star schema modelling, and Power BI reporting.

## Project Overview

The project was developed to build a simple end-to-end housing data workflow:

- raw housing data ingestion
- movement of data through Azure Data Factory
- cleaned and curated dataset creation
- modelling for analytics
- dashboard reporting in Power BI

## Azure Data Factory Pipeline

The Azure Data Factory pipeline was created to move housing data from the raw layer into the processed layer.

## Future Development: AI Listing Freshness Flow

A future extension of this project is to add an AI-supported property listing freshness workflow. While the current project focuses on regional UK housing price trends and Azure-based data engineering, the next phase could connect market insights with listing-level quality checks.

The proposed AI flow would focus on detecting outdated or reused property images in rental or sales listings. For example, when a property price is updated, the system could require the seller or landlord to upload new images. The uploaded images could then be checked using image hashing or computer vision techniques to identify whether the same old images are being reused.

Proposed future workflow:

1. A listing owner updates the property price or listing details.
2. The platform checks the last image upload date.
3. If the images are older than the latest price update, new images are required.
4. The new images are compared against previous uploads.
5. If duplicate or reused images are detected, the listing update is blocked or flagged for review.
6. Verified listings are marked as recently updated.

Potential technologies for this future extension include Python, OpenCV, perceptual image hashing, Azure Blob Storage, Azure Functions, Azure AI Vision, and a lightweight web application interface.

This future development would extend the project from regional housing analytics into a practical data-quality solution for housing platforms, helping improve listing transparency and user trust.

