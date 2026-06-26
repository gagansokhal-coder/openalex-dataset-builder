# OpenAlex Dataset Builder

A Python project demonstrating how to collect research paper metadata from the OpenAlex REST API and convert it into a machine learning-ready dataset.

## Project Overview

This project fetches research paper metadata from the OpenAlex API, processes the JSON responses using Pandas, and exports the final dataset as a CSV.

The goal is to demonstrate the complete data collection workflow used in many machine learning and data engineering projects.

## Features

* Fetch data from the OpenAlex API
* Handle paginated API responses
* Convert JSON into Pandas DataFrames
* Export datasets to CSV
* Ready for SQL, EDA, and Machine Learning

## Tech Stack

* Python
* Requests
* Pandas
* Jupyter Notebook

## Dataset

The generated dataset contains:

* OpenAlex Paper ID
* Title
* Display Name
* Publication Date
* Language

## Repository Structure

```text
data/
notebooks/
README.md
requirements.txt
```

## Getting Started

```bash
git clone https://github.com/<your-username>/openalex-dataset-builder.git
cd openalex-dataset-builder

pip install -r requirements.txt
```

Run the notebook inside the `notebooks` directory to generate the dataset.

## Dataset Download

The processed dataset is also available on Kaggle.

## License

This repository contains the data collection code. Please refer to OpenAlex for the original data licensing and attribution requirements.
