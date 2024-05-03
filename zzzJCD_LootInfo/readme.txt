Loot Info - It's empty? Or have I already opened/looted?
by JC Denton (PaulDenton on Nexus)
Version  : 1.8.0
Date     : 2020/02/22
Category : User Interface



Description
===========
Displays in the Loot/Open/Steal button whether the content is empty or has already been opened.
This mod has the localizations:
English/French/Spanish/Italian/Polish/Czech/Chineses/Russian and German.

Note:
Already opened chests etc. (before this mod installed)
are not displayed as "searched" after installation.
You have to open it again, then the condition will be displayed correctly.

Other Features:
* The mod can also show "empty" on the "loot/open/steal" button when the content is empty.
* Can display "(dead)" or "(unconscious)" on the npc name.
---------------------------------------------------------------------------------------------------
Zeigt beim Plündern/Öffnen/Stehlen-Button an, ob der Inhalt leer ist oder ob schon geöffnet wurde.
Diese Mod hat die Lokalisationen:
Englisch/Französisch/Spanisch/Italienisch/Polnisch/Tschechisch/Chinesisch/Russisch und Deutsch.

Hinweis:
Bereits geöffnete Truhen etc. (vor der Installation dieser Mod)
werden nach Installation erstmal nicht als "durchsucht" angezeigt.
Du musst diese nochmal öffnen, dann wird der Zutand korrekt angezeigt.

Andere Features:
* Die Mod zeigt auch "leer" auf der Schaltfläche "Beute / Öffnen / Stehlen" anzeigen, wenn der Inhalt leer ist.
* Anzeige "(tot)" oder "(bewußtlos)" im NPC-Namen.


Mod Dependencies
================
Kindom Come: Deliverance of course ;-) at least Version 1.8.1

CLAM
(Only necessary if you have installed a mod that is in the incompatibility list.)


Manual install
==============
Open the JCD_LootInfo-...zip, and extract all the content into your Mod folder
(e.g. Steam\steamapps\common\KingdomComeDeliverance\Mods\)
If the mods folder is not exist, then create it.
Now the folder "steamapps\common\KingdomComeDeliverance\Mods\" should contain
the folder "JCD_LootInfo".
--------------------------------------------------------------------------------------------------------------------------------------------------------
Öffne die JCD_LootInfo-...zip, und entpacke den kompletten Inhalt in deinen Mod-Ordner
(Steam\steamapps\common\KingdomComeDeliverance\Mods\).
Ist der Mods-Ordner nicht da, dann erstelle ihn neu.
Nun sollte sich in dem Ordner "steamapps\common\KingdomComeDeliverance\Mods\"
der Ordner "JCD_LootInfo" befinden.

IMPORTANT
---------
If you use CLAM together with my mod, then please also check CLAM for updates!


Manual uninstall
================
Delete the unpacked folder "JCD_LootInfo".
----------------------------------------------------------------
Lösche den entpackten Ordner "JCD_LootInfo".


Incompatibilities
=================
Perkaholic and Perkaholic - German﻿ or other translations.
Perkaholic new patch compatible
Please download and install CLAM if you use my Mod together with one of these mods.



For all other Mods which change the following scripts:
Under \Data\Scripts\Entities\WH\Stash:
AnimStash.lua
Nest.lua
StashCorpse.lua

Under \Data\Scripts\Entities\AI:
Boar_x.lua
Cow_x.lua
﻿DeerDoe_x.lua
﻿Dog_x.lua
Hen_x.lua
Horse_x.lua
NPC_Female_x.lua
NPC_x.lua
﻿Pig_x.lua
RedDeer_x.lua
RoeBuck_x﻿.lua
Sheep_x.lua

Under \Data\Scripts\Entities\AI\Shared:
BasicAIActions.lua

Under \Data\Libs\Localization:
localization.xml
If this file conflicts with another mod, which not exist in my Incompatibilities list,
then please report to me for a CLAM update.


History
=======

---------
ChangeLog "Loot Info"
---------
[ v1.8.0 ] 2020/02/22
- Adapted to Game-Version 1.9.5

[ v1.7.0 ] 2019/02/15
- Adapted to Game-Version 1.7.1
- fixed: Localization polish - change word "pusty" to "pusto" - reported by @Wiwra, thanks
- fixed: prevent the mounting of horses. - reported by @NiftyPower and @Cava1712, thanks
- fixed (hopefully): 
  Containers and NPCs seem to keep their searched tag even after respawning. - reported by @FESilencer, thanks

[ v1.6.0 ] 2018/10/27
- Adapted to Game-Version 1.7.1

[ v1.5.1 ] 2018/08/26
- Now the mod can display "(dead)" or "(unconscious)" on the npc name.

[ v1.5.0 ] 2018/08/26
- Now the mod can also show "empty" on the "loot/open/steal" button when the content is empty.
- Adapted to Game-Version 1.6.2

[ v1.4.0 ] 2018/06/09
- Now the mod is compatible with DLC "From The Ashes".
  This fixes the bug "no writing in the ledger" from FLC "From The Ashes".
- Adapted to Game-Version 1.6

[ v1.3.4 ] 2018/06/09
- adapted to Game-Version 1.5

[ v1.3.3 ] 2018/04/25
- adapted to Game-Version 1.4.3

[ v1.3.2 ] 2018/04/10
- adapted to Game-Version 1.4.2
  
[ v1.3.1 ] 2018/04/08
- fixed wrong translated words of polish language

[ v1.3.0 ] 2018/04/07
- added loot info on npc's (male, female)

[ v1.2.0 ] 2018/04/04
- added loot info on animals (Hare, Cow etc.)

[ v1.1.1 ] 2018/03/31
- fixed wrong translated words of czech language

[ v1.1.0 ] 2018/03/30
- adapted to Game-Version 1.4.1

[ v1.0.3 ] 2018/03/30
- added Mod depency CLAM
- added chineses translation
- added czech translation
- added ﻿polish translation
- changed description 

[ v1.0.2 ] 2018/03/26
- added spanish translation
- added italian translation
- added russian translation

  [ v1.0.1 ] 2018/03/25
- added french translation
- added support for upcoming patch 1.4

[ v1.0.0 ] 2018/03/25
- Initial Release / Work in progress




Credits
=======
In alphabetic order:

War Horse Studios:
Thanks for this great Game.

Now in alphabetic order:

guven34:
Thanks for the bug report and your help to send me necessary files for review.

lionroot:
Thanks for your help to send me necessary files for review.

daJbot Pyros Software:
Thanks for Guidelines ReadMe and Description Page generator.
Licensing/Legal

War Horse Studios:
Thanks for your help finding the solution for the "empty" feature.


This mod is released under the Creative Commons License - CC BY-NC-SA
http://creativecommons.org/licenses/by-nc-sa/3.0/
