=== Video Share VOD ===
Contributors: videowhisper, VideoWhisper.com
Author: VideoWhisper.com
Author URI: http://www.videowhisper.com
Plugin Name: Video Share VOD
Plugin URI: http://www.videosharevod.com
Donate link: http://www.videowhisper.com/?p=Invest
Tags: video, share, VOD, HTML5, RTMP, HLS, MP4, Strobe, player, video on demand, media, snapshot, thumbnail, FFMPEG, Wowza, playback, playlist, netflix, hulu, SVOD, membership, paid, subscription, iOS, iPhone, iPad, Android, mobile, upload, stream, turnkey, shortcode, page, Post, posts, admin, VAST, AVOD, pre-roll, ads, over-the-top, OTT, on-demand, HD, widget, script, clone, alternative, turnkey, scripts
Requires at least: 2.7
Tested up to: 3.9.1
Stable tag: trunk

Video Share / Video on Demand (VOD) plugin allows WordPress users and admins to share videos and others to watch from various devices. 

== Description ==

= Key Features =
* adds video post type to WordPress site
* extracts thumbnail, generates feature image
* extracts info: duration, resolution, bitrate, file size
* multiple playback methods
* playlist taxonomy, listing of videos with rest of posts in categories, tags, searches
* AJAX display and update of video list
* shortcodes for listing videos, displaying player, upload form, import form
* VAST (video ad serving template) support for video ads
* premium users that don't see ads
* mass video upload
* mass video import (from server)
* see more [Video Share VOD Features](http://videosharevod.com/features/
 "Video Share VOD Features") ...

= Membership VOD =
* define global video access list (roles, user emails & ids)
* role playlists: assign videos as accessible by certain roles
* exception playlists: free, registered, unpublished
* show preview and custom message when inaccessible
* read more about [Video On Demand](http://videosharevod.com/features/video-on-demand/ "Video On Demand") ...

= Players =
* HTML5 video conversion and playback support
* RTMP playback support (fast skip, no direct access to video files)
* HLS playback support (rtmp alternative for iOS)
* HD video support (player adapts to video size)
* HTML5 native tag player
* Video.js player with VAST support
* MediaElement.js (WordPress default video player)
* Strobe Flash player

= HTML5 Video Uploader =
* Drag & Drop
* AJAX (no Submit, page reload required to upload more videos)
* multi video support
* status / progress bar for each upload
* upredictable secure upload file names
* fallback to standard upload for older browsers
* mobile video upload (iOS6+, Android 3+)
* backend multi upload menu
* read more about [Video Uploader](http://videosharevod.com/features/video-uploader/ "Video Uploader") ...

= Live Streaming =
* integrates with [VideoWhisper Live Streaming](http://wordpress.org/plugins/videowhisper-live-streaming-integration/ "VideoWhisper Live Streaming") channels plugin
* import archived video streams (previous broadcasts)
* upload additional videos for each channel
* list videos on channel page
* channel button on video page (if channel exists)
* read more about [Live Streaming](http://videosharevod.com/features/live-streaming/ "Live Streaming") ...

= Special Requirements =
* FFMPEG and codecs are required to generate snapshots and convert videos.
* Optionally, to use RTMP playback, RTMP hosting is required. 
* Optionally, for HLS playback, a server with HLS support like Wowza is required.

== Screenshots ==
1. Video list (AJAX load and update, pagination, info)
2. HTML5 video upload (Multi file, AJAX, Drag & Drop, fallback (standard upload as backup), iOS & Android support)
3. RTMP player support (fast search, no direct file access, HD)
4. HTML5 player (plain and HLS, video conversion for mobile)
5. Admin settings (VOD setup)
6. VOD access roles playlists, custom message
7. Live Streaming channel management (with archive import and video upload)
8. Select category, order by date/views/watch time, move to another page with AJAX

== Documentation ==
* Plugin Homepage : http://www.videosharevod.com
* Developer Contact : http://www.videowhisper.com/tickets_submit.php
* Recommended Hosting: http://videosharevod.com/hosting/

= Shortcodes =
* videowhisper_videos playlist="" perpage="" perrow="" - Video list.
* videowhisper_upload playlist="" category="" owner="" - Upload form.
* videowhisper_player video="0" - Video player.
* videowhisper_preview video="0" - Preview only.
* videowhisper_player_html source="" source_type="" poster="" width="" height="" - HTML file player.

For more details see Video Share VOD - Documentation menu after installing plugin.

== Demo ==
* Test it live on http://livon.tv/


== Frequently Asked Questions ==
* Q: How much does this plugin cost?
A: This plugin is FREE. 

* Q: Does this work on mobiles?
A: Yes, videos are converted to formats accessible on mobiles and displayed with special players.
Uploading videos also works on latest mobiles. In example on iOS6+ user will be prompted to record a video or select on from camera roll when pressing Choose Files button.

* Q: Can I run this on my shared hosting plan?
A: Only if plan includes FFMPEG with support for codecs you use in your videos.
Special functionality like RTMP and HLS playback demands hosting that support it.

* Q: What exactly is VOD?
A: VOD allow users to select and watch/listen to video or audio content when they choose to, rather than having to watch at a specific broadcast time. For more details see http://videosharevod.com/video-on-demand/ .

* Q: How does a VOD site generate income?
A: By selling access to individual videos, subscriptions / membership to access all or budled content and advertising.

== Extra ==
Webcam plugins including Live Streaming plugin, can be found at http://www.videowhisper.com/ .


== Changelog ==

= 1.2.1 =
* custom playlist template with videojs html5 player

= 1.1.8 =
* widget to list videos with various options
* ajax controls to select category, order

= 1.1.7 =
* Mass import videos
* Premium users (no video ads)

= 1.1.5 =
* Video.js HTML5 player with VAST support

= 1.1.5 =
* VOD global access list
* VOD role playlists
* VOD free, registered, unpublished playlist exceptions
* multi video upload from backend
* WP default player (MediaElement.js)

= 1.1.4 =
* ** HTML5 Video Uploader *
* Drag & Drop
* AJAX (no Submit, page reload required to upload more videos)
* multi video support
* status / progress bar for each upload
* upredictable secure upload file names
* fallback to standard upload for older browsers
* mobile video upload (iOS6+, Android 3+)

= 1.1.1 =
* First public release.