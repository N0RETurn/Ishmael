# Network Intrusion Detection Analysis

## Overview
This Jupyter Notebook performs a comprehensive analysis of the UNSW-NB15 network traffic dataset for intrusion detection. The analysis includes data loading, exploration, cleaning, and visualization to identify patterns and potential cyber threats in network traffic.

## Dataset
- **Dataset**: UNSW-NB15 Training Set
- **Records**: 82,332 network traffic records
- **Features**: 45 columns (reduced to 37 after cleaning)
- **Target**: Binary classification (0 = Normal, 1 = Attack) with attack categories

## Features
The dataset contains various network traffic attributes including:
- Connection duration, protocols, services, and states
- Packet counts and byte statistics
- Traffic rates and load metrics
- Time-to-live values
- Connection-based features
- Attack categories and labels

## Analysis Steps

### 1. Data Loading and Initial Exploration
- Import required libraries (pandas, matplotlib, seaborn)
- Load the UNSW-NB15 training dataset
- Examine dataset structure and composition
- Display basic statistics and data preview

### 2. Data Cleaning
- Remove irrelevant columns (id, tcprtt, synack, ackdat, sloss, dloss, trans_depth, response_body_len)
- Handle missing values and remove duplicate records
- Final cleaned dataset: 55,935 records × 37 columns

### 3. Data Visualization
- Line plot showing relationship between connection duration and data transfer rate
- Analysis of network traffic patterns

## Key Findings
- The dataset contains both normal and attack network traffic instances
- Cleaned dataset maintains significant portion of original data (55,935 out of 82,332 records)
- Various network protocols and services represented in the data
- Comprehensive feature set for intrusion detection analysis

## Requirements
- Python 3.x
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

## Usage
Run the notebook cells sequentially to:
1. Load and explore the dataset
2. Clean and preprocess the data
3. Generate visualizations and analysis
4. Prepare data for machine learning models

## Author
Ismael Kipyegon

## Purpose
This analysis serves as a foundation for building network intrusion detection systems and understanding network traffic patterns in cybersecurity applications.
