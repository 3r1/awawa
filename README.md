# awawa filter

![image previewing poe2_item_filter](/preview_v2.png)

awawa filter is a PoE2 highlight filter that makes awawa noises on item drops and is color-themed around Jelly Hoshiumi's palette.

Features:
- highlight for all the important stuff
- socket & quality highlighting
- awawa sounds (and maybe some screaming)

## Install
Grab the latest release from https://github.com/3r1/awawa/releases

**Windows**: extract awawa_filter_sounds.zip into Poe2 game Documents folder alongside `.filter` file(s) as desired

`Documents\My Games\Path of Exile 2`

**Linux**: extract and place files into poe2 steam wineprefix

`Steam/steamapps/compatdata/2694490/pfx/drive_c/users/steamuser/Documents/My Games/Path of Exile 2`

## Filter versions
awawa lite filter is the recommended highlighting-only filter that should serve you well for the entire game, unless you desire to hide certain loot.

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
- does not hide jewellery or socketed & quality items
- scaling hiding of magic & normal items substantially lower than AreaLevel
- scaling waystone & gem highlights (no icon/sound for low level gems)
- hide 0 qual flasks after tier 6

### awawa strict filter
- for those who know what they're doing & don't want to see normal/magic items
- awawa sounds, highlighting, and strict hiding
- hide gold stacks under 100
- everything in awawa regular
- hide ALL normal & magic items and charms
- does not hide jewellery or socketed & quality items

## Filterblade module
There is a filterblade awawa module with sounds & color theming.

Using this module link you may choose your own strictness: https://www.filterblade.xyz/?profile=Elaroz&saveState=AJ22P5YRFGTS2K&isPreset=true&game=Poe2&preview=true

If you do not yet have the filter sounds, grab them from: https://github.com/3r1/awawa/releases/download/3.0/awawa_filter_sounds.zip

## Todo
- update coloring for new items added in 0.2.0
- make sure it works

## Credits/Thanks
- core filter inspired from [NeverSink](https://github.com/NeverSinkDev/NeverSink-PoE2litefilter)
- voice clips from [Jelly Hoshiumi](https://youtube.com/@JellyHoshiumi)
- made in compliance with Phase Connect's [fan works guidelines](https://phase-connect.com/fan-work-guidelines/)

