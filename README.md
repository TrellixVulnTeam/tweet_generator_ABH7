# Tweet Sentiment Labeller

Search for Tweets and download the data labeled with it's Polarity in CSV format

View Live at [https://twitter-sentiment-csv.herokuapp.com/](https://twitter-sentiment-csv.herokuapp.com/)

[![](http://i.imgur.com/H78FZUX.png)](http://i.imgur.com/H78FZUX.png)


## Development Guide - Windows

1. Create a virtualenv. `virtualenv venv`
2. Activate venv. `.\venv\Scripts\activate`
3. Install the requirements. `pip install -r requirements.txt`
4. Save the `ACCESS_TOKEN`, `ACCESS_TOKEN_SECRET`, `CONSUMER_KEY`, `CONSUMER_SECRET` as environment variables. You can follow [this](https://devcenter.heroku.com/articles/config-vars) guide for Heroku.
5. Run the server. `python app.py`

