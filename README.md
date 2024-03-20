# Twitter Sentiment Analysis: Ukraine vs. Russia War (January 1st, 2022 - March 6th, 2022)

This repository analyzes sentiment on Twitter regarding the conflict between Ukraine and Russia. It utilizes powerful Python libraries like pandas, NumPy, TextBlob, Matplotlib, and NLTK to extract, clean, analyze, and visualize Twitter data. The project is developed using Jupyter Notebook for interactive exploration.

**Key Features:**

**Data Collection:**

* Pre-collected dataset is used from Kaggle:
    * https://www.kaggle.com/datasets/bwandowando/ukraine-russian-crisis-twitter-dataset-1-2-m-rows

**Data Preprocessing:**

* Duplicate entries are removed.
* Date part of the dataset is sliced.
* Non-English tweets are removed.
* Punctuation, tags, and annotations are removed from the text. Everything is converted to lowercase to ensure different variations of the same word (like "happy" and "Happy") are treated the same.

**Sentiment Analysis:**

* Tweets are analyzed using TextBlob to score each tweet's sentiment (positive, negative, or neutral).
* Each day in the data is focused on, removing unnecessary details and counting the positive, negative, and neutral tweets for that day.
* A pie chart is used to show the distribution of positive, negative, and neutral tweets. N-grams are used to visualize sentiments over the 65 days.

**To further understand the project, please refer to the REPORT.**



