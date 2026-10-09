# CodeAlpha Data Visualization — Book Dataset

## Project Overview

This project transforms a dataset of 1,000 books into clear, informative visualizations using Python, Pandas, and Matplotlib. It focuses on communicating insights through charts, KPI summaries, and data storytelling.

## Objective

* Transform raw data into visual formats.
* Identify patterns in book categories, ratings, and prices.
* Compare average prices across categories.
* Explore the relationship between ratings and prices.
* Present findings clearly to support data-driven understanding.

## Dataset

* **Records:** 1,000 books
* **Original columns:** 6
* **Source:** Books to Scrape
* **Fields:** Title, price, rating, availability, category, and product URL

## Technologies Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook
* VS Code
* Git and GitHub

## Visualizations Created

1. **Top 10 Most Common Book Categories:** Compares the most frequently represented categories.
2. **Book Rating Distribution:** Shows the number of books at each rating level.
3. **Book Price Distribution:** Displays the distribution of book prices.
4. **Average Price by Category:** Compares average prices among categories containing at least 10 books.
5. **Rating vs Price:** Uses a scatter plot to investigate the relationship between ratings and prices.
6. **KPI Summary:** Presents total books, average price, median price, and number of categories.
7. **Data Story:** Summarizes the key findings and limitations.

## Key Findings

* The dataset contains 1,000 books across 50 categories.
* The average book price is approximately **£35.07**.
* The median book price is approximately **£35.98**.
* The most common rating is one star, with 226 books.
* The Spearman correlation between rating and price is approximately **0.0292**, indicating an extremely weak relationship.
* All books are marked as "In stock", limiting availability analysis.
* The category value "Add a comment" appears in 67 records (6.7%) and requires further investigation.
* Average prices for categories with very few books may not be representative.

## Project Structure

```text
CodeAlpha_Data_Visualization/
├── data/
│   └── books_dataset.csv
├── notebooks/
│   └── visualization.ipynb
├── README.md
└── .gitignore
```

## How to Run

1. Clone or download this repository.

2. Open the project in VS Code.

3. Create and activate a Python virtual environment.

4. Install the required packages:

   ```bash
   python -m pip install pandas matplotlib jupyter ipykernel
   ```

5. Open `notebooks/visualization.ipynb` in VS Code.

6. Select the project environment as the notebook kernel.

7. Run the notebook cells in order.

## Conclusion

This project demonstrates how data visualization can make a dataset easier to understand. Charts and KPI summaries communicate category patterns, rating distributions, pricing patterns, and the relationship between ratings and prices. The accompanying data story highlights both useful insights and limitations that should be considered before making decisions.
