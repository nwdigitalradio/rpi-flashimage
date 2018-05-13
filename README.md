# rpi-flashimage
Contents &amp; script for generating a flash image for HAM radio using UDRC

### HAM Program Contents of image

###### Name
* Program name

###### Group
* Arbitrary grouping of packages & program source

###### Pkg/Src
* Package refers to a Debian package
* Source means you have to build & install program on target system

###### Origin
* If Pkg/Src = P then Origin lists the Debian package name
* If Pkg/Src = S then the URL of the source code is given

###### Status
* Active
* In development
* Proposed

### Program Table

 Name   | Group    | Pkg/Src    |  Origin  | Status   |
 :----- | :------: | :--------: | :------: | :------: |
 Direwolf        | Core       | S | https://github.com/wb2osz/direwolf/archive/$DW_VER.zip | Active |
 AX.25 lib/tools | Core       | S | https://github.com/ve7fet/linuxax25/archive/master.zip | Active |
 paclink-unix    | Winlink    | S | https://github.com/nwdigitalradio/paclink-unix | Active |
 RMS Gateway     | Winlink    | S | http://k4gbb.no-ip.info/docs/scripts/rmsgw-2.4.0-181.1.tar.bz2 | Active
 nixtracker      | APRS       | S | https://github.com/n7nix/nixtracker | Active |
 Xaster          | APRS       | P | xastir | Active |
 fldigi          | HF         |   |  |  |
 ARDOP           | HF Winlink | S |  | In Dev |
 chirp           | Util       | S |  | Proposed |

