# Wavyr AI — Tracking Every Bar with Intelligence

![Signal Analyzer Banner](assets/screenshots/app_banner.png)

## 📊 Overview

Wavyr AI is Your personal Cellular Network Analyzer & Predictor 📶 
It is a powerful, interactive web application that helps students, telecom engineers, network administrators, and researchers analyze cellular network performance data and build predictive models. It combines data science and machine learning techniques with an intuitive interface to provide insights into network behavior and predict performance metrics.

## ✨ Features

- **Data Analysis**: Explore and understand your network data with statistical analysis and correlations
- **Model Training**: Build machine learning models for both regression and classification tasks
- **Prediction**: Make predictions on new data points using your trained models
- **Visualizations**: Generate insightful visualizations including:
  - Signal strength heatmaps
  - Network type performance comparisons
  - Throughput trends over time
  - Feature correlation analysis
  - Distribution analysis
  - Performance metric visualization
    
## 🧰 Technologies Used
-Python: The core programming language

-Streamlit: For the web interface

-Pandas & NumPy: For data manipulation

-Scikit-learn: For machine learning models

-Plotly & Matplotlib: For interactive visualizations

-Seaborn: For statistical visualizations

-Folium: For geospatial visualizations

## 🖼️ Screenshots

<div align="center">
  <img src="assets/screenshots/data_analysis.png" width="45%" alt="Data Analysis">
  <img src="assets/screenshots/model_training.png" width="45%" alt="Model Training">
  <img src="assets/screenshots/visualizations.png" width="45%" alt="Visualizations">
  <img src="assets/screenshots/predictions.png" width="45%" alt="Predictions">
</div>

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip or conda for package management

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/cellular-network-analyzer.git
cd cellular-network-analyzer
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run app.py
```

4. Open your browser and navigate to http://localhost:8501

## 📊 Sample Data

The application expects CSV files with some of the following columns:
- Network Type (e.g., 3G, 4G, 5G)
- Signal Strength (dBm)
- Data Throughput (Mbps)
- Latency (ms)
- Location data (Latitude, Longitude) - optional
- Timestamp - optional

A sample dataset is provided in the `data/` directory.

## 🔧 Usage

1. Upload your network data CSV file
2. Choose between Regression or Classification mode
3. Explore different sections from the navigation sidebar:
   - Data Analysis: Understand your data
   - Model Training: Train and evaluate ML models
   - Prediction: Make predictions with trained models
   - Visualizations: Generate visualizations from your data
   - About: Learn more about the application

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Owner
Mohamed Rashad M
