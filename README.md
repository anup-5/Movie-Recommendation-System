
# Movie Recommendation System

![](https://camo.githubusercontent.com/1c502d149c62da4bd1055404c29743154b7bdd316aab0d466025751c2df7e163/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d332e382d626c756576696f6c6574)
![](https://camo.githubusercontent.com/8785a2cfa54ec466fe1d65c77a0aa7495f2b9188c4c46e50588f3bd65641dcd8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4150492d544d44422d666362613033)

A Content Based Recommender System which recommends movies similar to the selected movie.


## Demo

Web app - https://mrs-anup-5.herokuapp.com/


![Screenshot (1022)](https://user-images.githubusercontent.com/86401425/132566930-7d2d2c4b-640d-4c85-a057-ed07327b44fb.png)


![Screenshot (1020)](https://user-images.githubusercontent.com/86401425/132567001-b70ec2e2-0de4-4c95-b722-3c238e48d930.png)


![Screenshot (1021)](https://user-images.githubusercontent.com/86401425/132567069-2a5eeca7-1f4c-403c-b329-b29c2aadb3dd.png)

## How to get the API key?

Create an account in https://www.themoviedb.org/, click on the `API` link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your `API` sidebar once your request is approved.

## How to run the project in your local machine?

1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the [requirements.txt](https://github.com/anup-5/Movie-Recommendation-System/blob/main/requirements.txt) file with the command `pip install -r requirements.txt`.
3. Get your API key from https://www.themoviedb.org/. (Refer the above section on how to get the API key).
4. Replace YOUR_API_KEY inside `main.py` fileand hit save.
5. Open your terminal/command prompt from your project directory and run the file `main.py` by executing the command `python main.py`.
6. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
7. And That's it.

## Similarity Score :

How does it decide which item is most similar to the item user likes? Here we use the similarity scores.

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

## How Cosine Similarity works?

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

![Image](https://user-images.githubusercontent.com/36665975/70401457-a7530680-1a55-11ea-9158-97d4e8515ca4.png)

More about Cosine Similarity :

- [Understanding the Math behind Cosine Similarity](https://www.machinelearningplus.com/nlp/cosine-similarity/)

- [Understanding Cosine Similarity And Its Application](https://towardsdatascience.com/understanding-cosine-similarity-and-its-application-fd42f585296a)

## Technologies Used

#### Machine Learning Library
NumPy, pandas, scikit-learn, Natural Language Toolkit (nltk)

#### Framework
Streamlit

#### Deployment
Heroku


![Image](https://camo.githubusercontent.com/b1b924a3e0d388bc85e1ee54ad420f661bb82608b2b6321e86cbef8c8a61512b/68747470733a2f2f696d672e796f75747562652e636f6d2f76692f4b6c716e2d2d4d753270452f687164656661756c742e6a7067)
         
![Image](https://pbs.twimg.com/profile_images/1243623122089041920/gVZIvphd.jpg)

![Image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRu6yUDaBtdYOkNdKDAm437OnJWvvrDjPnby-IcEbfcDfWNaBfQKZhRhk54CgwzaeQXBFM&usqp=CAU)


## Dataset

Dataset - https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv
