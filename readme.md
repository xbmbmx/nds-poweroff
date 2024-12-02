<p align="center">
    <img style="border: 3px solid lightgray; padding: .5em; border-radius: 15%;" src="https://github.com/xbmbmx/nds-poweroff/blob/63b2d1679a931c9f7078ce50e1e7cf4b72d7ceeb/icon.png?raw=true"/>
</p>

# Poweroff

A _very_ simple application that shuts your console off.

Built with [BlocksDS](https://github.com/blocksds/sdk).

## Installation

Head over to the [releases section](https://github.com/xbmbmx/nds-poweroff/releases) of this repository and download the latest `poweroff.nds` file.

To use this application, simply boot it using your favourite launcher.
If loaded correctly, this application should power your device off.

## Purpose

I created this application to power off the console without having to use the power button.

It can be used as a `BOOT.nds` file for homebrew applications that use it to go back to the launcher. Using `poweroff.nds` as a `BOOT.nds` file will cause these types of homebrew to turn the console of instead of returning to a launcher.

Take note that for this to work, you may need to adapt your Unlauch settings to no longer use `BOOT.nds` when no buttons are held, as that would cause your console to immediately turn off after booting.
