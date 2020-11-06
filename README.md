# SkySocial
Meet your new decentralized hangout spot.
![Logo](./dist/SkySocialLogo.png)
## SkyDB Hackaton

##### Set up SkyID

    git clone https://github.com/DaWe35/SkyID.git
    cd SkyID
    npm i
    npx webpack

##### Then set up SkySocial

    git clone https://github.com/10000multiplier/SkySocial.git
    cd SkySocial
    npm i
    npx webpack

##### Open SkySocial in browser

You can just open the /dist/index.html in your browser.

If you're using the file:// protocol (or idtest.local as localhost domain), SkyID will recognise you're in development mode and siasky.net will be used as default Skynet portal.

##### Run SkySocial

First change the source of `skyid.js` if you want to test with self-hosted SkyID.

![image](https://raw.githubusercontent.com/DaWe35/SkyID/main/assets/skyid-example.png)

You need to setup two local virtual-host domains.

If you have [Wamp.NET](https://wamp.net/) installed (recommended), this will be easy.

You just need to create two sites pointing to your local SkyID projects: `idtest.local` for SkyID and `skynote.local` for SkySocial.

![image2](https://raw.githubusercontent.com/DaWe35/SkyID/main/assets/skyid_wamp.jpg)

______

Contributors:

@DaWe35 (creator of SkyID)

@Delivator

❤ Thank you! ❤

Brainstorm participants & helpers:
Taek, wkibbler, redsolver, Nemo, pjbrone, kreelud, Mortal-Killer, RLZL
