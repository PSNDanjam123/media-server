# Media Server
My personal media server configuration using docker-compose

## Getting Started
1. Copy this repo to your server.
2. Configure your environment variables.
3. Run `docker-compose up -d` and follow the setup instructions for each app.

## Environment Variables
- **USER_ID** *REQUIRED: uid for volume permissions*
- **GROUP_ID** *REQUIRED: gid for volume permissions*
- **TIMEZONE** *OPTIONAL: defaults to `Europe/London`* 
- **CONFIG_DIR** *OPTIONAL: defaults to `./config`*
- **TELEVISION_DIR** *OPTIONAL: defaults to `./data/tv`*
- **MOVIES_DIR** *OPTIONAL: defaults to `./data/movies`*
- **TRANSCODE_DIR** *OPTIONAL: defaults to `./data/transcode`*
- **DOWNLOAD_DIR** *OPTIONAL: defaults to `./data/downloads`*
