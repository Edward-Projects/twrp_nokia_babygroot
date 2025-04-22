# TWRP Device configuration for Nokia 8.3 5G

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (1x2.4 GHz Kryo 475 Prime & 1x2.2 GHz Kryo 475 Gold & 6x1.8 GHz Kryo 475 Silver)
CHIPSET | Qualcomm SM7250 Snapdragon 765G
GPU     | Adreno 620
Shipped Android Version | 10
Memory  | 6 / 8GB
Storage | 64 / 128GB
Battery | 4500 mAh
Dimensions | 171.9 x 78.6 x 9 mm
Display | 1080 x 2400 pixels, 20:9 ratio, 6.81 inches, IPS LCD
Rear Camera  | 64 MP, f/1.9, (wide) + 12 MP, f/2.2, 120˚ (ultrawide) + 2 MP, (macro) + 2 MP, (depth)
Front Camera | 24 MP, f/2.0, (wide)

![Device Picture](https://fdn2.gsmarena.com/vv/pics/nokia/nokia-83-5g-1.jpg)

```sh
. build/envsetup.sh
lunch twrp_babygroot-eng
mka recoveryimage -j$(nproc --all) 
```

## Credits
- [TWRP](https://twrp.me)
- [TWRP device tree of OnePlus Nord](https://github.com/TeamWin/android_device_oneplus_avicii)

### Copyright
 ```
  /*
  *  Copyright (C) 2013-21 The OmniROM Project
  *
  * This program is free software: you can redistribute it and/or modify
  * it under the terms of the GNU General Public License as published by
  * the Free Software Foundation, either version 3 of the License, or
  * (at your option) any later version.
  *
  * This program is distributed in the hope that it will be useful,
  * but WITHOUT ANY WARRANTY; without even the implied warranty of
  * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  * GNU General Public License for more details.
  *
  * You should have received a copy of the GNU General Public License
  * along with this program.  If not, see <http://www.gnu.org/licenses/>.
  *
  */
  ```