# NlpProject
* Project Performed as part of CBNU's Natural Language Processing class
## Details
### Goal
* To explore if real-time posts from social media could be used to indicate some sort of disaster (earthquake, fire, sinkholes etc...) unfolding right now
### Libraries / Projects utilised in this project (not exhaustive)
* KoBERT (https://github.com/SKTBrain/KoBERT)
* KoNLPy (https://github.com/konlpy/konlpy)
### Not referenced nor utilised but still included
* [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started/overview)
### Caution
* The dataset collected from DCInside may contain language that may be vulgar or considered controversial / NSFW; The data are provided as-is from the search result. Proceed with caution!

## Table of contents
* [01_preprocess_fail.ipynb](./01_preprocess_fail.ipynb)
    * Brief analysis and reasoning on why the Kaggle dataset was dumped
* [02_collection.ipynb](./02_collection.ipynb)
    * Scrapes DCInside search results
* [03_1_preprocess.ipynb](./03_1_preprocess.ipynb)
    * Removes duplicate data from the dataset
* [03_2_label.ipynb](./03_2_label.ipynb)
    * Crudely labels the dataset before hand-labelling
* [03_3_transform.ipynb](./03_3_transform.ipynb)
    * Removes unnecessary data prior to model training
* [04_train_evaluate.ipynb](./04_train_evaluate.ipynb)
    * Trains and evaluates the ML model
    * and all the suffering trying to adopt an unmaintained 4-year-old project
