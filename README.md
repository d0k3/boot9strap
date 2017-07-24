Boot9strap (+bootonce support)
=====
![License](https://img.shields.io/badge/License-GPLv3-blue.svg)

Boot9/Boot11 code execution.

For more details, refer to the presentation [here](https://sciresm.github.io/33-and-a-half-c3/).

Install via [SafeB9SInstaller](https://github.com/d0k3/SafeB9SInstaller).

Launches "boot.firm" off of the SD card or CTRNAND. Hold Start + Select + X on boot to dump the bootroms/your OTP.

**Support for bootonce:**

[A9NC](https://github.com/d0k3/A9NC) and a certain feature in [GodMode9 v1.2.7](https://github.com/d0k3/GodMode9/releases/tag/v1.2.7) require bootonce support for full functionality. As bootonce support has since been [removed](https://github.com/SciresM/boot9strap/commit/ff16d59ff8fba431f5c5c934eea7db4d122eef1c) from the [official boot9strap source](https://github.com/SciresM/boot9strap), this fork exists. *Don't install this if you are not 100% sure you require bootonce support* - stay with the official release.

**Credits:**

[Normmatt](https://github.com/Normmatt): Theorizing the NDMA overwite exploit.    
[TuxSH](https://github.com/TuxSH): Help implementing bootrom payloads.    
[Luma3DS](https://github.com/AuroraWright/Luma3DS): Codebase used in the stage 2 FIRM loader.    

**Licensing:**

This software is licensed under the terms of the GPLv3.  
You can find a copy of the license in the LICENSE file.
