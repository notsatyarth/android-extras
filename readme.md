Based on [dhelleberg's androidscripts repo][1].
Its not a fork because of the lack of a brew dependecy

Just add the following block to your bash/zsh config (I use zsh).

```
devtools(){
    groovy /path/to/repo $*
}
```

Featureset:
- the [devtools][2] of the original script.
- Toggle charging mode for my Device(One Plus One)**Requires Root**
    -  Tweak the settings based on your particular device or phone.
    -  xda should be able to give you the location of the `charging_enabled` file on your device.


[1]:https://github.com/dhelleberg/android-scripts/
[2]:https://github.com/dhelleberg/android-scripts/#devtools