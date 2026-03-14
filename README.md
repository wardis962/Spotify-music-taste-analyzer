# 🎵 Spotify Music Taste Analyzer

A client-side web app that connects to your Spotify account and analyzes your liked songs to generate a personalized music taste profile — no backend, no server required.

## Features
- Authenticates with Spotify using the **PKCE OAuth 2.0** flow (secure, no client secret needed)
- Fetches your liked songs via the **Spotify Web API**
- Analyzes artist frequency, music eras, and genre distribution entirely **in the browser**
- Detects your listening mood and personality archetype from a 500+ artist genre database
- Zero external dependencies — pure HTML, CSS, and vanilla JS

## How to run it
1. Go to [developer.spotify.com/dashboard](https://developer.spotify.com/dashboard) and create a free app
2. Set the redirect URI to `http://127.0.0.1:3000`
3. Open `Spotify_Music_Taste_Analyzer.html` in Chrome
4. Paste your Client ID and follow the auth steps

## Tech used
- Spotify Web API
- PKCE Authorization Code Flow (OAuth 2.0)
- Vanilla JavaScript (no frameworks)
- Local genre/mood analysis engine (no AI API calls)

## What I learned
- How OAuth 2.0 PKCE works and why it's used for client-side apps without a backend
- Working with a real third-party REST API and handling paginated responses
- Building a data analysis pipeline entirely in JS from raw API responses
