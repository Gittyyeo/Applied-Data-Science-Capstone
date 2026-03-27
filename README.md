SpaceX Launch Success Prediction

Overview

Space missions are extremely costly, with traditional rocket launches averaging around $165 million per mission.

SpaceX has significantly reduced these costs to approximately $60 million by successfully recovering and reusing the first stage of its rockets.

This project investigates the key factors that influence first-stage landing success, using data science techniques to analyse historical launch data and build predictive models.


Objective

The goals of this project is to:

-Predict whether a rocket landing will be successful
-Identify the key factors influencing landing outcomes
-Understand how variables such as payload, orbit, and launch site affect success rates


Dataset

The dataset consists of historical SpaceX launch records, including:

-Launch date
-Payload mass
-Orbit type
-Launch site
-Booster version
-Landing outcome

Data was collected through:

-Web scraping (Wikipedia)
-API sources (SpaceX data)


Methodology

1. Data Collection
- Web scraping was used to extract launch data from publicly available sources
- Data was structured into a usable tabular format

2. Data Wrangling
- Cleaned missing and inconsistent values
- Standardised formats
- Created a binary target variable for landing success
3. Exploratory Data Analysis (EDA)

EDA was conducted using both:

- Python visualisation (Seaborn, Matplotlib)
- SQL queries

Key relationships explored include:

- Flight number vs launch site
- Payload vs launch site
- Orbit type vs success rate
- Payload vs orbit type
-Y early launch success trends

4. Feature Engineering
- Converted categorical variables into numerical form
- Prepared data for machine learning models

5. Predictive Modelling
- Built classification models to predict landing success
- Evaluated performance using standard metrics


Key Insights

1. Success improves over time
Launch success rates show a clear upward trend, suggesting:
- operational learning
- improved reliability

2. Payload mass matters
Certain payload ranges are more likely to succeed
For example, successful drone ship landings were observed for payloads between 4000–6000 kg

3. Launch location matters
Launch sites are concentrated near coastal regions and the equator
These locations are chosen to:
- improve efficiency
- reduce risk during landing operations

4. Orbit type influences success

Different orbit types exhibit different success rates, indicating that mission type affects landing difficulty


Model Results

Machine learning models were used to predict landing success based on historical features.

The models demonstrate that:

- landing outcomes can be reasonably predicted
- multiple interacting factors (payload, orbit, site) influence success


Implications

This project highlights how data can support decision-making in high-cost operations:

- Enables risk estimation for future launches
- Helps optimise mission planning
- Demonstrates how operational data can improve system performance


Limitations
- Web-scraped data may contain inconsistencies
- Limited feature set may not capture full mission complexity
- Results depend on historical patterns, which may evolve over time
