# About
A test. A trial. Just something for fun.

I am not going to try to port other spells from DOS2 to BG3 right now and I am not taking requests.

The passive, Leech, is attached to the "_Hero" record. So any starting player character will automatically have it. NPCs have no access to it, but companions will, because they also use that record. This part is a WIP, thank you to amanemonesia on Nexusmods for pointing that out to me!

The spell, Raining Blood, is available in all default Level 1 spell lists. I have not made patches for class mods yet.

Shouldn't conflict with anything. :fingers-crossed:

~enjoy

## How did I do this?
Leech is an edited version of the Wood Woad's regeneration passive.
Raining Blood is Create Water with the surface changed GROUND:CreateSurface(4,0, Blood) and ApplyStatus(BLEEDING,100,1) added. The vocal component was also changed to data "VocalComponentSound" "Vocal_Component_DamageNecroticVamparic".

Vocal Components are found in two places:
Assets/Public/Shared/Assets/Sound/SPELLVOCAL.txt and Shared/Public/Shared/Content/Assets/Sounds/Spellvocal/[PAK]_Spellvocal/_merged.lsx

## Installation
Requirements:
* [Patch 3 Modfixer](https://www.nexusmods.com/baldursgate3/mods/141)
* [Baldur's Gate 3 Mod Manager](https://github.com/LaughingLeader/BG3ModManager/releases)

If you prefer to install manually or are playing on Linux (like I am) here is the information for your modsettings file:
* Folder: Leech_RainingBlood
* Name: Leech_RainingBlood
* UUID: da3458a6-1ce3-4514-8b8f-50fcbd36cd4e

## Acknowledgements
Labotor pieced together a blank spell background for me to use. She and ACatInABox also helped me with my mod image, because I am not a graphic designer.
LostSoulMan provided invaluable coding knowledge.

This mod is unofficial fan content, not approved/endorsed by Larian Studios. Portions of the materials used are property of Wizards of the Coast LLC and Larian Studios Games ltd.

## Credits
* [LSLIB](https://github.com/Norbyte/lslib/releases)
* [Modding Tool](https://github.com/ShinyHobo/BG3-Modders-Multitool/releases)
* [UUID Generator](https://www.uuidgenerator.net/)
* [Larian Studios](https://store.steampowered.com/app/1086940/Baldurs_Gate_3/); for allowing their game to be moddable (is moddable a word? it is now.)

# [Join us on Discord!](https://discord.gg/JnPcvGr)
![DbtR Logo](https://i.ibb.co/WBQyJMn/button-hr-purple.png)
