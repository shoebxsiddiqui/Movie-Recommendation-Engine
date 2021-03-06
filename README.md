# MOVIE RECOMMENDATION ENGINE

![Python](https://img.shields.io/badge/Python-3.8-blueviolet)
![Framework](https://img.shields.io/badge/Framework-Flask-red)
![Frontend](https://img.shields.io/badge/Frontend-HTML/CSS/JS-green)
![API](https://img.shields.io/badge/API-TMDB-fcba03)

I've made a web application called “Cinemate” that demonstrate the working of a Movie Recommendation engine which supports all languages movies and have some extra features !!!

Movies have always been a substantial part of entertainment in our history and specially in this current world which is amidst a pandemic, movies have played a large role by helping people to relax their mind. But when you watch a movie the next big question is “WHAT NEXT?” it is the most confusing question that almost everyone has and to solve this problem I have created this project. It is a Content Based Recommendation System that recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

## Link to the application

Check out the live demo: https://movie-recommendation-engine1.herokuapp.com/

Check out the ppt:https://docs.google.com/presentation/d/1GxdCzoW5LBRJvjp8lu9AvCMbyymUwF8d/edit?usp=sharing&ouid=104805178903118814803&rtpof=true&sd=true

## Note

Don't worry if the movie that you are looking for is not auto-suggested. Just type the movie name and click on "enter". You will be good to go even though if you made some typo errors.


# How I got the details of the movie ?

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using `beautifulsoup4` and performed sentiment analysis on those reviews.

## How to get the API key?

Create an account in https://www.themoviedb.org/, click on the `API` link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your `API` sidebar once your request is approved.

# How to run the project?

1. Clone this repository in your local system.
2. Install all the libraries mentioned in the [requirements.txt](https://github.com/shoebxsiddiqui/Movie-Recommendation-Engine/blob/main/requirements.txt) file with the command `pip install -r requirements.txt`.
3. Replace YOUR_API_KEY in **both** the places (line no. 23 and 43) of `static/recommend.js` file.
4. Open your terminal/command prompt from your project directory and run the `main.py` file by executing the command `python main.py`.
5. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
6. Hurray! That's it.

### Sources of the datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

Please do ⭐ the repository, if it helped you in anyway.

Made with 💖 by Shuaib.
