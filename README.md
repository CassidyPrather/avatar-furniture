# Virtual Inebriation System

Feature-rich infrastructure for environmental-style props on avatars.

## Dependencies

### Packages

VRChat packages must be managed with the [VRChat Creator Companion (VCC)](https://vcc.docs.vrchat.com/).
VRLabs VCC listings are best aquired through [the organization website](https://vrlabs.dev/packages/).

### Asset Bundles

These dependencies must be "drag and dropped" into the root project's asset directory. They are unmanaged by package managers, and so will not recieve automatic updates.

* [WorldSync](https://github.com/JuzoVR/WorldSync) version ["6.15.2024"](https://github.com/JuzoVR/WorldSync/releases/tag/Release_6-15-2024) - that's a US-format date, **not** a [semver](https://semver.org/)

## Installation

1. Install the packages in [#Dependencies](#dependencies)
2. [Add this package's listing to the VCC.](https://cassidyprather.github.io/avatar-syringe/)
3. Instantiate prefab of choice on the root of the avatar.
4. Override parent constraint sources as required/desired with locations on your avatar (e.g. an empty game object with a static offset from your hand for hand-based placement).

## Legal

Copyright 2024 Cassidy Prather <pratherea@gmail.com>

Everything in this repository henceforth is licensed under [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html) (See `COPYING`) unless otherwise specified.

## Credits

* Template files from https://github.com/vrchat-community/template-package ([VRCHAT DISTRO LICENSE FILE](https://github.com/vrchat-community/template-package/blob/d9cf13fe9f56867cbf7315a4dbbf1901bc1537ec/Packages/com.vrchat.core.bootstrap/License.md))
* Icons from https://game-icons.net/ Creative Commons 3.0 BY license.
