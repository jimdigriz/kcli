This script sends a URL to a local password-less [Kodi](http://kodi.tv/) installation, the cunning bit is that it does the autodiscovery so you should not need to rummage for IP addresses.

The usage is straight forward:

    kcli https://www.youtube.com/watch?v=whatever
    kcli http://uwstream2.somafm.com:8808

    kcli STOP

# Preflight

Debian users will need to type:

    sudo apt-get install curl dnsutils

Mac OS X users should be able to just use this script.

## Kodi

You will also need to make sure that your Kodi center is configured for [remote access](http://yatse.leetzone.org/redmine/projects/androidwidget/wiki/XbmcConfig).

# Issues

 * is there a easier/safer way to do the mdns discovery
 * for something called kcli, we probably should do more than just blat the playlist
