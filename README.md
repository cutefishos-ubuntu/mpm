<div align="center">
    <h1>mpm</h1>
    <img height="150" src="https://dl.uploadgram.me/6119620f0356eh?raw">
</div>
## Overview 
mpm is a reference package manager for the [MPR](https://mpr.hunterwittenborn.com/), making it easier to build and install packages from MPR PKGBUILDs.

Currently, mpm has the following features:

- Searching
- Installing
- Updating
- Cloning

The following features are planned to be added at some point:

- Development (`-git`) package updates
- MPR dependencies

## Installation and usage
makedeb [PKGBUILD](https://raw.githubusercontent.com/cutefishos-ubuntu/mpm/main/makedeb/PKGBUILD)

Help with available commands can also be found after installation with `mpm --help`.

**Commands:**  
- install - Install packages  
- update/upgrade - Check for and install updates  
- search - Search for a package  
- clone - Clone packages  
  
**Options:**  
- -d, --directory Specifies an (empty) output directory when using the 'clone' command  
- -p, --parents Create parent directories if they don't exist when using the '-d' option  
- -h, --help Bring up this help menu and exit  
- --verbose Print (very) detailed logging
