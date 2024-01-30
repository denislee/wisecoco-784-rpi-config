# wisecoco-784-rpi-config

add these lines to "config.txt"

```
max_usb_current = 1
hdmi_group = 2
hdmi_mode = 87
hdmi_timings = 400 0 100 10 140 1280 10 20 20 2 0 0 0 60 0 43000000 3
```

for Raspberry Pi 4, comment the line `dtoverlay = vc4-fkms-V3D`
