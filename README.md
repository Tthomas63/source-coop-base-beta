# source-coop-base-beta
Source Engine 2013 MP Coop Base Beta

An attempt to re-vive community made mods for Source Engine, specifically co-op.

This does not include any game binaries/assets what so ever. This is simply the `mp` ( Multiplayer ) Source code for Source Engine 2013 with some tweaks. This is not really for re-distribtion, more for personal tracking. A polished, clean configurable version is the evnetual goal.

This is provided as is, and I am not liable for any damage done to you or your property. Once again, this is maninly for version tracking for me. A more polished, well rounded configurable version is the end-goal for public use.

Basic Features/Ideas:
 - Fix NPC/Animations
 - Fix Map Transitions
 - Add Gibbing
 - New Models/Textures ( Not included. )
 - Ironsights
 - Gluon Gun 
 - Some other various failed experiments
 
Concept/Play Material:
 - You should currently be able to play the HL2 campaign as multiplayer, without major hiccups and transitions. Known Issues:
      * NPC Allies Scripting/Animated Game sequences: May hang up unless the player is near them, etc. Need to re-write the UTIL_GetPlayer() to grab the nearest player or some such
 - It should be possible to import any other materials/maps from HL2:EP1/EP2 or any other source games. I believe this should be possible with Gameinfo.txt but I have yet to properly set this up.
 
 Also here is the license agreement from Valve:
```
               SOURCE 1 SDK LICENSE

Source SDK Copyright(c) Valve Corp.  

THIS DOCUMENT DESCRIBES A CONTRACT BETWEEN YOU AND VALVE 
CORPORATION ("Valve").  PLEASE READ IT BEFORE DOWNLOADING OR USING 
THE SOURCE ENGINE SDK ("SDK"). BY DOWNLOADING AND/OR USING THE 
SOURCE ENGINE SDK YOU ACCEPT THIS LICENSE. IF YOU DO NOT AGREE TO 
THE TERMS OF THIS LICENSE PLEASE DON’T DOWNLOAD OR USE THE SDK.  

  You may, free of charge, download and use the SDK to develop a modified Valve game 
running on the Source engine.  You may distribute your modified Valve game in source and 
object code form, but only for free. Terms of use for Valve games are found in the Steam 
Subscriber Agreement located here: http://store.steampowered.com/subscriber_agreement/ 

  You may copy, modify, and distribute the SDK and any modifications you make to the 
SDK in source and object code form, but only for free.  Any distribution of this SDK must 
include this LICENSE file and thirdpartylegalnotices.txt.  
 
  Any distribution of the SDK or a substantial portion of the SDK must include the above 
copyright notice and the following: 

    DISCLAIMER OF WARRANTIES.  THE SOURCE SDK AND ANY 
    OTHER MATERIAL DOWNLOADED BY LICENSEE IS PROVIDED 
    "AS IS".  VALVE AND ITS SUPPLIERS DISCLAIM ALL 
    WARRANTIES WITH RESPECT TO THE SDK, EITHER EXPRESS 
    OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, IMPLIED 
    WARRANTIES OF MERCHANTABILITY, NON-INFRINGEMENT, 
    TITLE AND FITNESS FOR A PARTICULAR PURPOSE.  

    LIMITATION OF LIABILITY.  IN NO EVENT SHALL VALVE OR 
    ITS SUPPLIERS BE LIABLE FOR ANY SPECIAL, INCIDENTAL, 
    INDIRECT, OR CONSEQUENTIAL DAMAGES WHATSOEVER 
    (INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF 
    BUSINESS PROFITS, BUSINESS INTERRUPTION, LOSS OF 
    BUSINESS INFORMATION, OR ANY OTHER PECUNIARY LOSS) 
    ARISING OUT OF THE USE OF OR INABILITY TO USE THE 
    ENGINE AND/OR THE SDK, EVEN IF VALVE HAS BEEN 
    ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.  
 
       
If you would like to use the SDK for a commercial purpose, please contact Valve at 
sourceengine@valvesoftware.com.```
