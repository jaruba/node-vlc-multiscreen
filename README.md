# WebChimera.js Player Multiscreen Demo

**This is a special feature created due to popular demand, it is usually used for surveillance cam software.**

#### Description

Demo for [wcjs-player](https://github.com/jaruba/wcjs-player)'s Multiscreen Feature showing WebChimera.js Player playing 4 videos at the same time.

``wcjs-player`` uses [WebChimera.js](https://github.com/RSATom/WebChimera.js) to draw the frames of libVLC to a canvas.


#### Demo Install

```
git clone https://github.com/jaruba/node-vlc-multiscreen.git
cd node-vlc-multiscreen
```

**Windows**
```
set WCJS_RUNTIME=electron
set WCJS_RUNTIME_VERSION=v0.37.6
set WCJS_VERSION=0.2.5
set WCJS_ARCH=ia32
```

**OSX/Linux**
```
export WCJS_RUNTIME="electron"
export WCJS_RUNTIME_VERSION="v0.37.6"
export WCJS_VERSION="0.2.5"
export WCJS_ARCH="ia32"
```

```
npm install
```

Now download Electron v0.37.6 for 32bit and run `app.js`

!! You can change the configuration values for `wcjs-prebuilt` according to your case, but keep in mind that the options are limited to the [prebuilt packages](https://github.com/RSATom/WebChimera.js/releases)

**Screenshots:**

WebChimera.js Player Multiscreen Demo running on NW.js (Windows)

<img src="http://webchimera.org/samples/wcjs-player-5.png">
