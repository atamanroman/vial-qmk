# VIAL Fork of 42keebs VIAL Fork

Initial setup:

```shell
$ qmk setup
```

Build lily58:

```shell
# double-click the reset button on the Lily58 to enter bootloader mode
$ CONVERT_TO=promicro_rp2040 make lily58:vial
$ cp lily58_rev1_vial_promicro_rp2040.uf2 /Volumes/RPI-RP2
```
