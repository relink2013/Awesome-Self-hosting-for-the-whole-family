[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
# Awesome-Self-hosting-for-the-whole-family
Self-hosting is the process of locally hosting and managing applications instead of renting from SaaS providers. And 9 times out of 10 it results in a frustrated spouse or family members who end up using "the cloud" anyway because they can't figure out how to use the server you setup.

This is a list for those of us who primarily live on our mobile devices, or have family members who do, but still want the privacy, security, and control of our own data that self-hosting provides.

The goal of this list is to curate all self-hosted services available that have mobile counterparts.

* All services must have an Android and iOS app to make the list, or at the very least have apps in development.
* 3rd party apps are ok, so long as it offers all core functionality of the service it is designed to work with.
* The mobile apps must not need Root or Jailbreak, and must be available through an official Appstore.
* Open source is always preferable, however Proprietary, paid, or even services that need specific/proprietary hardware are all welcome here, and will be specified next to each app.

--------------------

Place holder for a table of contents...as soon as i learn how to make one. 

--------------------

## Media Management (Movies, TV, Music, Books)

[**Synology Audio Station**](https://www.synology.com/en-us/dsm/feature/audio_station)
  * INFO/Requirements:
    * Synology Disk Station, Synology Rack Station, or XPenology

  * Description:
    Enjoy high-quality playback, listen to radios, manage own music collection, create personal playlist and share with friends on Audio Station and its mobile app DS audio everywhere.

  * Official Apps:
    * iOS - https://itunes.apple.com/app/ds-audio/id321495303?l=zh&mt=8
    * Android - https://play.google.com/store/apps/details?id=com.synology.DSaudio

  * 3rd Party Apps:
    * NONE
--------------------
[**Synology Video Station**](https://www.synology.com/en-us/dsm/feature/video_station)
  * INFO/Requirements:
    * Synology Disk Station, Synology Rack Station, or XPenology

  * Description:
    Video Station helps you manage all the movies, TV shows, and home videos on your Synology NAS. Moreover, it can stream videos to various devices — computers, smartphones, media players, and TVs — to provide you with non-stop, fun watching experience.

  * Official Apps:
    * iOS - https://itunes.apple.com/app/ds-video/id540949418?mt=8
    * Android - https://play.google.com/store/apps/details?id=com.synology.dsvideo

  * 3rd Party Apps:
    * NONE
--------------------
[**Plex**](https://www.plex.tv/)
  * INFO/Requirements:
    * Free with paid tier

  * Description:
    Plex brings together all the media that matters to you, organizing your personal collections alongside stellar online content, streaming music, and more, making it all look beautiful in one universal interface. Features include Plex Live TV & DVR, plus a growing catalog of great web shows, news, and podcasts, making it easier than ever to find and enjoy all the media you love in a single app, on any device, no matter where you are.

  * Official Apps:
    * [All official apps can be found here](https://www.plex.tv/apps-devices/)

  * 3rd Party Apps:
    * [Infuse 5](https://firecore.com/infuse) Free with paid tier, iOS/tvOS only, does not support LiveTV
--------------------
[**Emby**](https://emby.media/about.html)
  * INFO/Requirements:
    * Free with paid tier

  * Description:
    Powerful tools to manage your content, users, sharing, security, and more. The Emby Server dashboard is designed for smart phones, tablets, and big screens, allowing you to manage your media anytime, anywhere.

  * Official Apps:
    * [All official apps can be found here](https://emby.media/download.html)

  * 3rd Party Apps:
    * NONE
--------------------
[**TVHeadend**](https://tvheadend.org/)
  * INFO/Requirements:
    * Free

  * Description:
    Tvheadend is a TV streaming server and recorder for Linux, FreeBSD and Android supporting DVB-S, DVB-S2, DVB-C, DVB-T, ATSC, ISDB-T, IPTV, SAT>IP and HDHomeRun as input sources.
    
  * Official Apps:
    * NONE

  * 3rd Party Apps:
    * Most apps can be found [HERE](https://tvheadend.org/projects/tvheadend/wiki/Clients)
    * MrMc is an additional app for iOS, its basically a "approved" port of Kodi. It requires Paid tier to work with TVHeadend.
--------------------

NextPVR - Free

Subsonic - Free with paid tier - (Apps List)

Airsonic - Free - Fork of subsonic

Serviio - Free with paid tier

mStream - Free - Seems to be relatively new, Android app is in Alpha and iOS app not yet released.

Jellyfin - Free - Fairly recent fork of Emby. Android, and Android TV apps are out, and iOS app is in the works. Currently iOS can use Infuse, or VLC to play content.

Calibre - Free - eBook manager, uses 3rd party apps.

## Photo Management

Synology Moments - (requires Synology Diskstation or XPenology)

Synology Photostation - (requires Synology Diskstation or XPenology)

Piwigo - Free

NextCloud - Free

## Notes, Bookmarks, RSS etc

Synology Notestation - (requires Synology Diskstation or XPenology) - Similar to Evernote

*Joplin - Free - While it technically has no server component I figured id include it anyway because its very solid. Only requires a WebDav server.

StandardNotes - Free to self host - I would love to try this one, but I have never been able to get it working.

Wallabag - Free - Very similar to Pocket. Also has browser extensions available.

Leanote - Free with paid tier

Tiny Tiny RSS - Free - Uses mostly 3rd party apps

## Password Management

BitWarden - Free -

*Enpass - Free -

*KeePass - Free - Can sync using standard protocols (FTP, WebDAV, etc). 3rd party apps available.

## Home Security/Automation

Synology Surveillance Station - (requires Synology Diskstation or XPenology) - First 2 IP cameras are free, Paid License required after 2.

Lux Riot - Free for personal use up to 8 cameras

Home Assistant - Free

OpenHAB - Free

Blue Iris - Paid - Server and app are both paid, but reasonably priced.

ZoneMinder - Free - The Zoneminder server is free, apps are all 3rd party, some are free some are paid.

## Office/Productivity

OnlyOffice - Free to self-host

Collabora - Free - Works best when paired with a self hosted cloud platform such as Nextcloud or Pydio, others are compatible as well. Does not have full mobile apps.

## Files/General Purpose

NextCloud - Free

OwnCloud - Free

Synology Drive - (requires Synology Diskstation or XPenology)

Synology FileStation - (requires Synology Diskstation or XPenology)

Tonido - Free for personal use

Cozy Cloud - Free to self host

Pydio - Free for home use

Resilio Sync - Free with paid tier - Formerly Bittorrent Sync.

Seafile - Free Community Edition

## Chat/Communication

Synology Chat - (requires Synology Diskstation or XPenology)

Rocket Chat - Free

Riot.IM/Matrix - Free

NextCloud - Free

Mattermost - Free

Zulip - Free

*Delta Chat- Free - Uses email as its back end, since you can easily host your own email server it made the list.

Confluence - Paid - Ranges from $10 one time fee for a small team setup up to $200k a year for large data center installs.
