# cstrike-sdk-2013
Counter-Strike: Source SDK based on leak(s) from 2018-2020 and original 2013 SDK.

Implemented:
- implemented some fixes and features from VDC (per-entiry dynamic shadow angles, Discord RPC, better env_projectedtexture behaviour, general snippets);
- added viewmodel_offset_x/y/z and removed cheat protection from viewmodel_fov.

TODO:
- [ ] Make custom shaders work (not possible right now, materialsystem blocks custom shader dll loading for valve games, like cstrike, dod, tf2 ect);
- [ ] Fix rare crashes;
- [ ] Fix teammenu command not working;
- [ ] Fix viewmodels for weapon_famas, weapon_galil and weapon_m249 (they are X reverted, viewmodel_offset_x will make them move to the right, not left);
- [ ] Attach flashlight to viewmodel;
- [ ] Implement client-side global light.

Used code from:
- https://developer.valvesoftware.com/wiki/Env_projectedtexture/fixes
- https://developer.valvesoftware.com/wiki/General_SDK_Snippets_%26_Fixes
- https://developer.valvesoftware.com/wiki/Implementing_Discord_RPC
- https://developer.valvesoftware.com/wiki/Dynamic_RTT_shadow_angles_in_Source_2007

Source 1 SDK Licence:

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
sourceengine@valvesoftware.com.
```
