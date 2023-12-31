<h1 align="center">Full feature list</h1>

This will be a full list of all our custom stuff, since its gotten quite a lot over time. If you have any questions, feel free to ask on our [Discord](https://discord.gg/flipper-xtreme)

------

<h1 align="center">Xtreme Application</h1>

The Xtreme App is the heart, the centerpiece of all our additions. Every single one of them shows up in there. Countless hours of work have been spent on this application, to make sure everything works just about perfect. The application is structured as follows:

- `Interface`: Lets you configure the UI of the Flipper. Graphics, Main Menu, Lock screen, Statusbar, Common
- `Protocols`: Settings for BadKB (BadKeyboard) like Bluetooth remember mode, SubGHz frequency editor and restriction settings
- `Misc`: Changing level name, XP Level and Butthurt timer

-----

<details>
  <summary><code>Interface</code></summary>

The main Interface section allows you to change a whole array of graphical things. 

- <h4>Graphics:</h4>

  - Asset Pack:
    - Asset Packs allow you to change the background animations, lockscreen wallpaper, scanning assets and more. They are fairly simple to create and install, but for now, we will not explain it in too much detail. If you care about all of it, click [here](https://github.com/ClaraCrazy/Flipper-Xtreme/wiki/Asset-Packs).
<br><br>
  - Anim Speed:
    - Animation speed lets you change the speed at which your background animations play. You can slow them down or speed them up as you wish.
<br><br>
  - Cycle Anims:
    - Cycle Animations as you wish. You set the timer for how often, if at all, your background will change. Pick between a bunch of time options, turn it off alltogether or just let it be on the default "Meta.txt" setting, which uses the cycle speed defined by whoever made your used Asset Pack.
<br><br>
  - Unlock Anims:
    - Asset pack creators have the option to lock certain Animations behind a level, meaning you have to be Level X to see it. This option lets you bypass these restrictions.
<br><br>
  - Credits Anim:
    - Lets you decide whether the credit (thank you) animation will be randomly chosen.

<br>

------

<br>

- <h4>Main Menu:</h4>

  - Menu Style:
    - Lets you choose from a variety of different menu styles
<br><br>
  - App:
    - This is a display. It will show all the custom Apps you have so far added to the menu. Yes, you heard that right! You can add custom apps to the menu now. Should have been a feature this whole time, not ssure why it isnt.
<br><br>
  - Add / Remove:
    - This allows you to actually add / remove Applications to the menu. Note: The order in which they appear on the menu is defined by the order in which you add them. Simply hit "Add", select your app and you are ready to go! Same for remove: Select the App on the "App" slider above, and hit remove. Boom, simple as that!

<br>

------

<br>

- <h4>Lock Screen:</h4>

  - Lock on boot:
    - Decide if you want your flipper to lock on every boot, so you have to use your passcode to unlock it first.
<br><br>
  - Format on 10 Bad Pins:
    - Paranoid? Then enable this. It will fully wipe your flipper after 10 bad pin entries
<br><br>
  - Allow RPC While Locked:
    - Toggle the RPC in locked state (Android control)
<br><br>
  - Allow Poweroff:
    - 
<br><br>
  - Show Time:
    - Toggle the clock visibility on the lockscreen.
<br><br>
  - Show Date:
    - Toggle the date text on the lockscreen.
<br><br>
  - Show Statusbar:
    - Toggle statusbar visibility on the lockscreen.
<br><br>
  - Unlock Prompt:
    - Whether a prompt saying what button to press in order to unlock will be shown.
<br><br>
  - Transparent lockscreen:
    - This allows you to see the current animation of your flipper, instead of the lockscreen animation.
<br>

------

<br>

- <h4>Statusbar:</h4>

  - Battery Icon:
    - The Battery Icon allows you to pick between quite a few different Battery styles. One doesnt fit all. But many will increase the odds.
<br><br>
  - Show Clock:
    - Toggle the clock thats on your mainscreen
<br><br>
  - Status Icons:
    - Status Icons are loved by some, and hated by others. Whichever party you belong to, we got you covered. Turn the on / off as you wish.
<br><br>
  - Bar Borders:
    - Bar Borders allow you to add an additional border around your icons. Simply turn it on or off.
<br><br>
  - Bar Background:
    - The bar background is just a little fancy line on the top, connecting the Icons with the battery. If thats too much for you, turn it off.

<br>

------

<br>

- <h4>File Browser:</h4>

  - Folders above files:
    - Toggle the sorting to show folders first
<br><br>
  - Show hidden Files:
    - Toggle hidden files (.files) on or off
<br><br>
  - Show internal Tab:
    - Show the internal flipper storage tab in the file browser
<br><br>
  - Favorites timeout:
    - Timeout for favorites (quick actions) like running a specific NFC file 
-----

</details>

<details>
<summary><code>Protocols</code></summary>

There are a few options for protocols. Lets talk about those:
<br><br>
- <h4>BadKB Mode:</h4>

  - This allows you to toggle between USB and Bluetooth mode for BadKB (formerly known as BadUSB). More about that [here](https://github.com/ClaraCrazy/Flipper-Xtreme/wiki/BadKB).
<br><br>  
- <h4>BadBT Remember:</h4>

  - This option allows your Flipper to save the BT keys of the device it connected to, for automatic pairing next time.

<br>

------

<br>

- <h4>SubGHz Frequencies:</h4>

  - Use Defaults:
    - Toggle the default frequencies provided by the Firmware. Dont want them, turn it off.
<br><br>
  - Static / Hopper frequencies:
    - Frequency:
      - This is a basic frequency display, similar to the App display we talked about earlier. It shows you the frequencies you already added and lets you select them if you want to remove one.
<br><br>
  - Add Frequency:
      - Allows you to add your custom Frequency. Useful for keys / whatever, that we dont know about or can/will not implement for whatever reason we may have given.
  <br><br>
    - Remove Frequency:
      - Simply removes the selected Frequency. One click and its gone. Magic!

<br>

------

<br>

- <h4>SubGHz Extend:</h4>

  - Extending the subghz frequencies allows you to go beyond what the Flipper devs were testing the Chip on. But dont worry, we sure did!
<br><br>
- <h4>SubGhz Bypass:</h4>

  - This allows you to bypass the region lock of the Flippers SubGHz module.

-----

</details>

<details>
<summary><code>Misc</code></summary>


- <h4>Screen:</h4>

  - Dark Mode:
    - Yup, dark mode. For real. It simply inverts the colors of all areas.
<br><br>
  - Lefty Mode:
    - We know left-handed people exist. OFW seemed to forget about that for a solid three years, so we added it ourselves. It flips the screen on its head, and inverts the controls.
<br><br>
  - RGB Backlight:
    - If you have the *hardware* Backlight mod, then those are the settings you need. Individual LED colors, rainbow, etc.

<br>

------

<br>

- <h4>Dolphin:</h4>

  - XP Level:
    - Set your XP Level to whatever you want. No real use, just because you can.
<br><br>
  - Dolphin Angry:
    - Set the anger level of your dolphin (cosmetic only, compatible asset pack required)
<br><br>
  - Butthurt Timer:
    - Allows you to manually set the "Butthurt" Timer of the Flipper, controlling how fast it will get sad when its not used.

<br>

------

<br>

- Change Device Name:
  - Allows you to change the name of your Flipper. This shows up on the Passport, qFlipper and the Flipper mobile app.
<br><br>
- Charge Cap:
  - Set the max. charging % of your flipper
<br><br>
- Show Xtreme Intro:
  - Re-play the intro you seen when first installing xtreme

</details>

-----

You've just learned quite a lot. Now, have fun have fun customizing the Flipper the way you'd like it!
