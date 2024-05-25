# Disable Low Ram Flag

[![GitHub Release](https://img.shields.io/github/v/release/sekedus/disable-low-ram?label=Version)](https://github.com/sekedus/disable-low-ram) [![GitHub Release Date](https://img.shields.io/github/release-date/sekedus/disable-low-ram?label=Updated)](https://github.com/sekedus/disable-low-ram/releases) [![Minimum Magisk Version](https://img.shields.io/badge/minMagisk-20.4-00AF9C.svg?logo=Magisk)](https://github.com/sekedus/disable-low-ram?tab=readme-ov-file#requirements) [![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/sekedus/disable-low-ram/total?logo=DocuSign&label=Downloads)](https://github.com/sekedus/disable-low-ram/releases/latest) [![GitHub License](https://img.shields.io/github/license/sekedus/disable-low-ram?logo=gnu&label=License)](https://github.com/sekedus/disable-low-ram/blob/main/LICENSE)

This magisk module disable `ro.config.low_ram` flag on Android Go devices.

Low-Ram flag is typically enabled on smartphones with less than 2 GB of RAM to reduce memory and space usage, [more](https://android.stackexchange.com/a/228854).

## What it does

This module uses the magisk tool "**resetprop**" to modify Low-Ram property found in **vendor/build.prop** to:

`ro.config.low_ram=false`

## Requirements

* Magisk **v20.4** or higher
 
## Installation

1. Open the Magisk App and select the **Modules** menu.
3. Click **Install from storage** button and select this module's .zip file.
4. Wait for the installation process to complete and click **Reboot**.

## Credits

- [Magisk](https://github.com/topjohnwu/Magisk)
- [MMT-Extended](https://github.com/Zackptg5/MMT-Extended)

## License

This module is licensed under the GNU General Public License v3.0. See the [LICENSE](https://github.com/sekedus/disable-low-ram/blob/main/LICENSE) file for more details.
