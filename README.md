[![](https://images.microbadger.com/badges/image/rootwyrm/tc_sonarr.svg)](https://microbadger.com/images/rootwyrm/tc_sonarr "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/version/rootwyrm/tc_sonarr.svg)](https://microbadger.com/images/rootwyrm/tc_sonarr "Get your own version badge on microbadger.com")

# About Lidarr
* https://github.com/lidarr/Lidarr
* https://ci.appveyor.com/project/lidarr/lidarr/build/artifacts

# Connection Information
https://ContainerHost:8686/ - WORK IN PROGRESS

# Sample Setup
docker create -p 8686:8686 -v /media/config/lidarr:/config -v /media/download:/downloads -v /media/music:/media/music --name=lidtest docker.io/rootwyrm/tc_lidarr
