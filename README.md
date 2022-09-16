# Why?
When browsing YouTube, we often bias ourselves against which videos are good / bad based on the number of views the video has. While this is a reasonable indication, what if it didn't exist? 

This script removes all views from YouTube so that you focus entirely on the thumbnail / title.

# Prerequisites / Assumptions
1. Install [Tampermonkey](https://www.tampermonkey.net/). Tampermonkey allows for custom scripts to be executed on any webpage. In this case, we are executing a script on YouTube.
2. This script has only been tested on Google Chrome. If you use another browser, it may not work as expected.

# Installation
## Option 1
1. Download directly from GreasyFork, which will automatically open up the installation in Tampermonkey: https://greasyfork.org/en/scripts/451494-hide-youtube-video-views
2. Simply click the "Install this script" button
3. Save the script

## Option 2
1. Open the [hideYouTubeVideoViews.js](https://github.com/griffinbeels/hide-youtube-video-views/blob/main/hideYouTubeVideoViews.js) file
2. Copy the contents of the script
3. Click on the Tampermonkey extension and select "Create a new script..."
4. Paste the script
5. Save the script

# Usage
Load any page on YouTube, and the views should be gone! This has been tested on the following pages and is confirmed to work using Google Chrome as of 9/16/2022:
 * Channel Home
 * Channel Videos
 * YouTube Home
 * YouTube Search
 * Explore
 * Videos
 * Suggested Videos
 
 # Credits
 Thanks to https://twitter.com/Biasedobsrvr for inspiring the idea.
 
 Script written by https://twitter.com/griffinbeels with the power of Stack Overflow.
