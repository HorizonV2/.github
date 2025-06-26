
HorizonDroid
===========

![**HorizonBanner**](https://github.com/HorizonV2/.github/blob/main/horizon.svg)

Welcome to HorizonDroid!

HorizonDroid is based on LineageOS, allows users to experience Google's latest Pixel updates while integrating useful features from known custom ROMs.
We currently support Android 15, with the latest security patches from Google.

HorizonLabs:
------------------------
<p align="center">
<img src="https://github.com/ryzenforce990/ryzenforce990/blob/main/20240210_231505.png" />
</p>

**HorizonLabs** is the feature centre of **HorizonDroidLab**, this tab contains all the features / tweaks which are added to HorizonDroidLab.
Inside **HorizonLabs**, you can find all your needed features.
**HorizonDroid Team**

Count Download sourceforge:
-------
<a href="https://sourceforge.net/projects/horizondroid/files/latest/download"><img alt="Download horizondroid" src="https://img.shields.io/sourceforge/dm/horizondroid.svg" ></a>
<a href="https://sourceforge.net/projects/horizondroid/files/latest/download"><img alt="Download horizondroid" src="https://img.shields.io/sourceforge/dw/horizondroid.svg" ></a>
<a href="https://sourceforge.net/projects/horizondroid/files/latest/download"><img alt="Download horizondroid" src="https://img.shields.io/sourceforge/dd/horizondroid.svg" ></a>
<a href="https://sourceforge.net/projects/horizondroid/files/latest/download"><img alt="Download horizondroid" src="https://img.shields.io/sourceforge/dt/horizondroid.svg" ></a>

### Quick Source Initialization ###

```bash
repo init -u https://github.com/HorizonV2/android.git -b lineage-22.2 --git-lfs
```

```bash
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune --retry-fetches=5 -j10
```
HorizonDroid Flags:
```
# Maintainer username
HORIZON_MAINTAINER := superxorn

# Face Unlock
TARGET_FACE_UNLOCK_SUPPORTED := true

# Gapps flags
WITH_GMS := true/false
WITH_GMS_VARIANT := pico/core

# Other flags
TARGET_INCLUDE_MATLOG := true/false
TARGET_INCLUDE_ACCORD := true/false
TARGET_PREBUILT_BCR := true/false
PRODUCT_NO_CAMERA := true/false

```
Setup environment:

``` bash
lunch lineage_devicecodename-bp1a-buildtype
```

```bash
. build/envsetup.sh
```

```bash
mka horizon -j$(nproc --all)
```

[More build information](https://github.com/HorizonDroidLab/manifest)

### Official Support Group & Channel

* [**Telegram Channel**](https://t.me/horizondroid)
* [**Telegram Group**](https://t.me/HorizonDroidChat)
* [**Website**](https://horizonv2.github.io/HorizonDroid.github.io/)

-----------------------------------------------------------------------------
![CreditsImg](https://github.com/HorizonV2/.github/blob/main/credit.svg)
 Special thanks to All ROM Developers in this community
 * [**LineageOS**](https://github.com/LineageOS)
 * [**AxionAOSP**](https://github.com/AxionAOSP)
 * [**PixelOS**](https://github.com/PixelOS-AOSP)
 * [**CrDroid**](https://github.com/crdroidandroid)
 * [**EvoX**](https://github.com/evolution-x)
-----------------------------------------------------------------------------
