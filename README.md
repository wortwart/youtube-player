# youtube-player
A customized YouTube player for your own website

This project accompanies a tutorial about the YouTube API(s) in [c't Magazin 18/2015](http://www.heise.de/ct/ausgabe/2015-18-YouTube-Player-fuer-die-eigene-Website-bauen-2767539.html) (in German). You can see the player in action [on my website](http://woerter.de/projects/youtube-player) if you're able to cope with my slightly weird music taste.

- **basic-embed.html**: Embed options for single videos
- **tutorial-code.html**: Displays videos from a playlist and lets the user watch them. Corresponds to the code in the magazine tutorial.
- **player.html**: Extends the former with several features like play all and list sorting.
- **key.default.js**: Enter API key and list id and rename it to *key.js*

## Issues
- Video doesn't show (only sound) when you click a sort link and there is no player window yet
- Missing features: change list in UI, sort by random, paging, next/previous title
- The embedded font is too big (>400k).