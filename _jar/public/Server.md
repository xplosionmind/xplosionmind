---
date: 2020-03-21
updated: 2020-10-16
tags: ["geek"]
title: "Server"
description: "Everything about my server."
---
It is a surprisingly powerful (considered how much I pay for it) <abbr title="Virtual Private Server">VPS</abbr> hosted in Germany by [Contabo](https://contabo.com). It runs [Ubuntu 20.04](https://releases.ubuntu.com/20.04/).


[Here](Server%20setup) is a dedicated step-by-step walkthrough of my server setup and configuration.
{:.box}

<br>

## Improvements and fixes

- move Jitsi Meet from `call.tommiboom.tk` to `call.tommi.space`
- Make Server from `AJAX` to `Cron`
- [add Memcache to Nextcloud](https://docs.nextcloud.com/server/19/admin_manual/configuration_server/caching_configuration.html)
- document server saving issues

<br>
<br>

## Installed

- [Nextcloud](https://nextcloud.com)
	- [configuration and installation walk-through](Server%20setup#nextcloud)
	- [cheatsheet](Server%20setup#nextcloud-cheatsheet)
	- [Nextcloud Pi](https://ownyourbits.com/nextcloudpi/)
- [Jitsi Meet](https://jitsi.org)
	- [configuration and installation walk-through](Server%20setup#jitsi-meet)
	
<br>
<br>

## Mail server

- [Hardware specs requirements](https://discourse.mailinabox.email/t/minimal-server-performance/6997)
- A [Reddit post](https://www.reddit.com/r/selfhosted/comments/6h88qf/on_selfhosted_mail_servers/)
- A [Meduim post](https://medium.com/@stoyanov.veseline/self-hosting-a-mail-server-in-2019-6d29542dadd4)

### options

- [A script](https://github.com/LukeSmithxyz/emailwiz) by Luke Smith
- [Mail-in-a-Box](https://mailinabox.email) (requires a fresh server completely devoted to it)

<br>
<br>

## Wishlist

Useful server apps or services I haven’t installed yet, in order of urgence and importance.

1. [Mailcow](https://mailcow.email/) && [Roundcube](https://roundcube.net/) self hosted email
1. [Mailtrain](https://mailtrain.org) (very stable but old and not updated since 2 years ago) \|\| [listmonk](https://listmonk.app) (brand new and feature-packed, but in Alpha version), Newsletter managers
1. [Heedy](https://github.com/heedy/heedy), for [self-tracking](/self-tracking)
1. [Feedbin](https://feedbin.com), the best RSS reader I found yet.
	- [Installation overview](https://github.com/feedbin/feedbin#introduction)
	- [Installation guide](https://github.com/feedbin/feedbin/blob/master/doc/INSTALL-ubuntu.md)
1. [Fediverse](https://fediverse.network/) platforms
	- [Mastodon](https://joinmastodon.org/)
	    - [MastodonToTwitter](https://github.com/AmauryCarrade/MastodonToTwitter), Twitter - Mastodon cross-posting
	    - [mastodon-bot](https://github.com/yogthos/mastodon-bot), to automatically post RSS verde and tweets
	- [PeerTube](https://joinpeertube.org)
		- [official installation documentation](/https://docs.joinpeertube.org/#/install-any-os)
	- [PixelFed](https://pixelfed.org/), instagram alternative
1. [Ferdi](https://github.com/getferdi/server), all services in one place
1. [Ampache](http://ampache.org/), for music listening
1. [Huginn](https://github.com/huginn/huginn), an IFTTT Alternative
1. [Jellyfin](https://jellyfin.org/) personal streaming service
1. [Kanboard](https://kanboard.org/) Kanban Project Management Software
1. [OhMyForm](https://ohmyform.com/docs/install/) for forms
1. [Plex](https://www.plex.tv), media streaming platform

<br>
<br>

## General knowledge

- [Make Your Computer Into a Server in 10 Minutes](https://www.instructables.com/id/Make-Your-Computer-Into-A-Server-in-10-Minutes-fr/)
- [Apache for beginners \| WIRED](https://www.wired.com/2010/02/Apache_for_Beginners/)
- [Be Your Own Open ID Provider](https://www.wired.com/2010/02/Be_Your_Own_OpenID_Provider/)

<br>
<br>

## Docker

I hate Docker. Probably, because I don't get it. I believe that if one day I'll finally learn how it works, my life is going to change, everything will be easier. For this reason, I'm keeping at hand useful stuff which work and integrate with it.

- [Nginx Proxy Manager](https://developers.italia.it/it/news/feed.atom)

<br>
<br>

## DIY Home Server

- <https://youtu.be/DlQNciGVgbQ>
- <https://youtu.be/ohkMRA74MB4>
- <https://youtu.be/GeDo8mjB5oU>
- [Set Up a Home Server \| WIRED](https://www.wired.com/2010/02/set-up-a-home-server/)

### Raspberry Pi

- [IP Address](https://en.wikipedia.org/wiki/IP_address)
- [Several Guides](https://pimylifeup.com/category/projects/server/)
- [Less specific guides](https://pimylifeup.com/category/projects/server/)
- [Nextcloud Server](https://lonewolfonline.net/raspberry-pi-personal-cloud-server/)
- [Instructables](https://www.instructables.com/id/Ultimate-Pi-Based-Home-Server/)