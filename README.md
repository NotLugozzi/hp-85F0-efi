# hp-85F0-efi
Opencore EFI files for hp laptop DW0053-NL (motherboard 85F0). Current working opencore version: 0.9.2

## What works, what doesn't

Only thing that i'm still currently working on getting a fix for is the camera, other than that every basic laptop function is provided. 
- [X] Battery readouts, fairly accurate battery status reporting
- [X] NVMe Drive
- [X] Sleep
- [X] GPU with hw acceleration (can easily work on heavier apps like photoshop or fusion360 with no issues)
- [X] Keyboard and trackpad (even gestures!)
- [X] USB(both A and C ports) and SD card reader
- [X] Speakers, Microphone, AUX port and BT audio
- [X] Camera 
- [X] Wifi
- [X] Bluetooth (thanks to u/Seven_of_eleven for providing a patch for it. original thread [here](https://www.reddit.com/r/hackintosh/comments/13pvdhj/comment/jlbj2d9/?utm_source=share&utm_medium=web2x&context=3))
- [X] Backlight (on ventura it has the backlight off at boot issue)
- [X] Apple Services and IMessage


----
Updates (or at least going from monterey to ventura) worked flawlessly, and it didn't break anything.
