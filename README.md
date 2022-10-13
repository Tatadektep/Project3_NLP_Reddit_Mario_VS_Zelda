# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: NLP Classification of Reddit: Mario Vs Zelda

by ([*Kantaphon Vareekasem*](https://github.com/Tatadektep)) & ([*Pornpan Thongdee*](https://github.com/Tatadektep))

"It's-a-me, Mario!" - Super Mario 64.
"We must win! The fate of Hyrule depends on it!"

### [Presentation Deck](https://docs.google.com/presentation/d/1eM9roDkzjL45zVwXfc0ELQt3S4eltEgoB1IsOxTccRc/)


### Problem Statement
- Being part of the Nintendo Marketing Team of nintendo switch, I am interested in finding out what popular topics and keyword jargons belong to the fields of Mario and Legend of Zelda. Conducting analysis on Reddit posts will allow me to craft online content and advertisements to better target people interested in casual, adventure, platformer video games.

- The main objective of this project is to scrape two subreddits: `r/Mario` and `r/Zelda` using Reddit's API. The scraped data from the two subreddits will then be passed through various classification models, `CountVectorizer`/`TfidVectorizer` with `Naive Bayes Classifier` and `LogisticRegression` that will assign each observation to the most likely class of subreddit. The models should help the data science marketing team of my company identify what makes the respective subreddit posts unique from one another.

- In this process, the subreddit posts will undergo preprocessing and EDA. The success of the models that we decide on will be determined through the highest accuracy based on the scores obtained.

### Summary 

Natural Language Processing, or NLP for short, involves using specialized machine learning techniques to make predictions about the text in a body of documents, including things like authorship attribution, sentiment analysis, text generation, and in some cases the appearance of something resembling semantic understanding.

Nintendo Switch, a hybrid home console and handheld device is one of highest revenue generator of Nintendo, it had outsold the lifetime sales of Wii U, its home console predecessor.Mario Kart 8 Deluxe is the best-selling game on the platform at over 46 million copies sold The Mario franchise alone has sold 167.11 million copies on the Nintendo Switch, which is the most the franchise has ever sold on a single platform. The Legend of Zelda has also sold the most on a single platform with the Nintendo Switch with 41.13 million copies. 

In this project, we would like to further explore the key similarities and differences between Mario and Zelda in terms of the current discussions and topics that people are discussing on Reddit. Reddit, in recent times, have become a popular avenue for people all over the world to ask one another about different career prospects and experiences. As such, scraping Subreddit Posts gives us an interesting source of data that we can analyze to understand what are the popular topics in these respective career fields.

The web scraping portion of this project is covered in another notebook. In this notebook, we will be covering the steps taken to clean and analyze the data collected, as well as further steps taken to pre-process the text data, visualize the data, use different models to find the optimal model and analyze misclassified posts.

### **Conclusions**
- Mario's and Zelda's Reddit is quite different and easy to identify as the model can predict with an accuracy of over 90% after removing characters' names, game titles and movie-related words.
- Mario Reddit is more focused on the looks of characters and memes. Moreover, there are considerable numbers of designs and fans for the franchise.
- Zelda Reddit is more focused on art with the community-led event of the "linktober". Moreover, there are considerable discussions on gameplay-specific topics such as a boss event, seasonal event and story.

### **Recommendations**
- We should use more data from other social media platforms to better understand the difference between Mario and Zelda fans so that we could target advertising campaigns accordingly. 
- Additionally, gamers on different platforms tend to display a unique pattern of behaviour to fit in with the group.

### Contributors:
Special thanks to all the contributors who have contributed to this project. We are heartily thankful to you all.

And a special thanks to *James Larkin*, *Yamada Nozomi*, and *Apiwat Jaroonpol* for their support.
