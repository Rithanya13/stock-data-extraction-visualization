# stock-data-extraction-visualization
Extract and visualize Tesla and GameStop stock data using yfinance API and web scraping. Creates interactive plots showing stock prices and revenue trends.
# �� Project Overview

This project showcases essential data science skills including:
- **Data Extraction**: Using APIs and web scraping to gather financial data
- **Data Cleaning**: Processing and preparing data for analysis
- **Data Visualization**: Creating interactive charts and graphs
- **Financial Analysis**: Analyzing stock performance and revenue trends

## 🚀 Features

- **Stock Data Extraction**: Automated retrieval of historical stock data using yfinance
- **Web Scraping**: Extraction of revenue data from financial websites
- **Interactive Visualizations**: Dynamic charts showing stock prices and revenue trends
- **Data Processing**: Comprehensive data cleaning and preprocessing
- **Comparative Analysis**: Side-by-side analysis of Tesla and GameStop performance

## 📊 Sample Visualizations

### Tesla Stock Analysis
![Tesla Stock Graph](tesla_graph.png)
*Interactive visualization showing Tesla's historical share price and revenue data*

### GameStop Stock Analysis
![GameStop Stock Graph](gamestop_graph.png)
*Interactive visualization showing GameStop's historical share price and revenue data*

**Note**: These are static screenshots. To view the interactive versions, run the notebook locally.

## ��️ Technologies Used

- **Python 3.x**
- **pandas**: Data manipulation and analysis
- **yfinance**: Yahoo Finance API for stock data
- **BeautifulSoup**: Web scraping and HTML parsing
- **requests**: HTTP library for web requests
- **Plotly**: Interactive data visualization
- **Jupyter Notebook**: Development environment

## 📁 Project Structure
tock-data-extraction-visualization/
├── Final Assignment-v2.ipynb # Main Jupyter notebook
├── README.md # This file
└── requirements.txt # Python dependencies
## 🎯 Key Components

### 1. Data Extraction
- **Tesla (TSLA) Stock Data**: Historical price data using yfinance
- **GameStop (GME) Stock Data**: Historical price data using yfinance
- **Revenue Data**: Web scraping from financial websites

### 2. Data Processing
- Data cleaning and formatting
- Removal of null values and empty strings
- Currency symbol and comma removal from revenue data

### 3. Visualization
- Interactive stock price charts
- Revenue trend analysis
- Comparative performance graphs

## �� Sample Output

The project generates interactive visualizations showing:
- Historical share prices for Tesla and GameStop
- Quarterly revenue data for both companies
- Time-series analysis up to June 2021

## 🚀 Getting Started

### Prerequisites
- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Rithanya13/stock-data-extraction-visualization.git
   cd stock-data-extraction-visualization
   ```

2. **Install required packages**
   ```bash
   pip install yfinance pandas requests beautifulsoup4 plotly nbformat
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook "Final Assignment-v2.ipynb"
   ```

## �� Usage

1. Open the Jupyter notebook
2. Run all cells sequentially
3. View the generated interactive visualizations
4. Analyze the stock performance and revenue trends

## 🎓 Learning Outcomes

This project demonstrates proficiency in:
- **API Integration**: Working with financial APIs
- **Web Scraping**: Extracting data from websites
- **Data Manipulation**: Cleaning and processing financial data
- **Data Visualization**: Creating meaningful charts and graphs
- **Financial Analysis**: Understanding stock market data
## �� Data Sources

- **Stock Data**: Yahoo Finance (via yfinance)
- **Revenue Data**: Web scraping from financial websites
- **Time Period**: Historical data up to June 2021

## �� Contributing

This is an educational project, but suggestions and improvements are welcome!

## 📄 License

This project is for educational purposes.

## 👨‍�� Author

**Rithanya Chandran**
- GitHub: [@Rithanya13](https://github.com/Rithanya13)

## �� Acknowledgments

- IBM Data Science Professional Certificate
- yfinance library developers
- Plotly for interactive visualizations
