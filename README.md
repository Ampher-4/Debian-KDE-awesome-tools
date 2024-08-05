# Debian-KDE-awesome-tools

A collection of some awesome tool for KDE desktop Environment and Debian OS. Most of them can be found via searching on github repo.
when browsering, press `Home` key to back to **Index**.

### Index
[Multi-media-support](#multi-media-support)

[Entertainments](#entertainments)

[Power Toys](#power-toys)

[DE Customization](#de-customization)

[Funnies](#funnies)

## Multi-media-support
- **Pipewire** : audio server, provide better codec.
    - you may need to install libspa-0.2-bluetooth package to get bluetooth working.
- **Easy Effect** : powerful speaker mixer, in replacement of **Dolby Atoms**. 
- **Alsamixer** : command line speaker config tool, aims to solve some audio device conflict

## Entertainments
- **Yesplay & R3play** : replacement of the **netease music**, build in electron.
- **Proton** with **Steam** : playing games smoothly as like **Windows**.

## Power Toys
- **Fcitx 5 input**: input keyboard skeleton, can be loaded with Google Pinyin, Sougou pinyin or similar.
- **Krunner Translator**: runner based translator.
- **Translate Shell**: Shell based translator, written in awk, speed-optimized.
- **[Scrot & Tesseract](https://askubuntu.com/questions/280475/how-can-instantaneously-extract-text-from-a-screen-area-using-ocr-tools#:~:text=60-,Maybe,-there%20is%20already)**: Command line screen text extract
- **[Asus ctl](https://gitlab.com/asus-linux/asusctl)** : Replacement of **Armory Crate** in **Windows**, control fans speed, battery maximum charge rate, and rgb keyboard. Strong recommmend if your are using **Asus** with **Linux** distributions.
- **[Linux wifi hotspot](https://github.com/lakinduakash/linux-wifi-hotspot)**: Allow you to spread your wifi signal via hotspot, while keeping wifi connection alive. KDE doesn't have a build-in solution for such features, so this plugin works as replacement.
    - **Warning**: auto-start this software may conflict with your wireless card bootstrap, consequences is: your Network Manager fail to boot your wireless connection, leaving your computer in a offline status. Disable the auto start of this plugin can avoid this bug.
- **[Touchegg](https://github.com/JoseExposito/touchegg)** : Touch pad gesture customization. You can edit the config to implement your own gestures.
- **[Cap writter](https://github.com/HaujetZhao/CapsWriter-Offline)**: skeleton for voice-to-text, but it drains power quickly, used with cautions.
- **Scrcpy**: a command line tool based on `adb` from debian 12 apt repo, allow you playing your phone via your computer. 
- **[bat](https://github.com/tshakalekholoane/bat)**: Battery management, you don't want your battery health dropping like crazy, do you?
    - if you are using Asus Computer, please do not install this, using `asus-ctl` above.

## DE Customization
- **KDE** : Desktop Environment with more customization options. A wide platform for loading more plugin.
Below is my recommendation: A Mac - Flat style mixture.
Using deep color for transparent, blur and window content(inspire by Battlefield 2042 early UI design), with white window decoration, preserving some OS X highlights, reminding the user this is a UNIX system.
    - **Kvantum Manager** : GTK Application style manager (global)
    - Global Theme: Gently
    - Application Sytle: kvantum-dark
    - Plasma Style: Edna-light
    - Color: Gently
    - Window Decoration: Edna-light
    - Fonts: Roboto
    - Icons: Tela circle dark
- **Oh-my-zsh** : tool to manage your **zsh** shell plugins.
    - **powerlevel10k** : cool theme for **zsh** shell.
- **latte-dock** : next-gen evolution capacity for more panel and widget on desktop. 
**Warning**: This plugin has notorious **Memory Leak**. Used with cautions.
    - Template: **Edna**,  still. you might encounter dependency problem, this is caused by **System Tray** components.

## Funnies
- **[Fcitx Emoji Input Alias](https://github.com/kamabokowen/fcitx-emoji-quickphrase)** : allow your spam using ~~obsense~~ , nausea and offensive emoji quickly. You can set alias for frequently used emojis, but this already handle many of them for you. Greeting your opponents *Kindly*!
- **[Star Rails Grub Theme](https://github.com/voidlhf/StarRailGrubThemes)** : Don't mention that....check it yourself if you want such....
- **[~~E-hentai~~ Downloader](https://github.com/ccloli/E-Hentai-Downloader)** : Shooooooooo.....\*lower voice\* only when you are eager....
