---
weight: 3
title: Installing on macOS
slug: os-x
---

//TODO Get minimum macOS version
//TODO check with josh about what he means in step 4 with xcode and llvm

## Installation Instructions
Installing PROS on macOS could not be easier with our custom built installer! Just follow these instructions:

 1. Install [Python 3](https://www.python.org/downloads/)(Version 3.4 or higher) for macOS.  
 2. Download the [PROS installer](https://github.com/purduesigbots/pros/releases/tag/2.11.0) and run it. You will need to input an administrator's password, and must remain connected to the internet for the duration of installation. The installer will download Atom.app and the ARM toolchain to /Applications/PROS\_2.0, and will use pip3 to install the command line interface. You will be able to see the progress of the installer in a Terminal window automatically openned by the installer.   
 3. Open Atom (/Applications/PROS_2.0/Atom.app) and verify that PROS appears in the menu (Likely next to Help).   
 4. Congratulations! You have successfully installed PROS for macOS. If you want the Atom to be able to autocomplete your code, download either [Xcode](https://itunes.apple.com/us/app/xcode/id497799835?mt=12#) or [LLVM](http://llvm.org). Xcode is easier to install than LLVM, but you must open the application at least once and its command line tools must be installed.
