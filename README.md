A Chrome Extension base project with AngularJS
================

This is a scaffolding project to help you get started.
This includes :

- AngularJS Popup App `scripts/app/`
- Bootstrap JS and CSS
- jQuery / Underscore.js
- Mochai/Chai/SinonJS for testing contentscripts
- Grunt and Bower

See some slides about creating chrome extensions [here](http://www.slideshare.net/flrent/build-your-own-chrome-extension-with-angularjs)

![http://www.slideshare.net/flrent/build-your-own-chrome-extension-with-angularjs](http://i.imgur.com/pFPXooZ.png)

## Get Started
- Clone this repo
- Run `npm install` and `bower install`
- Go to `chrome://extensions/`
- Activate developer mode
- Click on  `load an unpacked extension` and locate your cloned repo, and select the `app` folder


## Build and deploy
The build `manifest.json` file is `manifest-build.json`. It differs from the regular `manifest.json` to use only built files (single files for the all popup app, content scripts or background pages).

To build the app and get a single scripts for each popup app, content script, or background page, simpy run :

`grunt build`

## Versions
- `0.1` May 2014 First version released


## License
[Florent Lamoureux @flrent](http://twitter.com/flrent)
<br>
Licensed under the MIT license.
<br>
Copyright (c) 2014 - [BugBuster SA](http://bugbuster.com)
