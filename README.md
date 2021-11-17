# Proposal: Learn About restaurants and cafes in Riyadh
## Data Overview:
By exploring this data, we can find out what are the good places to visit along with ratings, likes, tips and their exact location. Likewise, what are people's preferences and tastes.
## Source:
from Kaggle website: https://www.kaggle.com/fahd09/riyadh-restaurants-20k
## Size of Data:
- Number of rows: 17276 
- Number of columns: 11
## Columns description:
Each row is a place(restaurant/cafe). Columns are as follows:

- name: The name of the restaurant. Some names are only available in Arabic.
- categories: The list of categories (in English) separated by a comma.
- address: The address according to foursquare. Unfortunately, it is the least useful column in the dataset because lots of resutrants lack a formal address. The future version of this dataset may include an enhanced address format.
- lat: Latitude.
- lng: Longitude.
- price: shows the price category (Cheap, Moderate, Expensive, Very Expensive)
- likes: The number of likes.
- photos: The number of photos. Photos themselves are not included.
- tips: The number of tips in Foursquare (e.g., Don't miss their pasta). Tips themselves are not included.
- rating: The average rating out of 10.
- ratingSignals: The number of raters.
## Question:
1. Is there a relationship between prices and ratings?
2. Does everyone who likes the place take a photo of it?
3. Does the location affect the prices of the place?
4. What are the most common areas where cafes and restaurants are located?
5. What is the ratio of restaurants, cafes and shops?
6. What are people's preferences for the type of categories?
7. What is the most liked type of restaurant?
## Tools:
- Libraries: 
pandas, numpy, matplotlib, geopandas, geopy, plotly_express
- Softwares: 
VSCode, Jupyter, GitHub
## MVP goals:
- Answer all the questions.
- Explore the good places to visit.
- Find out what people like.
