Special thanks to The1L2P (Discord ID: 1L2P#5598) for his excellent work!

# 2024-07-23 R20 release for SPAD 0.9.18.4+ 

CFT_737_ATC_V7_SPAD_1L2P_R20_115200.ino.hex

- Serial device init improvements

Baud Rate is 115200

Internal devices features
- Backlight brightness level setting by pressing IDENT and turning Right outer encoder
- Display brightness level setting by pressing IDENT and turning Right inner encoder

To manage ATC V7 panel digits and backlight brightness from SPAD, search for these variables.
- DISPLAY_BRI : ATC panel digits brightness from 0 to 15 (DEVICE:1L2P/CFT737ATCV7/DISPLAY_BRI)
- BACKLIGHT_BRI : ATC panel backlight brightness from 0 to 255 (DEVICE:1L2P/CFT737ATCV7/BACKLIGHT_BRI)

Last published SPAD complete device Snippet on 03-26-2024: #10855
