# OVERVIEW

I want to scrape various subreddits and experiment with some NLP, as well as attempt to determine ideal post times, subreddits, and potentially title sentiment for maximizing traffic to that post


## Dependencies Used

I am doing all of this in Jupyter Notebooks with the following imports: 
```
import seaborn as sns
from pprint import pprint
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import praw
import nltk
from nltk.sentiment.vader import SentimentIntensityAnalyzer as SIA
```

## Next Steps

- [ ] create another dataframe with subreddit, upvote/downvote information, and timestamps in the "hot" category to identify ideal times to post for maximum interaction.
- [ ] visualize the post time to total upvotes/downvotes
- [ ] visualize different subreddits' most active time periods

