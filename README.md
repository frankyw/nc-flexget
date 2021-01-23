## frankyw/nc-flexget

This is a repository to version control a FlexGet configuration. This configuration is used in conjunction with Transmission for downloading, Filebot for post-processing and emby for viewing.
## Notes
Be aware of the following:
* This configuration It is a combination of private and public trackers.
* All traffic is proxied through a VPN using a HTTP Proxy (welcome to the UK).
* Movies are collected from two custom Trakt movie watchlists, combined with the [Watcht](https://apps.apple.com/us/app/watcht-for-trakt/id1396920723) app, one for 1080p+ and one specifically for 4K HDR releases.
* TV Series are controlled via two custom Trakt lists, one for 1080p and one for 4K releases.
* Most downloads are fetched in real-time via private tracker IRC announce channels, or near real-time from an RSS feed.
* Anything else not downloaded in real-time is downloaded via a periodic search.
* Extraction is handled by [Filebot-node](https://www.filebot.net/forums/viewtopic.php?t=2663) called by Transmission through a Python script, as Filebot is a) designed for this task, and b) much easier to configure than FlexGet for this.