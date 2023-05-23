# hp-85F0-efi
Opencore EFI files for hp laptop DW0053-NL (motherboard 85F0). Current working opencore version: 0.9.2

## What works, what doesn't

So far i've done a decent job at getting most things to work fairly well, in fact i'm currently daily driving the laptop with macos 13.4; Let's start with what works and with what i've tested:
- [X] Battery readouts, fairly accurate battery status reporting
- [X] Keyboard and trackpad (even gestures!)
- [X] USB, both the A and C ports
- [X] Speakers and AUX port 
- [X] Wifi (and bluetooth, i just haven't had time to get the proper KEXTs to make it work)
- [X] Sleep
- [X] Backlight (on ventura it has the backlight off at boot issue)
- [X] Apple Services and IMessage
- [X] NVMe Drive\
Now, onto the things that i'm still working on fixing but i can't either due to incompetence or lack of time
- [ ] Bluetooth is still a wip

----
Updates (or at least going from monterey to ventura) worked flawlessly, and it didn't break anything. If you have a similar, or even the same board, and got bluetooth to work on an intel 8265 card do shoot me a message on discord @mercury#0420 or open up an issue and show me what you did (please, i need bluetooth)
