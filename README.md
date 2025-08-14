# YouTube Virality Analysis & Forecasting

This repository contains a comprehensive data science project focused on analyzing and forecasting YouTube video virality. The project utilizes a multi-method approach, combining supervised learning, unsupervised learning, statistical modeling, and time series analysis to provide a deep understanding of what drives video performance.

---

## 🚀 Project Description

The primary goal of this project is to develop a system for predicting and understanding viral content on YouTube. Using a dataset of video metadata and engagement metrics, the project's workflow covers:

- **Data Preprocessing**: Cleaning, preparing, and transforming raw data into a structured format suitable for analysis.
- **Exploratory Data Analysis (EDA)**: Visualizing trends and relationships to gain initial insights into the dataset.
- **Machine Learning Models**: Building predictive and clustering models to identify viral videos and performance patterns.
- **Statistical Analysis**: Quantifying the impact of various features on a video's view count.
- **Time Series Forecasting**: Predicting future performance trends using historical data.

The final output is a complete Python script that runs the entire analysis, from data loading to generating a project summary.

---

## ✨ Features

- **Data Cleaning and Preparation**: Robust functions to handle missing values, convert data types, and encode categorical variables.
- **Interactive Visualizations**: Plots for viewing trends over time, correlation heatmaps, and a breakdown of top-performing videos.
- **Supervised Learning**: A **Random Forest Classifier** to accurately predict video virality with high accuracy.
- **Unsupervised Learning**: **K-Means Clustering** to group videos into distinct performance categories (e.g., viral vs. normal).
- **Statistical Modeling**: **OLS Regression** to identify and quantify the statistical relationships between video features and performance metrics.
- **Time Series Forecasting**: An **ARIMA model** to predict future video performance based on historical trends.
- **Comprehensive Summary**: A final section that consolidates the key findings, including model accuracy, cluster counts, and dataset information.

---

## 🛠️ Technologies Used

-   **Python**: The core programming language for the project.
-   **Pandas**: For data manipulation and analysis.
-   **Scikit-learn**: For implementing machine learning models (Random Forest, K-Means).
-   **Statsmodels**: For statistical analysis and time series forecasting (OLS, ARIMA).
-   **Matplotlib & Seaborn**: For data visualization.
-   **Jupyter Notebook**: The development environment where the code was written and executed.

---

## 📖 Project Walkthrough

The project is structured into several key sections, each addressing a critical part of the data science workflow:

1.  **Data Preprocessing**: The code first loads a CSV file (`youtube_virality.csv`) and then cleans the data by handling missing values and preparing features for modeling.

2.  ### Visualizations

    * **Correlation Heatmap**: This visualization shows the relationships between numeric features. It reveals strong positive correlations between metrics like `views`, `likes`, and `comments`, suggesting they are key indicators of a video's popularity.
    * <img width="795" height="633" alt="Screenshot 2025-08-14 133447" src="https://github.com/user-attachments/assets/2534ab18-f651-42d7-8f28-ba59bc0a9226" />

    

    * **Top 10 Videos by Views**: This bar chart highlights the videos with the highest view counts, providing an immediate overview of the most popular content in the dataset.
    * Visualization : <img width="1112" height="586" alt="Screenshot 2025-08-14 133456" src="https://github.com/user-attachments/assets/ad1a32a6-5504-4c00-adf9-0f3619e1cb23" />

    

    * **K-Means Clusters**: This scatter plot visualizes the results of unsupervised learning. It shows how the videos are grouped into 3 distinct clusters based on their `views` and `likes`, helping to identify different performance segments.
    * <img width="725" height="538" alt="Screenshot 2025-08-14 022922" src="https://github.com/user-attachments/assets/dd2f30a0-851e-48a8-89ee-fa6258d60820" />

    

3.  **Supervised Learning**: A Random Forest Classifier is trained to predict a binary "viral" label, and its performance is evaluated with metrics like accuracy, a confusion matrix, and a classification report.

4.  **Statistical Modeling**: An OLS Regression model is fitted to understand the linear relationships between features, and the results are summarized to highlight significant factors.

5.  **Time Series Forecasting**: An ARIMA model is used to forecast future views, and the results are plotted against the actual data to show the model's predictive power.

6.  **Final Summary**: A concluding section provides a high-level overview of the project, summarizing key findings and model performance metrics.
    ## **Conclusion and Future Scope**

This project successfully implemented a comprehensive data science approach to analyze and forecast YouTube video virality. By integrating various machine learning and statistical models, the project not only provided a deep understanding of the factors driving video performance but also developed predictive capabilities.

The analysis confirmed that a video's virality is predictable, as demonstrated by the **Random Forest Classifier's 100.00% accuracy**. The use of **K-Means clustering** successfully segmented the videos into distinct performance groups, offering valuable insights into different content tiers. Furthermore, **OLS Regression** identified key features with a significant statistical impact on a video's view count, while the **ARIMA model** provided a reliable method for forecasting future performance trends.

**Learning Outcomes:**
This project served as a practical application of the data science principles taught, reinforcing skills in data preprocessing, model implementation, and performance evaluation. It also highlighted the importance of using a multi-method approach to gain a complete and actionable understanding of a dataset.

**Future Scope:**
To further enhance this project, future work could focus on several key areas:
- **Feature Engineering:** Exploring more advanced features, such as sentiment analysis of comments or video duration-to-views ratio, could improve model accuracy.
- **Model Tuning:** Optimizing hyperparameters for all models (Random Forest, K-Means, ARIMA) could lead to even more robust results.
- **Real-Time Analysis:** Integrating the model with a live data source via an API could enable real-time predictions and insights for new videos.
- **Deployment:** Developing a simple web application or dashboard to visualize the forecasts and model outputs would make the project's findings more accessible to a wider audience.
