<div align="center"><img width="500"/>
</div>


# Monster Slide English Translation Patch

## Table of Contents
1. [Overview](#Overview)
1. [Screenshots](#Screenshots)
1. [About the Game](#About-the-Game)
1. [Patching Instructions](#Patching-Instructions)
1. [[Helpful Game Tips](#Helpful-Game-Tips)
   - [Cheats](Cheats)
1. [Credits & Special Thanks](#Credits)
1. [Release Changelog](#Release-Changelog)




## **Overview**
The first Dead or Alive game for Sega Saturn is one of the best fighting games on the system. While it never received an English localization, the game is almost entirely in English, which made it very import-friendly.

That said, this patch translates the last remaining Japanese elements to English, courtesy of the existing translation found in the 2004 Xbox release of *Dead or Alive 1 Ultimate*. While that's a good way to play the game, there's a bilinear filter applied to it that makes all the 2D elements look way too blurry. The Saturn version is still the _best_ way to play (IMO), and now you can do so with the following changes:

- All character bios on character select screen translated
- All move lists in Training mode translated
- Name entry instructions translated
- "Save warnings" translated


## **Screenshots**

<!-- Row 1 -->
<p>
  <img width="500" alt="Character Select" src="https://github.com/user-attachments/assets/c436a365-b2f8-4da8-9d95-62dc47f9165b" />
  <img width="500" alt="Round Intro" src="https://github.com/user-attachments/assets/72efaa2c-b3c4-44aa-a140-eee4e0ca9bdf" />
</p>

## **About the Game**

<div align="center">
<table>
  <tr>
    <td><strong>Original Title</strong></td>
    <td>Dead or Alive</td>
  </tr>
  <tr>
    <td><strong>Localized Title</strong></td>
    <td>Dead or Alive</td>
  </tr>
  <tr>
    <td><strong>Developer</strong></td>
    <td>Team Ninja</td>
  </tr>
  <tr>
    <td><strong>Publisher</strong></td>
    <td>Tecmo</td>
  </tr>
    <tr>
    <td><strong>Original Release Date</strong></td>
    <td>1997-10-09</td>
  </tr>
 </table>
</div>


## **Patching Instructions**

The patch is shipped as an XDelta patch. 

### XDelta Instructions ###

1. Grab an XDelta patching utility like <a href='https://www.romhacking.net/utilities/704/'>Delta Patcher</a>
2. Unzip patch bundle
3. Open **'DeltaPatcher.exe'**
4. For the Original File, locate Track 01 of the original Dead or Alive disc (for example: <kbd>Dead or Alive (Japan) (1M) (Track 01).bin</kbd>)
5. For the XDelta patch section, locate the <kbd>Dead_or_Alive_Full_English_v1.0.xdelta</kbd> patch.
6. Click **'Apply Patch'**
7. If successful, Track 01 will be replaced with the patched track.

**--> Important! <--**
- Tested with release <kbd>Dead or Alive (Japan) (1M)</kbd>, <kbd>Dead or Alive (Japan) (2M)</kbd>, and <kbd>Dead or Alive (Japan) (Rev A) (10M)</kbd>
- Tested on emulators Mednafen and Ymir, and real hardware with Satiator.

## **Credits**

**Translation**
- <a href='https://www.mobygames.com/game/15449/dead-or-alive-ultimate/credits/xbox/?autoplatform=true'>Team Ninja</a>

**Texture Art**
- Exxistance

**Playtesting**
- wonder-inc
- Exxistance

**Special Thanks**
- Tomonobu Itagaki (<a href='https://www.timeextension.com/features/best-of-2025-i-told-him-i-loved-him-because-i-do-a-tribute-to-the-late-dead-or-alive-creator-tomonobu-itagaki'>RIP</a>) & Team Ninja

## **Release Changelog**

- **Version 1.0.1 (08/23/2026)**
  - Fixed issue with English rendering of character profiles not appearing if 2P controller is used as the primary mode initiator
  - Original Xbox mistranslation of Bayman's トラースキック updated from "Trass Kick" to "Thrust Kick." Tina's move フライングメイヤー also updated to "Flying Mare." 

- **Version 1.0 (08/21/2026)**
  - Initial release


