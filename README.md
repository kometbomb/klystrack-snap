# klystrack-snap
Creates a snap for [klystrack](https://github.com/kometbomb/klystrack). Includes desktop-qt5 so the snap will be huge (but, hey, it works!).

The build process will download both klystrack and [klystron](https://github.com/kometbomb/klystron), build klystrack and snap the whole thing. It will use the code for the latest "stable" klystrack.

You can easily install klystrack on Ubuntu etc. (as long as you have snapd) as follows.

```
git https://github.com/kometbomb/klystrack-snap
cd klystrack-snap
snapcraft
snap install klystrack*.snap --dangerous --devmode
```
