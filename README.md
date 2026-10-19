# CS-122: Final Project | Car Fuel Cost Comparison

## Authors

- Author #1: Sean Tadina
- Author #2: Omar Yassin

## Project Description

Our project will be a Python application that compares the estimated fuel costs of two gasoline cars. It will collect vehicle information, fuel economy ratings, and fuel prices from the FuelEconomy.gov API. Users will select two cars and enter their expected annual mileage. The program will calculate each car’s estimated monthly and yearly fuel costs and show the potential savings. A graph will display the comparison to help users see which car would cost less to fuel.

## Project Outline/Plan

### Interface Plan (Tentative)

- We plan to use Python's Tkinter library to create a GUI with two windows. 
- The main window will allow users to select the two cars they want to compare by using dropdowns where they select the year, make, model, and configuration, then they enter their expected annual mileage. 
- Fuel prices will be retrieved automatically from the API but sometimes prices vary per location so the user can optionally manually adjust the fuel price.  
- The results window will then display each estomated monthly and yearly fuel costs, potential savings, and a comparison graph. Users can save these results to view them again later.


### Data Collection and Storage Plan — Sean Tadina

- We will use Python’s requests library to collect vehicle information and fuel prices from the FuelEconomy.gov API. 
- We will save each selected car’s information, MPG ratings, fuel type, and comparison inputs in a CSV file.
- We will also add options to load saved information and retrieve updated fuel prices.

Data source: [FuelEconomy.gov Web Services](https://www.fueleconomy.gov/feg/ws/)

### Data Analysis and Visualization Plan — Omar Yassin

- We will use Pythoin to calculate the estimated monthly and yearly fuel costs of each car based on the combined MPG rating, annual mileage, and fuel price.
- We will compare the results to see which car would ultimately cost less to fuel and calculate the potential savings in dollars and percentages.
- We will use Matplotlib to create a bar graph comparing the annual fuel costs of both cars.
- The graph will include labels, cost values, and vehicle info to make the differences easy to visualize.

### Folder Structure & Branches (Tentative)

Structure:
```text
CS-122-Final-Project/
├── docs/
│   └── final_project_description.pdf
├── data/
│   ├── .gitkeep
│   └── comparisons.csv
├── outputs/
│   ├── graphs/
│   │   └── fuel_cost_comparison.png
│   └── comparison_results.csv
├── README.md
├── .gitignore
├── LICENSE
├── requirements.txt
├── main.py
├── main_window.py
├── data_collection.py
├── analysis.py
└── results_window.py
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
