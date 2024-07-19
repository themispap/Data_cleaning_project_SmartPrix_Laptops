# Data Cleaning Project: SmartPrix Laptop Unclean Dataset

## Project Description

This project focuses on cleaning and preparing the 'SmartPrix Laptop Unclean Dataset' for further analysis. The dataset contains information about all the laptops available online on the SmartPrix website in India for the month of March 2024. The data cleaning process involves handling missing values, correcting data types, removing duplicates, and addressing any inconsistencies in the dataset.

## Dataset

The dataset used in this project is the 'SmartPrix Laptop Unclean Dataset', which includes the following columns:

- `name`: The name of the laptop.
- `price`: price
- `spec_score`
- `votes`: Number of votes
- `user_rating`
- `os`: Operating system
- `utility`
- `thickness`: The thickness
- `weight`: The weight
- `warranty`: The warranty period
- `screen_size`: The screen size
- `resolution`: The screen resolution
- `ppi`
- `battery`: The battery capacity
- `screen_feature1`
- `screen_feature2`
- `processor_name`: The name of the processor
- `processor_speed`: The processor's speed
- `no_cores`: The number of cores
- `caches`
- `graphics_card`: The name of the graphics card
- `rom_memory`: ROM size
- `internal_memory`: RAM size
- `port_connection`
- `wireless_connection`
- `usb_ports`
- `hardware_features`

## Tools and Libraries Used

- **Python**: The programming language used for the project.
- **Pandas**: A powerful data manipulation and analysis library for Python.
- **Jupyter Notebook**: An open-source web application that allows you to create and share documents that contain live code, equations, visualizations, and narrative text.

## Data Cleaning Steps

1. **Loading the Dataset**: Importing the dataset using Pandas.
2. **Handling Missing Values**: Identifying and dealing with missing values in the dataset.
3. **Correcting Data Types**: Ensuring all columns have the correct data types.
4. **Removing Duplicates**: Identifying and removing duplicate records.
5. **Addressing Inconsistencies**: Correcting any inconsistencies in the dataset.
6. **Standardizing Data**: Standardizing the format of various columns, such as price and storage capacity.

## How to Run the Project

1. **Clone the Repository**: Clone this repository to your local machine using:
   ```sh
   git clone https://github.com/your-username/smartprix-laptop-data-cleaning.git
   ```

2. **Navigate to the Project Directory**:
   ```sh
   cd smartprix-laptop-data-cleaning
   ```
   
3. **Install Required Libraries**: Install the required libraries using:
   ```sh
   pip install -r requirements.txt
   ```

4. **Open the Jupyter Notebook**: Launch Jupyter Notebook to view and run the project:
   ```sh
   jupyter notebook
   ```
   
5. Run the Notebook:
   Open and run the data_cleaning.ipynb notebook to see the data cleaning process.

## Results

The cleaned dataset is saved as cleaned_smartprix_laptops.csv and is ready for further analysis or machine learning tasks. The cleaning process ensures that the dataset is free of inconsistencies, missing values, and duplicates, providing a reliable basis for any subsequent analysis.

## Repository Structure

   ```kotlin
smartprix-laptop-data-cleaning/
│
├── data/
│   └── smartprix_laptops_unclean.csv
│
├── cleaned_data/
│   └── cleaned_smartprix_laptops.csv
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── README.md
│
└── requirements.txt
   ```

## requirements.txt

- `pandas`
- `jupyter`

## Acknowledgements

The data is of all the Laptops available online on SmartPrix website in India in the month of March of 2024. (dataset from [kaggle](kaggle.com))
