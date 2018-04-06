# Offline QR code generator

This is a (Firefox) Web Extension, which makes it possible to generate a QR code from any website.

In contrast to many other add-ons, which use Google Web APIs for that, this add-on woreks completly offline.
Effectively, the add-on [prevents any web connection]() for itself, so it does never contact the web. Thanks to the linked `manifest.json` you can also easily verify, that the claim to work offline is true.

## Design goals
* Put privacy first! Privacy should be the default, so it is generating QR codes offline.
* Follow [Firefox Photon Design](https://design.firefox.com/photon/welcome.html)
* Use an up-to-date, great, customizable [QR code library](https://larsjung.de/kjua/).
* Let the user choose the size of the QR code and customize things.
