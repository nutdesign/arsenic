# Notes on installing node, et al on Mac OS X 10.11.4
Last update: MJY - March 23, 2016


## Basic Mac system setup

* Install Node.js v5.9.0 Stable using dmg from https://nodejs.org/en/ (via https://coolestguidesontheplanet.com/installing-node-js-on-osx-10-10-yosemite/)
* npm install --save-dev gulp
* sudo npm install -g bower (fails without sudo)
* 


## Foundation ZURB Template docs seem to also require:

```bash
cd projectname
npm install
bower install
```

## Everyday Development Startup

### Run npm install:

* Failed at the phantomjs@1.9.19 install script 'node install.js'.
* Appears to have failed due to not getting through to the AWS servers. 
* Reissued "npm install" and it worked.

### Run bower install:

* Worked.


## "Finally, run `npm start` to run Gulp."

* "Error: The `libsass` binding was not found in /Users/mjy/Dev/arsenic/node_modules/node-sass/vendor/darwin-x64-47/binding.node This usually happens because your node version has changed. Run `npm rebuild node-sass` to build the binding for your current node version."
* Worked after running: npm rebuild node-sass

At this point the arsenic test page loaded in my browser.

Note that new directories have been created inside my 'arsenic' project:

* bower_components
* node_modules
* (Plus 'dist' which is expected.)

--- 

Also need:

* "sudo npm install --global foundation-cli" so that you can: "foundation new"






