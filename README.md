# awesome-android-root

A comprehensive, up-to-date list of Android apps that require or utilize root privileges.

Pull requests are welcome ✨

## Table of Contents
  - [What is root?](#what-is-root)
  - [Should I root](#should-i-root)
  - [How to root](#how-to-root)
  - [Magisk](#magisk)
  - [KernelSU](#kernelsu)
  - [APatch](#apatch)
  - [Which solution should I use?](#which-solution-should-i-use)
  - [LSPosed](#lsposed)
  - [Root Apps](#root-apps)
    - [Ad Blocking](#ad-blocking)
    - [App Management](#app-management)
    - [Automation](#automation)
    - [Backup and Restore](#backup-and-restore)
    - [Development and Debugging](#development-and-debugging)
    - [File Management](#file-management)
    - [Kernel](#kernel)
    - [Modifications](#modifications)
    - [Network Tools](#network-tools)
    - [Privacy and Security](#privacy-and-security)
    - [Root Specific](#root-specific)
## What is root?

Android rooting is the process of gaining privileged control (known as root access) over various Android subsystems. Rooting allows overcoming limitations that carriers and hardware manufacturers put on some devices, resulting in the ability to alter or replace system applications and settings, run specialized apps that require administrator-level permissions, or perform other operations that are otherwise inaccessible to a normal Android user.

## Should I root?
Now to the main question. Should i root?
First, let's view disadvantages then advantages.
### Disadvantages
- As a root user, if you ever mess up, it's all your responsibility to fix it.
- Personally i never faced it, even though i messed up the device to the worst condition. People usually say your device may hard brick.
- Banking apps won't work. Recently, some apps are detecting root even with Magisk (there are workarounds for most of them).
- Rooting process if messed, Although it can be fixed, it can be tough for beginners.

### Advantages
- You can grant apps, Su and they'll do a great job for you.
- You can tweak kernel= great performance for games.
- You can ban ads from your device completely.
- You can uninstall unnecessary apps, i.e., system apps.
- You can perform much more super enjoying tasks, they all can't be listed here.

### Debate
- Here is the [reddit thread](https://www.reddit.com/r/AndroidQuestions/comments/1c69h3q/is_rooting_still_something_you_would_do_in_2024/) Debating if its worth it rooting in 2024 (but in my opinion its worth every penny).
  
## How to root?
It really depends upon your device; it's recommended to check the XDA forum for your device, which usually has a good guide for your devices. Another option is telegram groups for your devices, as they have specific communities related to your device.
Generally, the following steps are common:
- Unlock the boot loader.
- Get a custom recovery installed.
- Flash your preferred method of rooting solutions from below.
- Enjoy the ultimate power of a rooted device.

## Magisk

[Magisk](https://github.com/topjohnwu/Magisk) is the most popular and powerful tool for Android power users, providing root access, boot scripts, and a module system for customizing Android devices systemlessly. It's actively maintained and regularly updated.

[Download Magisk](https://github.com/topjohnwu/Magisk/releases)

## KernelSU

[KernelSU](https://github.com/tiann/KernelSU) is a kernel-based root solution for Android devices. It provides a root method that works by modifying the kernel, offering an alternative to Magisk for some devices and use cases. KernelSU is gaining popularity, especially on newer devices.

[Download KernelSU](https://github.com/tiann/KernelSU/releases)

## APatch
[APatch](https://github.com/bmax121/APatch) uses patching of Android kernel and Android system to gain root access based on [Kernel Patch](https://github.com/bmax121/KernelPatch/).

[Download APatch](https://github.com/bmax121/APatch/releases)

## Which solution should I use?
If you are a newbie or don't know much about rooting, I'd  recommend going with Magisk, as it has a vast community support.

## LSPosed
[LSPosed](https://github.com/LSPosed/LSPosed) is an open-source framework that allows users to install and use Xposed/LSPosed modules on their Android devices.

## Glossary
-  FOSS = Free and Open Source Software
-  Non-FOSS = Closed Source Software
## Root Apps

### Ad Blocking

- [AdAway](https://adaway.org/) - Open-source ad blocker using hosts file (FOSS)
- [AdGuard](https://adguard.com/en/adguard-android/overview.html) - Comprehensive ad blocking solution (Non-FOSS)
- [Blokada](https://blokada.org/) - Advanced ad blocker with VPN functionality (FOSS)

### App Management
- [App Manager](https://github.com/MuntashirAkon/AppManager) - A full-featured package manager and viewer for Android (Foss)
- [Inure](https://github.com/Hamza417/Inure) - An elegant and beautiful premium Android app manager for rooted and non-rooted devices (Foss)
- [Hail](https://github.com/aistra0528/Hail) - Disable / Hide / Suspend / Uninstall Android apps (Foss)

### Automation

- [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm) - Automation app (Non-FOSS)
- [MacroDroid](https://play.google.com/store/search?q=macrodroid&c=apps) - Easy to use automation app (Non-Foss)

### Backup and Restore

- [Neo Backup](https://github.com/NeoApplications/Neo-Backup) - Powerful open-source backup solution (FOSS)
- [Swift Backup](https://play.google.com/store/apps/details?id=org.swiftapps.swiftbackup) - Modern backup solution with cloud support (Non-FOSS)

### Development and Debugging

- [Termux](https://termux.com/) - Advanced terminal emulator and Linux environment (FOSS)
- [LADB](https://github.com/tyronechen/LADB) - Local ADB shell (FOSS)

### File Management

- [MiXplorer](https://mixplorer.com/) - Feature-rich file manager (FOSS)
- [Root Explorer](https://play.google.com/store/apps/details?id=com.speedsoftware.rootexplorer) - File manager with root access (Non-FOSS)
- [Xplore File Manager](https://play.google.com/store/apps/details?id=com.lonelycatgames.Xplore) - A file manager with root support (Non-FOSS) 
- [Solid Explorer](https://play.google.com/store/apps/details?id=pl.solidexplorer2) - Powerful file manager with root support (Non-FOSS)

### Kernel
- [Franco Kernel Manager](https://play.google.com/store/apps/details?id=com.franco.kernel&hl=en)

### Modifications

- [Revanced Manager](https://github.com/ReVanced/revanced-manager) - YouTube with additional features (FOSS)
- [Lucky Patcher](https://www.luckypatchers.com/) - App patcher and modifier (Use with caution, Non-FOSS)

### Network Tools

- [Fing](https://play.google.com/store/apps/details?id=com.overlook.android.fing) - Network discovery and security (Non-FOSS)
- [NetGuard](https://github.com/M66B/NetGuard/) - No-root firewall (FOSS)

### Privacy and Security
- [Amarok](https://github.com/deltazefiro/Amarok-Hider)
- [AFWall+](https://github.com/ukanth/afwall) - Iptables-based firewall (FOSS)
- [Shelter](https://gitea.angry.im/PeterCxy/Shelter) - Isolate and clone apps (FOSS)
- [Island](https://play.google.com/store/apps/details?id=com.oasisfeng.island) - App isolation and cloning (Non-FOSS)

### Root Specific 
- [Hide-My-Applist](https://github.com/Dr-TSNG/Hide-My-Applist)
- [Zygisk Detch](https://github.com/j-hc/zygisk-detach)
- [Shamiko](https://github.com/LSPosed/LSPosed.github.io/releases)
- [Play Integrity Fix](https://github.com/chiteroman/PlayIntegrityFix)
- [Trick Store](https://github.com/chiteroman/TrickyStore)


---

**Note**: Always be cautious when using root apps, as they have the potential to modify system files and settings.
