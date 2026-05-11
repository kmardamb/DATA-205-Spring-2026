# DATA-205-Spring-2026
Capstone Project Repository for Data 205

DATA 205 Capstone Final Project

My name is Karim MardamBey and this repository contains my DATA 205 Capstone Final Project focused on crime frequency analysis in Montgomery County, Maryland. The purpose of this project was to analyze long-term crime trends, identify geographic crime patterns, and evaluate whether housing density and urban infrastructure correlate with increased crime frequencies.

Project Overview

This project combines two public Montgomery County datasets:

A Montgomery County Crime Incident dataset maintained by the Montgomery County Police Department.
A Housing Licensing and Registration dataset used to analyze residential infrastructure and housing density.

The project uses statistical analysis, GIS visualization, and comparative visualizations to better understand how crime frequencies vary across municipalities, seasons, housing structures, and residential density throughout Montgomery County.

Datasets
Dataset 1 — Montgomery County Crime Incident Dataset

Source:
Montgomery County Crime Incident Dataset

400,000+ original crime incident records
Updated daily by MCPD
Includes:
dispatch dates/times
crime classifications
municipalities
ZIP codes
geographic coordinates
police districts
victim counts
Dataset 2 — Housing Licensing and Registration Dataset

Source:
Housing Licensing and Registration Dataset

Residential licensing and rental housing records
Includes:
structure types
ownership information
property locations
geographic coordinates

This dataset was used to compare housing density and residential infrastructure with crime frequencies throughout Montgomery County.

Tools and Libraries

This project was completed entirely in RStudio using:

dplyr
tidyr
ggplot2
leaflet
ggfortify
lubridate
Data Cleaning and Preprocessing

Several preprocessing steps were performed before analysis:

Removed invalid and duplicate ZIP codes
Standardized municipality names
Parsed and separated timestamps
Created seasonal variables
Extracted latitude and longitude coordinates
Aggregated crime frequencies by city, season, and housing type

The cleaned crime dataset was reduced from over 400,000 original records to approximately 170,000 usable entries.

Exploratory Data Analysis (EDA)

The project includes:

Monthly crime trend analysis (2017–2026)
Seasonal crime frequency comparisons
Crime classification comparisons
Municipality crime frequency analysis
Crime location analysis
Housing structure summaries
GIS heat maps for crime and housing density

Key findings included:

Silver Spring accounted for the highest crime frequencies
Crimes Against Property represented approximately 66.8% of all incidents
Summer and Fall experienced the highest seasonal crime frequencies
Densely populated urban municipalities generally experienced elevated crime totals
Statistical Analysis

Statistical methods included:

Time-series analysis
Linear regression analysis
Regression diagnostics

The linear regression model comparing housing density and crime frequencies produced:

R² = 0.752
statistically significant relationship (p < 0.001)

The results suggest a strong positive relationship between housing density and crime frequency within Montgomery County.

GIS and Spatial Analysis

GIS heat maps were created using leaflet to visualize:

crime clustering patterns
residential infrastructure density
urbanized municipalities
housing concentration

The spatial analysis demonstrated that highly urbanized regions such as Silver Spring and Rockville experienced elevated crime concentrations and dense residential infrastructure.

Project Goal

The goal of this project was to create an accessible and data-driven analysis of crime frequency patterns in Montgomery County while evaluating how urban density and housing infrastructure may influence public safety trends.
