# Coffer

A file vault for Windows 11 and Linux. Coffer keeps your files encrypted and lets you sort them with folders, categories and tags.

## Install

**Windows:** download `Coffer-Setup-<version>.exe` from the newest release under **Releases** and run it. It installs for your Windows user only.

**Linux** (64-bit): pick one from the newest release.

- `coffer_<version>_amd64.deb` for Ubuntu, Debian, Linux Mint, Pop!_OS and others based on them: open it with your software installer, or run `sudo apt install ./coffer_<version>_amd64.deb`. **Use this one on Ubuntu 24.04 and newer.**
- `Coffer-<version>.AppImage` for any other distribution: make it executable (`chmod +x Coffer-<version>.AppImage`, or Properties → Allow executing as a program) and run it. Ubuntu 24.04 and newer block the sandbox AppImages of apps like Coffer need, so the AppImage may not start there; use the .deb.

On Linux, Coffer asks you to choose a start key the first time it opens, and it can't be turned off. Hiding Coffer from screenshots and screen sharing isn't available on Linux.

## Updates

Coffer checks this page for a new version when it starts. When there is one, the gear in Coffer gets a green dot, and **Settings → General** lets you download and install it (on Linux it opens the release page, where you download the new .deb or AppImage).

# Notices

This project is under active development and is tested by me alone, on my own files and use cases. The app works without any glaring issues, but it hasn't been fully tested, so depending on how you use it, you may run into bugs, mostly in usability. Although it is stable, the app is realistically in **BETA** and **is subject to change** without notice. It is **not** recommended for commercial use yet. Personal use should be fine, but I wouldn't rely on the app completely **yet**. If you use it, please keep a copy of your important files somewhere safe in case of file corruption or similar. (This hasn't happened to me at any point since development started on 29 September 2026.)

## How often Coffer updates

The first published version is 0.1.46.1; earlier versions were never released. An update can be anything from a small fix to a major new feature, which the version number shows: it reads OVERHAUL.MAJOR.MINOR.PATCH, a slightly modified form of semantic versioning. This also means several updates can come out in a single day, or only once in a while, depending on whether I make many small changes or fewer big ones. Either way, expect frequent updates. Coffer tells you when one is ready, and checking for updates is the only time the app goes online: nothing from your vault is sent or received, it only checks this page for a new version (you can turn this off in **Settings → General**).

## Helping this project

If you use this app, don't hesitate to suggest features or improvements, or to report bugs and other issues, either with **Report a bug or issue** and **Send a suggestion** in Coffer or under **Issues** on this page. I want to make not only a great app, but one that people can rely on. I am not looking for any co-developers.

## OS Support

Coffer runs on Windows 11 (and 10) and on 64-bit Linux. I don't own a Linux machine, so the Linux version is tested on a virtual Ubuntu system and by testers; reports from Linux users are especially welcome. There are no plans for macOS.

## Use of Artificial Intelligence

This app is being co-developed with **Claude Opus 5.5**:

While Claude does the heavy lifting, I personally design the whole app including its features and interfaces. Claude never decides on any major parts by itself, only minor changes like fixes and consistency it catches throughout the app. I alone decide what gets implemented, how it functions and how it looks. If I don't agree on what Claude has implemented (yes, I test every part for my use case), I make sure it gets done the way I believe it benefits the app the best. Claude can make suggestions and improvements to the technical side, but never actually decide on what the app does. Basically, it only does the coding, everything else is done entirely by a human (me).

If you dislike this approach, that is completely fine. I just don't want to hear it. I, like many others, hate AI-slop, but AI-assisted work is, in my opinion, just as much human as it is machine (like comparing CGI from films, it's a tool and how you use it is what is important, not just if you use it).
