# Cryptocurrency Price Analysis with AI

This project leverages advanced AI models to analyze and predict cryptocurrency prices. By using machine learning techniques, the project aims to forecast market trends and provide actionable insights for better decision-making.

## Overview
The **Cryptocurrency Price Analysis with AI** project uses **Long Short-Term Memory (LSTM)** and **Artificial Neural Network (ANN)** models to process and predict time-series data of cryptocurrency prices. The project includes data preprocessing, model training, evaluation, and visualization.

## Features
- **Data Collection and Preprocessing**: Handles raw market data, performs cleaning, and structures it for analysis.
- **LSTM and ANN Models**: Implements deep learning models for accurate time-series forecasting.
- **Performance Evaluation**: Uses statistical metrics like RMSE, MAE, and R² to evaluate model accuracy.
- **Data Visualization**: Provides graphical representations of historical trends and predictions.

## Technologies Used
- **Programming Languages**: Python
- **Libraries and Frameworks**: Pandas, NumPy, TensorFlow, Keras, Matplotlib, Seaborn
- **Database**: MySQL (for data storage and retrieval)

## Project Structure
```
Crypto-Price-Analysis/
├── data/
│   └── crypto_data.csv       # Raw and processed data files
├── models/
│   ├── lstm_model.py         # LSTM implementation
│   └── ann_model.py          # ANN implementation
├── notebooks/
│   └── analysis.ipynb        # Jupyter notebook for EDA and visualization
├── scripts/
│   ├── data_preprocessing.py # Data preprocessing scripts
│   └── evaluation.py         # Model evaluation scripts
├── visuals/
│   └── charts/               # Generated charts and visualizations
├── README.md                 # Project documentation
└── requirements.txt          # Python dependencies
```

## Getting Started
To set up and run this project locally, follow these steps:

### Prerequisites
Ensure you have the following installed:
- Python 3.8 or above
- MySQL Server

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Matamsathwik/Crypto-Price-Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Crypto-Price-Analysis
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up the MySQL database and update the connection details in the configuration file.

### Usage
1. Run the data preprocessing script:
   ```bash
   python scripts/data_preprocessing.py
   ```
2. Train the models:
   ```bash
   python models/lstm_model.py
   python models/ann_model.py
   ```
3. Visualize the results using the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```

## Results
- **Prediction Accuracy**: LSTM models performed well in capturing time-series trends with a low error margin.
- **Visualization**: Historical and predicted prices are visualized for easy interpretation.

## Future Enhancements
- Integrate real-time data feeds for live price analysis.
- Develop a web interface for user interaction.
- Explore additional deep learning models like GRU and Transformers.

## Contact
Feel free to reach out for any questions or suggestions:

- Email: [matamsathwik27@gmail.com](mailto:matamsathwik27@gmail.com)
- LinkedIn: [Matam Sathwik](https://linkedin.com/in/your-profile)
- GitHub: [Matam Sathwik](https://github.com/Matamsathwik)

---

Thank you for checking out my project! I hope you find it insightful and valuable. 😊
