# Potential Soccer Player Identification Tool

## Overview
This project presents a machine learning-based football player recommendation system designed to enhance scouting and player evaluation processes. By analyzing player statistics and incorporating user preferences, the system delivers personalized recommendations, streamlining decision-making for football scouts and team managers.

## Features
- **Random Forest Classification**: Predicts player mindset categories such as Attacking, Defensive, Playmaker, and Possession Holding.
- **K-Means Clustering**: Groups players with similar attributes to uncover insights into player roles.
- **Weighted Scoring System**: Allows users to prioritize attributes (e.g., technical, tactical skills) for tailored recommendations.
- **Comprehensive Skill Evaluation**: Analyzes technical, tactical, mental, and physical attributes for holistic player assessment.
- **Interactive Visualizations**: Includes bar charts, scatter plots, and histograms for intuitive insights.

## Key Algorithms
1. **Random Forest Classification**: Used for mindset prediction based on skill averages.
2. **K-Means Clustering**: Groups players for comparative analysis and regression target generation.
3. **Weighted Scoring Mechanism**: Tailors recommendations based on user-defined weights for various skills.

## Dataset
The project utilizes the [Soccer Players Statistics Dataset](https://www.kaggle.com/datasets/antoinekrajnc/soccer-players-statistics/data), featuring comprehensive player statistics from 2016.

## Installation and Usage

### Prerequisites
- Python 3.8+
- Required Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

### Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/potential-player-tool.git
   cd potential-player-tool

## Running the Tool
1. **Load the dataset** (`soccer_players_stats.csv`).
2. **Open the Jupyter Notebook** `Potential Player Identification Tool.ipynb` in your preferred environment.
3. **Follow the instructions in the notebook**:
   - Input your preferences for player attributes, age, position, and mindset.
   - Run the cells to process data, generate results, and visualize insights.
4. **View recommended players** and analyze their scores through intuitive visualizations.

---

## Project Workflow

### 1. Data Preprocessing
- Handle missing values by dropping or filling with appropriate measures.
- Standardize features using `StandardScaler` for consistent scaling.

### 2. Model Implementation
- **Random Forest Classifier**: Predicts player mindset categories.
- **K-Means Clustering**: Groups players with similar attributes.

### 3. User Interaction
- Collect user-defined weights for skill categories and filtering criteria.

### 4. Output Generation
- Display the top 5 recommended players based on the weighted scoring system.
- Generate visualizations for insights into player attributes and rankings.

---

## Results
- Achieved **85% testing accuracy** for mindset classification using Random Forest.
- Demonstrated robust generalization in K-Means regression with low Mean Squared Error values.
- Delivered actionable recommendations through personalized scoring and insightful visualizations.

