# Disable HTML5 Autoplay
**An extension for Chromium-based browsers that disables autoplay of all HTML5 audio and video**

This extension disables autoplay on all websites. Unlike others that simply pause the media or strip the autoplay attribute in HTML, this extension will also prevent JavaScript from playing the media. Furthermore, dynamically added media will be parsed by this extension.

## Using this extension

This extension creates an icon next to the address bar (which is called a Browser Action.) The icon has two states:<br />
* When the icon has color, this means there are media elements on the page.
* When the icon is a light grey, this means that no media elements are on the page.

The number that appears on the icon indicates the number of autoplay attempts on the page.<br />
<br />
Right now, clicking on the Browser Action does nothing. This will be changed in a future version.

## Installation

### Install from Chrome Webstore

* [Webstore page](https://chrome.google.com/webstore/detail/disable-html5-autoplay/efdhoaajjjgckpbkoglidkeendpkolai)
* [Webstore CRX download link (for advanced users)](https://clients2.google.com/service/update2/crx?prodversion=44&response=redirect&x=id%3Defdhoaajjjgckpbkoglidkeendpkolai%26uc)

### Install from Opera Addons

* [Opera Addons page](https://addons.opera.com/en/extensions/details/disable-html5-autoplay/)
* [Opera Addons NEX download link (for advanced users)](https://addons.opera.com/extensions/download/disable-html5-autoplay/)

### Install from source

1. Download and unpack the source code:
  * [Tagged versions](https://github.com/Eloston/disable-html5-autoplay/releases)
  * master branch source code: [.tar.gz](https://github.com/Eloston/ungoogled-chromium/archive/master.tar.gz) or [.zip](https://github.com/Eloston/ungoogled-chromium/archive/master.zip)
2. In `chrome://extensions/`, enable Developer mode
3. Use "Load unpacked extension..." and select the folder containing the extension source code

