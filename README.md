<!--
SPDX-FileCopyrightText: 2023 Robin Vobruba <hoijui.quaero@gmail.com>

SPDX-License-Identifier: CC-BY-SA-4.0
-->

# OSH (OSH) Logo - clean

[![License](
    https://img.shields.io/github/license/OSEGermany/osh-logo.svg?style=flat)](
    LICENSE)
[![REUSE status](
    https://api.reuse.software/badge/github.com/OSEGermany/osh-logo)](
    https://api.reuse.software/info/github.com/OSEGermany/osh-logo)

[![In cooperation with Open Source Ecology Germany](
    https://custom-icon-badges.demolab.com/badge/-OSEG-555555.svg?logo=oseg_logo)](
    https://opensourceecology.de)

- OSH: _Open Source Hardware_ (Machines and other things that free the user of the domination and control by the producer)

This repo hosts a **_clean_** reproduction of the well known
[OSH gear logo](https://www.oshwa.org/open-source-hardware-logo/).

## Issues with the original

The original SVG does not have a clean path,
which leads to the following issues:

- Some parts are non-symmetrical. \
  This can be witnessed for example,
  when copying the gear, flipping it horizontally,
  and then trying to make the two overlap.
- Editing the shape is a pain

It also does not have nice IDs.

The reason for all that,
is probably that SVG was not the original source format.
That seems to be Adobe Illustrator CS3.

Thus it is no big surprise,
that some info (and quality) gets lost during the export to SVG.

## Solution

We re-created the gear as close to the original as possible,
but keeping a clean path.
[Inkscape](https://inkscape.org/) was used to create the source file (SVG),
and we recommend to use it for editing too,
should that be necessary.

The [source file](src/gear_clean.svg) contains:

- the clean gear in full
- the clean gear with the cutout on the bottom
- the shapes used to create the clean gear,
  by using union and difference operations
- the original gear (with cutout),
  once as-is and once flipped horizontally
