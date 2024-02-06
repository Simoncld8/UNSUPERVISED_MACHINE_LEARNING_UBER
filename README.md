# UNSUPERVISED_MACHINE_LEARNING_UBER

## Description

One of the main pain point that Uber's team found is that sometimes drivers are not around when users need them. For example, a user might be in San Francisco's Financial District whereas Uber drivers are looking for customers in Castro.

Eventhough both neighborhood are not that far away, users would still have to wait 10 to 15 minutes before being picked-up, which is too long. Uber's research shows that users accept to wait 5-7 minutes, otherwise they would cancel their ride.

Therefore, Uber's data team would like to work on a project where their app would recommend hot-zones in major cities to be in at any given time of day.

## Goals
The project aims to create algorithms that will determine where are the hot-zones that drivers should be in.

## Dataset
The dataset consists of multiple CSV files in raw_data folder.

"taxi-zone-lookup.csv" can be used for further analysis

## Content
The project is organized into three main parts, each focusing on a specific aspect:

1. **Exploratory Data Analysis (EDA) of the Dataset**

2. **Data Preprocessing, Model Training (clustering)**
   - Preprocessing the data, which involves handling categorical and numerical values, and performing encoding.
   - Training two clustering models (DBSCAN and Kmeans).

3. **Visualization**
    - Visualization of hot-zones per hour and per day

## Usage

To utilize and explore this project, follow these steps:

1. **Clone the Repository:**

   git clone https://github.com/Simoncld8/UNSUPERVISED_MACHINE_LEARNING_UBER.git


2. **Install Dependencies:**

   pip install -r requirements.txt  

3. **Run the Analysis:**

   You will find all the analysis in the Jupyter Notebook provided (`Projet_Uber.ipynb`).


Contributors

Simon Claude

This project was undertaken as part of the "Data Science and Engineering Fullstack" program offered by Jedha. Its aim was to fulfill a component of the "Concepteur Développeur en Science des Données" certification.

