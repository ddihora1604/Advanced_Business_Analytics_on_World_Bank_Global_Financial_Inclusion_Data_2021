## 🚀 Project Overview
This project analyzes global financial inclusion data using the Global Findex dataset, focusing on understanding patterns of digital payments, account ownership, and financial services accessibility across different demographics and regions. The analysis leverages machine learning techniques to identify key factors influencing financial inclusion.

## 🎯 Key Features

### Data Analysis
- **Exploratory Data Analysis**: Comprehensive statistical analysis of financial inclusion metrics
- **Demographic Insights**: Analysis of financial access across age, gender, and income groups
- **Geographic Distribution**: Regional comparison of financial inclusion indicators
- **Correlation Analysis**: Identification of relationships between different financial behaviors

### Machine Learning
- **Feature Importance**: Identification of key factors affecting financial inclusion
- **Predictive Modeling**: Random Forest classification for financial behavior prediction
- **Model Evaluation**: Performance metrics and validation techniques
- **Cross-validation**: Robust model evaluation using k-fold validation

### Visualization
- **Interactive Plots**: Visual representation of financial inclusion metrics
- **Heatmaps**: Correlation analysis visualization
- **Distribution Plots**: Analysis of key variables across different demographics
- **Comparative Analysis**: Visual comparison of financial behaviors

## 🛠️ Installation Guide

### Prerequisites
- Python 3.9+
- Jupyter Notebook
- Required Python packages (see requirements.txt)

### Setup
1. Clone the repository:
   ```bash
   git clone [your-repository-url]
   cd [repository-name]
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 📁 Project Structure
```
Financial-Inclusion-Analysis/
├── data/                           # Data files
│   ├── micro_world_139countries.csv  # Main dataset
│   └── CountryLevel_DatabankWide.xlsx  # Supplementary data
│
├── notebooks/                      # Jupyter notebooks
│   ├── AIChemists.ipynb           # Main analysis notebook
│   └── Findex.ipynb               # Additional analysis
│
├── outputs/                       # Generated outputs
│   ├── plots/                     # Visualization outputs
│   └── models/                    # Saved models
│
├── presentations/                 # Presentation materials
│   ├── SAS GIM Bitathon 2025.pptx
│   └── AIChemists.pptx
│
├── docs/                          # Documentation
│   ├── GlobalFindex2021_MicrodataCodebook.pdf
│   └── Little Data Book on Financial Inclusion.pdf
│
├── requirements.txt               # Python dependencies
└── README.md                     # Project documentation
```

## 🛠️ Technical Stack
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: scikit-learn
- **Data Visualization**: Matplotlib, Seaborn, Plotly
- **Geospatial Analysis**: GeoPandas
- **Notebook Environment**: Jupyter

## 📝 Usage
1. Open the Jupyter notebooks in the `notebooks/` directory
2. Run the cells sequentially to perform the analysis
3. The notebooks are well-documented with markdown cells explaining each step

### Key Notebooks:
- `AIChemists.ipynb`: Main analysis notebook with data exploration and modeling
- `Findex.ipynb`: Additional analysis focusing on specific financial inclusion metrics

## 📊 Data Sources
- **Global Findex Database**: [micro_world_139countries.csv](./micro_world_139countries.csv) - Microdata from 139 countries
- **World Bank Databank**: [CountryLevel_DatabankWide.xlsx](./CountryLevel_DatabankWide.xlsx) - Supplementary country-level financial indicators

## 📄 License
[Specify your license here]

## 🤝 Contributing
[Your contribution guidelines]

## 📧 Contact
[Your contact information]
