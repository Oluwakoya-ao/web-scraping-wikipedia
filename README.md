# 🕸️ Web Scraping & Exploratory Data Analysis (EDA)

This repository contains a web scraping project using **BeautifulSoup** to extract data from Wikipedia. The dataset includes the **largest companies in the United States by revenue**. Following the scraping process, **exploratory data analysis (EDA)** was performed to uncover insights into the data.

---

## 📌 Project Overview

- **Source**: [Wikipedia - List of largest companies in the United States by revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)
- **Tools Used**:
  - `requests` – to fetch webpage content
  - `BeautifulSoup` – to parse HTML
  - `pandas` – for data wrangling
  - `matplotlib` & `seaborn` – for visualizations

---

## 📁 Files in this Repository

- `Web_Scraping_Wikipedia.ipynb`: Jupyter notebook containing the full code (scraping + EDA)
- `Web_Scraping_Wikipedia.pdf`: Exported PDF of the notebook
- `README.md`: This file

---

## 🧼 Data Cleaning

After scraping, the dataset underwent:
- Removal of special characters
- Conversion of string numbers to integers
- Handling missing values
- Standardization of column names

---

## 📊 EDA Highlights

- Distribution of revenue across companies
- Top companies by revenue
- Industry-wise segmentation
- Revenue growth comparisons

---

## 🛠️ How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/Oluwakoya-ao/web-scraping-wikipedia.git
    cd web-scraping-wikipedia
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook:
    ```bash
    jupyter notebook Web_Scraping_Wikipedia.ipynb
    ```

---

## 🧠 Insights

- Walmart leads as the highest revenue-generating company.
- Retail and healthcare dominate the top positions.
- Companies are primarily headquartered in states like California, Minnesota, and Arkansas.

---

## 📌 Note

This project is for educational purposes only. The scraped data is publicly available on Wikipedia.

---

## 📧 Contact

For questions or collaborations:
**Your Name**  
[LinkedIn](https://linkedin.com/in/yourprofile)  
your.email@example.com

