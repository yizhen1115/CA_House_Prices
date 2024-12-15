
# California Residential Housing Price Prediction

## Project Overview

This project focuses on predicting the final closing price of residential properties in California using machine learning techniques. The dataset, sourced from the California Regional Multiple Listing Service (CRMLS), includes over 50,000 records and 27 features, many of which require preprocessing due to missing values.

## Environment Requirements

- Python 3.8
- Required packages are listed in `requirements.yaml`.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yizhen1115/CA_House_Prices.git
   cd CA_House_Prices
   ```
2. Create and activate a virtual environment:
   ```bash
   conda env create -f requirements.yaml
   conda activate ca_housing_price_prediction
   ```

## Data Description

Please see more detail from the [California Regional Multiple Listing Service](https://go.crmls.org).

## Directory Structure

```
.
├── data/              # Contains raw and preprocessed datasets
├── figures/           # Contains generated visualizations and plots
├── results/           # Contains saved models and predictions
├── report/            # Contains the final report in PDF format
├── src/               # Contains source code and notebooks
├── .gitignore         # Git ignore file
├── LICENSE            # Project license
└── README.md          # Project documentation
```

## How to Run

1. Ensure the dataset is placed in the `data/` folder.
2. Execute the main notebook in the `src/` directory to preprocess data, train models, and generate results.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
