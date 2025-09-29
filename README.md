# Android device tree for samsung SM-M366B (m36x)

# How to build
## Sync twrp-12.1
    repo init -u https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git -b twrp-12.1; repo sync
## Clone Galaxy M36 Tree
    git clone https://github.com/SavedByLight/android_device_samsung_m36x.git -b android-12.1 device/samsung/m36x
## Build
    export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_m36x-eng; mka recoveryimage

# Known Bugs
 - /Data wont mount (known samsung issue)

```
#
# Copyright (C) 2025 The Android Open Source Project
# Copyright (C) 2025 SebaUbuntu's TWRP device tree generator
#
# SPDX-License-Identifier: Apache-2.0
#
```
