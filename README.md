[![Build status](https://ci.appveyor.com/api/projects/status/0xdrlreloetyyt1c?svg=true)](https://ci.appveyor.com/project/System32Booster/pcsxv) [![CI](https://github.com/InoriRus/Kyty/actions/workflows/ci.yml/badge.svg)](https://github.com/InoriRus/Kyty/actions/workflows/ci.yml)

# PCSXV
## Kytv revival project (Placeholder)

---

Licensed under the MIT license.

---
It is possible to run some simple games for PS4 and homebrews for PS5

There maybe graphics glitches, crashes, freezes and low FPS. It's OK for now.

Features that are not implemented:
- Audio input/output
- MP4 video
- Network
- Multi-user

Path to Savedata folder is hardcoded and can't be configured.
System parameters (language, date format, etc.) are also hardcoded.

---
### Get official firmware
[PS4](https://www.playstation.com/en-us/support/hardware/ps4/system-software/)

[PS5](https://www.playstation.com/en-us/support/hardware/ps5/system-software/)

---
### Screenshots

---
### Building
Supported platforms:
- Windows 10 x64

Toolchains:
- Visual Studio + clang-cl + ninja
- Eclipse CDT + mingw-w64 + gcc/clang + ninja/mingw32-make

Supported versions:
Tool                            | Version
:------------                   | :------------
cmake                           |3.12
Visual Studio 2019              |16.10.3
clang                           |12.0.1
clang-cl                        |11.0.0
gcc (MinGW-W64 x86_64-posix-seh)|10.2.0
ninja                           |1.10.1
MinGW-w64                       |8.0.0
Eclipse CDT                     |10.3.0
Qt                              |5.15.0

Define environment variable named Qt5_DIR pointing to the proper version of Qt

MSVC compiler (cl.exe) is not supported!

External dependencies:
* Vulkan SDK 1.2.198.1
* Qt 5.15.0
