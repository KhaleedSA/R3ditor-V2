<img src="https://themitosan.github.io/assets/img/R3V2.png" alt="R3V2_LOGO" title="R3ditor V2 (R3V2) Logo" width="100"/>

# R3ditor V2
Aka. R3V2, this is the second version of <a href="https://github.com/themitosan/R3ditor" target="_blank">R3ditor</a> - a tool to create mods and study classic Resident Evil 3.

### Project Status
This project is on alpha state.
It can open maps, text files and SCD Scripts. For now, your best usage is for edit some RDT sections! Sadly, it is not capable of compiling RDT files¹.

### Requirements
- Windows: 7, 8, 8.1, 10 or 11.
- Linux: Ubuntu 20.00 or higher
- macOS: 10.15 (Mojave) or higher²
- Hardware: Any hardware that is capable of running NW.js and the game!


### How to install
It's recommended to use our pre-compiled version! You can download on <a href="https://themitosan.github.io/" target="_blank" title="TheMitoSan's Website - Click here to open">TheMitoSan's website</a>, But if you want to run it on current state development, It is the same method for R3ditor OG.

<i>PS: <a href="https://themitosan.github.io/R3V2" title="Click here to test R3ditor V2 in your browser!" target="_blank">You can try this tool online!</a></i>

#### Windows
* Clone this repository
* Download NW.js version 0.38.4 [ <a title="x86 Version - Click here to download" href="https://dl.nwjs.io/v0.38.4/nwjs-sdk-v0.38.4-win-ia32.zip" target="_blank">x86 / 32 Bits</a> or <a title="x64 Version - Click here to download" target="_blank" href="https://dl.nwjs.io/v0.38.4/nwjs-sdk-v0.38.4-win-x64.zip">x64 / 64 Bits</a> ]
* Extract NW contents inside clone folder
* Run <code>nw.exe</code>

#### Linux
It's exactly the same process to run on windows!
The only difference is: To run R3V2:

* Open your terminal and navigate to R3V2 folder
* Run <code>./nw</code>

Download Links: [ <a href="https://dl.nwjs.io/v0.38.4/nwjs-sdk-v0.38.4-linux-ia32.tar.gz" target="_blank">x86 / 32 Bits</a> or <a target="_blank" href="https://dl.nwjs.io/v0.38.4/nwjs-sdk-v0.38.4-linux-x64.tar.gz">x64 / 64 Bits</a> ]

#### macOS
* Clone this repository
* Click using right button on <code>nw.app</code> and select "Show Package Contents"
* Navigate to <code>Contents/Resources</code> and create a new folder labelled <code>app.nw</code>
* Paste all content from cloned repo inside this folder
* Go back to NW folder and run <code>nw.app</code>

Download Link: [ <a target="_blank" href="https://dl.nwjs.io/v0.38.4/nwjs-sdk-v0.38.4-osx-x64.zip">x64 / 64 Bits</a> ]

## Third-Party software used on this project

### Engine:
* NW.js (aka. Node-Webkit) by NW.js community

### External JS Apps / Plugins:
* jQuery and jQuery UI by The jQuery Foundation
* eNGE by Reene-Kootstra

### NW.js Plugins:
- RPC by discord.js
- memoryjs by Rob--
- fs-extra by jprichardson

### These files can be found in "App/tools/":
- xdelta.exe (Xdelta patcher)
- SDL.dll (Required for rofs.exe)
- rofs.exe (Reevengi-tools - Rofs Unpacker)
- 7z.exe, 7-zip.dll, 7za.dll, 7zxa.dll and 7za.exe (7zip)

### Credits
<!-- Let's go wild! -->
I would like to pay credits from all sources and thank everyone who helped me with this project - since without your help none of this would be possible!<br><br>
<i>Many thanks to: CT-STARS, Elric (Aka. 3lric), El rincon del Lobezno, Rene Kootstra, discordjs, Rob--, hongru, Joshua MacDonald, jprichardson, Y (The Artist) zu, Mortican, Angus Johnson, Leo2236, MarkGrass, matteofumagalli1275, Klarth, "Shockproof" Jamo Koivisto, Diogo "Flag" Bandeira (Aka. Flag King), Khaled SA, Patrice Mandin (pmandin), ResidentEvilArtist and Biohazard España (BHE).<br>

<sup>eNGE is a PS1 emulator written in JS created by <a href="https://github.com/kootstra-rene" target="_blank">Rene Kootstra</a></sup><br>
<sup>Some icons was made using <code>shell32.dll</code> icons from <a href="https://github.com/microsoft" target="_blank">Microsoft</a> Windows 98 SE</sup><br>
<sup>RDT SLD Edit icon was created using the original icon from <a href="http://lgt.createaforum.com/tools-24/re3slde-a-tool-to-edit-sld-files/" target="_blank">Leo2236 RE3SLDE Editor</a></sup><br>
<sup>The new R3ditor V2 logo was created using <a href="https://www.dafont.com/pix-chicago.font" target="_blank">Pix Chicago</a> and <a href="https://www.fonts.com/font/linotype/plak/black-extra-condensed" target="_blank">Plak® Extra Condensed</a> fonts</sup><br>
<sup>Biohazard and Resident Evil are trademarks of ©CAPCOM CO., LTD. ALL RIGHTS RESERVED.</sup></i><br><br>

<sup><i>¹ - You can use a temp function called "SCD Hack" - but it's not recommended since in most cases it can make your game crash!</i></sup><br>
<sup><i>² - This software requires macOS versions that runs on Intel x64 arch, since this specific version of nw.js (0.38.4) was compiled targeting this same arch.</i></sup>
