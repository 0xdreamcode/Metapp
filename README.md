# voiceapp
Universal text to speech.

# How to download for iOS/Android
* Download launcher.html
* Set the homepage of Google Chrome or w/e to file://where/you/put/the/launcher.html
* Put voiceapp.html in the apps directory that is located where launcher.html is.

The launcher should then detect present apps in the directory using JSON magic and give you a nice home screen, then you can hit Voiceapp and there you have it.


## Basically 
Anything with a V8 engine and HTML renderer can run this and it is to be deployed thusly as a local file containing all the dependencies within itself, packed into a web version, with OS integration as a possible extention. The HTML file containing the layout, styling, encoded assets and executable section is the app itself.

All code must be released available within the app's file object (packed/obfuscated or html within executable) and if you find a use for this please let me know because I am so done writing user applications.

Like voiceapp.html could be anything, it could be a Discord client, it could be a game, it could even be a whole new virtual operating system in and of itsefs. Now if I find a way to run NodeJS on the Android, have ot run a sockt.io...
