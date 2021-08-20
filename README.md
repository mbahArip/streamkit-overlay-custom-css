# Discord Custom StreamKit Overlay
My collection of CSS Style for Discord Streamkit Overlay.  
https://streamkit.discord.com/overlay

## How to use
1. Activate Developer mode in discord.
2. Add this link into browser source in obs.  
    https://streamkit.discord.com/overlay/voice/[Guild-Server-ID]/[Voice-channel-ID]  
    _*Right click server > copy ID for Guild Server ID_  
    _*Right click voice channel > copy ID for Voice Channel ID_
3. Open style.css in this repository.
4. Copy the whole content into custom css box in obs.
5. Enjoy

## Customize
### Change avatar size
Search for _**img.avatar**_, and change width and height to your liking.

### Make avatar round / square
Search for _**img.avatar**_, and change border-radius.  
50% for rounded avatar, 0 for square avatar.  
_*If there are no border-radius, you can add it manually._

### Change or Hide Za Bois text
To change, search for _**div#app-mount:before**_, and change content value.  
To hide, search for _**div#app-mount:before**_, and change display value to none.

## Gallery
### [__Style 1__](/Style1/style.css)
<p>
    <img src="/Style1/image_2021-08-20_180926.png">
</p>  
