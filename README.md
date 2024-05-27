# parinaz-yousefi-mood-sync


## Overview
Mood Sync is a web app that uses the Spotify API to analyze your recent listening history, recommend new songs, detect your mood, and display your top tracks and artists.

### Problem
Music enthusiasts often seek personalized recommendations and mood-based playlists to enhance their listening experience. Mood Sync addresses this need by providing customized song recommendations and mood detection based on users' Spotify data.


### User Profile
**Music Enthusiasts:**
-  Users who are looking for personalized song recommendations.
-  Users who want to track their top songs and artists.
-  Users who want to track their top songs and artists.

### Features
-  **Mood Detection**: Analyzes recent listening history to detect and display your current mood.
-  **Top Tracks and Artists:** Displays your top tracks and artists based on your listening habits.
-  **Song Recommendation:** Provides personalized song recommendations.

## Implementation
**Tech Stack**
-  **Frontend:**
   -   React
   -   Axios
   -   React Router
-  **Backend:**
   -   Node.js
   -   Passport.js
   -   Express
   -   Spotify Web API

### APIs

-  The project utilizes the Spotify Web API for fetching user data, song recommendations, and creating playlists.
 [Spotify Web API Documentaion](https://developer.spotify.com/documentation/web-api)

### Sitemap
-  **Login to Spotify:** Allows users to authenticate and access their Spotify data.
-  **Mood Detection:** Displays the detected mood based on recent listening history..
-  **Top Tracks and Shows:** Shows the user's top tracks and artists.
-  **Song Recommendations:**Provides personalized song recommendations.

### Mockups
-  Mockups for the project can be found in the watchlist folder.
### Data
-  The project fetches data from the Spotify API, including information about user profiles, tracks, artists, and recommendations.

### Endpoints
**GET /me**
-  Fetches the authenticated user's Spotify profile information.
**GET /me/top/tracks**
-  Lists the user's top tracks
**GET /me/top/artists**
-  shows info  about the movie
**GET /recommendations**
-  Provides song recommendations based on the user's top tracks and artists.
**GET/3/genre/movie/list**
-  lists all of the movies with the specific genre
### Auth
  The project includes authentication functionality for user login using their Spotify account.
### Roadmap
- Create client:
  -   Set up a React project with routes and boilerplates.
  -  Develop the login page to store requested tokens.
  -  Deploy client and server projects so all commits are reflected in production.
-  Features:
  -  Sign up functionality.
  -  Discover feature to explore new content.
  -  Implement search functionality.
  -  Develop top tracks and artist display.
-  Bug fixes.
-  Deploy.

### Nice-to-haves

-  Users can add the recommended playlist to their profile.
