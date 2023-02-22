# The Adventures of Sparky
**![](https://lh3.googleusercontent.com/W7LluxbgEnH8S0eYSGWsZX1XEnD2kjVxXPGlSfCF5lSf0nXS_qmZlM46cFxq2SpPdPrpBUDYlU15zBVO5bbWpoHMqcG7xXSrTl7Jm02vPevUfYup6nYgf0bULmmHYJvRaCAz9DaK9wChE71KRG60GB0)**
<img alt="GitHub watchers" src="https://img.shields.io/github/watchers/alvarohghg/Adventures-of-Sparky?style=social">
<img alt="GitHub repo file count" src="https://img.shields.io/github/directory-file-count/alvarohghg/Adventures-of-Sparky">
<img alt="GitHub file size in bytes" src="https://img.shields.io/github/size/alvarohghg/Adventures-of-Sparky/game%20dev%20exe/gamedevproject.exe">
<img alt="Language" src="https://img.shields.io/badge/Language-Lua-green">
## Introduction
The purpose of this document is to serve as an approach to the development of the game **The Adventures of Sparky** as well as a tutorial of it. This project was carried out for the Game Dev course by **Alvaro Berjillos**, **Filip Gadja**, **Juan Chai** and **Brian O'Driscoll**. The executable file and the project files are included in this repository.

### Project
#### Technical aspects
The videogame was programmed entirely in Lua and it was developed using the [`Defold`](https://defold.com/) IDE on Windows.
The music, sound design and some models extracted from the asset collection of [`Kenney`](https://www.kenney.nl/assets) as well as [`Freesound`](Freesound.org), and [`Ludobits`](https://github.com/britzl/ludobits).

#### Game concept
We wanted to create a simple *2D puzzle based plataformer* game where the main theme is the management of **electricity**. The main character, **Sparky**, is immersed in the colourful city of **Tokyo**, where he discovers that he can morph through walls of the same colour as him. He also makes use of batteries throughout the world that allow him to regain energy and wires to move through the levels and avoid the multiple enemies and obstacles.

## First steps
### Install the game

 - From the Github Project's page, click on the *Code* button and select *Download ZIP* to download directly.
 - From the Git Bash, enter the folder where you wanna store the project (*cd myfolder*) and enter the  the following line:
	 ``` git clone https://github.com/alvarohghg/Game_dev.git ```
 
### Run the game
 1. Enter in the "game dev exe" folder and then double-click on the "gamedevproject.exe" file.
 2. Press the "Start" button in order to display all the available levels
 **![](https://lh4.googleusercontent.com/YOaHXFKUOHLX7zRzUPc18x7oU5GMcvuuUeYYcSBWnmlv5csYPbO0dheH4KVIPVh648LWV__4mrNaZgOZdDz3rxZiHRZ3pbpDOqcN_Gxo-9l4PMDqf5DwBcaamF63YBS8VXgCK4ZiSrVj7rJMrKeH9N0)**
 3. Select the level among all the options (Tutorial, 3 feature tests and Level 1).
 4. Have fun!

## Controls
|Action|Key  |
|--|--|
| Change color | Space bar |
| Jump | W |
| Move Left | A |
| Move Right | D |
| Double Jump | W+W (quickly) |
| Interact | E |
| Select (In the menus) | Left Click |

## Levels

### Tutorial
This level helps the player understand and get used to the basic mechanics of the game in a simple and understandable way.

 1. **Changing color**
	 Sparky's special ability is to change colour at will. When Sparky is coloured blue, he can pass through blue surfaces, and when he is coloured purple, he can pass through purple surfaces. 
	 ![](https://lh4.googleusercontent.com/VpRk3PhgBlJMssl2EQk59YWwCKy-gm2KrCswCHoqvbpU3_icAkEvu2_YVtDFQzCT7rLJ4MyvcrsZSLLl4BtgvivHxDv0VfjqYYI57dmjhwPdZ2JvDA1EXLIdijwC9A2scUWmeNTdIni8fcPSQ-RIHq8)
 
 2. **Encountering obstacles and receiving damage**
 
	 Throughout the game, the player will encounter a wide diversity of obstacles (such as *lamps*, *old lamps*, *insta-kill lamps*, *water* or *color surfaces*) fonts that will damage its **health**. Sparky will need **batteries** in order to regain health points. ![](https://lh3.googleusercontent.com/LzqR-icuAwQGxZtq2EO0Fe9sZtJotsvioK9XydejsMsBzSRr11Jo_ccWRBuUdd-z1yRpgKal4O2DnNmlsQSACnE_y7xloGJrUsuZ-6eW1f8cxcXnuwnUU87kgnFbKpaZ7FAhEYlAoeejQC_DvYz3c2M)![](https://lh3.googleusercontent.com/vBqHYoO3iSiU7yd_VPANi8T6nxrtjp0EY7FYmO2-946IakoO-lclpajnpGwXJcnxPfakKC1BHJoCIkF3_q7DvpIomqjBR8PyY5QX62MOt97-Ry2AvCBB_IwSyF9aUVZq7kgbPDwihGE7dvTR10SlVt8)
 

	> Sparky will lose 1 point of health per second when contacting with enemies. This is reflected in the healthbar, located in the left upper corner.

 3. **Keys System**
Sparky will need to pick **2 keys** in order to finish each level. When the player picks up one key, the corresponding key image in the HUD (next to the healthbar) becomes brighter. 
**![](https://lh3.googleusercontent.com/EcuZxENSFXCmT9A87ikSYDlKFDE8hEa6--C4rDiu5j4iIAMVnIAKBqwcI-ob3ZX4WvBHcCNPOo91Uh-8wm4ixzl-De5joDa2lrw6LRiOSll3iVN0KaBhgwz3_ddRvYGdZGQ_jpztZ9jBwqbEQHAeWU8)**
	> The keys are stored even if the player dies in the level.

 4. **Interacting with the environment**
	 Sparky will be able to reach high places thanks to the teleport system. By making contact with them, he will be teleported to platforms which could not be accessed by just jumping.
	 
**![](https://lh6.googleusercontent.com/kJ3k1lnTpiSeEnDq2OVEo41IXQjzYd5NiaJQQcIaeyAolEOSCHbUorU-f1ZqLdRwjteGSoNKHolePl7kXcOHcuRXtHlRAwPU_eXA-AmXFwBad1JJNiK4tZ8dUPvUJHMFbgdnQpaemC1DwmiMqN0I4-U)**

Some obstacles will require you to interact with buttons by pressing *E* near them, such as the *insta-kill lamps*:
	
**![](https://lh4.googleusercontent.com/O0rUtdbyhn_Jb9EHFcRtjEA52St-gsIcbZ1dLkkfkvJ3rzdDE9liVkXTjjC9RBoymeKdNfpoklKKTchAFjv0wsdEBXyvCjv-sY7uPKDMvbLrb8mYCWFGY2sNh8L6bicnNnQRDHQ2c1wb6Y2OJPA0S4E)**

### Level 1
In the first level, Sparky needs to collect the 2 batteries. Firstly, the player will need to test its agility by jumping the first platforms, surrounded by deadly *water* blocks.
**![](https://lh6.googleusercontent.com/lyRkne_YQkfu_Rm_Szp5bqN-4WzBegIt2-fiKBFJkrufEpohy51LiD63igmZBJrGP3guxyOCGB-1COvdUrW5AkQ2cxAm8aSE01LWEEJF-U4Xp4mn4q0WMKcogEIe2XynIW3AfCjhH7kP2-DbasMoUuY)**
In the second obstacle, the player will need to use the color changing skill in as well as some jumps to reach the next teleport as well as the first key of the level.

**![](https://lh5.googleusercontent.com/7uTFtpT_NRzOlXuqRQIBNJQlrdOfgmM_bzczSQfJCr7_K-BgaKdzGChxzTWqKnUFZ_FmSxn5gCyThQMEYe6Duc4rNi5_td5c4Ru3Jy8ns2KaaCGA0xilCUiY6wSBeKg8RropsoPfyfxpbWt_qCLtFhw)**
Then the first enemies appear: some lamps are blocking the exit! Nothing that the double jump can avoid, though. But be careful, you may need the battery at the end of the corridor if you suffer damage.

**![](https://lh5.googleusercontent.com/hhs7tBDG49NQxG0-eigkq6pEzeSBC-gbSQGVteLV57rmjwJRZymrceuQxCjPkBGtDB8m0UK0IxShW52CJ_Ye49RUH1LAMDrCNTcBi8qoRLRq90tbZ9BSpItzoyVWC1V6NaFbHPMlTZwUZ9IdCUIh9uM)**
**![](https://lh3.googleusercontent.com/EifpvTITR_1xeUcr0sltQikMxrgMiLhXhjf4GyyuCRcanfXttXB5tFTlCm80Kab9FsLQtrh_Q2Ajm7nQwCfTDb0fM3BR2JBeQ-3bsC_SLFq1iMwPAQr5TIVDA8SJ-tt-EHxUJmd6AGv0pErp0Uf9cdw)**
The rest is a piece of cake: use of the double jump again and make sure you have changed your color to the correct one to avoid falling to the waters. If you have collected the keys, the following message will appear:

**![](https://lh3.googleusercontent.com/cbYvb843WLeFmdbp8klIcZVdWJB0h2PvKtCngoz_LKsMLDjamVZu7PpuIL8KH4MEm_F0Fx_UK7eCpOCgtsqarsrChe-NhUs1xAlDrDuXSl4B2qkf48r3fLgpUUPEo--GyNQtN0Xgs8Lqr1pE53j3UmY)**
**![](https://lh4.googleusercontent.com/IPhCanq_rn94pdIvgFToamWE4MRoopB3M98bvXESHcmdYLPLQP6PHqnzZQhWDBscwiNpDlc1rDwZGFQ30ktFgsgP5Tx-p05ZXmcdjn_fhxB0O9isJWPYxJjYjcLFCkf3zuXbhLQE3o8iUwdprmMfTH8)**
## Bugs

The player may encounter some of the bugs listed here:

 - **Moving the game window** causes the main character to fall out of the level
 - **Changing colour while inside a platform** causes unexpected results
 - **Sharing the game file** could causes issues related with different versions of Defold
