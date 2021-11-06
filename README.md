# Movies-ETL
---
Analysis of movies from 1980 to 2018
## Objective
---
Using ETL to extract date from different sources, used python and pandas
to clean the data before loading the data into a Postgress DB for use.  The 
source for movie data was kaggle and screen scraping from wikiopidia via JSON
The rating file was so large the data had to be chunked before loading to Postgres
 
### Movies Table
---
![Movies Table](/Resources/movies_query.png)

### Ratings Table
![Ratings Table](/Resources/ratings_query.png)