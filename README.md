# Moodify 

![Logo](/assets/images/default_logo.png)

The project accesses Microsoft's facial detection API to detect the user's mood, and then queries Spotify's API for playlists based on the user's perceived emotion.

The motivation behind this group project was simple. Every team member on this project enjoys different music depending on their current mood, and we believe that others would enjoy this application as well. 

The technologies we used for this software is entirely created on client-side technology (javascript, css, and html). The issues we experience were cross-browser CORS issues(we used a Heroku Application to deal with this issue for spotify), as well as authentication issues with spotify and hiding API keys. 

Connor handle the Microsoft API, 

Megan and Josh handle the Spotify API call (Megan getting the access token call and Josh handle the subsequent calls that search for playlists).

Susanna created all of the HTML, CSS and developed the logo for the project. 

We're all relatively new to programming and we struggle a lot with API calls. In future development, we hope to make these API calls on the back-end and hide our API keys so that anyone can try our application without contacting us for the key information. 

We also hope to expand the emotion detection software so that we can leverage more terms to query Spotify's API and produce more diverse playlists. 
To view our application click here: [Moodify](https://meganthonykeogh.github.io/moodify/)





