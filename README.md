# 📊 Extracting and Visualizing Stock Data – Tesla and GameStop

## 📌 Project Overview

This project focuses on extracting, analyzing, and visualizing historical stock price and revenue data for two well-known companies: **Tesla (TSLA)** and **GameStop (GME)**.

Python libraries are used to collect stock market information, extract quarterly revenue data through web scraping, process the collected data, and create visualizations to understand changes in stock prices and company revenue over time.

## 🎯 Project Objectives

- Extract historical stock data using the yfinance library.
- Collect quarterly revenue information using web scraping.
- Clean and process the extracted datasets.
- Store the information using Pandas DataFrames.
- Visualize historical stock prices and revenue.
- Compare stock price and revenue trends through graphs.

## 🛠️ Technologies and Libraries Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Jupyter Notebook | Writing and executing Python code |
| yfinance | Extracting historical stock data |
| Pandas | Data manipulation and analysis |
| Requests | Downloading webpage content |
| BeautifulSoup | Extracting revenue data through web scraping |
| Matplotlib | Creating stock price and revenue graphs |

## 📂 Project Tasks

### 1. Tesla Stock Data Extraction
- Created a Tesla ticker object using the symbol `TSLA`.
- Extracted historical stock information using yfinance.
- Reset the DataFrame index.
- Displayed the first five rows of the dataset.

### 2. Tesla Revenue Data Extraction
- Downloaded webpage content using Requests.
- Parsed HTML using BeautifulSoup.
- Extracted quarterly Tesla revenue information.
- Cleaned the revenue data by removing dollar signs, commas, and empty values.
- Displayed the last five rows.

### 3. GameStop Stock Data Extraction
- Created a GameStop ticker object using the symbol `GME`.
- Extracted historical stock information using yfinance.
- Reset the DataFrame index.
- Displayed the first five rows of the dataset.

### 4. GameStop Revenue Data Extraction
- Downloaded webpage content using Requests.
- Extracted quarterly GameStop revenue information using BeautifulSoup.
- Cleaned the revenue column.
- Displayed the last five rows.

### 5. Tesla Stock and Revenue Visualization
Created graphs using Matplotlib to visualize:
- Historical Tesla share prices.
- Historical Tesla quarterly revenue.

### 6. GameStop Stock and Revenue Visualization
Created graphs using Matplotlib to visualize:
- Historical GameStop share prices.
- Historical GameStop quarterly revenue.

**Note:** The dashboard graphs display historical information up to June 2021, as specified in the assignment.

## 📈 Project Visualizations

The project includes four visual plots:

1. Tesla Historical Share Price
2. Tesla Historical Revenue
3. GameStop Historical Share Price
4. GameStop Historical Revenue

These visualizations help understand how stock prices and quarterly revenue changed over time.

## ⚙️ Installation and Execution

### Step 1: Clone the Repository

```bash
git clone https://github.com/AfraNibras/Tesla-GameStop-Stock-Analysis.git
```

### Step 2: Navigate to the Project Folder

```bash
cd Tesla-GameStop-Stock-Analysis
```

### Step 3: Install Required Libraries

```bash
pip install yfinance pandas requests beautifulsoup4 matplotlib
```

### Step 4: Open the Jupyter Notebook

```bash
jupyter notebook
```

Open `Revenue Data and Building a Dashboard.ipynb` and execute the cells in sequence.

## 📁 Repository Structure

```text
Tesla-GameStop-Stock-Analysis/
│
├── Revenue Data and Building a Dashboard.ipynb
│
└── README.md
```

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Extracting financial data using Python.
- Working with stock market information.
- Performing web scraping using BeautifulSoup.
- Cleaning and processing datasets using Pandas.
- Creating visualizations using Matplotlib.
- Working with Jupyter Notebook for data analysis.

## 👩‍💻 Author

**Afra Nibras**

GitHub: [AfraNibras](https://github.com/AfraNibras)

---

⭐ This project was completed as part of a Python-based financial data extraction and visualization assignment.
