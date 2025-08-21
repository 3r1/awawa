# awawa filter

![image previewing poe2_item_filter](/preview_v3.png)

**awawa filter** is a PoE2 filter that makes awawa noises on item drops and is themed around Jelly Hoshiumi's color palette.

Features:
- highlight and colors for all the important stuff
- socket and quality highlighting
- awawa sounds (and maybe some screaming)

## Install
Grab the latest release from https://github.com/3r1/awawa/releases

**Windows**: extract `awawa_filter_sounds.zip` into Poe2 game Documents folder alongside `.filter` file(s) as desired

`Documents\My Games\Path of Exile 2`

**Linux**: extract and place files into poe2 steam wineprefix

`Steam/steamapps/compatdata/2694490/pfx/drive_c/users/steamuser/Documents/My Games/Path of Exile 2`

## Filter versions
### awawa lite filter
- for campaign and early-mid endgame
- awawa sounds and highlighting
- beam for gold stacks over 500
- in endgame waystones, opacity of low level items is reduced 

### awawa regular filter
- for endgame
- awawa sounds and highlighting
- hide wisdom scrolls
- gold stacks under 100 are smol
- 1k+ gold stacks have a map highlight
- in waystones, hide low level normal & magic items (if DropLevel<50 && AreaLevel>70)
- does not hide jewellery, socketed & quality items, socketables, or currency
- scaling hiding of magic & normal items substantially lower than AreaLevel
- scaling waystone & gem highlights (no icon/sound for low level gems)
- hide 0 qual flasks after tier 6

### awawa strict filter
- for those who know what they're doing & don't want to see normal/magic items
- awawa sounds, highlighting, and strict hiding
- everything in awawa regular
- 2k gold has beams, 5k gold shows on map, hide gold stacks under 500
- hide ALL normal & magic items and charms
- hides socketed & quality items that give <2 salvage
- does not hide jewellery, socketables, or currency

## Filterblade module
There is a filterblade awawa module with sounds & color theming.

Using this module link you may choose your own strictness: https://www.filterblade.xyz/?profile=Elaroz&saveState=AJ22P5YRFGTS2K&isPreset=true&game=Poe2&preview=true

If you do not yet have the filter sounds, grab them from: https://github.com/3r1/awawa/releases/download/3.0/awawa_filter_sounds.zip

## Todo
- pray the filter works on 0.3.0 release on August 29th
- post 0.3.0, update currency tiers and currency rebalancing
  - support "normal", greater, perfect, also some Lesser
- update colors for jewels, runes, charms, relics, keys, tablets, logbooks, baryas, ultis
- revisit coloring of "league" items -- some disappear a little in currency tiers, potential gradient for stacked items
- create color tiers for UnidentifiedItemTier items
- potentially tweak gear coloring

## Credits/Thanks
- core filter inspired from [NeverSink](https://github.com/NeverSinkDev/NeverSink-PoE2litefilter)
- voice clips from [Jelly Hoshiumi](https://youtube.com/@JellyHoshiumi)
- made in compliance with Phase Connect's [fan works guidelines](https://phase-connect.com/fan-work-guidelines/)

