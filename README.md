## AppleMusic-DownloaderV2
Download videos and audios from AppleMusic!

## Why a V2 of the downloader ?

Since Apple modified the web API of Apple Music, it became impossible to get album informations directly from the album link, you can now only use single links like : "https://music.apple.com/fr/album/oh-no/1021582747?i=1021582769".
Therefore, I had to modify a few variables in order to keep it working like when you download an album and keep the tags on the songs.
If you download a song from an album, the name of the folder in "output" will be that the one of the album on which you downloaded the song.

## How can I get the cookies.txt

Use the extention "get cookies.txt"
- Chrome: https://chrome.google.com/webstore/detail/get-cookiestxt/bgaddhkoddajcdgocldbbfleckgcbcid
- Firefox: https://addons.mozilla.org/fr/firefox/addon/cookies-txt/

## How to use

It's now impossible for you to download an album from its link, you must download the album song by song.
* python applemusic.py https://music.apple.com/fr/album/oh-no/1021582747?i=1021582769

![AM-DL](https://user-images.githubusercontent.com/47661880/187037456-e188a4d1-a1c1-4fcf-aa7b-b241bda6f8e3.png)
![FOLDER PROOF](https://user-images.githubusercontent.com/47661880/187037508-5f3cafa2-f3af-4687-a0b9-24a5c47e7120.png)
