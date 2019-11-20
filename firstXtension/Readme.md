Sample Web Extension for Mozilla Firefox:

Prerequisite:

web-ext tool - helps in auto reloading and faster execution of addon

How it works:
Sample is copied from https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension

It just draws the border around web page whenever specified website is mentioned in manifest.json file (in these case mozilla.com).

1. go to /firstXtension/ directory
2. run command "web-ext run"
These will open a new instance of mozilla firefox. Type in mozilla in search barand enter in the mozilla website, there will be red color border of specified size as mentioned in "firstXtension/borderify.js"

