# Slyglif's Home Assistant add-on repository (Modified by ahajalie)
This repo will contain various add-ons I have needed.

## Add-ons
This repo contains the Home Assistant Add-Ons.  To use these, in Home Assistant, go to Settings, Add-ons, Add-On Store, click the 3 dots in the upper right corner, Repositories, and add this repository.  You can then install the add-ons.

### [Powerwall 3 to MQTT](https://github.com/ahajalie/powerwall3mqtt)
A simple Home Assistant Add On that acts as a bridge between the Powerwall 3 TEDAPI and MQTT. This forked version allows for a polling interval as little as 1, and reduces the cache to 1 second, allowing realtime monitoring updates within 1-2 seconds.

### [Static Route Manager](./staticroutes)
An add-on that will add or remove static routes to HAOS.  Useful for connecting to the Powerwall 3 TEDAPI when the PW3 is on the same network as HAOS.
