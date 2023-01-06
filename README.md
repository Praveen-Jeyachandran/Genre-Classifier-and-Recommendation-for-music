# Music-Genre-classifier-and-RecSys
Classifying the genres builds the base of a good recommendation system 
in this project we have used the GTZAN dataset which was a dataset built to visualise and understand music 
For understanding audio files we have used the librosa library in python to make spectograms and wavelet graphs and further trained a CNN model to classify genres 
Our CNN model achieved an accuracy of 92 percent with 100 epochs

Further we extracted some playlists from Spotify's API and recommended a fresh playlist based on vector distance and genre (Content based filtering)
In the near future we also plan to implement a hybrid of collaborative filtering and content based filtering to build the perfect recommendation system
Using the spotify api in java script we also build a web app that recommends songs based on your listening history 
Link to web app https://anantvedansh.github.io/Spotify-Web-Api-Project/auth.html
