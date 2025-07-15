# 🌮 Taco Sales EDA Project

## Overview

This project explores a dataset of taco sales across several U.S. cities, including details such as order time, delivery time, taco type, tip amount and more. The goal of this exploratory data analysis (EDA) is to uncover insights into customer behaviour, delivery dynamics, and sales patterns.

## Dataset Summary

The dataset includes the following features:
- **Restaurant and Location**
- **Order and Delivery Timestamps**
- **Taco Characteristics** (Type, Size, Toppings)
- **Sales Metrics** (Price, Tip)
- **Operational Metrics** (Distance, Delivery Duration, Weekend Indicator)

## Tools Used

- **Python**
- **Pandas** and **NumPy** for data manipulation
- **Matplotlib** for visualisation
- **Jupyter Notebook** for interactive analysis

## Key Analysis Performed

- Time-based analysis (order hours, day of week)
- Sales trends by taco type, size, and city
- Tip behavior across variables (e.g., distance, delivery duration)
- Correlation studies between delivery experience and customer tipping
- Feature engineering (tip percentage, delivery efficiency)

## Conclusion

Through this analysis, I concluded that the dataset is synthetic. This assessment is based on the unusually clean and simplistic structure of the data, particularly in the distribution of categorical features and the limited noise in numerical features. A key example is the lack of correlation between delivery time and tip percentage — a relationship that, in real-world data, would likely show at least some pattern. The absence of this and other expected relationships suggests the data may have been programmatically generated with limited complexity.

While synthetic, the dataset still serves as a useful sandbox for EDA practice, allowing exploration of feature relationships, plotting, and hypothesis testing in a structured environment.

## Folder Structure

├── taco_sales_eda.ipynb # Jupyter notebook with all analysis and visualisations

├── taco_sales.csv # Dataset (synthetic)

└── README.md # Project documentation


## Next Steps (if expanded)

- Build a predictive model for tip percentage
- Cluster customers or orders based on taco preferences and behavior
- Deploy an interactive dashboard using Streamlit

## License

This project is for educational and portfolio purposes only. The dataset is synthetic and does not represent real customer data.
