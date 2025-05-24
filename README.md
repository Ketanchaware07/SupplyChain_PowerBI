# Power BI Supply Chain Project

This repository contains a Power BI dashboard and supporting datasets for analyzing a supply chain system. It includes raw data files, a Power BI project file, and a Jupyter notebook for data exploration.

## 📁 Project Structure
power-bi-supply-chain/
├── data/ # Raw CSV data files
│ ├── disruptions.csv
│ ├── products.csv
│ ├── shipments.csv
│ ├── suppliers.csv
│ └── vendor_ratings.csv
├── notebooks/ # Jupyter notebooks for analysis
│ └── SupplyChain.ipynb
├── pbix/ # Power BI dashboard
│ └── Supply Chain Project.pbix
├── .gitignore # Git ignore rules
└── README.md # Project documentation

## 📊 Dashboard Overview

The Power BI dashboard visualizes key supply chain metrics:
- Supplier performance and ratings
- Shipment volumes and disruptions
- Product distribution and delivery patterns

## 📈 Data Sources

The following CSV files are included in the `data/` directory:
- `disruptions.csv`: Records of supply chain disruptions
- `products.csv`: Product information
- `shipments.csv`: Shipment data with volume and routes
- `suppliers.csv`: Supplier details
- `vendor_ratings.csv`: Performance ratings for vendors

## 🧪 Exploratory Analysis

Use the Jupyter notebook in the `notebooks/` folder (`SupplyChain.ipynb`) to:
- Clean and preprocess the data
- Perform basic visualizations
- Derive insights before modeling or dashboarding

## ⚙️ Requirements

- Power BI Desktop (to open `.pbix` file)
- Python 3.7+ (for running the notebook)
  - `pandas`
  - `matplotlib`
  - `seaborn`

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/power-bi-supply-chain.git
   cd power-bi-supply-chain
2. Open pbix/Supply Chain Project.pbix in Power BI Desktop.
3. Launch the notebook
   jupyter notebook notebooks/SupplyChain.ipynb
