# recommendation-system-using-consine-similarity
This system uses the data set scraped from IMDB website using scrapy. This code user cosine similarity to find the similar movies input the by user. 
The raw data scrapped from the IMDB site is cleaned using RE and Pandas libraries. and we use Tfidvectorizer to vectorize the required columns in the data (preferably cast, director, genre and year)
We input the data from the user and induvidually find all the smilar movies and do the same for all 5 inputs taken. we then merge all of them and sort them based on how often they repeat in the list of similar movies and output the top movies as recommendation to the user.

**Front end part of the system is still to be linked to the recommenadation system.
*This repo is made as a part of crowdhacks hackathon.
