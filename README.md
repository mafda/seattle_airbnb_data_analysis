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
CRISP-DM](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining).

What is expected to be achieved with the analysis of the **Airbnb dataset in
Seattle**? Some possible objectives may be:

- **Q1. Identify temporal patterns in reserves and prices.**
- **Q2. Evaluate customer satisfaction based on reviews.**
- **Q3. Determine factors that influence property prices.**
- **Q4. Analyze the demand and occupancy of properties.**

## References

- [Data Scientist Nanodegree
  Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025)
- [Seattle Airbnb Dataset](https://www.kaggle.com/datasets/airbnb/seattle/data)

---

made with 💙 by [mafda](https://mafda.github.io/)
