# twitter-user-classification
Twitter user classification tutorial at PyCon France 2016

__Setting up__:
- Clone this repo using

  `git clone https://github.com/dsquareindia/twitter-user-classification.git`
  
- Install `virtualenv` using

  `pip install virtualenv`
  
- Install all requirements in the virtualenv

  ```
  cd twitter-user-classification
  virtualenv gensim
  source gensim/bin/activate
  pip install -r REQUIREMENTS.txt
  ```
  
- Download pre-trained stanford GloVe vectors from [here](http://nlp.stanford.edu/data/glove.twitter.27B.zip)
- Download nltk data using
  `python -m nltk.downloader corpus`
- Unzip `pycon_dict_pkl.zip` to extract `pycon_dict.pkl` which is our toy dataset.
