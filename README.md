# qb-clothing
ST4LTH Qb-Clothing Language Fix
-------------------------------------------------
An absolutely not inspired Clothing menu...
Jokes aside this is a Nopixel inspired css edit of qb-clothing with some new features, such as FOV zoom, Depth of field, Use your mouse to rotate ur character etc.

Thanks to QBCore for an pretty good clothing menu from the start and shoutout to Nopixel, They are too awesome.

U can disable the Depth of field by deleting "SetUseHiDof()" in Main.lua:877

My Mapping/dev discord https://discord.gg/8SUJN7JXk2

## Screenshots
![image]([https://i.imgur.com/eAMST1Y)]

# License

    QBCore Framework
    Copyright (C) 2021 Joshua Eger

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>

## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)

## Features
- Depth of field
- FOV zoom
- Configurable Ped Selection
- Detailed nose, chin, jaw, cheek etc. configuration
- Camera Rotating
- 3 Different Camera Angles
- Clothing Stores
- Barbers
- Job Locker Rooms (Configurable Outfit Presets)
- Saveable Outfits
- /hat, /glasses, /mask (See the commands section below)

### Commands
- /skin (Admin Only) - Opens the clothing menu
- /hat - Toggles the hat on/off
- /mask - Toggles the hmaskat on/off
- /glasses - Toggles the glasses on/off

## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Import `qb-clothing.sql` in your database
- Add the following code to your server.cfg/resouces.cfg
```
ensure qb-core
ensure qb-clothing
```

## Configuration
Please see config.lua

