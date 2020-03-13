# StoryGeneration

------------------1_DateReader------------------------------------------------------------------------------------------------

1.1. Data Reader is a program that reads data items from a files (here linguistic corpora, perticularly wikipedia extractor sets) into machine learning + evolutionary computation program, and creates training/testing examples. This part of the project is just to make sure that you find your actual data and have a program that can interact with your data: Read the data from a folders/files and have your data items in the form of learning examples. Depending on how clean/structured is your data this step might need a bit of work for you.

1.2. Notice in this data-reader repository, we just focus on the reading+mining of data from wiki. It definitely needs more efforts to do cleaning or structured operations. So far we have not implemented that, but we will work on this during the entire cycle of this project.

1.3. This repository includes two parts, the first is a Wikipedia crawler, mainly through BeautifulSoup (aka bs4 to extract information) and requests library. The second one is mining and pre-processing documents. The output is wikiextractor/extracted/originaltext.

1.4. Next two parts are 1. put processed data into structured machine learning to classify/clean; 2. put classified data to evolutionary algorithm program to generate text, we will updata as the processing of the project.

1.5. Data Reader: mine.py, wikiextractor.py. Mined data see mined.zip




For the 2nd update of project:

--------------2_MinedDataClean------------------------------------------------------------------------------------------------

2.1 Cleaning of mined data see clean.py. Cleaned data set see cleaned.zip

2.2 package: (https://spacy.io/)
  $ python -m spacy download es_core_news_md
  - Installing pyasn1 (0.4.8)
  - Installing cachetools (4.0.0)
  - Installing oauthlib (3.1.0)
  - Installing pyasn1-modules (0.2.8)
  - Installing rsa (4.0)
  - Installing google-auth (1.11.2)
  - Installing requests-oauthlib (1.3.0)
  - Installing absl-py (0.9.0)
  - Installing google-auth-oauthlib (0.4.1)
  - Installing grpcio (1.27.2)
  - Installing h5py (2.10.0)
  - Installing markdown (3.2.1)
  - Installing protobuf (3.11.3)
  - Installing werkzeug (1.0.0)
  - Installing wheel (0.34.2)
  - Installing astor (0.8.1)
  - Installing gast (0.2.2)
  - Installing google-pasta (0.1.8)
  - Installing keras-applications (1.0.8)
  - Installing keras-preprocessing (1.1.0)
  - Installing opt-einsum (3.2.0)
  - Installing tensorboard (2.1.1)
  - Installing tensorflow-estimator (2.2.0rc0)
  - Installing termcolor (1.1.0)
  - Installing wrapt (1.12.1)
  - Installing tensorflow (2.1.0)

--------------------3_MachineLearning-----------------------------------------------------------------------------------------


