# **YTShortsCommentMover**

### **About**
This is a small script to move the Youtube Shorts comment to the side, so the video isn't occupied

<br>

### **How to use**
1. Get a plugin for your browser wich can inject code
2. Put this code in there:

```
click = (event) => {update()};

function update(){
    document.querySelector("body > ytd-app > ytd-popup-container > tp-yt-paper-dialog").style.left = "20em";
}
```

3. Reload Youtube
4. Enjoy!

### **Other**
+ Code by: **[MushroomFX](https://mushroomfx.github.io)**
+ Example plugin for chromeium: **[User JavaScript and CSS](https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld)**
+ Example plugin for Firefox: **[Code Injector](https://addons.mozilla.org/en-US/firefox/addon/codeinjector/)**
