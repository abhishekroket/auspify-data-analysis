# Netflix Data Analysis using Python

Internship project for Auspify Technologies (Data Analysis Using Python).
Completed 4 of 6 tasks using Python, Pandas, Matplotlib and Seaborn on the Netflix Movies and TV Shows dataset (8,790 titles).

## Tasks Completed

| Task | Folder | Summary |
|---|---|---|
| 1. Data Cleaning & Preparation | `task1_cleaning` | Handled missing values and duplicates, standardized Country, Rating and Type, converted dates and exported a cleaned dataset |
| 2. Content Type Analysis | `task2_content_type` | Compared Movies (69.7%) and TV Shows (30.3%) with bar, pie and stacked charts |
| 3. Country-Wise Analysis | `task3_country` | Ranked content-producing countries; the US leads with 38.1% and the top 10 account for 77.9% |
| 4. Trend Analysis by Release Year | `task4_trends` | Analyzed yearly releases, found the peak in 2018 and the growth and decline trends |

## Project Structure

    auspify-data-analysis/
    ├── data/
    ├── task1_cleaning/
    ├── task2_content_type/
    ├── task3_country/
    ├── task4_trends/
    └── README.md

## How to Run

1. Install the libraries: `pip install pandas matplotlib seaborn jupyter`
2. Place `netflix_titles.csv` in the `data/` folder.
3. Run the notebooks in order, starting with `task1_cleaning`. It creates `netflix_cleaned.csv`, which the other tasks use.

## Author

Your Name: Abhishek kumar Singh