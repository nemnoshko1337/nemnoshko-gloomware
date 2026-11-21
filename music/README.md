
# GloomWare Music

Official cloud music library for GloomWare Client.

Repository:
https://github.com/nemnoshko1337/nemnoshko-gloomware

Branch: main

## Structure

- config.json - Music library configuration
- tracks/ - MP3 audio files
- covers/ - Album covers
- lyrics/ - Synchronized LRC lyrics

## Adding a track

1. Upload an MP3 file to tracks/.
2. Upload its cover to covers/ (optional).
3. Upload synchronized lyrics to lyrics/ (optional).
4. Add track metadata to config.json.

## Track configuration

{
  "id": "unique-track-id",
  "name": "Track Name",
  "artist": "Artist Name",
  "file": "tracks/track-name.mp3",
  "cover": "covers/track-name.png",
  "lyrics": "lyrics/track-name.lrc",
  "duration": 180,
  "enabled": true
}

## Supported formats

Audio:
- MP3

Covers:
- PNG
- JPG
- JPEG
- WEBP

Lyrics:
- LRC

## Lyrics format

[00:00.00]First line
[00:05.20]Second line
[00:10.50]Third line

## Cloud access

Raw base URL:

https://raw.githubusercontent.com/nemnoshko1337/nemnoshko-gloomware/main/music/

Configuration:

https://raw.githubusercontent.com/nemnoshko1337/nemnoshko-gloomware/main/music/config.json

## Notes

- Track IDs must be unique.
- File paths are relative to the music directory.
- Disabled tracks are ignored by the client.
- Covers and lyrics are optional.
- Only upload music that you have permission to distribute.

Project: GloomWare Client
Author: nemnoshko1337
