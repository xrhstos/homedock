# homedock
Docker compose files for home lab server

# ***this is a testing repo !***

Rename the env.(appname) to .env then run them with docker-compose -f myfile.yml

Here is a listing of all docker compose files:

+ games/factorio : a factorio game server
+ media/lidarr   : a music management software for your server
+ media/radarr   : a movies management software for your server
+ media/sonarr   : a tvshoes management software for your server
+ media/bazarr   : a subtitles management software for your server
+ media/jackett  : an indexer for all your needs(you need lidarr/radarr/sonarr/bazarr & transmission in order to work)
+ media/transmission : media downloader
+ media/plex     : a mediacenter for your downloaded media
+ media/tautulli : metrics for your plex media center
+ media/ombi     : media requester for your plex
+ frontends/heimdall : a bookmark manager for your services
+ frontends/raneto   : a cms for your notes(markdown cms)
+ frontends/whoogle  : host google on your network (google without ads,tracking etc)
+ system/doozle      : monitor your docker logs
+ system/portainer   : manage your dock containers
+ system/yacht       : easy docker installs
+ tools/guacamole    : remote access gatewaty (rdp/ssh/vnc)
+ tools/duplicati    : backup your configs of your docker containers
+ developer/codeserver : visual studio on your browser
+ developer/gitea    : selfhosted git
