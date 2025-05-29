---
title: 'a guide to distro hopping (btw i use arch)'
date: '2024-03-31'
tags: []
draft: false
summary: finding your place in the linux world
authors: ['default']
---

NOTE : OUTDATED. I'M WORKING ON A NEW ONE

I have been a Linux user for a while now, and distro hopping is a ~~hobby~~ addiction of mine. While many appreciate Linux for its functionality, ease of use in managing development environments, or its lightweight nature - I am drawn to its customizability. The ability to design my entire workstation to look and function exactly as I want it to is mindblowing to me (I know, I know, "average r/unixporn" user).

I presume that those reading this have a decent amount of familiarity with linux as in this article, I will guide you through my process of exploring new distros, managing my configurations, and the relentless pursuit of the perfect setup. But first, let's set some ground rules.

## Things To Keep In Mind

- Don't attach yourself to the tools you use - your distro isn't your religion
- No matter how fun distro hopping is, it has a diminishing marginal utility so you need to know when to stop yourself
- Although you don't need to be a programming expert, some knowledge of bash scripting and maybe a little bit of python doesn't hurt
- Don't get too distracted by fancy UI or minimalistic ideals - backend (i.e. kernel, package managers, etc.) is also a huge part if not the entirety of your operating system
- oh and, RTFM

## Choosing A Distribution

**Distribution Philosophy**
Decide whether you want a do-it-yourself (DIY) distro or one that's more user-friendly out-of-the-box. Consider if having features like working Bluetooth immediately is important to you or if you're willing to spend time configuring it. While DIY is romanticised in the Linux community, it's not suitable for everyone, as people have varying preferences for customizability versus ease of use.

Notably, some distros, like Arch, Debbian, Gentoo, and NixOS, prioritise control and remove unnecessary bloat. These distros are ideal for those who want to mould their system to their liking.

Whereas distros like Linux Mint, Ubuntu & Pop OS come with pre-configured desktops (and sometimes even drivers) to make your experience hassle free - for people that "just want things to work".

**Package Managers**
The three main package managers—apt (Debian), pacman (Arch), and dnf/yum (Fedora/RHEL) — offer a vast array of packages. While there are minor differences in how they manage packages, these differences are generally inconsequential for most users. Here, Arch's AUR (Arch User Repository) deserves a mention for its extensive software collection, though some packages may not always be up-to-date.

I won't go to deep but I will take a second to give single-phrase stereotype for all 3 package managers which are _mostly_ true.

apt - stable and hence never has new updates
pacman - bleeding edge and hence breaks a lot
dnf - updates are a good balance between apt and pacman but installation can be a bit slow sometimes, especially if not updated in a while.

**Release Models**

Debian and derivatives follow a fixed release cycle, offering stability but requiring fresh installations for major upgrades. This approach can be tedious and may delay access to the latest software and drivers, however it also results in fewer bugs and an overall less stressful experience.

Arch and its derivatives (and opensuse leap) use a rolling release model, providing continuous updates and access to the latest features. While this can lead to occasional instability, the frequency of breakages is often overstated (imo).

Fedora employs a semi-rolling release strategy, balancing stability with the convenience of in-place upgrades to new versions.

## Kernel Choices

Your kernel is the core of your system. Between linux, linux-lts (Long-Term Support), and linux-zen, each offers a different balance of stability, longevity, and performance enhancements. The linux kernel is a "one size fits all" solution, the LTS version is great for those who prioritise extreme stability (generally either very old gpu users and for servers), while linux-zen is tweaked for desktop performance (although there are on-going arguments about its impact).

## Filesystem and Boot Loader

Just use btrfs and systemd-boot unless you want very specific things that are only available in ext4 or grub respectively. There's nothing special with my choices, they are just industry standard for now and work as expected with a huge team of developers behind them (so you know your problems will be fixed)

## Terminal Emulator

This is more than just a command line; it's your gateway to the system. Whether you prefer the minimalist rxvt-unicode or feature-rich Konsole, your choice should align with your workflow and aesthetic preferences. I personally use kitty for its config file and gpu-acceleration features.

## Choosing a DE/WM

Selecting a Desktop Environment (DE) or Window Manager (WM) is crucial, as it defines your daily interaction with your computer. The choice between a DE and a WM boils down to personal preference and the level of customization desired. If you are a fan of minimalism, a keyboard shortcut enthusiast or just some who wants to use all available screen real estate - use tiling window managers. Otherwise stick with DEs for now and install a TWM on the side for experimentation/fun.

## Colour Scheme

The unsung hero of your daily computing experience. Whether you're into solarized palettes or monochrome vibes, your colour scheme sets the mood for your work environment. Tools like pywal can even generate schemes dynamically from your wallpaper, tying your whole desktop together. I personally use onedark for everything but I've met many people that swear by gruvbox and others that can't live without catppuccin.

## Conclusion

I feel like I've said this multiple times over but all these choices are extremely personal. You can mold your OS into being whatever you want it to be, that's the beauty of linux. The goal of this article was just to make you aware of things you can change (not that I can ever come close to covering all of them).
