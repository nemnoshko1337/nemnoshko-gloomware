
# Music Tracks

This directory contains MP3 audio files.

## Naming

Use descriptive filenames:

- artist-track-name.mp3
- artist-another-track.mp3

## Adding tracks

After uploading an MP3, register it in:

../config.json

Example:

{
  "id": "example-track",
  "name": "Example Track",
  "artist": "Example Artist",
  "file": "tracks/example-track.mp3",
  "enabled": true
}

Supported format: MP3.
