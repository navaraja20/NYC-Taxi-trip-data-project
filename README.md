# 🚕 NYC Taxi Trip Data Analysis Project

[![Python 3.8+](https://img.shields.io/badge/python-3.8%2B-blue?style=flat&logo=python)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Latest-blue?style=flat&logo=pandas)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Latest-blue?style=flat&logo=numpy)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualizations-blue?style=flat)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Plots-blue?style=flat)](https://seaborn.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat)](https://opensource.org/licenses/MIT)

## 📌 Overview

This project performs **comprehensive exploratory data analysis (EDA)** and **statistical analysis** on NYC yellow taxi trip data. It uncovers patterns, trends, and insights about taxi usage, fares, distances, and passenger behavior in New York City.

## 🎯 Key Features

- 🔍 **Comprehensive EDA**: Detailed analysis of taxi trip patterns and distributions
- 📊 **Data Visualization**: Rich visualizations using Matplotlib and Seaborn
- 💰 **Fare Analysis**: Breakdown of pricing, surcharges, and tips
- 📍 **Geographic Patterns**: Distance and location-based analysis
- ⏰ **Temporal Trends**: Time-based patterns and seasonality
- 📈 **Statistical Insights**: Descriptive statistics and correlations
- 🎓 **Well-Documented**: Clear explanations and markdown annotations throughout

## 📦 Technologies Used

- **Languages**: Python
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Environment**: Jupyter Notebook
- **Statistical Analysis**: SciPy

## 📂 Project Structure

```
NYC-Taxi-trip-data-project/
├── README.md                     # Project documentation (this file)
├── NYC_Taxi_Analysis.ipynb       # Main Jupyter Notebook with complete analysis
└── data/                         # Dataset directory (NYC taxi data)
```

## 🚀 Installation & Setup

### Prerequisites
- Python 3.8 or higher
- pip package manager
- Jupyter Notebook

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/navaraja20/NYC-Taxi-trip-data-project.git
cd NYC-Taxi-trip-data-project

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install required dependencies
pip install pandas numpy matplotlib seaborn jupyter scipy

# 4. Launch Jupyter Notebook
jupyter notebook

# 5. Open the analysis notebook and run the cells
```

## 📊 Analysis Topics Covered

1. **Data Overview**: Dataset dimensions, data types, missing values
2. **Trip Distance Analysis**: Distribution and patterns
3. **Fare Analysis**: Average fares, surcharges, tips, and total amounts
4. **Temporal Analysis**: Peak hours, day-of-week patterns, seasonal trends
5. **Passenger Analysis**: Average passengers per trip
6. **Geographic Insights**: Pickup and dropoff location patterns
7. **Payment Methods**: Distribution of payment types
8. **Correlations**: Relationships between variables (distance, fare, tip)

## 📈 Key Insights

*Sample insights from typical NYC taxi data analysis:*
- Peak taxi usage occurs during morning (8-10 AM) and evening (5-7 PM) rush hours
- Average fare increases with trip distance
- Tips show correlation with fare amount
- Weekend usage patterns differ significantly from weekdays
- Certain pickup/dropoff locations dominate the data

## 💻 Usage

Simply open the Jupyter Notebook and run all cells to execute the complete analysis:

```bash
jupyter notebook NYC_Taxi_Analysis.ipynb
```

Then run cells sequentially to:
1. Load and explore the data
2. View summary statistics
3. Generate visualizations
4. Interpret findings

## 📚 Dependencies

See installation section. Main libraries:
- pandas (data manipulation)
- numpy (numerical computing)
- matplotlib (plotting)
- seaborn (statistical visualization)
- jupyter (interactive notebooks)
- scipy (statistical functions)

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Submit issues for bugs or suggestions
- Fork and submit pull requests
- Improve visualizations or analysis
- Add additional insights

## 📄 License

This project is licensed under the MIT License - see LICENSE file for details.

## 👤 Author

**Navaraja Mannepalli**
- GitHub: [@navaraja20](https://github.com/navaraja20)
- LinkedIn: [Navaraja Mannepalli](https://linkedin.com/in/navaraja-mannepalli)
- Email: navaraja13@gmail.com

## 🙏 Acknowledgments

- NYC taxi data source (public dataset)
- Data analysis best practices and EDA techniques
- Community contributions and feedback

## 📝 Notes

- This project uses publicly available NYC taxi data
- Analysis insights may vary depending on the dataset time period and size
- Visualizations are created using matplotlib and seaborn for clarity and publication quality

---

**Last Updated**: November 2025

*For questions or suggestions, please open an issue on GitHub.*
