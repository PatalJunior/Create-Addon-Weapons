# To add new addon weapons do

## Add to qb-core/shared/weapons.lua
#### OBS: Check default weapons and copy from there

```lua

[`weapon_m4a4`] = {['name'] = 'weapon_m4a4', ['label'] = 'M4A4', ['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
[`weapon_awp`] = {['name'] = 'weapon_awp', ['label'] = 'AWP', ['ammotype'] = 'AMMO_SNIPER',	['damagereason'] = 'Sniped / Picked off / Scoped'},

```


## Add to qb-core/shared/items.lua
#### OBS: Check default weapons and copy from there

```lua

['weapon_awp'] = {['name'] = 'weapon_awp', ['label'] = 'AWP', ['weight'] = 1000, ['type'] = 'weapon', 	['ammotype'] = 'AMMO_SNIPER', ['image'] = 'weapon_awp.png', ['unique'] = true, ['useable'] = false, ['description'] = 'A AWP'},
['weapon_m4a4'] = {['name'] = 'weapon_m4a4', ['label'] = 'M4A4', ['weight'] = 1000, ['type'] = 'weapon', ['ammotype'] = 'AMMO_RIFLE', ['image'] = 'weapon_m4a4.png', ['unique'] = true, ['useable'] = false,['description'] = 'A M4A4'},

```



## Add to qb-weapons/config.lua


**Go to WeaponAttachments and add weapon attachments**

#### OBS: Check default weapons and copy from there
#### OBS2: component names are in ReadMe.txt that you send me with weapons

```lua

WeaponAttachments = {

    ['WEAPON_AWP'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_AWP_CLIP_01',
            item = 'm4a4_defaultclip',
            type = 'clip',
        },
        ['scope'] = {
            component = 'COMPONENT_AT_AWP_SCOPE_LARGE',
            item = 'awp_scope',
        },
        ['redlinefinish'] = {
            component = 'COMPONENT_AWP_VARMOD_REDLINE',
            item = 'awp_redlinefinish',
        },
        ['mikufinish'] = {
            component = 'COMPONENT_AWP_VARMOD_MIKU',
            item = 'awp_mikufinish',
        },
        ['lightningfinish'] = {
            component = 'COMPONENT_AWP_VARMOD_LIGHTNING',
            item = 'awp_lightningfinish',
        },
        ['beastfinish'] = {
            component = 'COMPONENT_AWP_VARMOD_BEAST',
            item = 'awp_beastfinish',
        },
        ['dragonfinish'] = {
            component = 'COMPONENT_AWP_VARMOD_DRAGON',
            item = 'awp_dragonfinish',
        },
        ['corticerafinish'] = {
            component = 'COMPONENT_AWP_VARMOD_CORTICERA',
            item = 'awp_corticerafinish',
        },
        ['asiimovfinish'] = {
            component = 'COMPONENT_AWP_VARMOD_ASIIMOV',
            item = 'awp_asiimovfinish',
        },
    },


    ['WEAPON_M4A4'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_M4A4_CLIP_01',
            item = 'marksmanrifle_defaultclip',
            type = 'clip',
        },
        ['dkingfinish'] = {
            component = 'COMPONENT_M4A4_VARMOD_DKING',
            item = 'm4a4_dkingfinish',
        },
        ['techfinish'] = {
            component = 'COMPONENT_M4A4_VARMOD_TECH',
            item = 'm4a4_techfinish',
        },
        ['hazardfinish'] = {
            component = 'COMPONENT_M4A4_VARMOD_HAZARD',
            item = 'm4a4_hazardfinish',
        },
        ['hunterfinish'] = {
            component = 'COMPONENT_M4A4_VARMOD_HUNTER',
            item = 'm4a4_hunterfinish',
        },
        ['howlfinish'] = {
            component = 'COMPONENT_M4A4_VARMOD_HOWL',
            item = 'm4a4_howlfinish',
        },
        ['griffinfinish'] = {
            component = 'COMPONENT_M4A4_VARMOD_GRIFFIN',
            item = 'm4a4_griffinfinish',
        },
        ['zebrafinish'] = {
            component = 'COMPONENT_M4A4_VARMOD_ZEBRA',
            item = 'm4a4_zebrafinish',
        },
        ['desertfinish'] = {
            component = 'COMPONENT_M4A4_VARMOD_DESERT',
            item = 'm4a4_desertfinish',
        },
        ['asiimovfinish'] = {
            component = 'COMPONENT_M4A4_VARMOD_ASIIMOV',
            item = 'm4a4_asiimovfinish',
        },

}

```
