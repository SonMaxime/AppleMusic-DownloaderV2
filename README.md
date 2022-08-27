## AppleMusic-DownloaderV2
Download AAC from Apple Music !

## Why a V2 of the downloader ?

Since Apple modified the web API of Apple Music, it became impossible to get album informations directly from the album link, you have to download each song indivudualy and use single links like : "https://music.apple.com/fr/album/oh-no/1021582747?i=1021582769".
If you download a song from an album, the name of the folder in "output" will be that the one of the album on which you downloaded the song.
I made some code modifications to make an album folder in the output even if you download 1 song, which wasn't possible before.
I've set mp4decrypt to the default Widevide decryptor, the m4a container is compatible with mp41 and mp42, not like shaka-packager (only mp41).
Music video and playlist download are not available too for the moment, maybe I will never treat this problem, maybe I will, idk.
I've also removed ffmpeg who ruins the authenticity of the AAC, the decrypted temp is now tagged with the song infomations and moved to the album output folder.

## How can I get the cookies.txt

Use the extention "get cookies.txt"
- Chrome: https://chrome.google.com/webstore/detail/get-cookiestxt/bgaddhkoddajcdgocldbbfleckgcbcid
- Firefox: https://addons.mozilla.org/fr/firefox/addon/cookies-txt/

## How to use

It's now impossible for you to download an album from its link, you must download the album song by song.
* python applemusic.py https://music.apple.com/fr/album/oh-no/1021582747?i=1021582769

![AM-DL](https://user-images.githubusercontent.com/47661880/187050326-51ee0d1b-78ec-493b-b5e1-01f8b2ce9970.png)
![FOLDER PROOF](https://user-images.githubusercontent.com/47661880/187050300-8168693e-f843-4c82-897c-62e1fcb0f042.png)
