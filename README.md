
# Awesome List of Portainer V2 Templates

This  is a collection of an awesome list of various templates that available across github.  This should be a singular template focused on helping people spin up selfhosted services using Portainer.

### Prerequisites

1. A server Running the Portainer-Agent Image
2. A Server running the Portainer Server Image

*Both of the above instances would also be running docker.*

### Installing

1. Login to the Portainer Server
2. Click the *settings* link found in the bottom of the left-hand navigation.
2. Enable Use external templates
3. Add the url: `https://raw.githubusercontent.com/saedog/portainer_templates/master/template/template.json` then go to app templates and hit refresh at the top.

### Information
All templates are already configured to bind mount to various places on host drive. This branch works without the need for OMV. The following folders are all created in /portainer/

* **Files** - General file storage.
  * **AppData** - Subfolder where application data (unrelated to served data) is stored.
    * **Config** - Subfolder where configuration files for every container are stored.
* **Downloads** - Where bittorrent and usenet downloaders download files to.
* **TV** - Where tv shows are stored/moved to after downloaded.
* **Movies** - Where movies are stored/moved to after downloaded.
* **Music** - Where music is stored/moved to after downloaded.
* **Books** - Where books are stored/moved to after downloaded.
* **Comics** - Where comics are stored/moved to after downloaded.
* **Podcasts** - Where podcasts are stored/moved to after downloaded.
## App List

  - Adguard 
  - Airsonic 
  - Authelia 
  - Bazarr 
  - Beets 
  - Vaultwarden 
  - Booksonic 
  - Cops 
  - Calibre-web 
  - Chevereto 
  - Chowdown 
  - Code-server 
  - Codiad 
  - Couchpotato 
  - Daapd 
  - Dashmachine 
  - Davos 
  - Deemix 
  - Domoticz 
  - Duckdns 
  - Duplicati 
  - Emby 
  - EmbyStat 
  - Filebrowser 
  - Freshrss 
  - Gazee 
  - Guacamole 
  - Grocy 
  - Htpcmanager 
  - Headphones 
  - Heimdall 
  - Homer 
  - Huginn 
  - Invoice_ninja 
  - Jackett 
  - Jellyfin 
  - kodi-headless 
  - Lazylibrarian 
  - Letsencrypt / SWAG 
  - Librespeed 
  - Lidarr 
  - Lychee
  - Mariadb 
  - Mcmyadmin2 
  - Medusa 
  - Minetest 
  - Minisatip 
  - Mstream 
  - Murmur 
  - Musicbrainz 
  - Muximux 
  - Mylar 
  - Nzbget 
  - Nzbhydra2 
  - Nextcloud 
  - Nginx 
  - Nginx-proxy-manager 
  - Oscam 
  - Ombi 
  - Openvpn-as 
  - Organizr-v2 
  - Overseerr 
  - Owncloud 
  - Petio 
  - Photoshow 
  - Pihole 
  - Piwigo 
  - Plex 
  - Plexrequests 
  - Projectsend 
  - Protonmail-bridge 
  - Prowlarr 
  - Pydio 
  - Qbittorrent 
  - Quassel-core 
  - Radarr 
  - Reactive-resume 
  - Resilio-sync 
  - Rutorrent 
  - Sabnzbd 
  - Shiori 
  - Sickchill 
  - Sickgear 
  - Smokeping 
  - Snibox 
  - Sonarr 
  - Syncthing 
  - Tautulli 
  - Thelounge 
  - Tiddlywiki 
  - Tt-rss 
  - Transmission 
  - Transmission-openvpn 
  - Tvheadend 
  - Ubooquity 
  - Unifi-controller 
  - Watchtower 
  - Webgrabplus 
  - Whoogle 
  - Wikijs 
  - Yacht 
  - Youtubedl-material 
  - Znc 
 
 ## More Apps
 

## Contributing

If you wish to contribute make a pull request, create an issue, or email me.

## Authors
* **NASHosted** - *Current Work* - [NASHOSTED](https://github.com/nashosted)
* **sawdog** - *Current Work* - [sawdog](https://github.com/sawdog)
* **Jos Visser** - *Initial work* - [Qballjos](https://github.com/Qballjos)
* **xe-nvdk** - *template conversion to portainer V2* - [xe-nvdk](https://github.com/xe-nvdk)
* **tbiering** - *Termplate cleanup and typo fixes* - [tbiering](https://github.com/tbiering)

See also the list of [contributors](https://github.com/Qballjos/portainer_templates/graphs/contributors) who participated in this project.

## Acknowledgments

* LinuxServer.io for the old Template
* Inspiration being too lazy to create each container template manualy
* The team behind Portainer for there awesome product and support in the community
