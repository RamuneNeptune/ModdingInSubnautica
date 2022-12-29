---

<br></br>

---

# Table of Contents

- Info & FAQ
  - [General FAQ](#faq)
  - [General Resources](#resources)
  - [SN 2.0 | List of working mods](https://ramuneneptune.github.io/choices/modlist.html)
  - [BZ 2.0 | List of working mods](https://ramuneneptune.github.io/choices/modlist.html)
  - [Page Contributors](#contributors) ⭐
- Installing Mods
  - [Subnautica 2.0](#sn-latest)
  - [Subnautica Legacy](#sn-legacy)
  - [Below Zero](#bz-latest)
- Mod Making
  - [Via BepInEx](https://mroshaw.github.io/)
  - [Via QModManager](https://mroshaw.github.io/)
  
<br></br>

## Hey! I'm looking for contributors for this page.
If you feel there's something you could add, for some ideas, maybe something like a resource to [General Resources](#resources), a question and/or answer for [General FAQ](#faq), or even an entirely new section, I totally recommend you make a [PR](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) and do that!
  
<br></br>

---
<a name="faq"></a> 
<br></br>

---

## General FAQ
### What is Subnautica 2.0?
An update to the game which caused QModManager to break, and also brought along a ton of changes to the game code. Both of these have caused most (if not all) mods to require an update to be compatible with the latest version of the game. 

### What is Subnautica Legacy?
A branch of the game available to Steam users. It is the game version prior to the current build, which is 71137, and the Legacy build is 68598.
Keep in mind, as this is the previous version of the game, all mods that worked before the update, will work on Legacy.
You can find instructions to access the Legacy branch [here]().

### What is Submodica?
https://submodica.xyz, referred to as `Submodica`, is a relatively new site being useed to list & find amazing Subnautica & Below Zero mods. A key part of this website is it has mods listed that have been removed from [Nexus](https://www.nexusmods.com/), but posted here instead by their respective Mod Authors. Do also keep in mind that this site has not yet been fully announced to the [Subnautica Modding] discord community, and is currently still in Beta. A comment system is in-the-works or soon to be in-the works, so hopefully once that comes out we might get a public annnouncement of the site!

### What happened with Nexus?
On a cold winter morning, a lonely seal woke from his slumer. He opened his phone and stumbled upon an article - "NexusMods will no longer allow mod authors to remove their mods from the platform" 'Oh no!' he thought to himself, whatever will I do? Later that day, after the seal had some time to think, he decided to remove his mods from the platform before it was too late, and instead opted to host his mods via GitHub. Over the next few days, the seal told his friends about what was happening with NexusMods, most of them agreed that they too were going to move their mods off the platform. Some of the seals friends simply didn't care, and some of them made money from Nexus, of course not everyone can be on the same page, so our seal friend simply respeccted the others decisions. 

### How do I access the Legacy branch on Steam?
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed malesuada rutrum sem, eu efficitur metus tristique at. Proin hendrerit tellus quis odio vestibulum, vitae iaculis arcu aliquam. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed malesuada rutrum sem, eu efficitur metus tristique at. Proin hendrerit tellus quis odio vestibulum, vitae iaculis arcu aliquam. 


<br></br>

---
<a name="resources"></a> 
<br></br>

---

## General Resources
### Subnautica Modding Discord
[Click here to join!]()

<br></br>

---
<a name="sn-latest"></a> 
<br></br>

---

## Mod Setup for SN (Subnautica) 2.0
<strong>QModManager is no longer in-use, mods need to transition from `QMods` to `BepInEx` mods, so far around 50-60 already have made the transition. All of those mods are functional in 2.0, but are extremely likely to cause issues if used with the Legacy branch.</strong>
 1. Download the [Subnautica BepInEx Pack](https://www.nexusmods.com/subnautica/mods/1108), and optionally, but recommended, [BepInEx Tweaks](https://www.nexusmods.com/subnautica/mods/1104?tab=description), and [Configuration Manager](https://www.nexusmods.com/subnautica/mods/1112).
 
 2. If you have used `QModManager` before or have any existing mod installations, delete the `QMods` & `BepInEx` folders from your game folder. <strong>Backup your QMods folder if you believe you might switch to [Subnautica Legacy]() at some point in the future.</strong>
 
 3. Extract / Unzip the `Subnautica BepInEx Pack` zip file into your game installation folder. <strong>If it asks about replacing / overwriting files, select Yes, or confirm, or something of that equivalent.</strong>
 
 4. Launch the game to generate a `plugins` folder, which will appear inside the `BepInEx` folder located in your game installation folder.
 
 5. If installed, extract the `BepInEx Tweaks` & `Configuration Manager` zip files into your <strong>game folder</strong>, and they *should* end up inside the `BepInEx\plugins` folder. 
 
 6. You are now free to install mods that are updated for 2.0, [see the list here](https://ramuneneptune.github.io/modlists/sn.html). 
<br></br>

---
<a name="sn-legacy"></a> 
<br></br>

---

## Mod Setup for SN (Subnautica) Legacy
<strong>Holup! This guide is for the Steam Legacy Branch - If you're playing the latest version of the game, or don't know what Legacy is, [go here](#sn-latest)</strong>
 1. Download [QModManager v4.4.4](https://github.com/SubnauticaModding/QModManager/releases/download/v4.4.4/QModManager_SN1.STABLE.zip) here, and [SMLHelper v2.14.1](https://github.com/SubnauticaModding/SMLHelper/releases/download/v2.14.1/SMLHelper_SN.STABLE.zip) here.
 
 2. Place both zip files into your game installation folder.
 
 3. Extract / Unzip `QModManager_SN1.STABLE.zip` into your game folder. You should now have all the files highlighted.
 ![](https://snm.crd.co/assets/images/image01.jpg?v=e6c5ef0b)
 
 4. Launch the game to generate a `QMods` folder.
 
 4. Extract / Unzip `SMLHelper-SN.STABLE.zip` into the newly generated `QMods` folder, which should create a `Modding Helper` folder inside `QMods`.
 
 5. Delete the lefover <strong>zip files</strong> for `SMLHelper` & `QModManager`, and then you're ready to install mods to your `QMods` folder.
<br></br>

---
<a name="bz-latest"></a> 
<br></br>

---

## Mod Setup for BZ (Below Zero)
 1. Download [QModManager v4.4.4](https://github.com/SubnauticaModding/QModManager/releases/download/v4.4.4/QModManager_BZ.STABLE.zip) here, and [SMLHelper Zero v2.14.1](https://github.com/SubnauticaModding/SMLHelper/releases/download/v2.14.1/SMLHelper_BZ.STABLE.zip) here.
 
 2. Place both zip files into your game installation folder.
 
 3. Extract / Unzip `QModManager_BZ.STABLE.zip` into your game folder. You should now have all the files highlighted in Green.
 ![](https://snm.crd.co/assets/images/image01.jpg?v=e6c5ef0b)
 
 4. Launch the game to generate a `QMods` folder.
 
 4. Extract / Unzip `SMLHelper-BZ.STABLE.zip` into the newly generated `QMods` folder, which should create a `SMLHelper_BZ` folder inside `QMods`.
 
 5. Delete the lefover <strong>zip files</strong> for `SMLHelper` & `QModManager`, and then you're ready to install mods to your `QMods` folder.
<br></br>

---
<a name="contributors"></a> 
<br></br>

---

### Contributors:
  - <strong>RamuneNeptune:</strong> Everything, so far.
  - <strong>Not Your Name:</strong> It's not your name.. but it could be! Contribute today!
  - <strong>Not Your Name:</strong> It's not your name.. but it could be! Contribute today!
  - <strong>Not Your Name:</strong> It's not your name.. but it could be! Contribute today!
  - <strong>Not Your Name:</strong> It's not your name.. but it could be! Contribute today!
  - <strong>Not Your Name:</strong> It's not your name.. but it could be! Contribute today!
  - <strong>Not Your Name:</strong> It's not your name.. but it could be! Contribute today!
  - <strong>Not Your Name:</strong> It's not your name.. but it could be! Contribute today!

---

<br></br>

---

### This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a> <img src="https://i.imgur.com/mGSBx4J.png" width="18" height="18"/>
