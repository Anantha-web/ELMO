# ELMO
# README


### FILE STRUCTURE:

####  ├── DOWN_STREAM_TENSORFLOW.py
####  ├── ELMO_scratch.py
####  ├── elmo-v1.pt
####  ├── REPORT.md
####  ├── yelp-subset.test.csv
####  └── yelp-subset.train.csv
* The DOWN_STREAM_TENSORFLOW.py, contains direct library version of the model from Tensor Flow.
  
* Where as the ELMO_scratch.py contains, the from scratch implementation , followed by the downstream task.

* There should be a GLOVE.txt file for creating the glove embeddings, but it is large, so skipping it.
  
* The elmo-v1 is the pytorch model saved which can be retrieved by using model.load() functionality.
  
* For clarity if you want to have a look at the notebooks, it is always there in the .archives hidden directory.
  
* You can run the code by installing standard ML libraries, like tensorflow, keras, pytorch, etc. Not mentioning the requirement files as most of the work is done in the Cloud, and extracting requirements.txt file is a bit diffcult.


This folder contains the extracted subset data files from the original Yelp reviews dataset (https://huggingface.co/datasets/yelp_review_full).

- yelp-subset.train.csv - 50k instances
- yelp-subset.dev.csv - 2.5k instances
- yelp-subset.test.csv - 5k instances

Each instance is separated one a line.

#### Columns in the .csv file: label, text

- label: Classification label for the corresponding text, which get from 0 to 4
- text: Unprocessed text from the Yelp dataset


#Anantha Lakshmi
#2020101103
