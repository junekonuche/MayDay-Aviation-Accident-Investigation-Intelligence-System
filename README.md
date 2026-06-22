# MayDay-Aviation-Accident-Investigation-Intelligence-System
An aviation investigation intelligence system that uses machine learning and historical accident data to identify similar accident cases, retrieve investigation knowledge, and forecast aviation safety trends.


### Project Overview

MayDay: Aviation Investigation Intelligence System is a data science and machine learning project designed to support aviation accident investigations through intelligent analysis of historical accident data.

The project addresses a key challenge in aviation safety: investigators often need to review thousands of historical accident reports, findings, and safety recommendations to identify relevant cases and lessons learned. This process can be time-consuming and may result in important information being overlooked.

MayDay aims to provide an intelligent investigation support platform that helps users discover similar historical accidents, access investigation knowledge, and identify emerging aviation safety trends using machine learning and time series forecasting techniques.

### Problem Statement

Aviation investigators and safety analysts frequently face difficulties in quickly identifying historical accidents with similar characteristics to an ongoing investigation.

Accident information is often distributed across multiple reports, findings, recommendations, aircraft records, and operational data sources. As a result, retrieving relevant knowledge can take significant time and effort.

There is a need for an intelligent system that can automatically identify similar accidents, provide investigation insights, and support evidence-based decision-making during aviation accident investigations.

### Project Goal

To develop an Aviation Investigation Intelligence System that uses machine learning and historical aviation accident data to identify similar accident cases, provide investigation knowledge, and forecast aviation safety trends.

### Data Source

National Transportation Safety Board (NTSB)

This project uses aviation accident and incident data obtained from the National Transportation Safety Board (NTSB) Aviation Accident Database.

The dataset contains detailed records of U.S. civil aviation accidents and incidents from 1982 to the present and includes information on accident events, aircraft characteristics, weather conditions, investigation findings, probable causes, flight operations, injuries, and accident narratives.

The dataset has been converted into structured CSV tables linked through a common event identifier, enabling relational analysis across multiple investigation components.

## Key Tables

* Events
* Aircraft
* Findings
* Narratives
* Flight Crew
* Injuries
* Occurrences
* Engines

Dataset Link:
https://www.kaggle.com/datasets/mirzaniazmorshed/ntsb-aviation-accidents/data


### Objectives
Analyze historical aviation accident and incident data.
Identify patterns and relationships between aviation accidents.
Develop a machine learning model to predict Accident Similarity Scores.
Forecast aviation accident category trends using time series analysis.
Build an investigation support platform for aviation safety professionals.
Improve access to historical investigation knowledge and safety lessons.
Machine Learning Component
Regression Problem

## Target Variable: Accident Similarity Score

The model will estimate the similarity between aviation accidents based on factors such as:

Aircraft type
Aircraft manufacturer
Weather conditions
Flight phase
Operational characteristics
Accident circumstances

The output will be a numerical similarity score indicating how closely related two accident cases are.

## Time Series Component
Accident Trend Forecasting

The project will forecast future trends in aviation accident categories, including:

Runway excursions
Loss of control events
Engine-related occurrences
Weather-related accidents
Operational incidents

The forecasts will help identify emerging aviation safety patterns and support proactive safety planning.

## Core Functionalities
Similar Accident Finder

Searches historical aviation accident records and identifies accidents with characteristics similar to the current case.

# Role:
Supports investigators by rapidly locating relevant historical cases and lessons learned.

Investigation Knowledge Hub

Provides access to accident findings, probable causes, safety recommendations, and investigation summaries.

3 Role:
Acts as a centralized aviation investigation knowledge repository.

FDR, CVR, and ATC Evidence Explorer

Organizes investigation information related to:

Flight Data Recorder (FDR) findings
Cockpit Voice Recorder (CVR) findings
Air Traffic Control (ATC) communications


# Role:
Helps investigators understand evidence sources associated with historical accident cases.

Aviation Safety Trend Dashboard

Visualizes aviation accident patterns and forecasted safety trends.

# Role:
Supports safety monitoring and data-driven decision-making.

### Expected Outcomes
Improved retrieval of aviation investigation knowledge.
Faster identification of similar historical accidents.
Better understanding of recurring aviation safety issues.
Enhanced support for aviation accident investigations.
Data-driven insights into future aviation safety trends.  


### Technologies
Python
Pandas
NumPy
Scikit-Learn
Tableau / Power BI
SQL
Jupyter Notebook
Git & GitHub

### Data Methodology

## 1. Data Collection

Aviation accident and incident data will be collected from the NTSB Aviation Accident Database and integrated from multiple relational tables, including events, aircraft, findings, narratives, injuries, and occurrence records.

## 2. Data Cleaning

* Handle missing values
* Remove duplicate records
* Standardize aircraft and location information
* Convert date fields into consistent formats
* Validate relationships between tables

## 3. Data Integration

Relevant tables will be merged using the Event ID (EV_ID) as the primary key to create a unified investigation dataset.

## 4. Exploratory Data Analysis (EDA)

The project will analyze:

* Aircraft types involved in accidents
* Weather conditions
* Flight phases
* Accident locations
* Investigation findings
* Probable causes
* Accident trends over time

## 5. Feature Engineering

Features will be derived from:

* Aircraft characteristics
* Weather observations
* Flight operation details
* Investigation findings
* Narrative reports
* Accident categories

## 6. Machine Learning

A regression model will be developed to estimate Accident Similarity Scores based on accident characteristics and investigation data.

## 7. Time Series Forecasting

Time series models will be used to forecast trends in aviation accident categories and recurring safety issues over time.

## 8. System Development

The final system will provide:

* Similar Accident Finder
* Investigation Knowledge Hub
* FDR, CVR and ATC Evidence Explorer
* Aviation Safety Trend Dashboard



### Vision

MayDay seeks to transform historical aviation accident data into actionable investigation intelligence by helping investigators learn from past accidents, discover hidden patterns, and support safer skies through data-driven decision-making.
Data Science Capstone Project
