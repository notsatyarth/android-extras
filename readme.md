This project started out of just the lack of desire to repeat monotonous
tasks which dont really take more than a second.Its a simple wrapper
around adb with few long commands give much shorter forms. There is a groovy
dependency right now which i hope to remove some day[^1].Its really not anything
too new.All you have to do is setup your groovy path and add the following to
you config files:


(% highlight bash %}
devtools(){
    groovy /path/to/repo $*
}
{% endhighlight %}


##Toggle Charging:
**Requires Root**

Toggle charging mode for my Device(One Plus One)
       - Tweak the settings based on your particular device or phone.
       - xda should be able to give you the location of the charging_enabled file on your device.
