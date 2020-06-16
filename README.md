# Beer Recommender System

![Test Image 2](beer_3.jpg)


## What to drink next?

Once I moved to BC, I was overwhelmed by the number of beer brands available. I have always been a beer enthusiast and love to try new beers, but it was so hard to keep it up with the innovations.
After some research, I found out that, according to Beer Advocate, there are more than 300,000 beers listed.  There is an estimate of more than a million beer brands available worldwide. If you consider the average consumption per person of 200 cans in a year, it will take us around 5,000 years to try all the beers available and that’s what motivated me to create a beer recommender system.

The primary goal of my project was to create an engine that would learn from data about the beers, existing users and recommend beers to those users based on their preferences. I used a neural network model for that. 
The second goal was to be able to learn about the beers and its features to recommend to new users (cold start). To handle the cold start problem, I used the embeddings from the NN model, where each beer now is represented by a 50-dimensional vector. After normalizing the embeddings, the dot product between two embeddings becomes the cosine similarity. Using this technique, I was able to find the similarity between 2 beers.  I have also decided to use only BC Local Beers for that task to be able to recommend beers that are available in our region. 

Feel free to get beer recommendations here: https://recommender-beer.herokuapp.com/
Pick one of your favorite beers and check the beers the engine recommends :)



## Tools and Packages that I used for this project:


#### Web Scraping:
* Scrapy
* requests

#### Feature Engineering:
* Natural language processing
* TFIDF

#### Modeling/Machine Learning

* Scikit-learn
* Tensor Flow/ Keras
* Numpy
* Pandas
* Surprise

#### Data visualization:
* Matplotlib
* Seaborn
* Dash/Plotly
* Google Embedding Projector - TSNE and PCA visualization


![Test Image 1](beer_image.png)


Feedback is always welcome :)


Cheers!
