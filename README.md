# Final_Coordination

## Overview

Here's a repo to coordinate the final project of our Data Analytics and Visualization Bootcamp. This is for brainstorming, sharing and organizing resource, practicing our git process, and more!

## Hopeful Team

Sanil Veeravu
Marsha Curtis
Conor Hanson
Oliver Dykstra

## Project Ideas

A few ideas that have been mentioned. Add more!
- News cloud - a news exploration dashboard
- Crime and heat mapping
- Car performance analizer module


## News Cloud Feasability

In order to explore the feasability of this project I looked first for examples of word clouds being applied to the news, then I searched for api's and other methods to access news headlines and articles more easily, then I attempted to find ideas on how machine learning could be applied to the news (which itself was a challenge since Google just wanted to news about Machine Learning) 

Things I did not look at here, but should be considered as well, data storage, time to go live, and site design.

### News in Word Clouds

To start, there are only a few examples I could find of word clouds applied to the news.

- The [Bing News Word Cloud](https://www.wordcloud.news/) creates a word cloud based on Bing News and also allows for some interactivity. It will also bring you to a page with related articles when clicked on.

- [Red State Blue State](http://redstatebluestate.xyz/) creates a word cloud based on the last ten days of headlines, but only looks at two sources, Fox News and the New York Times.

### Accessing the News

There are tons of apis to gather news. Some are source specific (New York Times), some have provide lots and lots of sources but have costs associated, some only provide headlines! 

Source Specific APIs:

- New York Times
- BBC
- Bloomberg
- ESPN
- Guardian

Wide Net APIs:

- [News API](https://newsapi.org/s/google-news-api) - Has a free version with up to 100 hundred requests per day. Accesses 80,000 sources worldwide. Only provides headlines. 
- [Rapid API](https://rapidapi.com/contextualwebsearch/api/web-search) - Has a free version with up to 100 hundred requests per day. Has built in topic search.
- [GNews](https://gnews.io/#pricing)(not Google) - Has a free version with up to 100 hundred requests per day. Includes full article.
- [MediaStack](https://mediastack.com/) - Has a free version with up to 500 hundred requests per month.
- Google News
- Bing News
- Yahoo News
- And more!

As you can see there is no shortage of solutions to gather our data. Many of the APIs still require a webscraping option in order to get the full article. But I'm personally in favor of having a strong webscraping functionality so we are not reliant on limited API calls and so we can target specific websites. There are quite a few open source web scraping solutinos out there too if we didn't want to start from scratch.

In my vision we would be including a lot of "alternative" news sources, especially those with an especially partisan angle.

### Applying Machine Learning

There's quite a few interesting possibilities for appliying machine learning. All are heavily reliant on NLP of course. The examples I've been able to find fall into a few categories: sentiment analysis, topic segmentation(what's it about?), quality assessment(fake news!), difference in coverage (advanced sentiment analysis), and of course, recommendation.

There's also some significant open source resources for NLP in general, and also as applies to the news.

A few things I've been reading:

- [Parse.ly Currents NLP](https://blog.parse.ly/machine-learning-nlp-parse-ly-currents/) - A now shuttered product looking for what gets people's attention.
- [A network view on reliability: using machine learning to understand how we assess news websites](https://link.springer.com/article/10.1007/s42001-021-00116-w) - A scholarly look at machine learning to find fake news.
- [Machine Learning Versus The News](https://towardsdatascience.com/machine-learning-versus-the-news-3b5b479d8e6a) - James Baker's capstone project with the goal to "find a way to identify news articles that cover the same story, then evaluate those articles to understand how uniform or balanced the media’s coverage was."

## Conclusion

We would need to narrowly define our scope in order to keep this project within one month's worth of work. But it's totally Feasible. 