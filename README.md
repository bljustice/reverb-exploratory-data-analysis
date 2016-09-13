#Reverb.com Effects Pedal Exploratory Data Analysis and Clustering

##Summary
This repository contains several Jupyter notebooks written in Python 3.5 to explore a dataset including over 5000 effects pedals sold on Reverb.com. The CSV file included was created from data extracted from the Reverb.com listings API. Documentation on their APIs can be found at the link below.

https://dev.reverb.com/

Below are specific details about what's included in each notebook.

**reverb_eda_univariate.ipynb**
This notebook contains univariate exploratory data analysis of the effects pedals. [Plotly Offline](https://plot.ly/python/offline/) is used for visualization, and Pandas is used for the majority of data transformation and manipulation tasks.

**reverb_description_clustering.ipynb**
This notebook uses [TF-IDF](https://en.wikipedia.org/wiki/Tf%E2%80%93idf), [K-Means clustering](https://en.wikipedia.org/wiki/K-means_clustering), and [latent semantic analysis](https://en.wikipedia.org/wiki/Latent_semantic_analysis) to cluster together the majority of the effects pedals.

##Packages Used

* Scikit-Learn
* NLTK
* Pandas
* Plotly
* Re
