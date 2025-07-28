# GL3227E
GL3227E is a USB to 2 emmc HS400 adapter, supports raid 1

## Firmware:
`sudo flashrom -p ch341a_spi -r firmware_gl3227e.bin`
```
flashrom v1.6.0 (git:v1.6.0) on Linux 6.15.4-bredos (aarch64)
flashrom is free software, get the source code at https://flashrom.org

Found XTX Technology Limited flash chip "XT25F02E" (256 kB, SPI) on ch341a_spi.
===
This flash part has status UNTESTED for operations: WP
The test status of this chip may have been updated in the latest development
version of flashrom. If you are running the latest development version,
please email a report to flashrom@flashrom.org if any of the above operations
work correctly for you with this flash chip. Please include the flashrom log
file for all operations you tested (see the man page for details), and mention
which mainboard or programmer you tested in the subject line.
You can also try to follow the instructions here:
https://www.flashrom.org/contrib_howtos/how_to_mark_chip_tested.html
Thanks for your help!
Reading flash... done.
```
## SHA256:
```
832679c4b7610a9f6d83941e428e86a7b6e3f7a7eb43c807ab7e258c069213ac  firmware_gl3227e.bin
```
## Extra details
SPI chip: XT25F02E (256kB)

`lsusb`
```
ID 05e3:0756 Genesys Logic, Inc. USB Storage
```

