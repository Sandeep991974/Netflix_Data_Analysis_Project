# 🎬 Netflix Data Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing the **Netflix Titles dataset** using Python to uncover meaningful insights about Netflix's content library.

The analysis explores different aspects of Netflix content, including **content ratings, top directors, top actors, yearly production trends, and country-wise content distribution**.

The project was developed using **Google Colab** and Python's data analysis and visualization libraries, with **Plotly** used to create interactive visualizations.

---

## 🎯 Objectives

The main objectives of this project are:

* Analyze the distribution of Netflix content ratings.
* Identify the top directors with the highest number of titles.
* Identify the top actors appearing in Netflix content.
* Analyze how Netflix content production has changed over the years.
* Identify countries contributing the most content to Netflix.
* Compare the production trends of Movies and TV Shows.
* Extract meaningful insights from the dataset using data visualization.

---

## 🛠️ Technologies Used

* **Python**
* **Google Colab**
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical operations
* **Plotly** — Interactive data visualization
* **Matplotlib** — Data visualization

---

## 📂 Dataset

The project uses the **Netflix Titles dataset**, which contains information about Netflix movies and TV shows.

Important attributes analyzed include:

* `title`
* `type`
* `director`
* `cast`
* `country`
* `release_year`
* `rating`
* `duration`
* `listed_in`

---

# 🔍 Analysis Performed

## 1. 🎯 Content Rating Distribution

A pie chart was used to analyze the distribution of Netflix content across different ratings.

The analysis helps understand what type of audience Netflix's content is primarily targeted toward.

### Visualization

The analysis includes ratings such as:

* TV-MA
* TV-14
* TV-PG
* R
* PG-13
* TV-Y7
* TV-Y
* PG
* TV-G
* and other available ratings.

### Key Observation

**TV-MA** represents the largest portion of the analyzed content, followed by **TV-14**, indicating a significant amount of Netflix's catalog is targeted toward mature and teenage audiences.

---

## 2. 🎥 Top 5 Directors on Netflix

The project identifies the directors who have contributed the highest number of titles to Netflix.

### Top Directors Identified

* Rajiv Chilaka
* Raúl Campos
* Jan Suter
* Marcus Raboy
* Suhas Kadav

A horizontal bar chart was used to compare the number of titles associated with each director.

---

## 3. 🎭 Top 5 Actors on Netflix

The `cast` column was transformed and analyzed to determine which actors appear most frequently in the Netflix dataset.

### Top Actors Identified

* Anupam Kher
* Rupa Bhimani
* Takahiro Sakurai
* Julie Tejwani
* Om Puri

This analysis required splitting the multiple actor names stored within individual rows and then counting their appearances across the dataset.

---

## 4. 📈 Netflix Content Production Trend

A yearly trend analysis was performed to understand how Netflix content production has changed over time.

The analysis compares:

* 🎬 Movies
* 📺 TV Shows

### Key Observation

Netflix content production increased significantly after the mid-2010s, with Movies showing a particularly strong growth trend.

TV Show production also increased substantially during the same period.

The visualization demonstrates the rapid expansion of Netflix's content library during the 2010s.

---

## 5. 🌎 Top Countries by Netflix Content

The country information was cleaned and transformed because multiple countries can be associated with a single Netflix title.

The analysis identifies countries with the highest number of titles.

### Major Countries Observed

* United States
* India
* United Kingdom
* Canada
* Japan
* France
* South Korea
* Spain
* Mexico
* Germany
* Australia
* Egypt
* Turkey

### Key Observation

The **United States** has the highest representation in the dataset, followed by **India** and the **United Kingdom**.

This highlights the strong contribution of both Western and international markets to Netflix's content catalog.

---

# 📊 Visualizations

The project contains interactive Plotly visualizations for:

| Analysis                    | Visualization        |
| --------------------------- | -------------------- |
| Content Rating Distribution | Pie Chart            |
| Top Directors               | Horizontal Bar Chart |
| Top Actors                  | Horizontal Bar Chart |
| Yearly Content Production   | Line Chart           |
| Country-wise Content        | Bar Chart            |

Plotly's interactive features allow users to hover over charts and explore individual data points.

---

# 🧹 Data Preparation

Several data-cleaning techniques were applied during the analysis.

### Missing Values

Missing values in columns such as:

* `director`
* `cast`
* `country`

were handled appropriately before analysis.

# 💡 Key Insights

Some important insights obtained from the analysis include:

1. **TV-MA is the dominant content rating** in the Netflix dataset.
2. Netflix has a strong presence of content targeted toward mature and teenage audiences.
3. **Rajiv Chilaka** appears among the most frequently represented directors.
4. **Anupam Kher** is among the most frequently appearing actors in the analyzed dataset.
5. Netflix content production increased dramatically during the 2010s.
6. Movies generally experienced greater growth than TV Shows during the analyzed period.
7. The **United States** contributes the largest amount of content.
8. **India** is one of the major contributors to Netflix's international content library.
9. Netflix's content catalog demonstrates significant international diversity.
10. The growth in content production indicates Netflix's rapid expansion of its global streaming library.

---

# 📁 Project Structure

```text
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb
├── netflix_titles.csv
├── README.md
└── screenshots/
    ├── content_rating.png
    ├── top_directors.png
    ├── top_actors.png
    ├── yearly_trend.png
    └── top_countries.png
```

---

# 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Sandeep991974/Netlify_Data_Analysis.git
```

### 2. Open the notebook

Open:

```text
Netflix_Data_Analysis.ipynb
```

using **Google Colab** or Jupyter Notebook.

### 3. Upload the dataset

Upload:

```text
netflix_titles.csv
```

### 4. Run the notebook

Execute the cells sequentially to reproduce the analysis and visualizations.

---

# 📚 Learning Outcomes

Through this project, I practiced:

* Data cleaning with Pandas
* Handling missing values
* Data transformation
* String manipulation
* GroupBy operations
* Aggregation
* Sorting and filtering
* Exploratory Data Analysis (EDA)
* Interactive visualization with Plotly
* Extracting business insights from data
* Working with real-world datasets

---

# 🔮 Future Improvements

Some possible improvements for this project include:

* Building a fully interactive Netflix analytics dashboard.
* Adding genre-level analysis.
* Performing movie vs TV Show comparison.
* Analyzing Netflix's most common genres.
* Performing duration analysis.
* Creating a geographic visualization of Netflix content.
* Adding statistical analysis and correlation studies.
* Deploying the dashboard as a web application.

---

# 👨‍💻 Author

**Sandeep Chaurasiya**

B.Tech Computer Science & Engineering Student

Interested in:

* Data Analytics
* Python
* Machine Learning
* Web Development
* Data Visualization

---

## ⭐ Project Highlights

> **Dataset → Data Cleaning → Exploratory Data Analysis → Visualization → Insights**

This project demonstrates how Python can be used to transform a raw dataset into meaningful and visually understandable insights.

If you find this project useful, consider giving the repository a ⭐ on GitHub.
