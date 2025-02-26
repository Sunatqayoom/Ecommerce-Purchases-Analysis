# Ecommerce Purchases Analysis

This project is created for **learning purposes** and demonstrates how to analyze an e-commerce purchases dataset. It answers a few key questions related to the dataset and includes additional insights gained through data visualization.

## 📌 Features
- **Data Querying**: Extract meaningful insights from the dataset.
- **AM vs. PM Purchases**: Analyze and visualize whether people order more in the morning or evening.
- **Top Email Providers**: Identify the most commonly used email providers by customers.
- **Data Visualization**: Added charts to visually represent key findings.

## 📊 Key Insights
1. People tend to order **more in the PM** than in the AM.
2. The top 5 email providers used for purchases are displayed in a bar chart.

## 🚀 How to Run
1. Install required libraries:
   ```sh
   pip install pandas matplotlib seaborn
   ```
2. Open and run the Jupyter Notebook (`.ipynb`).
3. View the visualizations and analyze the results.

## 📈 Sample Visualization
Bar chart comparing AM vs. PM purchases:

```python
import matplotlib.pyplot as plt

time_counts = data['AM or PM'].value_counts()
time_counts.plot(kind='bar', color=['blue', 'orange'])
plt.xlabel('Time of Day')
plt.ylabel('Number of Purchases')
plt.title('Purchases in AM vs PM')
plt.show()
```

## 🔗 Connect
If you found this project helpful, feel free to **star ⭐ the repository** or suggest improvements! 😊

