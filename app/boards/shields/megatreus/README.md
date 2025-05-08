```
west build -b adafruit_feather_nrf52840 -- -DSHIELD=megatreus
and sudo mount /dev/sda $MOUNT_POINT
and sudo cp build/zephyr/zmk.uf2 $MOUNT_POINT
and sync
and sudo umount /dev/sda
```
