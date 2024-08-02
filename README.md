# Movies Exploratory Data Analysis (EDA)

### Overview
This project involves an exploratory data analysis (EDA) on a dataset containing information about movies. The analysis focuses on cleaning and processing the data, followed by exploring various insights using statistical and graphical methods. The primary goal is to uncover interesting patterns, correlations, and trends within the dataset.

### Dataset
The dataset contains information about 4,803 movies, including details such as budget, genres, revenue, runtime, popularity, release date, and more. After cleaning and removing unnecessary data, the final dataset used for analysis contains 3,229 entries with 12 features.

### Libraries Used
* Pandas: For data manipulation and analysis.
* NumPy: For numerical computations and data type conversions.
* Seaborn: For data visualization, particularly for generating attractive and informative statistical graphics.
* Matplotlib: For creating static, interactive, and animated visualizations in Python.
* Datetime: For handling and manipulating date and time data.
* JSON & ast: For parsing JSON-formatted data.

### Project Workflow
1. Data Cleaning and Preprocessing:

* Unnecessary columns were removed to focus on relevant data.
* Rows with missing or zero values in critical columns like budget, revenue, release_date, and runtime were discarded.
* The release_date column was converted to DateTime format, and the release year was extracted for further analysis.
* Data types were adjusted for easier manipulation, especially for numerical operations.
* JSON-formatted columns such as genres, production_countries, and spoken_languages were parsed and converted to a more manageable format.

2. Exploratory Data Analysis:

* Top 5 Most Expensive Movies: Identified and visualized the movies with the highest budgets.
* Top 5 Cheapest Movies: Analyzed the movies with the lowest budgets.
* Budget vs. Revenue Analysis: Investigated the relationship between a movie’s budget and its revenue.
* Top 5 Most Profitable Movies: Calculated and visualized the movies with the highest profits.
* Most Popular Movies: Sorted and visualised movies based on their popularity score.
* Highly Rated Movies: Identified and visualised movies with a rating above 7.
* Genre Frequency Analysis: Analysed and visualised the frequency of different genres within the dataset.

3. Data Visualisation:

* Created bar plots, line plots, and other visualisations to summarise key insights and trends.
* Three additional visualisations were generated:

  * Genre Popularity Over Time: Showed the evolution of genre popularity across different years.
  * Top 15 Countries by Popularity of Movies: Highlighted countries with the highest number of movies.
  * Popular Movies Over Time: Displayed the trend in the number of movies released per year.


### How to Run the Project

1. Clone the Repository:

  * bash: git clone <repository-url>

2. Install Dependencies:

* Make sure you have Python 3.x installed. Install the required libraries using pip:
  * bash: pip install pandas numpy seaborn matplotlib

3. Run the Notebook:

* Open the notebook in Jupyter or any other compatible environment and run the cells sequentially.

### Thank you, Farinaaz :)
