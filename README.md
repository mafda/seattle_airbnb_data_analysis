# Seattle Airbnb Data Analysis

The Seattle Airbnb dataset is a comprehensive collection of data related to
Airbnb listings in Seattle. It provides detailed information across several
aspects of the Airbnb ecosystem, including listings, calendar availability, and
user reviews.

The Seattle Airbnb dataset offers a rich source of information for analyzing
various aspects of Airbnb listings in Seattle, including trends in pricing and
availability, geographic distribution of listings, and customer satisfaction
based on reviews. This dataset is valuable for conducting detailed exploratory
data analysis (EDA), machine learning projects, and deriving insights into the
short-term rental market in Seattle.

The dataset is divided into three main files:

- `listings.csv`: Contains detailed information about each Airbnb listing in
  Seattle.
- `calendar.csv`: Provides daily availability and pricing information for each
  listing.
- `reviews.csv`: Contains user reviews for each listing.

## Project Setup

### Clone this repository

```shell
(base)$: git clone git@github.com:mafda/seattle_airbnb_data_analysis.git
(base)$: cd seattle_airbnb_data_analysis
```

### Configure environment

- Create the conda environment

    ```shell
    (base)$: conda env create -f environment.yml
    ```

- Activate the environment

    ```shell
    (base)$: conda activate seattle_airbnb
    ```

- Download the dataset from [Seattle Airbnb Open
  Data](https://www.kaggle.com/datasets/airbnb/seattle/data), create `data`
  folder and copy the data here.

    ```shell
    (seattle_airbnb)$: mkdir data
    ```

## Project Structure

```shell
.
├── README.md
├── data
│   ├── calendar.csv
│   ├── listings.csv
│   └── reviews.csv
├── environment.yml
└── src
    └── seattle_airbnb_data_analysis.ipynb
```

## Metodology

This project will follow [CRoss Industry Standard Process for Data Mining -
CRISP-DM](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining)
methodology.

### Key Highlights

- **Business Understanding**: Identify the key business questions, such as factors
  influencing occupancy rates, pricing strategies, and customer satisfaction.

- **Data Understanding**: Explore the structure and content of the dataset,
  including listings.csv, calendar.csv, and reviews.csv. Summarize the key
  attributes and their significance.

- **Data Preparation**: Clean and preprocess the data by handling missing values,
  converting data types, and normalizing text reviews. This step includes
  filtering non-English reviews for consistent sentiment analysis.

- **Modeling**: Apply statistical and machine learning models to analyze trends in
  occupancy rates, pricing, and sentiment from reviews. Use visualization
  techniques to illustrate temporal patterns and relationships.

- **Evaluation**: Assess the findings to ensure they address the initial business
  questions. Validate the models and analysis results for accuracy and
  reliability.

- **Deployment**: Document the insights and recommendations based on the analysis.
  Provide actionable strategies for optimizing listings, pricing, and improving
  customer experience.

## Findings

- **Occupancy Rates**: Identified seasonal patterns with peaks in January and July.
  Occupancy rates increased from March to July 2016, followed by a decline until
  January 2017.
- **Pricing Trends**: Prices showed a corresponding increase during high occupancy
  periods, peaking in July 2016. A slight decrease was observed from August to
  November 2016, with stability through January 2017.
- **Customer Satisfaction**: High levels of customer satisfaction were observed,
  with 97% positive reviews. Common positive keywords included "great," "clean,"
  "location," and "comfortable."

## References

- [Data Scientist Nanodegree
  Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025)
- [Seattle Airbnb Dataset](https://www.kaggle.com/datasets/airbnb/seattle/data)

---

made with 💙 by [mafda](https://mafda.github.io/)
