# INST414

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

Analyzing audience and cinephile reception, this project examines how visual and thematic elements influence the ratings of auteur-driven films across Criterion, IMDb, and Letterboxd, balancing artistic significance with broader audience trends.

# Exploring Auteur Theory with Quantitative Methods  
### Audience and Cinephile Reception of Criterion Films  

## **Project Overview**  
This research examines how auteur-driven films are perceived differently by cinephiles versus broader audiences. Using **Criterion Collection metadata, Letterboxd ratings, and IMDb data**, the project integrates quantitative analysis, sentiment trends, and clustering techniques to explore rating disparities, thematic correlations, and stylistic patterns.  

## Project Organization (CCD)

This repository contains data cleaning and visualization scripts for analyzing [your dataset topic]. The project processes social media datasets, standardizes structures, and generates insights on engagement.

### Repository Structure

docs/ - Contains CSV data files 

notebooks/ - Includes Google Colab notebook for analysis 

.gitignore - Specifies files to exclude from version control
README.md - Project documentation 
requirements.txt - Dependencies for running the analysis

## Data Sources

The dataset consists of three CSV files, which provide input for data processing:
1. `criterion.csv` - Films in the Criterion Collection are curated specifically for their artistic and cultural significance, ensuring my dataset includes highly stylized and auteur-driven works.
2. `letterboxd.csv` - Letterboxd ratings can capture a diverse and passionate cinephile community's perspectives, offering unique insights into a niche audience preferences and trends align with Criterion’s mission.
3. `imdb_top_1000.csv` - Incorporating IMDb ratings brings in a broader, more global measure of audience perception and popularity, balancing Letterboxd’s critical focus with audience-driven insights.
4. `merged_dataset.csv` - Identifies column in Letterboxd dataset to match IMDb and Criterion. Merge IMDb and Letterboxd datasets on 'Title', and merge the result with Criterion dataset on 'Title.'

## Analysis Pipeline
1. Load CSV files and preprocess data.
2. Handle missing values and clean inconsistencies.
3. Standardize formats across datasets.
4. Generate metrics such as engagement rates.
5. Visualize trends using Python.

## Notebooks
The main notebook (`notebooks/INST414 - Research.ipynb`) performs:
- Data cleaning procedures.
- Merging operations to align datasets.
- Visualization of trends in engagement metrics.

## Setup Instructions
To replicate the analysis:
```bash
git clone https://github.com/glaraterpmail/INST414-Research.git
cd INST414-Research
pip install -r requirements.txt
