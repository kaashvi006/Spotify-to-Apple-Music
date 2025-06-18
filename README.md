
# Spotify to Apple Music Playlist Converter

This script is designed to help transfer playlists from Spotify to Apple Music.  
Due to the absence of an Apple Developer subscription, the script does not create Apple Music playlists directly. Instead, it extracts individual track links from a Spotify playlist and finds their corresponding Apple Music URLs using the iTunes Search API.

## What It Does

- Accepts a public Spotify playlist URL.
- Authenticates via Spotify Developer credentials.
- Extracts track names and artist names.
- Searches for each track on Apple Music.
- Generates:
  - `apple_music_links.json`: list of matched tracks and Apple Music URLs.
  - `apple_music_urls.txt`: plain list of Apple Music track links.

## Setup Instructions

1. Create a Spotify app at [Spotify Developer Dashboard](https://developer.spotify.com/dashboard).
2. Copy your `client_id` and `client_secret` into the script.
3. Run the script in your Python environment or Google Colab.
4. Paste the Spotify playlist link when prompted.
5. Download the generated `.json` and `.txt` files containing Apple Music links.


