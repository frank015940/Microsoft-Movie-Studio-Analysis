# Cinema Success Blueprint: Informing Microsoft's Movie Studio

## Introduction
Microsoft, a technology giant, is venturing into the movie industry by establishing a new movie studio. However, lacking experience in the film domain, they need to overcome the challenge of understanding what types of films are currently performing well at the box office. The objective is to analyze relevant data and provide actionable insights that will help Microsoft's movie studio leadership make informed decisions regarding the types of films they should produce to achieve success in the market.

### Problem statement
Identifying the types of films that are currently performing well at the box office to assist Microsoft's new movie studio in making informed decisions and maximizing their chances of success in the highly competitive movie industry.

### Specific objectives
Identify key factors, such as production budget and release year, that significantly impact a movie's commercial performance at the box office.

## Data Understanding 
- The project aims to explore the movie industry and provide insights for Microsoft's new movie studio. To accomplish this, several datasets have been provided:

* bom.movie_gross.csv: This dataset contains information about movie titles, studios, domestic gross revenue, foreign gross revenue, and release year.
* rt.movie_info.tsv: The dataset includes details about movies such as IDs, genres, writers, runtimes, and ratings.
* tmdb.movies.csv: It contains movie information like IDs, original language, titles, popularity, release dates, vote averages, and vote counts.
* tn.movie_budgets.csv: This dataset provides information about movie budgets, release dates, titles, domestic gross revenue, and worldwide gross revenue.

- Each dataset has different columns representing various aspects of movies, such as financials, ratings, genres, and release information.
- The datasets allow us to explore the performance of movies in terms of box office revenue, genres, ratings, and other relevant factors. By analyzing and combining these datasets, we can gain insights into successful movie genres, influential directors, the impact of ratings, and other factors that contribute to box office success.

## Data Wrangling
During the data wrangling phase, multiple datasets were merged using pandas based on key columns such as movie titles and release dates. The data was cleaned by handling missing values, converting data types, and removing unnecessary columns. Dollar signs and commas were removed from financial columns to enable numeric analysis.


## Exploratory Data Analysis
Exploratory data analysis was conducted to gain insights into the movie industry. Visualizations were created using matplotlib and seaborn to analyze the distribution of variables, explore relationships between variables, and identify patterns and trends. Key visualizations included the box office revenue by genre, the success rate of directors, and the correlation between runtime and box office revenue.

## Data Preprocessing
Data preprocessing involved transforming and manipulating the data to prepare it for analysis. This included converting date columns to datetime format, extracting the year from release dates, and calculating the total domestic gross revenue by genre. Outliers and missing data were also identified and handled appropriately.

## Conclusion
Based on the analysis, several key findings can be summarized. The most successful movie genres in terms of box office revenue were found to be Action, Adventure, and Comedy. Directors such as Mel Gibson, Peter Jackson, and Steven Spielberg had the highest average box office revenue. There was a positive correlation between runtime and box office revenue, suggesting that longer movies tend to generate higher revenue.

## Recommendations
* Microsoft's new movie studio should consider producing movies in the Action, Adventure, and Comedy genres, as they have shown higher box office revenue.
* Collaboration with successful directors like Mel Gibson, Peter Jackson, and Steven Spielberg could be beneficial in terms of revenue generation.
* It is recommended to focus on movies with longer runtimes, as they have a positive impact on box office revenue.

## Non Technical Presentation
To access the canvas slides click on the link [Presentation][https://www.canva.com/design/DAFj_a9dAPU/G8PCcq5VwJrDyH1PhXy5Cg/edit?utm_content=DAFj_a9dAPU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton]