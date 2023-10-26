# SQL Database Creation and Python Analysis
Project using IMDB data to create a SQL database and use Python for data analysis.

## Project Overview
Ultimately, this project strives to discover, what makes a movie successful?

## Data Source:

Data was collected from The Internet Movie Database: https://datasets.imdbws.com

Data dictionaries for all datasets can be found here: https://developer.imdb.com/non-commercial-datasets/

Additional data was collecting using API calls with The Movie Database.

## Methods:
- Data was downloaded from IMDB's open data sets.
- Data sets were then filtered to include only full-length movies made in the United States between the years 2000-2021. The filtered data also removed movies missing values for genre or runtime, and only focused on fictional movies (not documentaries).
- Additional data was collected using API calls from TMBD. This allowed the data to include financial information, such as budget and revenue, and also added the MPAA rating of the film.
- Once all the data was collected and combined, basic EDA was performed to explore average revenue and budget per certification category.
- Next, the data was used to create a MySQL database. Tables were normalized as needed, and connected using primary and foreign keys.
- Then, hypothesis testing was done to see if this dataset could be statistically significant in the real world. The main question answered here is: does the MPAA rating of a movie (G/PG/PG-13/R) affect how much revenue the movie generates?
- Finally, linear regression models were tested on the data to generate revenue predictions. The models were tested for all linear regression assumptions, so that teh results of the predictions can be reliably trusted.

## Results:

## Limitations and Next Steps:

## For More Information:

For more information, or to answer any other questions, please contact:
- Kris Barbier
- krisbarbier02@gmail.com
