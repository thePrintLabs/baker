Project Baker
=============

**The HTML5 ebook framework to publish interactive books & magazines on iPad & iPhone using simply open web standards**
<http://bakerframework.com>
<https://github.com/bakerframework/baker/>

WHAT IS THEPRINTLABS BAKER
-------------
thePrintLabs Baker branch is aimed at updating and adding features the Baker Framework for iOS. See the Project Baker page for full details.

CHANGELOG
---------
<<<<<<< HEAD

* **4.3** (in development)
  * Added support for iOS 8, iOS 8.1, iPhone 6 and iPhone 6 Plus
  * The Baker app is now a universal app
  * Support for iOS 6 is dropped, Baker now requires iOS 7 or newer
  * The shelf header is now a separate view that can be customized
  * The embedded book "A Study Of Scarlet" is now responsive

* **4.2.1** (26/01/2014)
  * Branding changes.  New Baker Framework logo assets
  * Open local files in modal view.  Action button not shown.  Useful if you have local documents (html, pdf, etc...) related to the content of your Baker HPub
  * Bugfixes related to iOS 7 app validation (Asset Catalog Errors)

* **4.2** (28/10/2013)
  * iOS 7 support
  * Text Kit support
  * Support for analytics/tracking frameworks
  * Info box in shelf
  * `init` JS event for Info box with `user_id` and `app_id`
  * Asset Catalog support
  * Added `environment` parameter to Baker API calls
  * Made most remote calls asynchronous
  * Support for removing issues from `shelf.json`
  * Replaced AQGridView with UICollectionView
  * Minor improvements and bugfixes

* **4.1** (06/05/2013)
  * In-App Purchases for your magazine issues (server required)
  * Paid Subscriptions support (server required)
  * Push notifications capabilit (server required)
  * Baker API defined to allow third-party servers
  * Vertical pagination flexibility with `<meta name="paged" content="YES">`
  * Issue data can now be refreshed
  * book: protocol now works within the issues on the shelf
  * Index handling improvements
  * Removed JSONKit, using iOS5+ parser
  * Memory enhancements
  * Cleaned up the debug console log and error messages
  * Bugs and fixes

* **4.0** (22/12/2012)
  * Full Newsstand support
  * Shelf to manage multiple publications
  * Free subscriptions support
  * Orientation handling improvement

* **3.2.3** (25/10/2012)
  * Added more complete user-agent to work with JS that do user-agent detection for features
  * Fix: HTML5 Video playback now uses the Audio session
  * Fix: long touch doesn't trigger the index bar anymore

* **3.2.2** (10/10/2012)
  * iOS 6 and iPhone 5 display support
  * Improved modal web view offline handling
  * Fixed orientation bug and javascript property
  * Fixed modal web view crash when interrupted and other minor fixes
  * For developers: now Baker view is a separate class
  * User agent and status bar tweaks (thanks to @jcampbell05)

* **3.2.1** (20/08/2012)
  * Internal release

* **3.2** (20/03/2012)
  * iOS 5.1 and Retina display support
  * External links now open in internal browser, see referrer=Baker (thanks to @steiny2k)
  * Custom events fired on window blur and focus
  * Book.json parameters to disable tap and swipe: -baker-page-turn-tap/swipe
  * Index bar dynamically sized from index.html size. Use viewport meta property to configure
  * Change: referrer=Baker variable now not passed to destination website
  * Fix: "white flash" workaround found
  * Fix: solved issue with pre-compiled screenshots and books with more than 50 pages
  * Fix: rare bug of content loaded into index view instead of page

* **3.1** (20/12/2011)
  * Newsstand basic support
  * iOS5/iCloud data storage guidelines support
  * Pre-build screenshots in screenshot mode using -baker-page-screenshots in book.json
  * Retina display support in screenshot mode (thanks to @zenz)
  * Manga support: start from the last page, or any arbitrary page using -baker-start-at-page in book.json
  * Email protocol support
  * Change JSON library to JSONKit (thanks to @zenz)
  * Fix: block idle when downloading
  * Fix: spinner color and iOS4.x support
  * Change: -baker-background-image-* properties are now relative to ./book/ folder, see Issue #247

* **3.0.2** (29/10/2011)
  * Fix: iOS 4 support for the spinner feature available only in iOS 5

* **3.0** (18/10/2011)
  * Two rendering modes to improve performances: screenshots (thanks to @pugpig) and three-cards
  * index.html view on double-tap to manage navigation and menu
  * Full Hpub 1.0 support
  * Improved rendering speed and responsiveness
  * Improved handling of internal and external links
  * Memory optimization
  * iOS 5 and Xcode 4.2 compatibility
  * Minimum supported version: iOS 4.0
  * Minor fixes and improvements
  * Thanks to @francesctovar @therabidbanana @eaglejohn @ffranke for the great support

* **2.0** (28/04/2011)
  * Multi-orientation books support: portrait, landscape, both (thanks to @svdgraaf)
  * iPhone support
  * Xcode 4 compatibility
  * Added support to open a specific page of a downloaded book
  * Added support to remove vertical bounce (for non-scrolling books)
  * Added support to enable automatic media playback
  * Changed the gesture to open the status bar to the more reliable doubletap
  * Fix: page anchors now handled in internal links
  * Fix: orientationchange event now fires
  * Minimum supported version: iOS 3.2
  * Minor fixes

* **1.1** (19/01/2011)
  * Added book:// protocol to allow downloadable HPub books
  * Support for zipped HPub books (to allow downloading)
  * Link support (internal/external)
  * Multitap page navigation
  * Alphabetical ordering (WARNING: breaks previous books, check before upgrading)
  * Statusbar on tap
  * Full screen swipes
  * Fix: now the previous page doesn't flash anymore when you change page
  * Minor fixes

* **1.0** (03/11/2010)
  * First release

=======
* (26/09/2014)
* Added support for iOS8
* Project converted to use ARC
* Updated project settings for Xcode 6
>>>>>>> Added iOS8 support and ARC enabled

LICENSE
-------

_Copyright (C) 2010-2013, Davide Casali, Marco Colombo, Alessandro Morandi_
_Licensed under **BSD Opensource License** (free for personal and commercial use)_

> _Elementary, my dear Watson._
