Pre-requisites :

import nltk.corpus 
from nltk.corpus import gutenberg
from nltk.corpus import brown
from nltk.text import Text
from nltk.corpus import stopwords
from scipy import spatial
import matplotlib.pyplot as plt
from sklearn.cluster import KMeans
from sklearn.metrics import silhouette_score
from sklearn.metrics import davies_bouldin_score
from sklearn.metrics import jaccard_score
import numpy as np
import re
import json
import string