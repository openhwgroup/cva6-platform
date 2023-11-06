# CVA6 Platform

CVA6 Platform is a multi-core CVA6 with CV-MESH intended for software testing and regression.

![CVA6 Platform](static/redhat_openhwgroup.png)


## Genesys II: Getting Started

1. Download the pre-built bitstream from [downloads.openhwgroup.org](https://s3.eu-west-1.amazonaws.com/downloads.openhwgroup.org/cva6/20231104-4-uboot-g2-2c.bit).
2. Put it on a FAT32 formatted USB stick.
3. Insert the USB stick into the top USB port on the Genesys II board. Set the JP5 to switch to USB/SD and JP4 to USB, this will use the bitstream on the pendrive (more detailed instructions can be found [here](https://digilent.com/reference/programmable-logic/genesys-2/reference-manual#usb_host_and_micro_sd_programming)).
4. Download the Fedora image from [downloads.openhwgroup.org](https://s3.eu-west-1.amazonaws.com/downloads.openhwgroup.org/cva6/summit_fedora_20231104_2.img.gz).
5. `gunzip` and flash the image on an SDCard using [BalenaEtcher](https://etcher.balena.io/).
6. Power on the board and play `tetris`.

![CVA6 Platform](static/tetris.png)

