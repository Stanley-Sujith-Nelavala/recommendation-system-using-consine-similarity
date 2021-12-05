# recommendation-system-using-consine-similarity
This system uses the data set scraped from IMDB website using scrapy. This code user cosine similarity to find the similar movies input the by user. 
The raw data scrapped from the IMDB site is cleaned using RE and Pandas libraries. and we use Tfidvectorizer to vectorize the required columns in the data (preferably cast, director, genre and year)
We input the data from the user and induvidually find all the smilar movies and do the same for all 5 inputs taken. we then merge all of them and sort them based on how often they repeat in the list of similar movies and output the top movies as recommendation to the user.

## Demo
 ![Demo](https://github.com/Stanley-Sujith-Nelavala/recommendation-system-using-consine-similarity/blob/main/Screenshot%20(18).png)
## Data Before Cleaning
 ![Data Before Cleaning](https://github.com/Stanley-Sujith-Nelavala/recommendation-system-using-consine-similarity/blob/main/1.png)
## Data after Cleaning
 ![Data after Cleaning](https://github.com/Stanley-Sujith-Nelavala/recommendation-system-using-consine-similarity/blob/main/2.png)
## List of lists with top recommendations from given input
 ![List of lists with top recommendations from given input](https://github.com/Stanley-Sujith-Nelavala/recommendation-system-using-consine-similarity/blob/main/3.png)
 
## required dependencies

-> widgetsnbextension

-> ipywidgets

-> voila

Install them using "pip install"


## Contributors
1. Vidya Sri Gummadi [coe19b040@iiitdm.ac.in](coe19b040@iiitdm.ac.in)
2. Vennela Kudala [coe19b032@iiitdm.ac.in](coe19b032@iiitdm.ac.in)
3. G V Sanjay Reddy [ced19i042@iiitdm.ac.in](coed9i042@iiitdm.ac.in)
4. Stanley Sujith Nelavala [coe19b043@iiitdm.ac.in](coe19b043@iiitdm.ac.in) 'Thats ME'

**This repo is made as a part of crowdhacks hackathon.
