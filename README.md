# Introduction
This repository contains a 3D printable case design for the Domesday Duplicator.

The case is designed using OpenSCAD and full source code is included.  There are also ready-made STL files for the various parts and materials if you don't want to build them yourself in OpenSCAD.

The case design contains multiple materials however you can easily remix the design using OpenSCAD customization GUI if you wish to print in a single material only (simply deselect the 'fill out text' and 'add logo' options and re-render).  Ready-made single material STL files are also included.

<img src="/images/case1.png" width="800">

# Printing instructions

## Overview

The model has been printed and tested on the Prusa MK3S/MMU2S printer. All parts fit on a 20x20 printing bed.

The OpenSCAD source files provide a parameter interface that allows you to render either the whole model or the individual parts (ready for STL (or other 3D format) export).  This requires OpenSCAD 2019.05 or later.

## Recommended print settings
* Material: PLA Blue and PLA White
* Layer: 0.20mm (Quality)
* Infill: 15%
* Supports: None
* Notes: The upper and lower case parts simply snap together.  4x M3 6mm screws are required to hold the electronics in place.

## Print time
Clearly this depends on your printer and it's settings.  For the 2 colour multi-material print the time was 11h 15m for both the upper and lower case.  For single-material printing to time was 8h 30m.

## Notes
The design also includes approximate renderings of the FPGA board, the DdD board and the USB3 board.  These are to assist with the design process and are not intended for printing.

<img src="/images/case3.png" width="800">

# Author

The DomesdayDuplicator case is designed and maintained by Simon Inns.

# Licensing

## OpenSCAD source files - software license (GPLv3)

    This is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
    
    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

## 3D model file - Creative Commons license (Creative Commons BY-SA 4.0)

Please see the following link for details: https://creativecommons.org/licenses/by-sa/4.0/

You are free to:

Share - copy and redistribute the material in any medium or format
Adapt - remix, transform, and build upon the material
for any purpose, even commercially.

This license is acceptable for Free Cultural Works.

The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:

Attribution - You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

ShareAlike - If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

No additional restrictions - You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.
