# rpi-flashimage
Contents &amp; script for generating a flash image for HAM radio using UDRC

### Contents of image

* Package refers to a Debian package
* Status
  * Active
  * In development
  * Proposed

#### Table

|Name| Group | Pkg/Src | Origin |Status|
|-----| ------ | ----- | | ------ |-----|
| Direwolf | Core | S | https://github.com/wb2osz/direwolf/archive/$DW_VER.zip | Active |
| AX.25 lib/tools | Core | S | https://github.com/ve7fet/linuxax25/archive/master.zip | Active |
| paclink-unix | Winlink | S | https://github.com/nwdigitalradio/paclink-unix | Active |
| RMS Gateway  | Winlink | S | http://k4gbb.no-ip.info/docs/scripts/rmsgw-2.4.0-181.1.tar.bz2 | 
| nixtracker | APRS | S | https://github.com/n7nix/nixtracker | Active |
| Xaster | APRS | P | xastir | Active |
| fldigi | HF |   |  |  |
| ARDOP  | HF Winlink | S | In Dev |
| chirp | Util | S | Proposed |

#### Test table

## Amost always imports

|  R |  Python |    Matlab |
| --------- |:---|:---------|:-----|
| library(tidyverse) |import numpy as np|
