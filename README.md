# milestone_ii
For our project our team had two tasks.

1. Group articles based on the words that appear in their titles into a predefined number of topics.
2. Predict user engagement with news articles. Specifically the number of clicks an article receives.

Our team utilized the MIND, or Microsoft News Dataset, that was released in 2020. The link to the dataset is below.

https://learn.microsoft.com/en-us/azure/open-datasets/dataset-microsoft-news?tabs=azureml-opendatasets

The MIND dataset consists of multiple data assets: behaviors.tsv and news.tsv.

The behaviors.tsv file contains impression logs, user history, and the columns described below.

- Impression ID; a unique identifier for the impression instance,
- User ID; an anonymized identifier for each user,
- Time; or timestamp of the impression,
- History; or the list of news article IDs clicked by the user before the current impression, and
- Impressions; or the list of news presented in the impression with a label for each indicating whether it was clicked or not.

The news.tsv contains metadata for each article and has the columns described below.

- News ID; the unique identifier for each article,
- Category; the high level category of the news (e.g. sports, politics, entertainment),
- Subcategory,
- Title,
- Abstract; or a short summary or abstract of the article,
- URL; or a link to the full article on MSN,
- Title entities; or keywords that appear in the title, and
- Abstract entities; or keywords in the abstract.

Python package dependencies are shown below.

- sklearn
- pandas
- numpy
- nltk
- gensim
- altair
- scipy
- random
- re
- imblearn
- collections
- matplotlib
- seaborn
- wordcloud

