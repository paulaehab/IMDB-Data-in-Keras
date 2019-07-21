# Machine Learning Engineer Nanodegree
# Deep Learning
## Project:IMDB_In_Keras 

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [keras](https://keras.io)


You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 

### Code

Template code is provided in the `IMDB_In_Keras.ipynb` notebook file. 

### Run

In a terminal or command window, navigate to the top-level project directory `IMDB-keras/` (that contains this README) and run one of the following commands:

```bash
ipython notebook IMDB-keras.ipynb
```  
or
```bash
jupyter notebook IMDB-keras.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data
This lab uses a dataset of 25,000 IMDB reviews. Each review comes with a label. A label of 0 is given to a negative review, and a label of 1 is given to a positive review. The goal of this lab is to create a model that will predict the sentiment of a review, based on the words in the review. You can see more information about this dataset in the Keras website.

Now, the input already comes preprocessed for us for convenience. Each review is encoded as a sequence of indexes, corresponding to the words in the review. The words are ordered by frequency, so the integer 1 corresponds to the most frequent word ("the"), the integer 2 to the second most frequent word, etc. By convention, the integer 0 corresponds to unknown words.

Then, the sentence is turned into a vector by simply concatenating these integers. For instance, if the sentence is "To be or not to be." and the indices of the words are as follows:

"to": 5
"be": 8
"or": 21
"not": 3
## Accuracy here is 
 0.85756
