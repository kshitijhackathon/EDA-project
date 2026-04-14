# YouTube Data Analysis

A Python-based exploratory data analysis project on YouTube channel performance data. This notebook investigates patterns in subscribers, video views, earnings, uploads, channel types, countries, and creation trends using `pandas`, `matplotlib`, and `seaborn`.

---

## Project Overview

The goal of this project is to explore YouTube channel metrics and uncover interesting trends such as:

* Which categories attract the most subscribers
* How channel type affects performance
* Which countries contribute the highest subscriber totals
* How subscriber growth changes across years and months
* The relationship between subscribers, video views, earnings, and education-related indicators

This project is useful for practicing data cleaning, aggregation, and visualization in Python.

---

## Files Used

* `Youtube-analysis.ipynb` — main Jupyter Notebook
* `youtube_data.csv` — dataset used for analysis

> Note: Make sure the CSV file is in the same directory as the notebook before running it.

---

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Dataset Features Used

The notebook uses columns such as:

* `category`
* `channel_type`
* `subscribers`
* `video views`
* `video_views_rank`
* `Country`
* `created_year`
* `created_month`
* `subscribers_for_last_30_days`
* `uploads`
* `highest_monthly_earnings`
* `highest_yearly_earnings`
* `Unemployment rate`
* `Gross tertiary education enrollment (%)`
* `Latitude`
* `Longitude`

---

## Analysis Performed

### Data inspection

* `head()`
* `info()`
* `describe()`
* Missing value check
* Duplicate check

### Group-based analysis

* Mean subscribers by category
* Channel type distribution
* Total subscribers by country
* Average subscribers by creation year
* Median video views rank by channel type
* Maximum subscribers gained in last 30 days by country
* Total uploads by channel type
* Standard deviation of video views by category
* Minimum unemployment rate by country
* Average unemployment rate by channel type
* Subscriber trend by year and month
* Highest yearly earnings trend by country

### Visualizations

* Bar chart of mean subscribers by category
* Pie chart of channel type distribution
* Scatter plot of subscribers vs video views
* Bar chart of total subscribers by country
* Box plot of highest monthly earnings by channel type
* Stacked bar chart for subscribers by category and country
* Scatter plot of subscribers vs gross tertiary education enrollment
* Line plot of average subscribers for last 30 days by month
* Area chart for monthly subscriber trends

---

## Key Insights You Can Derive

* Some categories may consistently attract more subscribers than others.
* Channel type can influence uploads, views, and earnings.
* Subscriber concentration may differ significantly across countries.
* Creation year and month may show patterns in audience growth.
* Education, unemployment, and earnings-related variables can be compared with subscriber performance.

---

## How to Run

1. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

2. Open the notebook:

```bash
jupyter notebook
```

3. Run all cells in `Youtube-analysis.ipynb`.

4. Make sure `youtube_data.csv` is available in the same folder.

---

## Suggested Project Structure

```bash
youtube-analysis/
├── Youtube-analysis.ipynb
├── youtube_data.csv
└── README.md
```

---

## Future Improvements

* Clean and standardize column names
* Handle missing values more systematically
* Add correlation heatmaps
* Build country-wise and category-wise comparison dashboards
* Create a final summary section with business insights

---

## Author

Prepared as an exploratory data analysis project on YouTube channel statistics.

---

## License

This project is for learning and portfolio use.
