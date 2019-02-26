[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
# Awesome-Self-hosting-for-the-whole-family
Self-hosting is the process of locally hosting and managing applications instead of renting from SaaS providers. And 9 times out of 10 it results in a frustrated spouse or family members who end up using "the cloud" anyway because they can't figure out how to use the server you setup.

This is a list for those of us who primarily live on our mobile devices, or have family members who do, but still want the privacy, security, and control over our own data that self-hosting provides.

The goal of this list is to curate all self-hosted services available that have mobile counterparts.

* All services must have a native Android and iOS app to make the list, or at the very least have apps in active development.
* PWAs (Progressive web apps) unfortunately do not qualify an app for this list. Atleast not until Apple allows better integration of them on iOS, and stops refreshing them every time you switch to another app. For now they are just too cumbersome, atleast on iOS. 
* 3rd party apps are ok, so long as it offers all core functionality of the service it is designed to work with.
* The mobile apps must not need Root or Jailbreak, and must be available through an official Appstore.
* Open source is always preferable, however Proprietary, paid, or even services that need specific/proprietary hardware are all welcome here. This is about ease of use, not soapboxing for FOSS. The intent here is getting people out of the cloud. 
* The app must beable to function outside of your home network, eg. a DLNA server really doesnt belong on this list, it can work through a VPN but that outside the scope of this list. 

--------------------

**Table of Contents**

* [Media Management (Movies, TV, Music, Books)](#Media-Management-Movies-TV-Music-Books)
* [Photo Management](#Photo-Management)
* [Notes, Bookmarks, RSS, etc](#Notes-Bookmarks-RSS-etc)
* [Password Management](#Password-Management)
* [Home Security/Automation](#Home-SecurityAutomation)
* [Office/Productivity](#OfficeProductivity)
* [Files/General Purpose](#FilesGeneral-Purpose)
* [Chat/Communication](#ChatCommunication)

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
    
  * Additional Categories:
    Photo Management - A newer plex pass feature allows for private photo libraries, complete with automatic tagging, geo location, automatic uploads from mobile devices and more.

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
[**NextPVR**](https://www.nextpvr.com/)
  * INFO/Requirements:
    * Free

  * Description:
    NextPVR is a personal video recorder application for Microsoft Windows, making it easy to watch or record live TV, and provides great features like series recordings, web scheduling, playing music, video and image files, iPhone/iPad client application, Kodi/Emby integration etc.
    
  * Official Apps:
    * [All official apps can be found here](https://www.nextpvr.com/download.html)

  * 3rd Party Apps:
    * NONE
--------------------
[**Subsonic**](http://www.subsonic.org/pages/index.jsp)
  * INFO/Requirements:
    * Free with paid tier

  * Description:
    Enjoy your music and movies everywhere.
Share with family and friends.

  * Official Apps:
    * [All official and 3rd party apps can be found here](http://www.subsonic.org/pages/apps.jsp)

  * 3rd Party Apps:
    * [All official and 3rd party apps can be found here](http://www.subsonic.org/pages/apps.jsp)
--------------------
[**Airsonic**](https://airsonic.github.io/)
  * INFO/Requirements:
    * Free

  * Description:
    Airsonic is a free, web-based media streamer, providing ubiquitous access to your music. Use it to share your music with friends, or to listen to your own music while at work. You can stream to multiple players simultaneously, for instance to one player in your kitchen and another in your living room.

  * Official Apps:
    * NONE

  * 3rd Party Apps:
    * [All official and 3rd party apps can be found here](https://airsonic.github.io/docs/apps/)
--------------------

## Photo Management

[**Synology Moments**](https://www.synology.com/en-us/dsm/feature/moments)
  * INFO/Requirements:
    * Synology Disk Station, Synology Rack Station, or XPenology

  * Description:
    Gather all your photos and videos in one private place and organize them in an entirely new way. Synology Moments opens a new era for photo storage, allowing random photos to be automatically sorted by an image-recognizing technique that can identify the people, subjects, and places in the photos.
    
  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/synology-moments/id1284004851?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.synology.moments&hl=en_US)

  * 3rd Party Apps:
    * NONE
--------------------

[**Synology Photostation**](https://www.synology.com/en-us/dsm/feature/photo_station)
  * INFO/Requirements:
    * Synology Disk Station, Synology Rack Station, or XPenology

  * Description:
    Photo Station lets you efficiently manage photo storage, share and access files on the go, collect client feedback, and do a lot more.
    
  * Official Apps:
    * [iOS](https://itunes.apple.com/app/ds-photo/id321493106?l=zh&mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.synology.dsphoto)

  * 3rd Party Apps:
    * NONE
--------------------

[**Piwigo**](https://piwigo.org/)
  * INFO/Requirements:
    * Free

  * Description:
    Piwigo is open source photo gallery software for the web. Designed for organisations, teams and individuals.
    
  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/piwigo/id472225196)

  * 3rd Party Apps:
    * [Android](https://play.google.com/store/apps/details?id=delit.piwigoclient.paid&hl=en_US)
--------------------

## Notes, Bookmarks, RSS, etc

[**Synology Notestation**](https://www.synology.com/en-us/dsm/feature/note_station)
  * INFO/Requirements:
    * Synology Disk Station, Synology Rack Station, or XPenology

  * Description:
The important and the trivial, in one place yet everywhere. Note Station allows your precious ideas to be synced to all your devices with maximum privacy and security. Having any thoughts or feelings now? Just open the package, then create, edit and enjoy!

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/ds-note/id918177542?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.synology.dsnote&hl=en_US)

  * 3rd Party Apps:
    * NONE
--------------------

[**Joplin**](https://joplin.cozic.net/)
  * INFO/Requirements:
    * Free
    * Joplin does not have its own server backend and instead requires keeping clients in sync through a WebDAV server. However WebDAV servers are very easy to self host, and Joplin is a solid app that deserves a place on this list. However Due to not having its own backend, this also means that Joplin has no WebUI and relies on it clients to view notes. 

  * Description:
Joplin is a free, open source note taking and to-do application, which can handle a large number of notes organised into notebooks. The notes are searchable, can be copied, tagged and modified either from the applications directly or from your own text editor. The notes are in Markdown format.

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/joplin/id1315599797)
    * [Android](https://play.google.com/store/apps/details?id=net.cozic.joplin&utm_source=GitHub&utm_campaign=README&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1)

  * 3rd Party Apps:
    * NONE
--------------------

[**StandardNotes**](https://standardnotes.org/)
  * INFO/Requirements:
    * Free to self-host

  * Description:
Standard Notes is a safe place for your notes, thoughts, and life's work. Free, open-source, and completely encrypted.

  * Official Apps:
    * [iOS](https://standardnotes.org/extensions?downloaded=ios)
    * [Android](https://standardnotes.org/extensions?downloaded=android)

  * 3rd Party Apps:
    * NONE
--------------------

[**Wallabag**](https://www.wallabag.org/en)
  * INFO/Requirements:
    * Free to self-host

  * Description:
Save and classify articles. Read them later. Freely. 

  * Official Apps:
    * [iOS](https://appsto.re/fr/YeqYfb.i)
    * [Android](https://play.google.com/store/apps/details?id=fr.gaulupeau.apps.InThePoche)

  * 3rd Party Apps:
    * NONE
--------------------

[**Leanote**](http://leanote.org/)
  * INFO/Requirements:
    * Free to self-host

  * Description:
Use leanote as a notebook/note, manage your knowledge on leanote. Do you like markdown ? don't worry, leanote support it.

  * Official Apps:
    * [iOS](https://itunes.apple.com/app/leanote/id1022302858)
    * [Android](https://qn-cdn.leanote.top/apk/Leanote-v1.0-beta.7.apk) App is still in Beta, so this is a direct link to the Beta APK file. 

  * 3rd Party Apps:
    * NONE
--------------------

[**Tiny Tiny RSS**](https://tt-rss.org/)
  * INFO/Requirements:
    * Free

  * Description:
Tiny Tiny RSS is a free and open source web-based news feed (RSS/Atom) reader and aggregator

  * Official Apps:
    *  NONE

  * 3rd Party Apps:
    * [iOS](https://itunes.apple.com/us/app/tiny-reader-rss/id689519762?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=org.fox.ttrss&hl=en_US)
--------------------

## Password Management

[**BitWarden**](https://bitwarden.com/)
  * INFO/Requirements:
    * Free

  * Description:
Solve your password management problems. The easiest and safest way for individuals, teams, and business organizations to store, share, and sync sensitive data. 

  * Official Apps:
    * [iOS](https://itunes.apple.com/app/bitwarden-free-password-manager/id1137397744?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.x8bit.bitwarden)

  * 3rd Party Apps:
    * NONE
--------------------

[**Enpass**](https://www.enpass.io/)
  * INFO/Requirements:
    * Free basic plan, Paid to unlock all features.
    * Enpass does not have its own server backend and instead requires keeping clients in sync through a WebDAV server. However WebDAV servers are very easy to self host, and Enpass is a solid app that deserves a place on this list. However Due to not having its own backend, this also means that Enpass has no WebUI and relies on its clients to work. 

  * Description:
Enpass ensures maximum security for your data by using open source and peer reviewed cryptography libraries of SQLCipher engine. Moreover, it is an offline password manager offering you the peace of mind that all your data is with you only and nothing is stored on our servers.

  * Official Apps:
    * [iOS](https://itunes.apple.com/app/enpass-password-manager/id455566716)
    * [Android](https://play.google.com/store/apps/details?id=io.enpass.app)

  * 3rd Party Apps:
    * NONE
--------------------

[**KeePass**](https://keepass.info/) - Free - Can sync using standard protocols (FTP, WebDAV, etc). 3rd party apps available.
  * INFO/Requirements:
    * Free
    * Keepass does not have its own server backend and instead requires keeping clients in sync through a WebDAV or FTP server. However WebDAV and FTP servers are very easy to self host, and Keepass is a solid app that deserves a place on this list. However Due to not having its own backend, this also means that Keepass has no WebUI and relies on its clients to work. 

  * Description:
KeePass is a free open source password manager, which helps you to manage your passwords in a secure way. You can put all your passwords in one database, which is locked with one master key or a key file. So you only have to remember one single master password or select the key file to unlock the whole database. The databases are encrypted using the best and most secure encryption algorithms currently known (AES and Twofish).

  * Official Apps:
    * NONE

  * 3rd Party Apps:
    * [All 3rd party apps can be found here](https://keepass.info/download.html)
--------------------

## Home Security/Automation

[**Synology Surveillance Station**](https://www.synology.com/en-us/surveillance)
  * INFO/Requirements:
    * Synology Disk Station, Synology Rack Station, or XPenology
    * First 2 IP cameras are free, Paid License required after 2.

  * Description:
Protect your business, home, and other environments with reliable, intuitive Surveillance Station, delivering intelligent monitoring and video management tools to safeguard your valuable assets.

  * Official Apps:
    * [iOS](https://itunes.apple.com/app/ds-cam/id349087111?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.synology.DScam)

  * 3rd Party Apps:
    * NONE
--------------------

[**Lux Riot**](https://www.luxriot.com/product/ip-camera-software/luxriot-evo/)
  * INFO/Requirements:
    * Free for personal use up to 8 cameras

  * Description:
Delivering an outstanding quality performance, this security and video IP camera software and surveillance system supports over 4000 cameras from major producers and is ideal for use at homes or small offices with surveillance networks of nine cameras or fewer. The meticulously designed interface will allow any user to quickly understand the whole process of configuration and start using the Video Management System software.

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/luxriot-evo-mobile/id1086037968?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.Luxriot.evomobile)

  * 3rd Party Apps:
    * NONE
--------------------

[**Home Assistant**](https://www.home-assistant.io/)
  * INFO/Requirements:
    * Free

  * Description:
Open source home automation that puts local control and privacy first. Powered by a worldwide community of tinkerers and DIY enthusiasts. Perfect to run on a Raspberry Pi or a local server. 

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/home-assistant-open-source-home-automation/id1099568401?mt=8)
    * [Android](https://www.home-assistant.io/docs/frontend/mobile/) Progressive Web APP

  * 3rd Party Apps:
    * [Android](https://play.google.com/store/apps/details?id=com.axzae.homeassistant&hl=en_US)
--------------------

[**OpenHAB**](https://www.openhab.org/)
  * INFO/Requirements:
    * Free

  * Description:
a vendor and technology agnostic open source automation software for your home

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/openhab/id492054521?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=org.openhab.habdroid)

  * 3rd Party Apps:
    * NONE
--------------------

[**Blue Iris**](http://blueirissoftware.com/)
  * INFO/Requirements:
    * Paid

  * Description:
Keep an eye on your home, place of business, cars, and valuables; watch your pets or your kids; monitor your nanny, babysitter, or employees. Watch your door for mail, packages or visitors. Use motion detection, audio detection, or capture continuously. Receive alerts via loudspeaker, e-mail or phone.

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/blue-iris/id585350145?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.blueirissoftware.blueiris)

  * 3rd Party Apps:
    * NONE
--------------------

[**ZoneMinder**](https://zoneminder.com/)
  * INFO/Requirements:
    * Free

  * Description:
A full-featured, open source, state-of-the-art video surveillance software system. Monitor your home, office, or wherever you want. Using off the shelf hardware with any camera, you can design a system as large or as small as you need.

  * Official Apps:
    * NONE

  * 3rd Party Apps:
    * [iOS](https://itunes.apple.com/us/app/zmninja-pro/id1067914954?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.pliablepixels.zmninja_pro&hl=en&utm_source=global_co&utm_medium=prtnr&utm_content=Mar2515&utm_campaign=PartBadge&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1)
--------------------

## Office/Productivity

[**OnlyOffice**](https://www.onlyoffice.com/)
  * INFO/Requirements:
    * Free community edition

  * Description:
ONLYOFFICE provides you with the most secure way to create, edit and collaborate on business documents online. 100% compatible with MS Office formats 

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/onlyoffice-documents/id944896972)
    * [Android](https://play.google.com/store/apps/details?id=com.onlyoffice.documents)

  * 3rd Party Apps:
    * NONE
--------------------

## Files/General Purpose
###### Many services in this category may crossover into other categories, so its work checking out the specific features of each service listed here.
--------------------

[**NextCloud**](https://nextcloud.com/)
  * INFO/Requirements:
    * Free

  * Description:
Nextcloud offers industry-leading on-premises file sync and online collaboration technology. Our expertise is in combining the convenience and ease of use of consumer-grade solutions like Dropbox and Google Drive with the security, privacy and control business needs.

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/nextcloud/id1125420102?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.nextcloud.client)
    * [Android](https://f-droid.org/packages/com.nextcloud.client/) F-Droid

  * 3rd Party Apps:
    * NONE
--------------------

[**OwnCloud**](https://owncloud.org/)
  * INFO/Requirements:
    * Free

  * Description:
ownCloud is the most straightforward way to file sync and share data. You don’t need to worry about where or how to access your files. With ownCloud all your data is where ever you are; accessible on all devices, any time.

  * Official Apps:
    * [iOS](http://itunes.apple.com/us/app/owncloud/id543672169?ls=1&mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.owncloud.android)

  * 3rd Party Apps:
    * NONE
--------------------

[**Synology Drive**](https://www.synology.com/en-us/dsm/feature/drive)
  * INFO/Requirements:
    * Synology Disk Station, Synology Rack Station, or XPenology

  * Description:
Synology Drive unifies multiple file portals on Synology NAS and greatly simplifies data management by synchronizing files across various platforms. To fulfill your need for office collaboration, Drive also provides seamless sharing features to ensure that you do not lose important files.

  * Official Apps:
    * [iOS](https://itunes.apple.com/app/synology-drive/id1267275421?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.synology.dsdrive)

  * 3rd Party Apps:
    * NONE
--------------------

[**Synology FileStation**](https://www.synology.com/en-us/knowledgebase/DSM/help/FileStation/FileBrowser_desc)
  * INFO/Requirements:
    * Synology Disk Station, Synology Rack Station, or XPenology

  * Description:
File Station is an easy-to-use file management tool, allowing DSM users over the Internet to access Synology NAS folders with their web browsers. By launching two or more File Stations, you can manage all your Synology NAS data by dragging and dropping them between different File Stations.

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/ds-file/id416751772?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.synology.DSfile&hl=en_US)

  * 3rd Party Apps:
    * NONE
--------------------

[**Tonido**](https://www.tonido.com/tonidodesktop_downloads/)
  * INFO/Requirements:
    * Free for personal use

  * Description:
Access, Share and Sync your PC’s Files From Anywhere

  * Official Apps:
    * [iOS](http://itunes.apple.com/us/app/tonido/id388726418?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.tonido.android)

  * 3rd Party Apps:
    * NONE
--------------------

[**Cozy Cloud**](https://cozy.io/en/)
  * INFO/Requirements:
    * Free for personal use

  * Description:
Cozy Cloud offers everyone a smart digital home, Cozy that combines comfort and security for more services.
With Cozy, change the rules and become the only one that control your data.

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/cozy-drive/id1224102389?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=io.cozy.drive.mobile&hl=en)

  * 3rd Party Apps:
    * NONE
--------------------

[**Pydio**](https://pydio.com/)
  * INFO/Requirements:
    * Free for personal use

  * Description:
Modern file management platform built according to your business needs and regulations, Pydio is open-source software deployed on your servers or wherever you decide

  * Official Apps:
    * [iOS](https://itunes.apple.com/fr/app/pydio/id709275884)
    * [Android](https://play.google.com/store/apps/details?id=com.pydio.android.cells&hl=fr)

  * 3rd Party Apps:
    * NONE
--------------------

[**Resilio**](https://www.resilio.com/) -Formerly Bittorrent Sync.
  * INFO/Requirements:
    * Free with paid tier

  * Description:
Sync All Your Data, Across All Your Devices. Resilio Sync is a fast, reliable, and simple file sync and share solution, powered by P2P technology

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/id1126282325)
    * [Android](https://play.google.com/store/apps/details?id=com.resilio.sync&referrer=utm_source%3Dresilio%26utm_medium%3Ddownloads%26utm_campaign%3Dhome)

  * 3rd Party Apps:
    * NONE
--------------------

[**Seafile**](https://www.seafile.com/en/home/)
  * INFO/Requirements:
    * Free community edition

  * Description:
Seafile is an enterprise file hosting platform with high reliability and performance. Put files on your own server. Sync and share files across different devices, or access all the files as a virtual disk.

  * Official Apps:
    * [iOS](https://itunes.apple.com/cn/app/seafile-pro/id639202512?l=en&mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.seafile.seadroid2)
    * [Android](https://f-droid.org/repository/browse/?fdid=com.seafile.seadroid2) F-Droid

  * 3rd Party Apps:
    * NONE
--------------------

## Chat/Communication

[**Synology Chat**](https://www.synology.com/en-us/dsm/feature/chat)
  * INFO/Requirements:
    * Synology Disk Station, Synology Rack Station, or XPenology

  * Description:
Synology Chat reduces the time users spend on composing emails and optimizes companies' internal communications. Chat is a messaging service that runs on Synology NAS and transforms the way you collaborate with colleagues.

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/synology-chat/id1121875041?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.synology.dschat&hl=en_US)

  * 3rd Party Apps:
    * NONE
--------------------

[**Rocket Chat**](https://rocket.chat/)
  * INFO/Requirements:
    * Free community edition

  * Description:
Rocket.Chat is free, unlimited and open source. Replace email, HipChat & Slack with the ultimate team chat software solution.

  * Official Apps:
    * [iOS](https://itunes.apple.com/app/rocket-chat/id1148741252)
    * [Android](https://play.google.com/store/apps/details?id=chat.rocket.android)

  * 3rd Party Apps:
    * NONE
--------------------

[**Matrix**](https://matrix.org/blog/home/)
  * INFO/Requirements:
    * Free

  * Description:
An open network for secure, decentralized communication.

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/vector.im/id1083446067)
    * [Android](https://play.google.com/store/apps/details?id=im.vector.alpha)

  * 3rd Party Apps:
    * NONE
--------------------

[**Nextcloud Talk**](https://nextcloud.com/talk/)
  * INFO/Requirements:
    * Free

  * Description:
Screensharing, online meetings & web conferencing without data leaks.

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/nextcloud-talk/id1296825574)
    * [Android](https://play.google.com/store/apps/details?id=com.nextcloud.talk2)

  * 3rd Party Apps:
    * NONE
--------------------

[**Mattermost**](https://mattermost.com/)
  * INFO/Requirements:
    * Free Team Edition

  * Description:
Mattermost is a flexible, open source messaging platform that meets even the most demanding privacy and security standards. 

  * Official Apps:
    * [iOS](http://about.mattermost.com/mattermost-ios-app/)
    * [Android](http://about.mattermost.com/mattermost-android-app/)

  * 3rd Party Apps:
    * NONE
--------------------

[**Zulip**](https://zulipchat.com/)
* INFO/Requirements:
    * Free Community Edition

  * Description:
Zulip combines the immediacy of real-time chat with an email threading model.
With Zulip, you can catch up on important conversations while ignoring irrelevant ones. 

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/zulip/id1203036395)
    * [Android](https://play.google.com/store/apps/details?id=com.zulipmobile)

  * 3rd Party Apps:
    * NONE
--------------------

[**Delta Chat**](https://delta.chat/en/)
  * INFO/Requirements:
    * Free
    * Does not have its own backend server. Instead Delta Chat relies on using the existing email standards. It is on the list due to being a solid messenger, and the fact that it is fairly simple to self host an email server just for use with this app. Which just barely qualifies it as self hosted. 

  * Description:
Delta Chat is like Telegram or Whatsapp but without the tracking or central control. Check out our GDPR compliancy statement. Delta Chat doesn’t have their own servers but uses the most massive and diverse open messaging system ever: the existing e-mail server network. Chat with anyone if you know their e-mail address, no need for them to install DeltaChat! All you need is a standard e-mail account. 

  * Official Apps:
    * [iOS](https://testflight.apple.com/join/WVoYFOZe) Testflight (app is still in beta)
    * [Android](https://play.google.com/store/apps/details?id=chat.delta)

  * 3rd Party Apps:
    * NONE
--------------------

[**Confluence**](https://www.atlassian.com/software/confluence)
  * INFO/Requirements:
    * Paid
    * Ranges from $10 one time fee for a small team setup up to $200k a year for large data center installs. 

  * Description:
Create, collaborate, and keep all your work in one place. Unlike document and file-sharing tools, Confluence is open and accessible, helping your team, and your company do their best work together

  * Official Apps:
    * [iOS](https://itunes.apple.com/us/app/id1288365159?mt=8)
    * [Android](https://play.google.com/store/apps/details?id=com.atlassian.confluence.server)

  * 3rd Party Apps:
    * NONE
--------------------
