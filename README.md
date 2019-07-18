# Sentence-Similarity-Check-Using-NLP
In this we will solve sentence similarity problem using NLP concepts.


## Pre-requisites:
1. Python 3.7
2. Pandas
3. numpy
4. nltk
6. TfidfVectorizer

### STEP 1: Prepare directory:
Make a folder in which you have dataset and are going to store your code in. 

### Step 2: Import libraries:

I am using Librosa and pydub for this task. So, If you have these libraries installed It's good. But, If not then execute these commands on jupyter notebook. 
```python
!pip3 install pandas
!pip3 install numpy
!pip3 install sklearn
!pip3 install re
```
Now, you have to import these libraries as follows:

```python
import pandas as pd
import numpy as np
import re
from sklearn.feature_extraction.text import TfidfVectorizer
```

I am using cosine similarity concept to find the similarity between sentences present in dataset and sentence passed to my code. 

