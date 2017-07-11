# @reacts_guy

**Reacts_guy** is a twitterbot that reacts to news headlines posted by the [New York Times twitter account](https://twitter.com/nytimes).

## Method

**Reacts_guy** runs news headlines from _@nytimes_ through a sentiment detection algorithm based on  _nrc_ sentiment scores from the [tidy text package](https://cran.r-project.org/web/packages/tidytext/tidytext.pdf). The twitterbot reads a headline, determines the sentiment evoked by said headline, and returns a sentence in the same sentiment as said headline. 

## Deployment

This twitterbot runs on a cronjob on a remote AWS instance and tweets as often as the New York Times does. 