author: Pascal Obry
date: 2019-03-21 18:44:00+00:00
layout: post
title: darktable 2.6.2 released
lede: dieppe.jpg
lede_author: <a href="https://photos.obry.net">Pascal Obry</a>
tags: announcement, darktable release

we’re proud to announce the second bugfix release for the 2.6 series of darktable, 2.6.2!

the github release is here: [https://github.com/darktable-org/darktable/releases/tag/release-2.6.2](https://github.com/darktable-org/darktable/releases/tag/release-2.6.2).

as always, please don't use the autogenerated tarball provided by github, but only our tar.xz. the checksums are:

```
$ sha256sum darktable-2.6.2.tar.xz
9cb9efbb09a40375ff05cef89343235a621c58339539e44985470a029a7ffb45 darktable-2.6.2.tar.xz
$ sha256sum darktable-2.6.2.dmg
8cd945744e56a85c35f982a96be42332a57dc383ec228fcc1d21eb57c068f27c darktable-2.6.2.dmg
$ sha256sum darktable-2.6.2-win64.exe
??? darktable-2.6.2-win64.exe (to be announced later)
```

when updating from the currently stable 2.6.x series, please bear in mind that your edits will be preserved during this process, but it will not be possible to downgrade from 2.6 to 2.4.x any more.

#### Important note: to make sure that darktable can keep on supporting the raw file format for your camera, *please* read [this post](https://discuss.pixls.us/t/raw-samples-wanted/5420?u=lebedevri) on how/what raw samples you can contribute to ensure that we have the *full* raw sample set for your camera under CC0 license!

and the changelog as compared to 2.6.1 can be found below.

## New Features

- Update colorbalance french translation

## Bugfixes

- Fix SSE bug in filmic introduced in #2025
- Fix issue when looking for input color profile (backward compatibility)
- Add missing Czech translation file
- Fix possible halo issue in local contrast module.
- Fix contextual help link to point to new HTML manual for 2.6 series.

## Changed Dependencies

- None.

## Camera support, compared to 2.6.1

### Base Support

- DSC-RX100M6
- Phase One P30 (fixed)
- Olympus OM-D E-M10 (enhanced)
- Nikon D7500 (enhanced)

### White Balance Presets

- Nikon D500
- Olympus E-PL8

### Noise Profiles

- Sony SLT-A35
- Nikon Z6

## Translations

- Catalan
- Czech
- Dutch
- Finnish
- French
- German
- Norwegian bokmål
- Polish
- Russian
- Slovenian
- Spanish