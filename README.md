# Microsoft Movies Project

**Data Scientists** - Nathan Venos & Max Tingle 

**Flatiron School** - Module 1 Project


## Project Description

Microsoft hired us to help them understand the movie industry and make recommendations for their **new movie studio**. They have seen all the big companies creating original video content, and they want to get in on the fun. 

We have been charged with doing data analysis and creating a presentation that explores what other studios are doing and which films are doing the best at the box office. We have translated our findings into actionable insights for the CEO to use when deciding what type of films Microsoft should be creating. 


## Folder Contents

*When making your way through our repository, please follow the numbered list below to explore the steps of our analysis.*

1. README.md
2. Microsoft Studios Presentation (PDF)
3. Data Analysis (Technical Jupyter Notebook)
4. Data Cleaning (Technical Jupyter Notebook)
5. Data (Folder)
6. Figures (Folder)
7. Archive (Folder)


## Methodology 

After initial examination of the descriptive statistics of the data sets, we decided to define movie and studio success by engagement metrics - worldwide revenue and ratings multiplied by number of votes. Revenue reveals consumer engagement because it is a direct indicator of where consumers are spending their money. Second, ratings show the consumers' quality measure of a film and the number of votes measures the number of consumers who took time to leave a rating. When mean rating is multiplied by number of votes it gives a more scaled engagement metric.

We then asked three research questions. 
1. Which studios are the top studios by our defined engagement metrics?
2. What is the top genre produced by the top studios?
3. How does the top genre perform by our defined engagement metrics?

Next, we cleaned and joined the four datasets listed in data sources section below, before performing statistical analysis and visualizing our findings.


## Recommendations
In order to create movies that yield high consumer engagement in terms of revenue and ratings, we recommend that Microsoft use its technical proclivities to produce movies that are:
1. Animated,
2. Family-Friendly,
3. Top-Quality, and
4. Original Franchises.


## Data Sources

- Box Office Mojo
  - data
    - bom.movie_gross.csv.gz
  - documentation
    - scraped from [this page](https://www.boxofficemojo.com/yearly/chart/?view2=worldwide&yr=2010&p=.htm) (from 2010-2018).
    - revenue has already been converted into pure dollars
- IMDB
  - data
    - imdb.title.basics.csv.gz
    - imdb.title.ratings.csv.gz
  - documentation
    - All data has come from https://www.imdb.com/interfaces/, just filtered to only 2010-2018 movies.
- TheMovieDB.org
  - data
    - tn.movie_budgets.csv.gz
  - documentation
    - This comes straight from [The-Numbers.com](https://www.the-numbers.com/movie/budgets/all)
    - this includes all data from The Numbers! it is not subset to 2010-2018


## Responsibilities

- Project Methodology - Nathan & Max
- IMDb Data Clean & Join - Max
- BOM & TN Data Clean & Join - Nathan 
- Visualizations - Together (Nathan Driving)
- Visualization Bells & Whistles - Nathan
- Data Cleaning Technical Notebook - Max
- Data Analysis Technical Notebook - Nathan
- Presentation - Max

