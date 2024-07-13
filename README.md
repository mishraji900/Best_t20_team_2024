# ICC Men's T20 2024 World Cup Dream 11 Predictor

This project aims to predict the best playing 11 for the ICC Men's T20 2024 World Cup using advanced data analytics and visualization techniques.

## Data Collection

### ESPNCricinfo Data Collection:
- Data is collected using BeautifulSoup (bs4) to scrape match details, player statistics, and performance metrics from the ESPNCricinfo website.
- Specifically, data from the ICC Men's T20 2024 World Cup tournament page is extracted.
- Match details, and player statistics, including batting averages, strike rates, bowling economy, wicket-taking abilities, and fielding efficiencies, are collected and structured into a dictionary format.
- The dictionary is converted to JSON for efficient handling and storage.

### ICC Official Website Data Collection:
- Player details and images are gathered from the official ICC website.
- BeautifulSoup is utilized to extract relevant information such as player names, teams, and images.
- The collected data is integrated into the existing JSON dataset.

## Data Preprocessing

### Data Preprocessing.ipynb:
- JSON data is loaded into a Jupyter Notebook for preprocessing using Pandas.
- Data cleaning tasks are performed to handle missing or inconsistent values.
- Dataframes are created for comprehensive analysis, enabling manipulation and transformation.
- Categorical variables are encoded into numerical representations for modelling purposes.

## Data Modeling

### Power Query and DAX:
- Preprocessed data frames are converted to CSV files for further modelling and analysis.
- Power Query is employed for data transformation, merging, and filtering to create refined datasets.
- DAX (Data Analysis Expressions) in Power BI is utilized to perform advanced calculations, define table relationships, and create measures for predictive modeling.

## Methodology

- **Data Collection and Cleaning:** Comprehensive extraction and preprocessing of match and player data.
- **Exploratory Data Analysis:** Analyzing player performance metrics to identify key insights.
- **Feature Engineering:** Deriving new features from existing data to enhance predictive modelling.
- **Model Selection and Training:** Evaluating and selecting the best-performing models for Dream 11 team prediction.
- **Model Evaluation and Validation:** Validating model accuracy and performance using historical data.
- **Dashboard Development:** Creating interactive dashboards in Power BI for visualizing and interpreting cricket analytics.

## Final Outcome

- **Dream 11 Team Formation:** Formation of a top-performing Dream 11 team for the ICC Men's T20 2024 World Cup based on insights derived from data analysis and visualization.
- **Impact and Contribution:** Contributing to the advancement of cricket analytics and data-driven decision-making in men's cricket.
#### Dashboard Openers Page

![Dashboard Openers Page](https://github.com/mishraji900/Best_t20_team_2024/blob/main/Screenshot%202024-07-14%20041834.png)

#### Dashboard Middle Order

![Dashboard Middle Order](https://github.com/mishraji900/Best_t20_team_2024/blob/main/Screenshot%202024-07-14%20041846.png)

#### Dashboard Lower Order Anchor

![Dashboard Lower Order Anchor](https://github.com/mishraji900/Best_t20_team_2024/blob/main/Screenshot%202024-07-14%20041855.png)

#### Dashboard All Rounders

![Dashboard All Rounders](https://github.com/mishraji900/Best_t20_team_2024/blob/main/Screenshot%202024-07-14%20041905.png)

#### Dashboard Bowlers

![Dashboard Bowlers](https://github.com/mishraji900/Best_t20_team_2024/blob/main/Screenshot%202024-07-14%20041914.png)
By focusing on the ICC Men's T20 2024 World Cup, this project aims to showcase the power of data analytics in enhancing team selection strategies and driving performance optimization in international cricket tournaments.
