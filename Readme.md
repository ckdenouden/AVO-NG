# :evergreen_tree: Animonculory Visual Overhaul - Next Generation (AVO-NG)

![image](https://raw.githubusercontent.com/The-Animonculory/AVO-AE/main/.github/AVOAENewLogo.webp)

Wabbajack Modlist Installer by The Animonculory

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/The-Animonculory/AVO-AE/main/.github/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><img src="https://raw.githubusercontent.com/The-Animonculory/AVO-AE/main/.github/GitHub.png" width="72px" /></td>
<td><a href="https://discord.gg/DffHKcszfg">Support Discord</a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## :information_source: Preamble

> `"...the best way to make your own list."`
> 
> `"...gorgeous visuals and ability to make it your own..."`
>
> `"...absolutely amazing..."`

The premier graphical overhaul for Skyrim Special Edition, **Animonculory Visual Overhaul** has been installed several thousand times and garnered a reputation for offering a perfect base to build your modded game from.

The Next Generation (NG for short) version of Animonculory Visual Overhaul seeks to being the game up to modern standards without drastically changing the things that make Skyrim Skyrim. Featuring minimal tweaks to settlements, full creation club integration, a comprehensive graphical overhaul and no feature creep, it remains the perfect base to build off.

AVO-NG replaces and supersedes previous versions/Editions of Animonculory Visual Overhaul and, as a result, is **not compatible** with saves made using the older versions. Major engine and graphical changes have been made which **will** cause you to crash.

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## :computer: System Requirements

:exclamation: **AVO-NG DOES NOT SUPPORT GOG VERSIONS OF SKYRIM AE** :exclamation:

:warning: AVO-NG requires the most recent update to Windows 10 or 11 to function properly. LTSC or special variants of the operating systems **WILL NOT WORK**. :warning:

AVO-NG is a heavier list than AVO was and thus, as a result, requires beefier hardware to run it.

My specs:

- R7 5800x
- 32GB DDR4
- NVME M.2
- RTX 3090 FE

I average *locked* 84fps @ 1440p ultrawide (21x9).

:warning: RX 500 series cards (580 or similar) are **not supported.** :warning:

Space required: Approx 162GB (Downloads included)

## :page_facing_up: Installation

:warning: AVO-NG requires a **COMPLETELY UNMODIFIED** installation of the **LATEST VERSION** of Skyrim. :warning:

Installing AVO-NG is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### :clipboard: Pre-Installation

Prior to installing AVO-NG, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Fully disable OneDrive and any other programs which hook into user file areas.
5. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location. If you only have one drive, look into LostDragonist's [SteamLibrary tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).
6. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
7. Start the game to the main menu in order to download all the creations.

***

### :page_with_curl: Wabbajack Installation

#### :scroll: Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### :open_file_folder: Downloading and Installing AVO-NG

Downloading and installing AVO-NG can take a while depending on your internet connection and computer. To install AVO, complete the following steps.

1. Open Wabbajack and click on browse modlists. Check the tickbox that says `show unofficial`.
2. Press the download button on AVO-NG and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\AVONG. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

***

##### :confused: Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
	- **Make sure you have downloaded all the creation club content!**

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## :floppy_disk: Post-Installation


### :file_folder: Stock Game

AVO-NG utilises a Wabbajack technology called Stock Game. What this essentially does is create a copy of your Skyrim installation within the installation location of the list. This enables greater compatability with other mod-lists.

***

### :telescope: ENB

AVO-NG uses Solas weathers for its weather mod and Enhanced Lighting for ENB + Relighting Skyrim for lighting improvements. By default, the list uses E.V.C ENB which complements it perfectly. If you wish to change the ENB, an ENB manager is included to facilitate this.

### :telescope: Upscaler/TAA

Skyrim Upscaler is also included, configured in DLAA mode to enable ENB comatability. You will need to enable it in game by pressing the `End` key on your keyboard. 

If you do not have an Nvidia GPU, set the mode to `TAA` to ensure that the antialiasing works properly.

:warning: If your game crashes and the crashlog references upscaler, disable the mod. :warning:

**NOTE**: Screenshots save to `AVONG/Game Root`.

## :arrow_forward: Playing the List

### Ultrawide Setup

To enable 21x9 ultrawide support, activate the mods under `21x9 user interface`. **NOTE**: Resolutions outside of 21x9 and 16x9 are **NOT** supported.

### :runner:  Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `SKSE` and press the `Run` button.

### :bookmark: In-Game MCM options

AVO-NG has all it's MCM options pre-configured via MCM recorder. If you wish to change any settings, you can do so.

### :horse_racing: Starting the Game

By default, AVO-NG uses [Optional Quick Start](https://www.nexusmods.com/skyrimspecialedition/mods/63953) to bypass the starting sequence of the game and spawn you into the Helgen tunnel. The equipment chest has been custom configured for the list to provide a range of starting equipment.
	
## :chart_with_upwards_trend: Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

### :nut_and_bolt: Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Remove Shadows`: I really don’t recommend turning this on, but if you must, then you can.

## :put_litter_in_its_place: Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## :hearts: Credits and Thanks

- _YOU_ for reading this.
- The Animonculory Team.
- Noggog for Mutagen.
- xSlim for Proofreeading documentation.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.

## :telephone_receiver: Contact

Whilst I am available primarily on [my server](https://discord.gg/DffHKcszfg), please check the [issues](https://github.com/The-Animonculory/AVO-NG/issues) tab on github first if you have any issues. DO NOT DM ME ON DISCORD.

You are welcome to [contribute](https://github.com/The-Animonculory/AVO-NG/blob/main/Contributing.md) to the list, however please check the [changelog](https://github.com/The-Animonculory/AVO-NG/blob/main/Changelog.md) before you do.

## :guardsman: The Animonculory Team
- Althro - Leader & Head of Development (Author of [ADT](https://github.com/The-Animonculory/ADT/blob/main/README.md), [AVO](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul) & Tinvaak)
- Styyx - Senior Management Team & Dev Team (Author of [Ruvaak](https://github.com/chri3i/Ruvaak-Readme))
- Chef/Para0x - Senior Management Team & Dev Team (Author of [Fahdon](https://github.com/Para0x/Fahdon-A-Skyrim-Together-Experience/blob/main/Readme.md))
- The Spaniard -Senior Management Team, Documentation & Dev Team
- GuitarBarbarian/KFC - Senior Management Team
- Abandoned by Arkay - Dev Team & Testing (Author of [DNGG](https://github.com/Arkay-1248/Do-Not-Go-Gentle))
- Astro - Dev Team & Testing
- DestinySlayer - Dev Team, Testing & Community Engagement (Author of [Krahven](https://sites.google.com/view/krahven/krahven-main-page))
