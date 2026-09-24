# Netflix Movies and TV Shows Analysis

## 📌 Project Overview

This project analyzes the **Netflix Movies and TV Shows dataset** to identify useful patterns and trends in Netflix content.

The analysis focuses on content type, release year, countries, genres, ratings, movie duration, TV show seasons, content added to Netflix, and sentiment analysis of descriptions.

An **interactive dashboard** is also developed using Python and `ipywidgets`, which runs directly inside **Google Colab**.

---

## 🎯 Project Objectives

* Analyze Netflix Movies and TV Shows data.
* Clean and prepare the dataset for analysis.
* Identify important content trends and patterns.
* Analyze countries, genres, ratings, and release years.
* Analyze movie duration and TV show seasons.
* Perform sentiment analysis on content descriptions.
* Create meaningful data visualizations.
* Develop an interactive dashboard inside Google Colab.
* Provide data-based insights and recommendations.

---

## 📊 Dataset

**Dataset:** Netflix Movies and TV Shows

**Rows:** 8,807
**Columns:** 12

The dataset contains information such as:

* Show ID
* Content Type
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre
* Description

### Dataset Source

[Netflix Movies and TV Shows Dataset – Zenodo](https://zenodo.org/records/13925131)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* ipywidgets
* TextBlob
* Google Colab
* Jupyter Notebook

---

## 🔄 Project Workflow

1. Import Python libraries
2. Load the Netflix dataset
3. Explore the dataset
4. Check missing values and duplicates
5. Clean and prepare the data
6. Perform Exploratory Data Analysis (EDA)
7. Create visualizations
8. Perform sentiment analysis
9. Build an interactive dashboard
10. Identify insights
11. Provide recommendations

---

## 📈 Exploratory Data Analysis

The project analyzes:

### 1. Movies vs TV Shows

Comparison of the number of Movies and TV Shows available in the dataset.

### 2. Content by Release Year

Analysis of how Netflix content has changed across different release years.

### 3. Content Added to Netflix

Analysis of the content added to Netflix over time.

### 4. Top Countries

Identification of countries contributing the most content.

### 5. Top Genres

Analysis of the most common genres/categories.

### 6. Ratings Distribution

Analysis of the distribution of Netflix content ratings.

### 7. Movie Duration

Analysis of movie duration using average, median, minimum, and maximum duration.

### 8. TV Show Seasons

Analysis of the number of seasons of TV Shows.

---

## 💭 Sentiment Analysis

Sentiment analysis is performed on Netflix content descriptions using **TextBlob**.

Descriptions are classified into:

* Positive
* Negative
* Neutral

The sentiment analysis represents the **tone of the descriptions** and does not represent viewer ratings or audience satisfaction.

---

## 📊 Interactive Dashboard

The project includes an interactive dashboard that runs directly inside **Google Colab**.

### Dashboard Filters

* Content Type
* Release Year
* Rating

Changing the filters updates the dashboard results.

### Dashboard Visualizations

* Movies vs TV Shows
* Content by Release Year
* Top Ratings
* Key Performance Indicators (KPIs)

No external server, Streamlit, ngrok, or deployment is required.

---

## ▶️ Setup and Run Instructions

### Step 1: Open Google Colab

Open the project notebook in Google Colab.

### Step 2: Upload the Dataset

Upload:

`netflix_titles.csv`

to the Google Colab session.

### Step 3: Run the Notebook

Run the notebook cells from top to bottom.

The notebook performs:

* Data loading
* Data cleaning
* Exploratory analysis
* Visualizations
* Sentiment analysis
* Interactive dashboard creation

### Step 4: Use the Dashboard

After running the dashboard cell, use the dropdown filters to explore the Netflix dataset interactively.

---

## 🔑 Key Insights

* The dataset contains more **Movies than TV Shows**.
* The **United States** contributes the largest amount of content in the dataset.
* International Movies and Dramas are among the most frequently listed categories.
* TV-MA and TV-14 are among the most common ratings.
* Most TV Shows contain a relatively small number of seasons.
* Movie durations vary considerably across the dataset.
* Netflix content descriptions contain positive, negative, and neutral language.

---

## 💡 Recommendations

Based on the analysis:

* Netflix can continue monitoring content trends across different countries and genres.
* Content categories and ratings can be analyzed to understand the overall content mix.
* Release-year trends can help identify changes in Netflix's content collection.
* Description sentiment can be used as an additional text-based analysis feature.
* Interactive filtering can help users explore the dataset based on their interests.

---

## 📁 Project Submission Files

The project submission contains **only these 4 required files**:

| File                                                                | Description                                                                           |
| ------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| `NaraharisettiVenkataApoorva_NetflixMoviesandTVShowsAnalysis.ipynb` | Complete Python project code                                                          |
| `requirements.txt`                                                  | Required Python libraries/dependencies                                                |
| `NaraharisettiVenkataApoorva_ProjectReport.docx`                    | Complete project documentation                                                        |
| `README.md`                                                         | Project overview, dataset link, technologies, setup instructions, and key information |

---

## 📌 Project Deliverables

### Code File

Complete project implementation in Jupyter Notebook format.

### Requirements File

List of Python libraries required to run the project.

### Project Report

Complete documentation of the project, analysis, visualizations, insights, and recommendations.

### README File

Brief project overview with dataset source, technologies, setup instructions, and key project information.

---

## 👩‍💻 Author

**Naraharisetti Venkata Apoorva**

B.Tech – Computer Science and Engineering
Graduated – 2025

---

## 🔗 References

* [Netflix Movies and TV Shows Dataset – Zenodo](https://zenodo.org/records/13925131)
* [Pandas Documentation](https://pandas.pydata.org/docs/)
* [NumPy Documentation](https://numpy.org/doc/)
* [Matplotlib Documentation](https://matplotlib.org/stable/)
* [Seaborn Documentation](https://seaborn.pydata.org/)
* [Plotly Documentation](https://plotly.com/python/)
* [ipywidgets Documentation](https://ipywidgets.readthedocs.io/)
* [TextBlob Documentation](https://textblob.readthedocs.io/)

---

## ✅ Project Status

**Completed**

The project includes data cleaning, exploratory data analysis, visualization, sentiment analysis, insights, recommendations, and an interactive dashboard running directly in Google Colab.
