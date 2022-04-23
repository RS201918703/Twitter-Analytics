# Investigating LSE Department's digital presence on Twitter

### Overview and motivation
Given how most events moved online during COVID-19, having a strong digital presence is a huge advantage for organisations. Therefore, the main problem I would like to answer in this project is which departments at the LSE have the strongest digital presence and whether Twitter is a social media platform worth considering. This is an academic project for ST115.

### Description
For this project, the dataset itself is derived from the Twitter accounts itself using API calls. Majority of the code involves extracting the tweets, cleaning them up, and classifying the sentiments of tweets using TextBlob. Following the creation of the dataset, I've analysed the data using packages such as NetworkX, Seaborn, and Matplotlib.

### How to run
- Make sure you have the following packages installed on Python: [Pandas](https://pandas.pydata.org/docs/getting_started/install.html), [NumPy](https://numpy.org/install/), [Seaborn](https://seaborn.pydata.org/installing.html), [Matplotlib](https://matplotlib.org/stable/users/installing/index.html), [BeautifulSoup](https://pypi.org/project/beautifulsoup4/), [Requests](https://pypi.org/project/requests/), [Json](https://pypi.org/project/jsonlib/), [TextBlob](https://textblob.readthedocs.io/en/dev/install.html) and [NetworkX](https://networkx.org/documentation/stable/install.html).
- Make sure you have a [Twitter Developer account](https://developer.twitter.com/en) with elevated access
- Update the [keys.json](https://github.com/RS201918703/Twitter-Analytics/blob/main/keys.json) file with your own access token
- Run the [code](https://github.com/RS201918703/Twitter-Analytics/blob/main/Project%20code.ipynb)

### Improvements
- Analysing non-public metrics (Unavailable due my Twitter developer account access)
- Analysing tweets over the years instead of the last 100 tweets
- Comparing analysis with other social media platforms like Facebook and Instagram
- Comparing analysis with other university departments on Twitter

### Conclusion
I learned a lot about about API calls on Twitter, but I would now look into the possibility of making the code more efficient. I will try to find a way to loop through the API calls without a higher developer account access. However, if I had higher access, using non-public metrics like impression counts and profile views would tremendously help this analysis.

### References
1. [Twitter APIs](https://developer.twitter.com/en/docs/twitter-api)
2. [NetworkX graphs](https://medium.com/future-vision/visualizing-twitter-interactions-with-networkx-a391da239af5)
3. [Sentiment analysis](https://towardsdatascience.com/step-by-step-twitter-sentiment-analysis-in-python-d6f650ade58d)
4. [TextBlob](https://towardsdatascience.com/my-absolute-go-to-for-sentiment-analysis-textblob-3ac3a11d524)
5. [Social media analytics](https://netbasequid.com/blog/what-is-social-media-analytics-why-is-it-important/)
6. [Seaborn documentation](https://seaborn.pydata.org/)
