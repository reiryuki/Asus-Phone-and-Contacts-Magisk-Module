# Asus Phone and Contacts Magisk Module

## DISCLAIMER
- Asus apps are owned by Mobile, ASUSTek Computer Inc.
- The MIT license specified here is for the Magisk Module only, not for Asus apps.

## Descriptions
Asus Phone and Contacts app by Mobile, ASUSTek Computer Inc. ported and integrated as a Magisk Module for all supported and rooted devices with Magisk

## Sources
- https://apkmirror.com com.asus.dialer and com.asus.contacts by Mobile, ASUSTek Computer Inc.
- libmagiskpolicy.so: Magisk (debug) 31.0 (31000)

## Changelog

v0.3
- Update libmagiskpolicy.so from Magisk (debug) 31.0 (31000)
- Prepare /storage/emulated/"$UID"/Android/data/$PKG/ directories
- Resets module folders/files permissions at post-fs-data
- Move _uninstall.log to /data/adb/logs/

v0.2
- Add Action button to clear apps caches
- Fix bug in uninstall.sh

v0.1
- Initial release

## Screenshots
https://t.me/androidryukimods/2608

## Requirements
- Android 10 (SDK 29) and up
- Magisk or Kitsune Mask or KernelSU or Apatch installed

## Installation Guide & Download Link
- If you are using KernelSU, you need to disable Unmount Modules by Default in KernelSU app settings and install https://github.com/KernelSU-Modules-Repo/meta-overlayfs or https://github.com/KernelSU-Modules-Repo/magic_mount_rs or https://github.com/KernelSU-Modules-Repo/hybrid_mount or https://github.com/maxsteeel/nomount first depending on ROM compatibility
- Install this module https://github.com/reiryuki/Asus-Phone-and-Contacts-Magisk-Module via Magisk app or KernelSU app only
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (and your home launcher app also) (enable show system apps) and reboot after
- If you are using SUList, you need to allow list manually your home launcher app (enable show system apps) and reboot after

## Download Tutorial
https://t.me/ryukinotes/97

## Optionals
Global: https://t.me/ryukinotes/35

## Troubleshootings
Global: https://t.me/ryukinotes/34

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- https://t.me/androidryukimodsdiscussions
- https://t.me/androidappsportdevelopment

## Sponsors
https://t.me/ryukinotes/25


