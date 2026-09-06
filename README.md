# ASG Airlines: End-to-End Data Engineering Case Study
NeoStats Round 1 Submission — Aimee Joseph

## Overview
This repo contains all files for an end-to-end data pipeline for ASG Airlines' flight operations 
data: ingestion, cleaning, PII protection, and a Power BI dashboard that covers Duration Analysis, Route Performance, Airline Trends, and Delay/Anomaly Insights.

## Repo Structure
- `data/UseCase - Airlines.xlsx` — original source file (4 sheets: flights, bookings, payments, passengers)
- `data/cleaned/` — cleaned output datasets (flights, bookings, passengers)
- `python files/ASGAirlines_Cleaning.ipynb` — full cleaning/transformation pipeline
- `dashboard/` — Power BI report (.pbix) and screenshots
- `ASG_Airlines_Documentation.docx` — assumptions, cleaning logic, PII approach, data model, dashboard walkthrough

## How to Run
Open the notebook in Jupyter, ensure `pandas` and `haslib` are installed, and run from top to bottom. This reproduces the cleaned CSVs used in the Power BI dashboard.
