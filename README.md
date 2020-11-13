# My Spotify Profile - Server
Backend service for using My Spotify Profile

# Pre-Requisites
Make sure you export the following environment variables before running the App. 
Details on how to register your App to get a Client id and Client Secret for using Spotify's Web Api -> 
https://developer.spotify.com/documentation/general/guides/app-settings/#register-your-app

Make sure you export the following environment variables before running the App. 
Eg. 
```
export CLIENT_ID=< your client id> 
```
CLIENT_ID,
CLIENT_SECRET,
REDIRECT_URI,
FRONTEND_URI

Note: If running locally, 
Redirect Uri should be "http://localhost:8888/callback"

# Project Setup
```
npm install
```

# Runnning the Server

```
npm run start
```
