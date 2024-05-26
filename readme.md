# LG G6 unlock.bin Generator

Use this utility to check if you have a valid unlock.bin for your LG G6 (may also work for LG G5).

After compiling, run it in with your terminal: java -jar lg-bf.jar

```
Imei: 356144084428859
DeviceId: DBEF9C5B33E8DE4F9930D164DECD6A62F1C5C49955D3DCB310DB5303B730209A
OutputFile: ~/git/lg-g6-unlockbin-gen/sample/unlock.bin
Sun Oct 29 08:00:08 CET 2023 - File exists and length matches!
Sun Oct 29 08:00:08 CET 2023 - Magic numbers found and correct!
Sun Oct 29 08:00:08 CET 2023 - Start attacking first signature
Sun Oct 29 08:00:08 CET 2023 - First signature verified
Sun Oct 29 08:00:08 CET 2023 - Start attacking second signature
Sun Oct 29 08:00:08 CET 2023 - Second signature verified
Sun Oct 29 08:00:08 CET 2023 - Writing file to disk
```

Mostly based on: https://github.com/jaehyek/lk/blob/master/platform/lge_shared/lge_verified_boot.c

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
