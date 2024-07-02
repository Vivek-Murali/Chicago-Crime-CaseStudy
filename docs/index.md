
<p align="justify"> 
This case study is a comprehensive analysis of data crimes from 2001 to present using various data engineering tools and practices. The goal of this project is to provide insights into crime trends, patterns, and correlations using datasets from Airflow, AWS, GCP, DBT, PySpark, PyFlink, and other related technologies.
<br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>
## Purpose
The purpose of this project is to:
* Analyze the impact of data crimes on law enforcement and communities
* Identify trends and patterns in data crime statistics
* Evaluate the effectiveness of different tools and practices in processing large datasets related to crime data
* Provide insights that can inform policy and decision-making for data crime prevention and mitigation.

#### Dashboard Visualization:
To visualize the trends and patterns in crime data, we will be creating a dashboard using Tableau, Power BI, or similar visualization tools. The dashboard will display key findings, including:

##### 1. Time series plots of crime rates over time
* Daily/weekly/monthly/yearly crime rates for different types of crimes (e.g. property crime, violent crime)
* Comparison of crime rates across different cities, states, or countries

##### 2. Geographic heat maps and choropleth maps
* Mapping crime hotspots and coldspots across different regions
* Visualizing the concentration of crimes in urban vs. rural areas

##### 3. Bar charts and scatter plots
* Comparing crime rates by different demographic factors (e.g. age, gender, income)
* Correlating crime rates with weather, economic, or other environmental factors

##### 4. Interactive filters and drill-downs
* Filtering by date ranges, geographic areas, or crime types to explore specific trends and patterns
* Drilling down into detailed crime statistics for specific cities or regions

## 🏁 Getting Started <a name = "getting_started"></a>

To get started with this project, follow these steps:

### 1. Clone the repository
```
git clone https://github.com/Vivek-Murali/data-crimes-case-study.git
```
### 2. Install the required tools:
    - [List tools]
    
See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo.

## 🔧 Running the tests <a name = "tests"></a>

Explain how to run the automated tests for this system.

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## 🎈 Usage <a name="usage"></a>

To use this project, follow these steps:

### 1. Load the dataset into your preferred tool
    - [List tools]

### 2. Run a query to analyze crime trends and patterns



## 🚀 Deployment <a name = "deployment"></a>

For deployment, we will be using AWS/GCP to scale the data processing tasks and handle large datasets. The comparison of practices section highlights the advantages of each tool for deployment.

## ⛏️ Built Using <a name = "built_using"></a>

This project was built using various data engineering tools and practices, including:

    - Airflow
    - AWS/GCP for deployment
    - DBT for database tasks
    - PySpark and PyFlink for processing large datasets


## ✍️ Authors <a name = "authors"></a>

- [@VivekMurali](https://github.com/vivek-murali) - Idea & Initial work

See also the list of [contributors](https://github.com/kylelobo/The-Documentation-Compendium/contributors) who participated in this project.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Hat tip to anyone whose code was used
- Inspiration
- References

## :balance_scale: Comparison of Practices <a name = "comparison"></a>
We have compared the performance, scalability, and ease of use of each tool in handling large datasets. This section provides a comprehensive overview of our findings.

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    |── setup              <- Folder conatins all DOcker Helm charts.
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io
