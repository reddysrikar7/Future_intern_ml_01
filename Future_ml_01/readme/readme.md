.

├── Data/

│   └── superstore\_sales.csv       # 📄 Input data file

├── Images/

│   └── \*.png                      # 📸 All saved visualizations

├── superstore\_analysis.py        # 🐍 Main Python script

└── README.md                     # 📘 Project documentation

Features

✅ Loads and processes superstore\_sales.csv



📆 Converts order dates to datetime format



📈 Monthly sales trend plot



🔮 Forecasts next 6 months of sales using Prophet



📊 Multiple visualizations:



Sales by Category (bar chart)



Sales by Segment (pie chart)



Profit by Segment (pie chart)



Top 10 States by Sales (bar chart)



🖼️ All visualizations saved to Images/ folder



📦 Requirements

Install required libraries using:



bash

Copy

Edit

pip install pandas matplotlib seaborn prophet

🧪 How to Run

Place the dataset in a folder named Data:



bash

Copy

Edit

Data/superstore\_sales.csv

Run the script:



bash

Copy

Edit

python superstore\_analysis.py

📸 Output Visualizations

All plots are saved in the Images/ folder:



Visualization	Filename

Monthly Sales Trend	monthly\_sales\_trend.png

Forecast Plot (6 months)	forecast\_plot.png

Forecast Trend \& Seasonality	forecast\_trend\_seasonality.png

Sales by Category	sales\_by\_category.png

Sales by Segment (Pie)	sales\_by\_segment.png

Profit by Segment (Pie)	profit\_by\_segment.png

Top 10 States by Sales	top\_10\_states.png



📈 Forecasting Model

The project uses Facebook Prophet for time series forecasting:



Automatically detects trend \& seasonality



Generates future dates \& predictions



Plots confidence intervals



💡 Future Enhancements

Add interactive dashboard (e.g., using Streamlit or Dash)



Include regional or product-level forecasts



Add user input filters



👨‍💻 Author

**Srikar Reddy**

Machine Learning | Visualization | Forecasting

