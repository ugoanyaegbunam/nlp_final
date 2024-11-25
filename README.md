# nlp_final
Our task/question was building a topic model trained on song lyrics to look at it's proficiency in grouping songs compared to us as humans and chatgpt based on lyrics.

Details about our dataset can be found here: https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset
(should be included in the submission but on the off chance it's too big or incovnenient it can be downloaded here as well)

Our implementation is sourced from and built on top of https://www.kaggle.com/code/samuelcortinhas/nlp6-topic-modelling-with-lda/notebook#3.-Application

Chatgpt was consulted for dataframe formatting as well as api usage
Claude was consulted for implementing statistical analysis of topic model

Directions:
We created a virtual env and ran pip install -r requirements.txt, you most likely won't need the venv, but it's an option
Then download the spacy model by running python -m spacy download en_core_web_sm
you can then hit run all and watch it go to work
you may run into an issue with max requests reached which means they've capped the requests for that app for a time period. To solve this, just register a new app on the spotify api's website and paste the new client id and secret in the code. However, 
I'm not sure if at one point I was blocked by too many requests leaving my ip, I don't really know, but all should be well.
https://developer.spotify.com/dashboard
