# Exploratory Data Analysis [4chan]
Exploratory Data Analysis on the posts/comments on desired 4chan channels (Technology, Television, Literature, Cooking) and generate insights:
* Most common words in a channel
* Message count per thread (OP/ excluding OP) [OP- Original Post]
* Frequency of post per channel
* Unique words that differentiate a channel

Built a Naive-Bayes Classifier to predict the 4chan channel, given a post/comment. 

## Environment setup
```
pip install -r requirements.txt
```

## Generate Dataset
Generate the dataset for the required 4chan channels by fetching posts/comments

```jupyter notebook data_generate.ipynb ```  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mkartik/EDA_4chan/blob/master/data_generate.ipynb)  [Dataset Generation](https://github.com/mkartik/EDA_4chan/blob/master/data_generate.ipynb) 

## Vizualization
Vizualize and get insights on the desired channel posts/comments using 

```jupyter notebook exploratory_data_analysis.ipynb ```

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mkartik/EDA_4chan/blob/master/exploratory_data_analysis.ipynb)  [Visualization](https://github.com/mkartik/EDA_4chan/blob/master/exploratory_data_analysis.ipynb) 

