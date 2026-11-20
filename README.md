# WatchMyMedia for Unraid

Unraid Docker templates for [WatchMyMedia](https://watchmy.media), a
self-hosted media server for your movies and TV shows, with live TV and
recording from an HDHomeRun tuner.

- `templates/watchmymedia.xml`: the template Community Applications lists.
- `ca_profile.xml`: this repository's profile in Community Applications.
- `images/`: the icon.

Install it from Unraid's Apps tab (Community Applications): search for
WatchMyMedia and click Install. Its listing is on the web at
<https://ca.unraid.net/apps/watchmymedia-1q0vytr13s083f>.

The guide for installing on Unraid, giving the container your GPU and
keeping it updated is at <https://watchmy.media/guide/unraid>.

Where Apps can't be used, install it by hand: in the Unraid terminal,

    wget -O /boot/config/plugins/dockerMan/templates-user/my-WatchMyMedia.xml \
      https://raw.githubusercontent.com/WatchMyMedia/unraid-templates/main/templates/watchmymedia.xml

then open Docker › Add Container and pick WatchMyMedia from the template
list.

Problems with the template go in this repository's Issues. The templates
are MIT licensed; WatchMyMedia itself has its own licence.
