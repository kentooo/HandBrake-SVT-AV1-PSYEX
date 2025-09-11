# HandBrake-SVT-AV1-HDR
### Purpose of the project
This project contains the patches needed to replace SVT-AV1 with SVT-AV1-HDR inside HandBrake.\
In addition, using GitHub Actions, nightly build of patched executables will be released.
### Instructions to patch/build
* Run ```patch.sh``` on linux. The script will patch the previously cloned HandBrake repo. If you want to also clone it you can use ```--clone``` argument.
* Compile for the desired platform using the commands provided on the HandBrake wiki ([BSD](https://handbrake.fr/docs/en/latest/developer/build-bsd.html), [Linux](https://handbrake.fr/docs/en/latest/developer/build-linux.html), [Mac](https://handbrake.fr/docs/en/latest/developer/build-mac.html), [Windows](https://handbrake.fr/docs/en/latest/developer/build-windows.html))
### Downloads and Build Status
| Operating System  | Download        | Build Status *1 |
| ----------------- | --------------- | ------------- |
| Windows           | [Download](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/releases/tag/win_hdr_build) | [![Windows Build](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/actions/workflows/nightly-win.yml/badge.svg)](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/actions/workflows/nightly-win.yml)  |
| macOS             | [Download](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/releases/tag/mac_hdr_build) | [![macOS build](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/actions/workflows/nightly-mac.yml/badge.svg)](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/actions/workflows/nightly-mac.yml)  |
| Linux (Flatpak)   | [Download](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/releases/tag/flatpak_hdr_build) | [![Flatpak Build](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/actions/workflows/nightly-flatpak.yml/badge.svg)](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/actions/workflows/nightly-flatpak.yml) |
| Ubuntu            | [Download](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/releases/tag/ubuntu_hdr_build) | [![Flatpak Build](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/actions/workflows/nightly-ubuntu.yml/badge.svg)](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/actions/workflows/nightly-ubuntu.yml) |
| Arch Linux        | [Download](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/releases/tag/arch_hdr_build) | [![Flatpak Build](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/actions/workflows/nightly-arch.yml/badge.svg)](https://github.com/kentooo/HandBrake-SVT-AV1-PSYEX/actions/workflows/nightly-arch.yml) |

*1 Please note that if a build is marked as failed, previous builds may still be available for download!
### Testing
I can currently only test the custom build on Windows. Help for testing on other platforms would be helpful.
### Special thanks
A special thanks to [vincejv (Docker container for HandBrake)](https://github.com/vincejv/docker-handbrake) from which I took inspiration for some patches.

