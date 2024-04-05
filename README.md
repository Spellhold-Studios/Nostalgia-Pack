# Nostalgia Pack
**A Spellhold Studios mod for Baldur's Gate: Enhanced Edition**

<br>

**Author: [Andrea C.](http://www.shsforums.net/user/7164-andrea-c/)**

**Download: [Spellhold Studios](http://www.shsforums.net/files/file/1283-nostalgia-pack/) | [GitHub](https://github.com/SpellholdStudios/Nostalgia-Pack/releases)**

**Forum: [Spellhold Studios](http://www.shsforums.net/forum/684-nostalgia-pack/) | [Beamdog](https://forums.beamdog.com/discussion/82532/bg-ee-bgii-ee-nostalgia-pack-putting-the-bg-back-in-bg-ee)**

## Overview
This mod has had a very, very long gestation. It started way back in 2012-2013, when BG:EE was released and lacked the nostalgic punch I was expecting it to pack. No stony AD&D FR-inspired UI, no BG1 sprites & paperdolls, no BG casting sounds and voices... the list goes on. So I started looking into ways to bring all that stuff back into the Enhanced Editions and yes, it took this long to accomplish half of what was originally planned. I hope you'll enjoy this nonetheless!

## Content
### Restore BG Character Sprites
The component that started it all. BG1 sprites may not be feature-complete owing to their lack of support for dual-wielding, but they still look leaps and bounds better than their BG2 counterparts—and they make no use of that crime against aesthetics that is sprite mirroring. Enjoy thus of this component, that brings those sprites back to BG:EE in all their non-mirrored, directional glory.

There are, however, a few caveats:
- Contrary to what happens in the classics, the Enhanced Editions will not CTD if you equip an off-hand weapon on a character with a BG1 sprite. However, no off-hand weapons and attack animations were ever made for these sprites, so you won't be able to *visually* dual-wield (mechanically you can.) If you equip the off-hand weapon first and the main-hand weapon second, the latter will display and visually perform all of the attacks; if you go the other way around, no weapon will show up and it'll look like your character is punching their enemies to death. In both cases, you get all mechanical perks of dual-wielding (extra attack, bonuses from items held in the off-hand, etc..)
- Dual-classing a character that has a BG1 sprite will result in the character's getting a BG2 sprite of the wrong class, race, sex or any combination thereof. There's a technical reason why this happens that I won't bore you with; if you dual-class, be ready to use EE Keeper to assign the correct sprite back to your character. (Note: in the classics this is taken care of by ToBEx AfterLife; alas, there's no way around it in the Enhanced Editions unless the engine was fixed at source, which I doubt will ever happen.)
- The game is hardcoded to assign a BG2 sprite to newly created characters. If you want your character to use a BG1 sprite, you'll need to save your game, open it in EE Keeper, and manually assign the sprite. (Note: in the classics this is taken care of by ToBEx AfterLife; alas, there's no way around it in the Enhanced Editions unless the engine was fixed at source, which I doubt will ever happen.)

**Note:** The mod offers the possibility to patch your existing saved games so that the characters therein are given a BG1 sprite. I do advise against it unless you know exactly what you are doing. If you patch your saved games, they will never work again without this component (or they will, but everyone who received a BG1 sprite will look like Sarevok.)

### Restore BG Paperdolls
If you're going to use BG1 sprites, you'll want the classic BG1 paperdolls to go with them (paperdolls in the Enhanced Editions are from 1PP.) Note that these are the BG1 paperdolls modified by Erephine to support displaying weapons in the off-hand. Because BG1 sprites cannot, however, only one weapon will ever display at a time. Either way, I secured permission from Erephine to use these and all credit should go to her.

### Restore BG Portraits and Colors
This is pretty much CamDawg's Continuos NPCs mod except it also restores the original BG1 colors to the characters affected. I actually made this component before CamDawg's released his mod and I left it here, but if you're using his mod of course you won't need this.

### Restore BG Item Icons & Appearance
This component ensures that all items that are common across the two games get their original BG icon and colors, whereas items that only existed in BG2 get their BG2 icon and colors. This component is necessary for the ultimate nostalgic experience because the Enhanced Editions applied 1PP wholesale across the board, which includes recolors of pretty much every item (and a few icon changes.) I've included a brute-froce icon dump from the classics as well because in the Enhanced Editions some item icons are way too tiny and this solves the problem (I won't bore you with the reason why.)

### Restore BG Flaming Fist Appearance
Siege of Dragonspear changed the color scheme of the Flaming Fist so they could assign it to some other army that came along to fight against the crusade. Why they couldn't simply give the new colors to the other army is beyond me. This component gives back the original red and white color scheme to all Flaming Fist characters, and assigns a cleric sprite to them to restore the original BG look (this includes Flaming Fist characters from Siege of Dragonspear.)

### Restore BG Amnian Guard Appearance
This component is for EET, which changes the appearance of the Amnian soldiers in Nashkel to that of the Amnian soldiers from SoA. I've never liked the latter look and I especially don't wanna see it when I play BG1, so here goes.

As of RC2 this component also affects BG:EE as the Amnian Guards would otherwise have a cleric sprite instead of the fighter sprite they had in classic BG.

### Restore BG Dimension Door Effect
In BG:EE, Dimension Door got the same animation as Shadow Door. However in BG1 it had its own animation that suits the spell better and, in my opinion, looks pretty spiffy. This component restores that animation with its accompanying sounds, courtesy of skellytz.

### Undo EE Changes
The Enhanced Editions brought forth a lot changes compared to the originals, ranging from very subtle to immediately noticeable. This component is about reversing these changes, and will be expanded over time as more changes are run into and reported.

Here's what it does so far:
- Remove extra items added to stores and characters that are not part of one of the new NPCs' storyline. This includes extra copies of items that were already there (e.g. Gauntlets of Weapon exprtise), new items added by the Enhanced Editions, and copies of BG2 items (e.g. katanas, wakizashis, ninja-tos.)
- Restore original stock in the Friendly Arm store.
- Restore original stock in the Thunderhammer Smithy.
- Restore original stock in the Feldepost Inn store.
- Restore classic Poison Weapon behavior.
- Change the save vs. Death penalty from the Claw of Kazgaroth back to +3.

If you're planning a character that wields eastern weapons such as katanas, wakizashis, and nina-tos, this component may not be for you.

## FAQ
> Why no UI component?

This is now covered by K4f4r's [Classic BG UI](https://forums.beamdog.com/discussion/83508/mod-classic-bg-ui-v1-6) mod.

> Why no sound component?

Because skellytz's [Infinity Sounds](https://github.com/skellytz/infinity-sounds) already handles that.

## Best Enjoyed With
- Sam.'s [BGEE Classic Movies](https://github.com/Sampsca/BGEE-Classic-Movies)
- Argent77's [Convenient EE NPCs](https://github.com/Argent77/A7-NoEENPCs)
- skellytz's [Infinity Sounds](https://github.com/skellytz/infinity-sounds)
- K4f4r's [Classic BG UI](https://forums.beamdog.com/discussion/83508/mod-classic-bg-ui-v1-6)

## Acknowledgements
I'm new to modding and, let's face it, not very good at it.

This mod would not exist without the generous, friendly help of people like Scott Brooks, Erephine, CamDawg, Miloch, Cuv, Troodon80, skellytz (who single-handedly coded the Dimension Door component), kjeron, Argent77, Liam Esler.

Finally, thanks to Beamdog for reviving interest in these games, birthing a new generation of modders while drawing veterans back, and still patching the Enhanced Editions almost ten years after their initial release. 

## Version History
**v1.1 (4 April 2024)**
- Fixed an issue with spell scrolls receiving a generic letter icon when installing component "Restore BG Item Icons & Appearance" 
- Fixed issues with component "Undo EE Changes" that prevented installation on BGII:EE

**v1.0 (8 November 2023)**
- Fixed a bug that prevented certain items from being patched
- Fixed incorrectly displayed spell scroll icons in the inventory
- Added code to prevent winged sprites from being patched, as BG1 sprites don't support wings

**RC4 (27 July 2021)**
- Initial GitHub release
