# Final Group Project
## Building a System to Identify Real vs Fake News Articles
### w207: Applied Machine Learning (Spring 2022)
###### Authors: Akiko Iwamizu, Allison Fox, Jason Yang, Rohin Chabra

## Project Background

Our goal for this project was to use labeled news datasets to make an algorithm that is able to determine if an article is fake news or real news. To build the model, we used a dataset provided by Kaggle. During the model development process, we explored performance of Logistic, Naive Bayes, and KNN models, along with unigram, bigram, and trigram feature vectors for text representation. To test the generalizability of the models, we then evaluated the models against a second dataset provided by Kaggle.

## Data Background

### Dataset 1
* Provided by Kaggle: https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset
* Contents: two data sets -- one that includes labeled fake news articles and one that includes labeled real news articles
* Primary focus of our analysis

### Dataset 2
* Provided by Kaggle: https://www.kaggle.com/c/fake-news/code
* Contents: two data sets -- one that includes labeled train data and one that includes unlabeled test data
* Supplementary dataset to explore generalizability of the models

## Repository Organization

    ├── LICENSE
    ├── README.md                          <- Describes the project objectives.
    ├── baseline_submission.ipynb          <- Includes EDA of the first data set.
    ├── final_submission.ipynb             <- Includes model results and limitations.
    ├── input
    |   ├── fake-and-real-news-dataset     <- The first Kaggle data set.
    │   ├── fake-news-dataset2             <- The second Kaggle data set.
    │   └── processed-dataset              <- The train/test/dev segments.
    ├── poc
    |   ├── Allison_Fox_EDA.ipynb          <- Allison's project notes.
    |   ├── eda_ai.ipynb                   <- Akiko's project notes.
    |   ├── jyang_notebook.ipynb           <- Jason's project notes.
    │   └── Ruff_draft_Rohin.ipynb         <- Rohin's project notes.
