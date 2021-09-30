[![Build Status](https://travis-ci.com/tuxfoo/jellyfin-skill.svg?branch=master)](https://github.com/tuxfoo/jellyfin-skill)
# Jellyfin
This skill is a fork of the emby skill that allows audio playback from a Jellyfin server

## About
Stream music from your Jellyfin server using Mycroft! Play all songs by an artist or an instant mix of any artist/album/song in your Jellyfin library.

## Installation
* mycroft-msm install https://github.com/tuxfoo/jellyfin-skill

## Common Play Framework
This skill supports the common play framework! This means you don't have to specify "Jellyfin" in your intent. For Example
* "Play The Beatles"
* "Play artist The Beatles"
* "Play song Hey Jude"
* "next song"
* "pause"
* "stop"
* "resume"

## From Intent
If you have other music services you can use the from intent
* "Play artist Blackmore's Night from jelly fin"

## OTHER
You can ask for the track information.
* "what song is this"
This feature does not work with all codecs. It works for flacs but not mp3's.

## Set up
Go to https://account.mycroft.ai/skills
Make sure to enter in your jellyfin server details including a API key.
You can generate and revoke API keys in your jellyfin dashboard
The API key requirement might be removed in a future version

## Credits
rickyphewitt
tuxfoo

## Category
**Music**

## Tags
#Jellyfin,#Music

## Contributing
Always looking for bug fixes, features, translation, and feedback that make the Jellyfin for Mycroft experience better!

## Troubleshooting
### Setup Connection Info
* Ensure your host, port, api key, username, and password are set at https://account.mycroft.ai/skills
### Check Server Connection
* "Check Jellyfin/Emby"
    * This will attempt to connect then authenticate to your Jellyfin server using the connection info provided above
