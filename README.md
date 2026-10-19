# CS-122: Final Project | Car Fuel Cost Comparison

## Authors

- Author #1: Sean Tadina
- Author #2: Omar Yassin

## Project Description

Our project will be a Python application that compares the estimated fuel costs of two cars. It will collect vehicle information and fuel economy ratings from the FuelEconomy.gov API. Users will select two cars and enter their expected annual mileage and gas prices. The program will calculate each car’s estimated monthly and yearly fuel costs and show the potential savings. A graph will display the comparison to help users see which car would cost less to fuel.

## Project Outline/Plan

### Interface Plan (Tentative)

TODO: write here

### Data Collection and Storage Plan — Sean Tadina

We will use Python’s requests library to collect vehicle information and fuel prices from the FuelEconomy.gov API. We will save each selected car’s information, MPG ratings, fuel type, and comparison inputs in a CSV file. We will also add options to load saved information and retrieve updated fuel prices.

Data source: [FuelEconomy.gov Web Services](https://www.fueleconomy.gov/feg/ws/)

### Data Analysis and Visualization Plan — Omar Yassin

TODO: write here

### Folder Structure & Branches (Tentative)

Structure:
```text
CS-122-Final-Project/
├── README.md
├── .gitignore
├── LICENSE
├── requirements.txt
├── main.py
├── main_window.py
├── data_collection.py
├── analysis.py
├── results_window.py
└── data/
    ├── .gitkeep
    └── comparisons.csv
```

Branches:
```text
main
├── feature/interface
├── feature/data-collection
├── feature/cost-analysis
└── feature/visualization
```
### Development Steps

1. Test retrieving vehicle choices, MPG ratings, and fuel prices.
2. Add CSV saving and loading.
3. Build the vehicle selection and results windows.
4. Add fuel cost calculations and the comparison graph.
5. Connect the components and test different vehicles and inputs.
6. Update the README with installation instructions and possible future improvements.
