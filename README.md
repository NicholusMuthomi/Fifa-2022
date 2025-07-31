# FIFA 2022 Player Analysis

## Overview

This project performs an in-depth analysis of FIFA 22 player data to uncover insights about player attributes, team compositions and performance metrics. The dataset includes over 16,000 players with 60+ attributes such as physical characteristics, skills, wages and nationalities. The analysis explores player distributions, team strengths and clustering techniques to identify similar players.

## Features

- **Data Cleaning**: Handles missing values, outliers, and irrelevant records to prepare the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Includes univariate and bivariate analysis to uncover patterns in player attributes, nationalities, and club performances.
- **Feature Engineering**: Transforms and scales features like player values, wages, and physical attributes for modeling.
- **Clustering**: Uses algorithms like K-Means, DBSCAN, and Agglomerative Clustering to group players based on skills and attributes.
- **Visualizations**: Provides clear plots and heatmaps to illustrate player distributions, correlations, and team comparisons.

## Installation

### Prerequisites

- Python 3.x
- pip (Python package installer)
- Required libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `fuzzywuzzy`

### Steps

1. Clone the repository (if applicable):
   ```bash
   git clone https://github.com/NicholusMuthomi/Fifa-2022
   ```

2. Navigate to the project directory:
   ```bash
   cd fifa-22-analysis
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the analysis script:
   ```bash
   python fifa_22_data_analysis.ipynb
   ```

## Code Functionality

- **Data Loading and Cleaning**: Loads the dataset, removes retired players and drops irrelevant features.
- **Feature Transformation**: Converts player heights, weights, wages and values into standardized numeric formats.
- **Exploratory Analysis**: Analyzes player distributions by age, nationality, club and position.
- **Clustering**: Groups players using algorithms like K-Means and evaluates clusters using silhouette scores.
- **Visualizations**: Generates plots for player attributes, team comparisons and correlation heatmaps.

## Results

### Key Insights
1. **Player Age Distribution**: Most players are aged 20-30, with performance peaking around 30.
2. **Top Clubs**: Paris Saint-Germain, Manchester City and Real Madrid have the highest-rated squads.
3. **National Teams**: Spain, Germany and France dominate in player quality.
4. **Player Attributes**: Goalkeepers excel in reflexes and handling, while forwards shine in dribbling and shooting.

### Clustering
- Players were grouped into clusters based on skills, potential and attributes.
- The K-Means algorithm (with k=50) achieved a silhouette score of 0.45, indicating reasonable cluster separation.

## Business Implications
- **Scouting**: Clubs can use clustering to identify undervalued players with high potential.
- **Team Strategy**: Insights into positional strengths can guide training and recruitment.
- **Game Development**: EA Sports can refine player ratings based on real-world performance trends.

## Contributing

Contributions are welcome, If you have suggestions for improvements or find any issues, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For inquiries or feedback, please reach out to [Email Address](muthominicholus22@gmail.com).
