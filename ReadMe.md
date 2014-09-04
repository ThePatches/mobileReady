Mobile Ready Examples with SCSS
===============================


##Setup
+ Install [Compass][1]
+ (Optional) Compile the SCSS files
+ Point MAMP to the project folder

##Testing
Use the iOS simulator for the most reliable tests in OSX. Chrome's device emulation also works.

###Some Notes
This is really rough, since it just needed to prove how things worked. SCSS works best by defining stylesheets for each format using the `<link rel="[href]" media="[selector]" />` with the `media` property. You can dynamically define styles using CCS3's built in _@media_ selector, but given than SCSS saves you from re-use by allowing importing and mixins, I think that SCSS is more reasonable.

[1]: https://www.youtube.com/watch?v=tciT9bmCMq8
