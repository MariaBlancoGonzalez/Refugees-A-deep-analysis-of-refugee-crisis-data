# Refugees a deep analysis of refugee crisis data

## Project description

This project aims to collect and analyze data on asylum and refugee requests in Spain and internationally. 
The data will be used to answer the following questions:

* How many people have applied for asylum in Spain over the years, and how many of those applications have been granted?
* What are the top 10 countries with the highest asylum application rates since 2010? What are the top 10 with the lowest?
* Depending on armed conflicts, for example, the Ukrainian-Russian conflict in 2022, has the number of applications from these two countries increased compared to previous years?
* Interactive maps of asylum requests in Spain over the years in each autonomous community.
* With spanish data, make comparisons with a gender perspective on asylum requests.

The project has developed a complete process for data collection, transformation, and analysis. The data processing is located in the Jupyter notebooks. These notebooks provide a detailed record of the steps taken transform and analyze the data.

## Data sources

* Internal Displacement Monitoring Centre
* Spanish government open data sources
* Kaggle

## Visualization

Visualization analysis has been develop in Tableau public. What you can find there:

**Interactive map about incoming refugee requests**
![assets/Map.png](https://github.com/MariaBlancoGonzalez/Refugees-A-deep-analysis-of-refugee-crisis-data/blob/main/assets/Map.png?raw=true)

**Interactive map about autonomous community requests**
![assets/MapCCAA.png](https://github.com/MariaBlancoGonzalez/Refugees-A-deep-analysis-of-refugee-crisis-data/blob/main/assets/MapCCAA.png?raw=true)

> [!IMPORTANT]  
> Tableau public project [here](https://public.tableau.com/views/Refugees-analysis-of-refugee-crisis-data/IntRef?:language=es-ES&:display_count=n&:origin=viz_share_link).

## Project Structure

```
Refugees-A-deep-analysis-of-refugee-crisis-data
.
├── assets
│   ├── Map.png
│   └── MapCCAA.png
├── data
│   ├── process
│   │   ├── AsiloCA.csv
│   │   ├── AsiloEspaña.csv
│   │   ├── DeplazConflictos.csv
│   │   └── PeticionesInternacionales.csv
│   └── raw
│       ├── Asilo2012
│       ├── Asilo2013.xlsx
│       ├── Asilo2014.xlsx
│       ├── Asilo2015.xlsx
│       ├── Asilo2016
│       ├── Asilo2017
│       ├── Asilo2018
│       ├── Asilo2019
│       ├── Asilo2020
│       ├── Asilo2021
│       └── IDMC_Internal_Displacement_Conflict-Violence_Disasters.xlsx
├── notebooks
│   ├── 1.0-data-preprocessing.ipynb
│   ├── 1.0-jqp-initial-data-exploration.ipynb
│   ├── 2.0-data-preprocessing.ipynb
│   └── 3.0-data-preprocessing.ipynb
└── reports
    ├── 1.0-jqp-initial-data-exploration.html
    └── README.md
```

> [!NOTE]  
> This project has been develop following [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/#directory-structure) structure.
