umax/visionbook_12wa_flex
---------------------------------------------

| Item                      | Description |
|---------------------------|-------------|
| Manufacturer              | UMAX |
| Device                    | VisionBook 12Wa Flex |
| Website                   | https://www.umax.cz/umax-visionbook-12wa-flex/ |
| Vendor driver (Windows)   | ftp://ftp.conquest.cz/pub/MID/12Wa_Flex_Drivers.rar |
| Extracted firmware        | [firmware.fw](firmware.fw) |
| Firmware for gslx680-acpi | [silead_ts.fw](silead_ts.fw) |
| Display resolution        | 1920x1080 |
| Touch panel resolution    | 1920x1440 (width might not be exact) |
| Touch controller          | GSL1680 (not verified) |
| Multitouch support        | Yes (10 points) |
| Finger tracking           | Yes |
| Mirrored horizontally     | No |
| Mirrored vertically       | Yes |
| Axes swapped              | No |
| Comments                  | fwtool -c silead.fw -m 1680 -w 1920 -h 1440 -t 10 silead_ts.fw -f yflip |

There is a small horizontal offset.
