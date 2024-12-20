DOCUMENTATION:

What is this ?
A music dashboard UI for Home Assistant that uses mini-media-player to work with Alexa Echo devices and most other sound systems.

This system is designed optimally for Spotify Premium accounts.


Features
  - A clean and easy-to-navigate UI
  - Program your favourite playlists, tracks, artists and your home devices to easily select what you want to hear, where you want to hear it.
  - Adjust the volume with an optionally-disappearing slider
  - Song progress timer
  - Artwork, song name, artist and album name that transitions when songs change
  - Repeat, shuffle, next and previous song functionality
  - Power button to easily restart devices after a restart


Installation
HACS


Requirements:
  - HACS
  - Mini-media-player HACS integration
  - Spotify Premium account or other music account with associated integrations
  - Spotify integration
  - Spotcast HACS integration
  - Spotify Plus integration
  - Save the two .PNG files into your www folder - create subfolders as you see fit.  Adjust the file paths in the YAML accordingly.

*You will need to ensure the three Spotify integrations above run properly with the mini-media-player card before using this UI.

**If you do not use Spotify, you will need to ensure your music system runs properly with the mini-media-player card before using this UI.

1. Create a new dashboard view
	- In Home Assistant, click on Overview on the top of the left sidebar.
 	- Click the pencil on the right
	- Click the plus + sign
	- Under Layout, choose Panel (single card)
 	- Give the dashboard a Title and click save
	- Click Add Card
	- Choose Picture Elements
	- Choose Show Code Editor
	- Type CTRL-A on your keyboard/delete all the text within the Editor
	- Paste in the YAML from the file attached
	- Adjust any components that may be misaligned due to varying screen sizes
	- Copy your Spotify account name from config.yaml and replace all instances of "entity: media_player.spotifyplus_SpotifyAccountName" with your own account name by deleting "SpotifyAccountName" and replacing with your own
	- Use Spotify on a desktop and find the playlists/artists/songs/stations you want to program in.  Click the three dots, and press the control button on your keyboard while clicking "Share"
	- The "Copy URL" menu button in  Spotify will change to a URI.  Click "Copy URI"
	- Use this URI to replace the Spotify links in the YAML

https://github.com/user-attachments/assets/68fab1e1-2423-4347-a4d1-25cf213ecccc

