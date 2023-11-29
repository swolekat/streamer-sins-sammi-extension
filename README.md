#Streamer Sins Sammi Extension

This extension is based off of Shindig's original redeem ( https://twitter.com/shindags/status/1729405299143184851 )

##Set Up

### OBS
In OBS you need to make a browser source. The URL should be https://swolekat.github.io/streamer-sins-sammi-extension  Make the size 1920x1080

![Browser source](./readme-images/browser%20source.png)

Make sure that this browser source is at the top of the scene. 

### Sammi

You'll need to install streamer-sins.sef (go to the releases page if you're on github). Then you need to modify the button in the streamer-sins deck. 

You should modify the trigger to be whatever your channel point is. Make sure that in twitch you require text.

Modify the commands to point to your source that you just made:

![Browser source](./readme-images/browser%20source.png)


## Customization

If you want to change the fonts and stuff, you'll need to modify the custom CSS in the browser source. Pretty much the only two elements can be accessed by the `.top-bar` and `.bottom-bar` classes.