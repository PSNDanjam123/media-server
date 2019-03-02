# Media Server
My personal media server configuration using docker-compose

## Getting Started
1. Copy this repo to your server.
2. Create and configure the `.env` inside the base project directory, see Environment Variables section below.
3. Run `docker-compose up -d` and follow the setup instructions for each app.

## Environment Variables
Before you start the server you need to configure the environment variables, an `example.env` has been included.
Simply copy and rename this file to `.env` (don't forget to change the values inside).

- USER_ID User identifier, e.g 1000
- GROUP_ID Group identifier, e.g 1000
- TELEVISION_DIR Directory for TV shows, e.g /data/tv
- MOVIES_DIR Directory for movies, e.g /data/movies
- TRANSCODE_DIR Directory for plex transcoding, e.g /data/transcode
- DOWNLOAD_DIR Temporary download directory used by transmission, e.g /data/downloads
- WATCH_DIR Directory for sonarr/radarr watch e.g /data/watch
- PLEX_MEM_LIMIT Memory limit for Plex, e.g 1024m
- OMBI_MEM_LIMIT Memory limit for OMBI, e.g 1024m
- RADARR_MEM_LIMIT Memory limit for Radarr, e.g 1024m
- TRANSMISSION_MEM_LIMIT Memory limit for Transmission, e.g 1024m
- JACKETT_MEM_LIMIT Memory limit for Jackett, e.g 1024m
