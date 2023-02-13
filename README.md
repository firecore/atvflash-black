# atvflash-black
aTV Flash (black) for ATV 2

Installation guide
https://support.firecore.com/hc/en-us/articles/215090337-Install-aTV-Flash-black-

Community support forum
https://community.firecore.com/c/legacy/2nd-gen-apple-tv/12

Copyright © 2010-2018 Firecore, LLC. All rights reserved.

**Release notes**

2.6.1 Jan-19-2018
- Compatibility with macOS 10.13
- Security fixes

2.6 Aug-28-2015
- NEW! All-new native YouTube plugin
- NEW! Clear caches feature to free up unused disk space
- Updated many backend components to latest versions
- Other various fixes and improvements

2.5 Jan-27-2015
- NEW! Added trakt watch history sync
- Updated to trakt v2 API
- Resolved issues with deprecated Last.fm API features
- Other various fixes and improvements

2.4 Jan-4-2014
- NEW! Added support for untethered Apple TV 5.3
- Improved reliability of installation process
- Improved diagnostic reporting
- Other various fixes and improvements

2.3 Jul-2-2013
- NEW! Added Apple TV 5.3 compatibility
- NEW! Added Croatian, Hungarian, Romanian, and Slovak localizations
- NEW! Media Player is now ‘Infuse for Apple TV’
- Improved Dolby (AC3) audio
- Improved metadata fetching
- Improved detection of subtitle encoding
- Improved reliability of settings backups
- Other minor fixes and performance improvements

2.2.1 May-31-2013
- NEW! Subtitle encoding type is now automatically detected
- NEW! Added option to display both ‘bordered’ and ‘shadowed’ subtitle effects simultaneously
- Updated movie search for recent TMDb API change 
- Minor performance improvements and bug fixes

2.2 Feb-13-2013
- NEW! Added support for Apple TV 5.2 and Bluetooth keyboards
- Minor improvements to backups
- Minor improvements to DVD playback
- A handful of other bug fixes and improvements

2.1 Jan-11-2013
- NEW! TV Show Playlists - easily pick up from the last unwatched episode
- NEW! Custom Favorites - create favorites from almost anything, including search terms
- Big speed improvements while browsing movies/shows
- Library and Search items can now be hidden from main menu
- Now showing ‘Writers’ instead of ‘Producers’ on pre-playback screen
- .ite folders are now hidden from view
- Hidden files are no longer included in slideshows
- Better metadata fetching
- Better trakt syncing and scrobbling
- Better handling of network settings and errors
- Many search related improvements
- Many subtitle related improvements (special characters, performance, etc...)
- Fixed rare Last.fm scrobbling issue
- Fixed rare problems when playing audio files
- Fixed a few memory related issues
- iOS 6 support
- Many other bug fixes and improvements

2.0.2 Nov-26-2012
- Bug fixes and performance improvements

2.0.1 Oct-3-2012
- Improved trakt.tv syncing and scrobbling
- Improved handling of nested favorites
- Resolved issues with DRM file playback
- Resolved SMB related conflicts with XBMC
- Resolved minor conflict with Plex
- Resolved rare issue with thumbnail loading
- Resolved minor issue observed when clearing metadata
- Resolved a number of rare crashes
- Resolved issue that caused some music files to appear in 'Other' section
- Enabled playlist option for top level music folder

2.0 Sep-11-2012
- Added all-new Library View
- Added integrated media search
- Added trakt.tv 2-way syncing
- Added Last.fm scrobbling
- Added genre/artist based playlists
- Added Recently Added display option
- Improved handling of WTV files
- Improved handling of DVD audio tracks
- Improved AFP connections
- Improved filename recognition
- Improved subtitle handling
- Resolved various navigation issues
- Resolved rare DVD playback issues
- Resolved rare subtitles positioning issue
- Many other minor improvements and fixes

1.7 Jul-12-2012
- Added trakt.tv integration (scrobbling and ratings)
- Added localized movie poster art
- Added localized movie ratings
- Added AirControl (beta) - an open control API for Apple TV
- Added support for embedded DVB subtitles
- Added advanced read-ahead buffering for SMB and NFS shares
- Added Simplified Chinese translation
- Added 'Update All' option
- Added support for secure web logins
- Improved metadata fetching speed
- Improved video rotation detection for MOV files
- Improved support for YUVJ420 & YUVJ422 formats (used by digital cameras)
- Improved top-level menu layouts
- Resolved crash when accessing ISO files on certain shares
- Resolved potential streaming issues when using an unstable network
- Resolved AFP related memory management issues
- Other minor improvements & fixes

1.6 Jun-1-2012
- Added integrated subtitle downloads from OpenSubtitles.org
- Added support for purchased iTunes content (matching iTunes login required)
- Added video deinterlacing option
- Added Wake-on-Lan (WOL)
- Added Portuguese (Portugal) translation
- Added support for displaying subtitles in lower 'black bar'
- Added support for .WTV files
- Added support for multiple simultaneous AFP connections
- Improved bulk fetching & added automatic artwork caching
- Improved automatic downscaling for large thumbnails
- Improved metadata reloading for images
- Improved buffering over AFP
- Resolved various audio synchronization issues
- Resolved possible overflow in 5.1 AC3 audio
- Resolved issues with zoom for 4:3 movies
- Resolved missing audio for .dvr-ms files (ASF containers)
- Resolved rare SRT file crash
- Resolved issues with slideshow animation
- Resolved file specific metadata fetching issues
- Resolved rare ISO file crashes
- Resolved issue with displaying identical thumbnails for images with the same name
- Resolved metadata loading issues for files containing non-latin characters
- Resolved rare 5ch audio file crash
- Resolved issues with incorrect metadata for files with '<TVShow Name>/S01E0.avi' pattern
- Resolved auto-start issues in Couch Surfer
- Reduced memory footprint for large software-decoded videos and slideshows
- Other minor UI improvements & bug fixes

1.5.1 May-25-2012
- Minor installer improvements
- Minor fixes for Apple TV 5.0.1

1.5 Apr-17-2012
- Revamped player with improved performance (Apple TV 4.4 and later)
- Added NFS streaming
- Added Catalan, Czech, Korean and Traditional Chinese translations
- Added support for localized TV show pattern: TV Show/Season #/S##E##.extension
- Added manual subtitle time correction (-10.0s to +10.0s)
- Added support for embedded .FLAC cover art
- Added support for .AC3 and .MOD files
- Improved .EYETV file handling
- Improved audio synchronization in slow and unstable networks
- Improved slideshow operation with small images
- Improved movie folders detection logic to ignore hidden files
- Improved metadata fetching to support movies split into multiple files (dvd#, cd#, disk#)
- Improved zoom mode operation for non-square pixels
- Improved DVD menu handling
- Improved .OGG file handling (now correctly treated as audio)
- Improved error handling for connection issues
- Improved buffering logic
- Improved installation routine
- Other minor UI improvements
- Resolved format detection that was causing rare playback issues
- Resolved issue with volume level resetting during rw/fw
- Resolved floating crashes usually observed when using SMB with Windows 7 shares
- Resolved conflicts with XBMC related to SMB
- Resolved issues with metadata fetching for 'Show.Name.###.extension' pattern
- Resolved crashes observed in folders with significant number of files
- Resolved playback error on DVD and ISO files observed when file path contains '?' character
- Resolved crashes when working with long file paths
- Resolved rare issue with incorrect pre-playback screen layout
- Other miscellaneous bug fixes

1.4.1 Mar-30-2012
- Added support for Apple TV 5.0 (iOS 5.1)
- Improved memory management
- Miscellaneous bug fixes

1.4 Mar-8-2012
- Added center channel audio boost (+6dB and +12dB) for 5.0 and 5.1 audio tracks
- Added Finnish, German, Japanese, Norwegian, Polish, Russian, and Swedish translations
- Added '4:3 Crop' and '4:3 Stretch' zoom options
- Added support for M3U and PLS playlists
- Added EyeTV folder detection
- Added TrueHD audio (downmixed)
- Added 24-bit and 32-bit audio (downmixed) 
- Added enhanced downmixing for 5.1 AC3 audio (Dolby Pro Logic II)
- Added support for embedded MP3 covers
- Added automatic EXIF-based image rotation
- Added MP4s embedded subtitles
- Added main menu clock
- Improved poster art quality in list and grid view
- Improved buffering logic for DVD files
- Improved cover art fetching from Last.fm
- Improved DVD menu highlighting
- Improved photo viewer & slideshow
- Improved slideshow to match native Flickr style
- Improved Danish, Dutch, French, Greek, Italian, Brazilian Portuguese, and Spanish translations
- Minor UI improvements
- Resolved downmixing issues for specific audio tracks
- Resolved playback issues for single ISO files in a folder
- Resolved AFP login timeout issues
- Resolved metadata issues for files that contain '/' in folder or file name
- Resolved operation of the photo slideshow on iOS 4.x
- Resolved issue with favorites removal when share password is changed
- Resolved incorrect navigation in grid view on iOS 4.*
- Resolved issue with DVD marked as watched after viewing menu
- Resolved rare issue with incorrect pre-playback screen layout
- Resolved rare crash in libdvdnav when playing DVD files
- Resolved rare DVD playback error
- Resolved rare 'Bad URL' error
- Other miscellaneous bug fixes

1.3 Feb-8-2012
- Added automated firmware signature backups
- Added Danish, Dutch, French, Greek, Italian, Brazilian Portuguese, and Spanish translations
- Added support for advanced (learned) remote commands
- Added support for multiple external subtitles (movie.en.srt, movie.de.srt, etc...)
- Added support for folder based organization/playback
- Added support for embedded DVD chapters
- Added chapters section heading to Playback Menu
- Added global zoom setting
- Improved playback performance for movies with invalid timestamps
- Improved appearance of VobSub subtitles
- Improved metadata fetching for localized file names
- Improved audio track filtering
- Improved playback bar to match native player
- Improved metadata and bulk folder fetching stability
- Improved Media > Settings menu layout
- Resolved issues with folder name changing on metadata fetching
- Resolved issues with buffering
- Resolved rare DVD related crash
- Resolved floating AFP issue that was causing connection issues
- Resolved floating buffer overflow in software decoder
- Minor changes to Grid View appearance
- Minor UI improvements
- Other miscellaneous bug fixes

1.2 Jan-17-2012
- Added video zoom options (available through Playback Menu)
- Added watched indicators to grid view
- Added 'Recently Visited' section to Browser top shelf
- Added support for MicroDVD .SUB files
- Added screensaver during pause
- Added file delete option
- Added activity indicator for metadata clearing
- Added 'tune' icon placeholder for audio files without metadata
- Added episode number to the fetched name the list view
- Added Reload Metadata' option in contextual menu for folders
- Added 'no items' message to the 'Unwatched' filter of the list view
- Added gray ticket image caching
- Added loading screen when opening Manage Extras menu
- Improved scrubber bar logic
- Improved audio feedback for watched and pre-playback screens
- Improved poster loading for large folders
- Improved support for DVDs without menus
- Improved subtitle support for right-to-left languages (e.g. Hebrew)
- Improved installer device detection
- Resolved minor memory management issues
- Resolved issues with subtitles settings while playing a playlist
- Resolved issues with yellow subtitles displayed for movies converted with Handbrake
- Resolved conflicts with default audio player
- Resolved issues with passwords that contain @ symbols
- Resolved issues with metadata loading for files that contain '/' in folder or file name
- Resolved buffer overflow in libafpclient observed when navigating folders with long names
- Resolved issues with installer Bonjour detection
- Resolved rare crashes during web browsing
- Changed metadata format to S.# / Ep.# for TV Shows
- Disabled metadata processing during movie playback
- Corrected audio feedback when pressing Menu while in grid view
- Minor UI improvements
- Other miscellaneous bug fixes

1.1.1 Dec-22-2011
- Added support for embedded 'Timed Text' subtitles
- Added support for external SSA subtitles
- Added support for .dvr-ms files
- Added background audio looping for DVD menus
- Improved metadata loading performance
- Improved .SRT subtitles parsing
- Improved compatibility with AirPlay
- Improved filter bar selection in list view mode
- Improved support for special characters
- Improved file name parsing
- Improved playlist behavior
- Resolved rare DVD playback and menu issues
- Resolved floating crash when accessing remote files
- Resolved floating crash when audio queue service is not available
- Resolved rare crash when opening pre-playback screen
- Resolved playback issues when attempting to use corrupt subtitles
- Resolved issues related to hiding menu items
- Resolved issues with installer version check
- Removed white line visible on some h.264 videos
- Files that are 90% viewed are now marked as watched
- Minor UI improvements
- Other miscellaneous bug fixes

1.1 Dec-6-2011
- Added support for .IMG files
- Added option to mark specific folders as grid or list view
- Added subtitle position setting
- Added support for larger thumbnail images
- Added support for UTF-8 paths in DVD files
- Added web page auto-loading feature
- Added screen position setting in Couch Surfer
- Added show/hide menus option
- Improved audio synchronization in DVD and AVI files
- Improved metadata fetching logic
- Improved filenames parsing logic
- Improved playlist logic that marks files as watched
- Improved buffering performance
- Improved ISO files handling (resolved network error warning)
- Improved error handling for DVD files
- Improved growl notifications display logic for audio files
- Improved warning messages for unplayable files
- Improved grid view stability
- Improved fanart loading
- Improved memory management
- Improved installation routine
- Improved installer device detection
- Resolved issues with long DNS names
- Resolved issue with extra period appearing at the end of some DNS names
- Resolved crash observed when audio subsystem could not be initialized
- Resolved issues with chapter handling logic
- Minor UI improvements
- Many other miscellaneous fixes

1.0 Nov-16-2011
- Added support for FLAC and MTS files
- Added support for files with 5.0, 4.0, 3.0 and 2.1 audio tracks
- Added support for embedded covert art (m4a, m4v, mp4)
- Added fanart backdrops for TV Shows
- Added new folder artwork in Grid View
- Added loop and shuffle playlist options
- Added TV Show series cover art in Grid View and Top Shelf
- Added top to bottom and right to left navigation in grid view
- Added global setting for enabling/disabling subtitles
- Added support for large photo collections
- Added support for folders containing dot ('.') in their name
- Added (watched) view options in List View (use Play/Pause button to switch mode)
- Added backup type options
- Added relaunch prompt after restoring from saved backup
- Improved folder cover art logic
- Improved setup of new shares
- Improved handling of invalid XML files
- Improved cursor handling in DVD menus
- Improved recently watched item handling
- Improved metadata caching logic
- Improved TV Show filename parsing
- Improved Grid View stability
- Improved metadata fetching speed
- Resolved issues with audio file metadata fetching
- Resolved floating crashes related to metadata fetching
- Resolved issues with metadata overriding when starting playback from top shelf
- Resolved issues with chapter selection screen layout observed on short files
- Resolved issues with metadata reloading in Grid View
- Resolved issues with TV Shows aired date
- Resolved issues with hangs on certain DVD menus
- Resolved minor memory management issues
- Resolved issues with scrolling in Top Shelf
- Resolved issues with folder names overlapping in Grid View
- Minor UI improvements

RC1 Oct-27-2011
- Added grid view and pre-playback view options
- Added bulk metadata fetching with growl-like status
- Added fetched names in list view
- Added hardware decoding for .m2ts files
- Added support for embedded subtitles (MKV, M4V, etc...)
- Added support for ISO (DVD) files
- Added TV Show metadata fetching
- Added metadata correction for Movies and TV Shows
- Added movie title in Top Shelf (instead of filename)
- Added DSI ping for better operation with AFP shares
- Added folder tagging
- Added metadata view indicator
- Added support for metadata overriding using xml files
- Added DVD menu buffering
- Added support for subtitles with invalid timestamps
- Added support for Apple TV 4.4 (iOS 5)
- Added subtitle 'Weight' setting
- Added option to show/hide local files
- Improved data buffering and playback performance
- Improved XSUB subtitle support
- Improved network error handling
- Improved filename parsing for metadata fetching
- Improved NAS drives support and increased connection timeout
- Improved video loading process
- Improved DVD menu handling
- Improved playback position detection
- Improved memory footprint
- Improved SMB share handling
- Resolved DVD subtitle issues
- Resolved Voiceover related issues
- Resolved audio synchronization issues
- Resolved problems when streaming from an AirPort Extreme
- Resolved AFP related issue when resuming after a long pause
- Resolved issues that caused the first subtitle section to be skipped
- Resolved performance and crash related issues for certain DVD files
- Resolved audio playback issues when the connection to Last.fm fails
- Resolved potential issues in shares handling and filename processing
- Resolved AFP related crashes
- Resolved .dvdmedia extensions and folder images not hiding
- Resolved floating crash during metadata fetching
- Resolved various cloud backup issues
- Many other miscellaneous fixes

Beta7 Sep-6-2011
- Added support for music files (mp3, aac (adts), wav, aiff, m4a)
- Added AC3 (5.1+ surround) sound
- Added playback menu (hold select during playback)
- Added support for .srt subtitles
- Added support for multiple audio tracks
- Added support for chapters
- Added cloud backup for 3rd party settings
- Added three metadata views (overview, synopsis, technical)
- Added MPAA rating to metadata
- Added support for localized metadata
- Added support for local cover art
- Added option to refetch metadata for a specific file
- Added option to clear all metadata
- Added toggle setting for volume control
- Added access to DVD menus during playback (press menu)
- Added low buffer detection warning (prevents stuttering)
- Improved metadata fetching (courtesy of themoviedb.org)
- Improved progress bar controls
- Improved AFP/SMB reliability
- Improved DVD file playback
- Improved playback of larger files
- Improved buffering and re-buffering (when required)
- Improved FF/RW controls for larger files
- Improved audio decoding performance
- Improved center channel (voices) audio mixing
- Improved file sorting logic
- Improved performance and memory management
- Improved error handling
- Resolved screensaver/slideshow related issues
- Resolved playback issues for files with 20+ streams
- Resolved issues with AFP volumes with long file names
- Resolved floating issues with subtitles
- Resolved issues related to 3rd party remote apps
- Resolved floating crash in SMB library
- Resolved aspect ratios issues for certain video types
- Resolved file browsing related crashes
- Resolved metadata fetching related crashes
- Resolved audio queue related errors
- Resolved Top Shelf related playback issues
- Resolved playback related memory leaks
- Resolved DVD subtitle issues
- Resolved stalls observed with some files during and after FF/RW
- Resolved synchronization issues observed after buffering some files
- Resolved audio synchronization issues
- Resolved rare floating crash observed at the end of some files
- Resolved resume related playback issues
- Resolved various screensaver related issues
- Local files are now hidden when one or more remote shares are setup
- Minor UI and other miscellaneous fixes

Beta6 July-1-2011
- Added new lightweight player
- Added recently played items to 'Top Shelf' in main menu
- Added Favorites to main menu
- Added option to manually mark files as watched/unwatched
- Added 'Test Connection' option for AFP/SMB shares
- Added support for DVD subtitles
- Added support for multiple DVD audio tracks
- Added basic support for M2TS files
- Added show/hide options for standard Apple TV menus
- Added option to manually install if no Apple TVs are detected
- Improved overall video playback (especially HD video files)
- Improved thumbnail generation when cover art is not available
- Improved FF/RW controls
- Improved DVD menu and video playback
- Improved DVD playback progress reporting
- Improved memory management
- Improved AFP/SMB streaming
- Improved error handling for invalid files
- Improved auto-update disabling
- Improved installation error handling
- Resolved most video stuttering issues
- Resolved energy saver mode issue
- Resolved issue that resulted in some DVDs being displayed in (squished) 4x3 mode
- Resolved numerous DVD playback issues
- Resolved flickering when navigating through certain menus
- Resolved additional conflicts with XBMC
- Reduced number of network connections used
- Minor UI and other miscellaneous fixes

Beta5 May-12-2011
- Added Apple TV 4.2.2 compatibility
- Added SMB streaming
- Added photo slideshows
- Added basic video playlists
- Added 'Favorites' section
- Added individual photo browsing and viewing
- Added support for 'xxx.xxx.xxx.xxx/folder' shares
- Added support for guest/anonymous NAS logins
- Added volumes list sorting
- Added option to disable metadata fetching
- Added option to hide file extensions
- Added HTML5 audio support (for sites like http://tv.tunein.com/)
- Added EyeTV streaming
- Added new SSL indicator
- Added lightweight Last.fm audio streaming player
- Added 5-day forecasts
- Added weather location search option
- Added automatic weather location detection
- Added day/night weather forecasts
- Added 'Feels Like' temperature info
- Improved installer routine
- Improved handling of failed installations
- Improved error handling
- Improved handling of HD video files
- Improved memory management
- Improved DVD file detection
- Improved remote share folder browsing (root folder issue)
- Improved Remote.app support
- Improved web pages scrolling and layout handling
- Improved iOS-optimized JavaScript support
- Improved highlighting of large web elements
- Resolved artifact issues (green line near bottom of screen)
- Resolved rare crashes related to AFP streaming
- Resolved issues in share navigation resulting in incorrect 'menu' button handling
- Resolved issues resulting in incorrect video playback after rewinding on 'fastest' speed
- Resolved issues related to removing saved shares
- Resolved duplicate AFP share entries
- Resolved conflicts with XBMC
- Minor UI adjustments
- Other miscellaneous fixes

Beta4 Mar-25-2011
- Added 'alpha preview' version of new Media Player
- Added native Weather and RSS apps (will appear under Internet menu when installed)
- Added support for Remote HD iPhone/iPad app
- Added option to restart 'Lowtide' via Maintenance menu
- Added support for Apple TV 4.2.1 (iOS 4.3)
- Added Google search suggestions to Couch Surfer Search menu (iOS 4.3+ only)
- Added ability to delete bookmarks
- Improved animations, HTML5 and CSS3 support
- Improve iPhone/iPad Remote app navigation
- Improved text box handling
- Resolved issues related to Facebook and similar sites
- Many other performance improvements and bug fixes

Beta3 Feb-12-2011
- Added one-click XBMC install option
- Added support for iOS 4.3
- Added support for touch and double-click events in web browser
- Added one-click diagnostic report submissions
- Added support for Last.fm Scrobbling 2.0
- Improved installer to better handle iOS updates
- Improved installer error handling
- Improved web page rendering
- Improved web history; filtered duplicates
- Improved handling of video elements
- Eliminated 'flickering' during page loads
- Resolved issues with auto-completion (search and URL entry)
- Many minor UI improvements

Beta2 Dec-10-2010
- Added Apple TV 4.1 (iOS 4.2.1) support
- Added Windows compatible installer (requires Windows XP or later)
- Added optimized web navigation when using the standard Apple remote
- Added web search and url suggestion engine
- Added browser user-agent toggle setting
- Added Last.fm streaming support for Australia, Canada, Germany, and New Zealand
- Added Last.fm 'Growl' style notifications
- Improved error handling during installation (no more mysterious password prompts)
- Improved version checking for app downloads
- Improved Last.fm scrobbling
- Many additional improvements and bug fixes

Beta1 Dec-1-2010
- Initial beta Release
