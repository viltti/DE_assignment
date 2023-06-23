# Ferry Data Analysis

This project aims to analyze data from ferry trips between Helsinki and Tallinn, and provide various insights.

## About the data

The [dataset](https://hri.fi/data/en_GB/dataset/matkustaja-alusten-aikataulu-liikennointi-ja-sijaintitietoja-helsingin-ja-tallinnan-valilla) contains a multitude of attributes for trips made by four different passenger ships. The key fields include
- Ship names
- Departure and arrival ports
- Scheduled departure and arrival times
- Estimated departure and arrival times
- Actual departure and arrival times
- And a few others

These attributes allow us to analyze and gain insights into the performance of the ferries and overall operations.

## Structure 

To keep things simple and clear, the projects structure is also rather simple:

```
.
├── data
│   ├── raw
│   └── processed
├── notebooks
│   └── 1.00-vil-ferrydata.ipynb
├── results
│   ├── metrics
│   └── figures
└── requirements.txt
```

## Run locally

**Clone the repository, navigate to the project directory, install dependencies and run the jupyter notebook:** jupyter lab / jupyter notebook / or launch in some appropriate IDE. Get the data from the link above, and put it in data/raw.
