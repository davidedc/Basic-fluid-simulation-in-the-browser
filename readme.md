# What

A very simple fluid simulation running in your browser.

[Demo here.](http://davidedc.github.io/Basic-fluid-simulation-in-the-browser/)

![demo animation](https://raw.githubusercontent.com/davidedc/Basic-fluid-simulation-in-the-browser/master/readme-images/demo.gif)

For more info on the how the Smoothed-particle hydrodynamics (SPH) method is implemented, see [this readme in my other related github project](https://github.com/davidedc/Ascii-fluid-simulation-deobfuscated/blob/master/readme.md).

# Hack it!

...just hack the javascript files.
If you want to work on the coffeescripts, install node and node-coffee, then use this terminal command to automatically generate the .js files (and the .map files to help with the debugging):

```coffee --watch  -c --bare --map *.coffee```

# Also see...

I also made [a few C versions.](https://github.com/davidedc/Ascii-fluid-simulation-deobfuscated)
