<!--
SPDX-FileCopyrightText: 2023 Robin Vobruba <hoijui.quaero@gmail.com>

SPDX-License-Identifier: CC-BY-SA-4.0
-->

# OSH (OSH) Logo - clean

[![License: CC-BY-SA-4.0](
    https://img.shields.io/badge/License-CC--BY--SA--4.0-blue.svg)](
    LICENSE)
[![REUSE status](
    https://api.reuse.software/badge/codeberg.org/oseg/osh-logo)](
    https://api.reuse.software/info/codeberg.org/oseg/osh-logo)

[![In cooperation with Open Source Ecology Germany](
    https://raw.githubusercontent.com/osegermany/tiny-files/master/res/media/img/badge-oseg.svg)](
    https://opensourceecology.de)

- OSH: _Open Source Hardware_
  (Machines and other things that free the user
  of the domination and control by the producer)

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

## Files

- new, clean source image \
  (contains hidden parts, including shapes used for the construction) \
  ![new, clean source image](src/gear_clean.svg)
- partial gear
  - SVG: ![SVG](res/media/img/gear_part.svg)
  - PNG: ![PNG](res/assets/media/img/gear_part.png)
- full gear
  - SVG: ![SVG](res/media/img/gear_full.svg)
  - PNG: ![PNG](res/assets/media/img/gear_full.png)
- both gears
  - SVG: ![SVG](res/media/img/gear_both.svg)
