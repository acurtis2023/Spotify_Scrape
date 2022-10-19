# Spotify_Scrape
Welcome to my first web-scraping project I'm creating for my data science class!

John Mayer has got to be one of my favorite artists of all time. I've seen him in concert 6 times, in 3 different states, and I've got a joint playlist with my mom that shares our top favorite songs. 

In the spirit of finding a project that was interesting to me and wasn't a trivial web scrape, I decided to look at my John Mayer playlist on Spotify and scrape the URI to access the track information! Python has a relatively lightweight package called "Spotipy" that helps decipher the music data accessible from the Spotify Web API. 

To get an API key for this project, I linked my Spotify account to the Spotify Developers website and created an app on my dashboard. This provided me with a client id and a client secret, which I have excluded from this repository since they are private keys. 

One interesting aspect of the Spotify API is that they limit scraping endpoints to 100 tracks. John Mayer has several studio and live albums, which makes his total track list exceed 100 songs. To account for this, I created a playlist of just his studio albums, and used the last couple of indeces to add a few of my favorite live recordings. 

This repository contains the code I used to scrape the John Mayer data, a .json file with my playlist's URI, and a .gitignore file.
