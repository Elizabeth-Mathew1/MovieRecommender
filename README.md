# :performing_arts:  MovieRecommender
#### A simple web application that suggests you movies based on your entry.
---
### :mortar_board:  About the project

Movie Recommender recommends you top five movies based on a single entry of a movie. The project explores [content based filtering](https://www.educative.io/edpresso/what-is-content-based-filtering) 
of data, which is a type of recommender system that attempts to guess what a user may like based on that user’s activity. Content-based filtering makes 
recommendations by using keywords and attributes assigned to objects in a database. Youtube uses CBF along with other filtering techniques. 
The backend service is provided by [streamlit](https://docs.streamlit.io/) and is hosted on [Heroku](https://www.heroku.com/what).

The different stages of the project included:
  1) Preprocessing where the data from two csv files which contained information about 4086 movies were processed for futher detailing.
  2) Model building where a model was trained using the algorithm of k-nearest neighbours using CountVectorizer and cosine_similarity libraries.
  3) Website building done using streamlit
  4) Deployed on Heroku

[Click here to view the deployment](https://movie-recommender-system-liza.herokuapp.com/)

---
### :pencil2: Tools Used

1) Python 2.7 or greater
2) Natural Language Toolkit (NLTK)
3) Streamlit
4) Pickle
5) Requests
6) Sci-Kit learn
7) Numpy

and a few other libraries and dependencies for preprocessing.

---
### :circus_tent: Screenshots
1) Opening Screen

![Screenshot](https://i.postimg.cc/9Qb727xt/Screenshot-2021-12-11-at-9-33-57-PM.png)

2) Option Menu - I

![Screenshot](https://i.postimg.cc/GtP5hKTm/Screenshot-2021-12-11-at-9-33-45-PM.png)

3) Recommendations - I

![Screenshot](https://i.postimg.cc/xC5mfbTS/Screenshot-2021-12-11-at-9-34-05-PM.png)

4) Recommendations - II

![Screenshot](https://i.postimg.cc/8crTyqYn/Screenshot-2021-12-11-at-9-33-23-PM.png)


---

:round_pushpin: [Click Here](https://movie-recommender-system-liza.herokuapp.com/) to test the application on your own.

:star2: If you liked the application, make sure to star this repo, Thankyou.



