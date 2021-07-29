![Website](https://img.shields.io/website?down_color=lightgray&down_message=offline&style=flat-square&up_color=green&up_message=online&url=https%3A%2F%2Fzenithos.org)
# ZealOS

The Zeal Operating System is a modernized, professional fork of the 64-bit Temple Operating System. Guiding principles of development include transparency, full user control, and adherence to public-domain/open-source implementations.

![](/screenshots/screenshot2.png)

ZealOS strives to be simple, documented, and require as little of a knowledge gap as possible. One person should be able to comprehend the entire system in at least a semi-detailed way within a few days of study.
Simplify, don't complicate; make accessible, don't obfuscate.

> The CIA encourages code obfuscation. They make it more complicated than necessary.\
—Terry A. Davis

Features in development include:
  - Fully-functional AHCI support
  - [32-bit color VBE graphics](https://github.com/TempleProgramming/HolyGL)
  - Network card drivers and a networking stack


Changes include:
  - 60 FPS
  - VBE graphics with variable resolutions
  - 440Hz 'A' tuning changed to 432Hz
  - HolyC -> CosmiC
  - System-wide renaming for clarity
  - Removed shift-space mechanism
  - Reformatted code for readability
  - Added comments and documentation

## Getting started

### Prerequisites

- For running in a VM: Intel VT-x/AMD-V acceleration enabled in your BIOS settings. (Required to virtualize any 64-bit operating system properly.)
- Working knowledge of the C programming language.

Every commit contains a "ZealOS-YYYY-MM-DD-HH_MM_SS.iso" in the root of master, which is a timestamped ISO build of that commit.

This is basically a read-only repository. Everything happens inside the OS, as intended by Terry. After you've installed the latest release in a VM, you can make changes to the source. Once you've made your changes, you can make copies of the relevant files and put them into a folder, along with some kind of notes as to what you've done either as a DolDoc document or in the pull request later. You can then make a RedSea ISO file out of that folder by running `RedSeaISO("MyChanges.ISO", "/Home/Folder");`. Export the contents of the VM hard drive in whatever OS-specific way you have to (there are scripts in the root of the repo), grab the ISO, and send it; a pull request attachment with the zipped ISO would work fine.

## Background

In around November of 2019, [Z3N1THM4N](https://github.com/Z3N1THM4N) decided to create [ZenithOS](https://github.com/ZenithOS/ZenithOS) to continue Terry's work in a direction that would make it a viable operating system while still keeping the innovative and divine-intellect ideas and design strategies intact.

At first, development occurred exclusively inside a VM and ISOs were occasionally generated as official releases. It was scrapped and restarted from scratch.\
Releases of the "old" ZenithOS are currently archived on the `mega.nz` website:
  - [Previous Releases](https://mega.nz/#F!ZIEGmSRQ!qvL6Wk6THzE-dazkfT6N3Q)

The repository was removed in August of 2020, and reuploaded to [ZenithOS](https://github.com/ZenithOS/ZenithOS). The latest archived [front page](https://web.archive.org/web/20200811190005/https://github.com/VoidNV/ZenithOS/), [master.zip](https://web.archive.org/web/20200811190054/https://codeload.github.com/VoidNV/ZenithOS/zip/master), and [related links](https://web.archive.org/web/*/https://github.com/VoidNV/ZenithOS/*) can be found on archive.org.

In July of 2021, ZealOS was forked from ZenithOS.

## Screenshots

System Report, Z Splash and AutoComplete, with Stars wallpaper

![](/screenshots/screenshot3.png)

32-bit color!

![](/screenshots/screenshot1.png)
