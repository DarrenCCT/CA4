# CA4 – Time Series Forecasting of Elon Musk's Tweet Sentiment (2016)

This project was completed as part of a MSc programme in Data Analytics. It involves applying both **Big Data Storage and Processing** techniques and **Advanced Data Analytics** to perform time series forecasting on the sentiment of Elon Musk's tweets from the year 2016.

## Project Structure

- **BDSP.ipynb** – Focuses on Big Data Storage and Processing using **Apache Spark** and **HDFS**. This part of the project demonstrates how to handle and process large datasets efficiently using distributed computing frameworks.
- **ADA.ipynb** – Implements Advanced Data Analytics techniques in Python to analyse and forecast the sentiment of tweets using **time series forecasting** models.

## Dataset

The dataset used in this project was sourced from Kaggle:
👉 [Elon Musk Tweets Dataset (Kaggle)](https://www.kaggle.com/datasets/kingburrito666/elon-musk-tweets)

Only tweets from **2016** were used for analysis and forecasting.

## Technologies Used

- Python (Jupyter Notebooks)
- Apache Spark
- HDFS (Hadoop Distributed File System)
- pandas, NumPy, matplotlib, seaborn
- scikit-learn
- Natural Language Processing tools
- Time Series Forecasting models

## How to Run

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/CA4.git
    cd CA4
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run Notebooks**:
    - Open Jupyter Lab or Jupyter Notebook:
      ```bash
      jupyter lab
      ```
    - Run `BDSP.ipynb` for the big data pipeline.
    - Run `ADA.ipynb` for analytics and forecasting.

> ⚠️ **Note**: To run the **BDSP** notebook, you’ll need access to an Apache Spark environment with HDFS configured.

---

## 📉 Disclaimer

> **Interpretation of visualisations and charts is intentionally limited in the notebooks.**  
> This is due to a course requirement mandating that analytical conclusions and detailed explanations be presented separately in the accompanying report.

---

## License

This project is licensed under the **MIT License**. See `LICENSE` for details.

## Author

- Darren Smith
