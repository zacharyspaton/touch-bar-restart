# touch-bar-restart
A simple automator script converted to a .app that restarts the touch bar control strip (along with the escape key for 2018 and older touchbar models)

Click [here](https://github.com/zacharyspaton/touch-bar-restart/raw/master/Restart%20Control%20Strip.app.zip) to download it

It's literally just a shell command made quick and easy to run with a .app you can chuck in your dock
```
pkill "Touch Bar agent";
killall "ControlStrip";
```

Thanks Marcus for the icon
