---
weight: 2
title: Installing on Windows
slug: windows
---

## Installation

PROS for Atom is the new best way to program for VEX Robotics. Getting started with PROS is easy on Windows.

To begin, [download](https://github.com/purduesigbots/pros/releases/latest) and run the installer. Please note
that an Internet connection is required throughout the installation process.

Most users will wish to complete the typical installation process, which will install the PROS Core components
(the PROS CLI and GCC toolchain) and Atom with Clang and the PROS plugin. If you already have Atom installed, then
the installer will simply add the PROS plugin to your existing Atom environment.

If VEX drivers haven't previously been installed, you will be prompted to install the official drivers released
by VEX.

Once the installation is completed, Atom can be started via the Start Menu or Desktop shortcut.


## Issues and Notes about Installation

### APM Failure
During some installations, Atom may not install correctly. This is best diagnosed by there not being shortcuts to
Atom after installation, or if `apm` isn't on PATH. If this is the case, you may need to manually install Atom by visiting
https://atom.io/download/windows. Once installed and Atom appears, you will be able to install the PROS plugin by pressing
**Win**+**R** and entering `apm install file-icons linter tool-bar tool-bar-main busy build platformio-ide-terminal pros`

### Installing alongside PROS for Eclipse
It is possible to install Atom alongside Eclipse, if you have previously installed Eclipse. However, the uninstall utility for
PROS for Eclipse will remove all the contents in `C:\Program Files\PROS`, so the new version of PROS will also be affected.
If you decide to remove Eclipse but want to keep the PROS Core components, either run the PROS for Eclipse uninstall utility and
reinstall/repair the new version of PROS or manually delete all files/folders in `C:\Program Files\PROS` except: `C:\Program Files\PROS\cli-64`
(or just `cli` if x86), `C:\Program Files\PROS\toolchain`, `C:\Program Files\PROS\updater.exe`, and `C:\Program Files\PROS\updater.ini`
