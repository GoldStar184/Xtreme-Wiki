# Welcome to the Flipper-Xtreme wiki!

This is the heart of the Wiki page, here you will find a short explanation for what the individual pages are about, an FAQ section and a few words from the Devs.

If you have any questions, please join our [Discord](https://discord.gg/flipper-xtreme) and we will be more than happy to answer each and every one of your questions!
<br><br>
# Sub-pages:

| Number | Usage |
---------|-----------
| 0.X | Basic overview of the Flipper & XFW |
| 1.X | Simple explanation of the different formats used for Flipper files. Helpful when making your own or debugging broken ones |
| 2.X | More in-depth nerd talk about the various systems. |

This should help you navigate this wiki, if not just let us know and we will help you out!
<br><br><br>
# FAQ:
**1)** How do I change the manifest / disable levels?
> Open qFlipper, go to `SD/Dolphin` and rename your `no_lvlup_manifest.txt` to `manifest.txt`

**2)** How do I enable **SFW** mode?
> From the Home screen (the one with the animations) hit the `Arrow UP` button, its gonna be right there for you to select it

**3)** I get an error saying "furi_version mismatch" when loading an app, how do I fix that?
> Open qFlipper, go to `SD` and delete the `Apps` folder. Then launch the latest update again. This folder houses all the .fap files, which do not update to the correct API versions by default if old ones are present (Thanks flipper devs). If the issue persists, its our fault and please open a ticket!

**4)** After a while, my Slut stops to level up, why is that?
> We added max. daily limits to make sure you arent just cheating your way to level 30

**5)** I really like the firmware, can I help?
> You can donate on the links you find on the github releases, preferrably the Patreon. You can spend time in our server to help others with issues, you can contribute to the project by making PRs on github and most importantly, you can simply spread the word!

**6)** I dont like the animations, and dont want to switch to another FW, how do I change them?
> <https://www.youtube.com/watch?v=9uOn6M9m0Dg>

**7)** After an Update / Randomly one day, qFlipper says something like *permission denied*.. Whats going on?
> Windows is going on... Essentially, either two devices use your COM port qFlipper expects, or Windows assigned your Flipper a completely different COM port. This is partially documented here: <https://forum.flipperzero.one/t/qflipper-not-recognizing-device-2-devices-on-one-com-port-while-bluetooth-on-windows-is-turned-on/1910>, let us know if you require help with this


<br><br><br>
# Our words:

- A huge thank you, obviously. This FW turned from a joke to a massive project with over 1k Users in **a week**. You guys are just mad, lol. We got many things planned and are working on them every day. Mainly a full rewrite of the animation handler to allow easy swapping of animations. Let me give you a TL;DR of how it works:
> so basically inside your dolphin folder you got like "xfw_nsfw", "stock", "custom1", "ligma-animation".. and in the firmware you can just select which folder to use for animations **& passport**

- Working on this is a lot of fun! This will keep being in development for a very long time, and unlike other "developers", we actually focus on adding new functionality and providing a stable experience for our userbase. We don't ever put our Firmware behind a PayWall, and we not only tolerate criticism, we ask for it. Be honest if you dislike something. We don't know if you don't tell us. Thats the only way we can work on making it better.