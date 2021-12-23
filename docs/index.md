## 1. Introduction 	

Welcome to the Open Spanish NLP (OSN) project whose objective is to position [CENIA](https://www.cenia.cl) as a reference in the centralization, release and elaboration of NLP resources in Spanish.



Our goal is to build a repository that concentrates resources of diverse nature and allows easy access to the scientific community, industry and students. 



## 2. Resources

Below are the types of resources we want to collect and build.



### 2.1 Raw Corpora



The training of large language models requires large collections of text. For this reason we will centralize all corpora available in Spanish:



* https://github.com/josecannete/spanish-corpora
* Common Crawl (Spanish version) [https://commoncrawl.org 	](https://commoncrawl.org/) 
* Scrapper of reviews from Mercado Libre, sensaCine, Tripadvisor, AirBnB in Spanish.   
* Tweets?

### 2.2 Labeled Data

On the one hand, we want to collect all existing labeled datasets to train models in the various [NLP tasks](https://nlpprogress.com/).



* https://github.com/dccuchile/GLUES
* [SemEval 	2018 Affect in Tweets ](https://competitions.codalab.org/competitions/17751)(Spanish datasets for various emotion tasks)
* TASS 2012- 2020: [http://tass.sepln.org/tass_data/download.php?auth=QtDa3s5sA4ReWvYeWrf 	](http://tass.sepln.org/tass_data/download.php?auth=QtDa3s5sA4ReWvYeWrf) 



We also want to identify important tasks that do NOT have data labeled in Spanish in order to create new resources.

### 2.3 Language Models

We will centralize all existing language models for Spanish.



* https://github.com/dccuchile/beto



We will also train new models (e.g. distilled models).



### 2.4 Task-specific Models



We will train state-of-the-art models for all the tasks of section  2.2 using the language models described in section 2.3. 

###  2.5 Benchmarks

We will implement model benchmarks for the tasks that will be made available at 

http://nlpprogress.com/

### 2.6 Shared Tasks



For all the tasks where we create new datasets, we will organize shared tasks to invite the scientific community to work on these problems. 



Conferences where our shared tasks could be hosted. 



* SemEval
* CLEF  



### 2.7 Tutorials, APIs, others



We will release tutorials (jupyter notebooks), APIs, online demos, etc. to facilitate the use of our task-specific models to all our target audience. 



## 3. Publishing Platforms



We will rely on available platforms to publish different types of resources 



* Transformers library for model hosting.
* Zenodo for Dataset Hosting
* Github for hosting code and tutorials



## 4. Dissemination

We will write papers to give visibility to our resources.

Some conferences and journals where resources can be published:



* LREC
* [Language 	Resources and Evaluation](https://www.springer.com/journal/10579)
