# Keg External Example
* An example app for use with the [Keg-CLI](https://github.com/simpleviewinc/keg-cli)
* This app gets injected into the Keg-CLI as a TAP through the `tap link` command
* All tap tasks can then be used on this app

### Setup
* Make sure to have the [Keg-CLI](https://github.com/simpleviewinc/keg-cli) installed
* Clone this repo locally
* Navigate to this directory
* Run the command `keg tap link kee` in your terminal
  * This will create a new linked tap for this repo

### Run
* Run the command `keg kee start` in your terminal
  * Should start this app
* Navigate to [kee.kegdev.xyz](http://kee.kegdev.xyz) in your browser
  * Should the `index.html` page
