# Jamming

Jamming is a React website application for searching, creating and saving new playlists with Spotify. 

Link to the website - [Click here](https://saatvikrao-jamming.netlify.app/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/88c7111f-d249-454e-8e8e-d42d682e0f1f/deploy-status)](https://app.netlify.com/sites/saatvikrao-jamming/deploys)


## Overview

> This is a React web application called Jammming. Using the knowledge of React components, state, and requests with the Spotify API I have built a website that allows users to search the Spotify library, create a custom playlist, then save it to their Spotify account.


## Features

* Spotify Login — the first time a user searches for a song, album, or artist, Spotify will ask them to log in or set up a new account.
* Search by Song, Album, or Artist — a user can type the name of a song, artist, or album into the search bar and click the SEARCH button.
* Populate Results List — Jammming displays the list of returned tracks from the user’s query.
* Add Song to a Custom Playlist — users can add a track to their playlist by selecting a + sign on the right side of the track’s display container.
* Remove Song from Custom Playlist — users can remove a track from their playlist by selecting a - sign on the right side of the track’s display container.
* Change Playlist Title — users can change the title of their custom playlist.
* Save Playlist to Account — users can save their custom playlist by clicking a button called SAVE TO SPOTIFY.


## Good Features improvements

* Pressing enter triggers a search (done)
* Include preview samples for each track (done)
* Prompt user before saving the playlist to the Spotify account 


## Potential Improvements
* After user redirect on login, restoring the search term from before the redirect 
* Only display songs not currently present in the playlist in the search results
* Update the access token logic to expire at exactly the right time
* Ensure playlist information doesn’t get cleared if a user has to refresh their access token


## Available Scripts 
In the project directory, run:

### ```npm start``` 
Runs the app in the development mode.    
Open http://localhost:3000 to view it in your browser.

The page will reload when you make changes.    
You may also see any lint errors in the console.

### ```npm test```
Launches the test runner in the interactive watch mode.  
See the section about running tests for more information.

### ```npm run build```
Builds the app for production to the build folder.  
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.  
Your app is ready to be deployed!
