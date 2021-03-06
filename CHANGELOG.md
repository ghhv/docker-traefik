# Changelog
## Planned: 
* Replace or remove Transmission/qBittorrent (duplicate functionality)
* Add LazyLibrarian, Calibre, Caliber-web, projectsend, cloudflare ddns, traefik cert extractor, embystat, nextcloud, photoprism, nut-upsd, HealthChecks, FileRun, smtp-to-telegram, cloud commander
* Replace VSCode Server with linuxserver/code-server

## March 31, 2020
* Added Ombi, PhotoShow
* Moved Traefik-Home, MQTT Admin, xTeVe, Piwigo, MiFlora Daemon, xTeVe, Logarr to Obsolete list

## January 14, 2020
* Added dozzle, smokeping, Traefik-Home, and VSCode Server - Thanks github.com/thefrenchmatt

## January 9, 2020
* Replace TellyTV with xTeve
* Re-added Emby for Testing

## January 7, 2020
* Added MiFlora MQTT Daemon to monitor plant status, AirSonic, and MariaDB
* Obsoleted Varken

## January 6, 2020
* Switched radarr and sonarr to "preview" tag to use the new low resource UI.
* Renamed Traefik 1 folder from "traefik" to "traefik1"

## December 16, 2019
* Significant changes - too many to list
* Included first draft of Traefik 2.1 setup
* Included a draft of Traefik 1 in Docker Swarm mode
* Removed monitorr (use statping instead)

## November 22, 2019
* Replaced Emby with Jellyfin
* Added Postgres database for StatPing

## November 21, 2019
* Added Autoindex
* Addded TellyTV for IPTV proxy for plex 
* Added StatPing with Grafana Dashboard - not working yet
* Separated VPN apps into different compose file
* Removed IPVanish container and put vpn apps behind Transmission-VPN's network

## November 8, 2019
* Harmonized paths and removed unused volumes
* Moved Plex and Emby transcoding to /dev/shm (RAM)

## November 7, 2019
* Added IPVanish VPN container. 
* Added VPN support for Jackett, qBittorrent, and jDownloader.
* Initial push to GitHub

## November 6, 2019
* Moved environmental variables to .env file

## November 4, 2019
* Added plex-sync to sync two plex servers.
* Added MakeMKV.

## October 28, 2019
* Added Plex, MKVToolNix, QDirStat

## October 24, 2019
* Added Picard, Handbrake, and Filebot

## Oct 14, 2019
* Implemented Google OAuth

## Oct 11, 2019
* Added Firefox, Glances, jDownloader, Logarr, Monitorr, and apcupsd
* Replaced watchtower with Ouroboros

## Oct 4, 2019 
* Added Heimdall

## Sep 17, 2019 
* Fixed traefik v1.7.16
* Added organizr
* Fixed traefik labels
* Switched to hydra2. 
* Removed Heimdall. 
* Cleaned up docker compose.

## Aug 20, 2019 
* Removed Unifi (moved to VPS). 
* Switched back to linuxserver for sonarr and radarr.

## Feb 25, 2019 
* Moved to NUC. 

## Feb 8, 2019
* Added jlesage/handbrake
* Switched from linuxserver/sonarr to aront/sonarr, linuxserver/radarr to aront/radarr for mp4_automator support

## Feb 5, 2019 
* Removed Plexms, Nodered, Hole, Syncthing
