# Retro Pie Scratch
Experimental Phosophorous Scratch Installer Script for RetroPie.
## Not Working on RetroPie
After attempting a Scratch 1.4 port and a Scratch 2.0 port on Chromium without much luck, I have decided to try Phosphorous. Still isn't working. The issue seems to be with matchbox and X. It works on the desktop though lol.

Installation
------------
1) Install RetroPie. https://github.com/retropie/retropie-setup/wiki/manual-installation

2) Install the Simple theme on your RetroPie. (That's the only theme that works so far) (If you don't do this, it is not going to be pretty)
 https://github.com/retropie/retropie-setup/wiki/themes
 
3) Switch your x11 settings to anybody
```
dpkg-reconfigure x11-common
```
4) Then run installation shell script using one of the following command lines in the terminal:

```sh
curl -L https://goo.gl/j7Uj3f | bash
```

or

```sh
wget --no-check-certificate https://goo.gl/j7Uj3f -O - | bash
```
5) Pray it works

Note: I have no affliation with the makers of RetroPie, Phosophorous, QJoy, or Scratch. 
