# 6str-carpack

## Installation

* Take this and place into your resources folder

* Place this in your server.cfg
```
ensure 6str-carpack
```

* Restart Server

# QBCore Snippets

## Vehicles.Lua

* Place this in your qb-core/shared/vehicles.lua

```lua
	-- 6STR Customs
	['gauntlet6str'] = {
		['name'] = 'Gauntlet 6STR Custom',
		['brand'] = 'Bravado',
		['model'] = 'gauntlet6str',
		['price'] = 300000,
		['category'] = 'tuner',
		['hash'] = `gauntlet6str`,
		['shop'] = '6str',
	},
	['tempesta2'] = {
		['name'] = 'Tempesta Widebody',
		['brand'] = 'Pegassi',
		['model'] = 'tempesta2',
		['price'] = 300000,
		['category'] = 'tuner',
		['hash'] = `tempesta2`,
		['shop'] = '6str',
	},
	['schwarzer2'] = {
		['name'] = 'Schwartzer Widebody',
		['brand'] = 'Benefactor',
		['model'] = 'schwarzer2',
		['price'] = 300000,
		['category'] = 'tuner',
		['hash'] = `schwarzer2`,
		['shop'] = '6str',
	},
	['ruiner6str'] = {
		['name'] = 'Ruiner 450 Custom',
		['brand'] = 'Imponte',
		['model'] = 'ruiner6str',
		['price'] = 300000,
		['category'] = 'tuner',
		['hash'] = `ruiner6str`,
		['shop'] = '6str',
	},
	['yosemite6str'] = {
		['name'] = 'Drift Yosemite',
		['brand'] = 'Declasse',
		['model'] = 'yosemite6str',
		['price'] = 300000,
		['category'] = 'tuner',
		['hash'] = `yosemite6str`,
		['shop'] = '6str',
	},
	['sentinel6str2'] = {
		['name'] = 'Sentinel Classic Custom',
		['brand'] = 'Ubermacht',
		['model'] = 'sentinel6str2',
		['price'] = 300000,
		['category'] = 'tuner',
		['hash'] = `sentinel6str2`,
		['shop'] = '6str',
	},
	['ellie6str'] = {
		['name'] = 'Drift Ellie',
		['brand'] = 'Vapid',
		['model'] = 'ellie6str',
		['price'] = 300000,
		['category'] = 'tuner',
		['hash'] = `ellie6str`,
		['shop'] = '6str',
	},
	['zr3806str'] = {
		['name'] = 'ZR380 6STR Custom',
		['brand'] = 'Annis',
		['model'] = 'zr3806str',
		['price'] = 300000,
		['category'] = 'tuner',
		['hash'] = `zr3806str`,
		['shop'] = '6str',
	},
	['tampa4'] = {
		['name'] = 'Drift Tampa',
		['brand'] = 'Declasse',
		['model'] = 'tampa4',
		['price'] = 300000,
		['category'] = 'tuner',
		['hash'] = `tampa4`,
		['shop'] = '6str',
	},
```

## QB-VehicleShop

* Add this to your qb-vehicleshop config.lua

```lua
    ['6str'] = {
        ['Type'] = 'managed',  -- meaning a real player has to sell the car
        ['Zone'] = {
            ['Shape'] = {
                vector2(120.73, -3050.16),
                vector2(128.49, -3050.18),
                vector2(128.6, -3044.34),
                vector2(120.90, 3044.35),
            },
            ['minZ'] = 5.04,
            ['maxZ'] = 9.04,
            ['size'] = 2.75, -- size of the vehicles zones
        },
        ['Job'] = '6str', -- Name of job or none
        ['ShopLabel'] = '6STR Custom Tuners',
        ['showBlip'] = false,  -- true or false
        ['blipSprite'] = 326,  -- Blip sprite
        ['blipColor'] = 3,  -- Blip color
        ['Categories'] = {
            ["tuner"] = "Tuner",
        },
        ['TestDriveTimeLimit'] = 0.5,
        ['Location'] = vector3(140.46, -3030.47, 7.04),
        ['ReturnLocation'] = vector3(162.05, -3006.04, 5.96),
        ['VehicleSpawn'] = vector4(163.02, -3009.28, 5.94, 271.67),
        ['TestDriveLocation'] = vector4(163.02, -3009.28, 5.94, 271.67),
        ['ShowroomVehicles'] = {
            [1] = {
                coords = vector4(124.58, -3047.27, 6.04, 269.63),
                defaultVehicle = 'gauntlet6str',
                chosenVehicle = 'gauntlet6str'
            },
        },
    },
```

All Rights and Creation go to GTAWiseGuy. Visit https://www.gta5-mods.com/users/GTAWiseGuy for more!
