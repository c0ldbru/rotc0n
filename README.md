# rotc0n

This is the official repo for the rotc0n badge and its firmwares. That's right, firmwareS, as in multiple. We 
wanted this badge to bring folks joy even after rotc0n itself is done, so we're planning to periodically release 
new firmware for it to get you into secret parties we host at other cons!

Want to get your hands on one before they're gone? You can snag a rotc0n badge [Here](https://www.youtube.com/watch?v=dQw4w9WgXcQ) or [Here](https://goimagine.com/rotcon-0-badge/)

## Firmwares Included

There are currently three different firmwares available for the rotc0n badge:

- rot13labs_rotc0n_default.hex -- This is the default rotc0n firmware that your badge shipped with.
- rot13labs_rotc0n_bsides.hex -- This firmware was made for the unofficial rot13labs afterparty for BSides Tampa 2024
- rot13labs_rotc0n_defcon.hex -- This firmware contains the time/date/location for the rotcon party at DEFCON 32

## Flashing The Badge

The rotc0n badge is fully QMK compatible, which means you can use the [QMK 
Toolbox](https://github.com/qmk/qmk_toolbox) to flash new firmware onto your badge! heres how you can get 
started.

1. Download the hex file for the firmware you want to install onto your badge
2. Download or install QMK Toolbox (link to the project for download and install instructions above)
3. Open QMK Toolbox and select ATmega328P as the MCU
4. Click "Open" and select your firmware hex file
5. While holding down *either* the boot button **or** the "R" key, hit reset on the badge
> NOTE: you should see "USBasp device disconnected: www.fischl.de USBasp" show up in your QMK Toolbox console if 
you did this properly.
6. Hit "Flash" to flash the new firmware onto your badge. When it says "Flash Complete" hit reset on your badge 
again and it will restart and use the new firmware. 
