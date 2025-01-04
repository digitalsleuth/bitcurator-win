
# BitCurator for Windows Installer (BitCurator-WIN)

BitCurator for Windows Installer

![GitHub release (with filter)](https://img.shields.io/github/v/release/digitalsleuth/bitcurator-win?style=flat&label=Latest%20BitCurator-WIN%20Release)

The design behind this is to use a barebones Windows 10 VM or a Windows machine (preferably 1909 and higher to support WSLv2).
Once configured, and activated (to support customization features), then you can use one of the installers to
install all of the packages.  

The installer is a graphical interface to click and choose which items you want, and to enter the settings you need

Check out the [Releases](https://github.com/digitalsleuth/BitCurator-WIN/releases) section for the most up-to-date installers.

## BitCurator Customizer

**FIRST OFF - Requires .NET 8.0 Desktop Runtime**
**If you do not have it, you will be prompted to install at execution**

The customizer tool gives you the following features:

- Point and click to choose which tools you want installed in your distro (instead of just choosing them all)
- Checkboxes to choose if you want the WSLv2 BitCurator Distro installed during the process, or click `WSL Only` to install it at a later date
- Save your current selections in a custom SaltStack State file for your own purposes or record
- Identify the current version of the BitCurator environment with a single click
- Check for updates to the Customizer
- Graphically enter any settings you need!

# Issues

All issues should be raised [here](https://github.com/digitalsleuth/BitCurator-WIN/Issues)
