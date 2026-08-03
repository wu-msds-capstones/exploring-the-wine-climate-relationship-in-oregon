# Oregon Wine & Climate Database

Jennifer Arreola · Rebekah Peterson · Victoria Fox
DATA 510 Data Science Capstone, Willamette University · Summer 2026

## Overview

A 38-year integrated database linking Oregon vineyard production records to daily
climate data, built to ask two questions: how has climate change affected Oregon
wine production and variety composition since 1987, and does climate sensitivity
differ by variety and by point in the growing season?

We find that yield has climbed for decades and, within the climate range Oregon
has experienced so far, warming hasn't hurt production. But climate sensitivity
is not uniform: a staged machine learning model shows variety identity outweighs
climate as a yield predictor at every stage of the growing season, and the
ripening-season diurnal temperature range that defines Pinot Noir's character is
narrowing in a way no yield-only model can detect.

## Repository structure
├── _01_intro.qmd Introduction and problem statement
├── _02_background.qmd Prior research and motivation
├── _03_data.qmd Data sources, ingestion pipeline, ethics
├── _04_analysis.qmd Statistical and correlation analysis
├── _05_results.qmd Yield/climate findings and ML results
├── _06_conclusions.qmd Synthesis and future work
├── _07_references.qmd Bibliography
├── capstone.qmd Manuscript entry point (assembles the above)
├── data/ Analysis-ready climate and production panels
├── data/ml_results/ Model outputs (metrics, importance, predictions)
└── poster/ Conference poster (PDF)

## Data sources

- Oregon Vineyard and Winery Annual Reports, 1987–2024 (Oregon Department of Agriculture / industry reporting)
- PRISM Climate Group, daily climate observations, 1981–2024
- TTB American Viticultural Area shapefiles

