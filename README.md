IMDb Movie Ratings Analysis 🎥

Overview

This project explores patterns and trends in IMDb movie ratings using a dataset of the top 1,000 movies. The analysis covers:

Rating distributions and summary statistics

Highest-rated movies and directors

Genre-level average ratings

Relationship between duration and rating

Top grossing movies based on box-office revenue

Dataset

Source: Kaggle – IMDb Top 1000 Movies Dataset

Link: https://www.kaggle.com/datasets/sajjad2goudarzi/imdp-top-1000-csv

Contents: Includes columns such as movie_title, imdb_score, Meta_score, duration, genre, gross, director_name, and more.

Tools & Libraries

Python 3

pandas

matplotlib

seaborn

collections (Counter)

Jupyter Notebook

Analysis Steps

Data Loading & Cleaning

Loaded the CSV into a DataFrame

Handled missing values in Meta_score and gross

Rating Distribution

Plotted histogram of IMDb scores

Calculated summary statistics (mean, median, mode)

Top Rated Movies & Directors

Identified the top 10 movies by IMDb score

Found directors with the highest average ratings

Genre Analysis

Split multi-genre entries and computed average ratings per genre

Visualized the top genres by average score

Duration vs Rating

Converted movie durations to numeric minutes

Explored correlation between duration and IMDb score

Box-Office Gross

Cleaned gross revenue data and converted to numeric

Listed the top 10 highest grossing movies

Key Insights

High Ratings Concentration: Most IMDb scores cluster between 7.0 and 8.5.

Top Directors: [Director A], [Director B], and [Director C] have the highest average scores among directors with ≥10 films.

Genre Performance: Documentaries and Biography films tend to have slightly higher average ratings.

Duration Correlation: Longer movies (150+ minutes) show a mild positive correlation with higher ratings.

Box-Office Leaders: The top grossing movies include blockbusters like Avatar and Titanic.

How to Run

Clone this repository:

git clone https://github.com/your-username/IMDb_Movie_Analysis.git

Navigate to the project folder:

cd IMDb_Movie_Analysis

Install dependencies (if needed):

pip install pandas matplotlib seaborn

Open the Jupyter Notebook:

jupyter notebook IMDb_Movie_Analysis.ipynb

Run all cells to reproduce the analysis and visualizations.

Conclusions

IMDb ratings offer valuable insights into movie quality distribution and trends.

Specific genres and directors consistently receive higher ratings.

Duration and rating correlation suggests audience preference for longer films.

Box-office success does not always align with IMDb score but highlights commercial appeal.

Feel free to raise an issue or submit a pull request with suggestions or improvements!

