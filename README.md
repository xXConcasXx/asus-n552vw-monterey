# asus-n552vw-monterey
[Discontinued] macOS Monterey for ASUS N552VW-FI202T

Works in macOS Monterey 12.0.1 in BIOS ver. 300
This EFI uses OpenCore EFI Bootloader.

Just generate your build info: serial, smbios, etc.. and you're ready to go.

Tested and works perfectly:

1. Intel graphic card with all DVMT (64 -> 512);
2. Keyboard light and all FN shortcuts;
3. WiFi/Bluetooth with Handoff, Airport (i've BCM94360CS2 with NGFF M.2 adapter);
4. iMessage and FaceTime if you are lucky like me and if you have a minimum of knowledge of iMessage, FaceTime, SMBIOS, RTVariables, NVRAM, ecc..;
5. Touchpad with all gesture;
6. Battery recognition;
7. SD card reader;
8. All USB ports;
9. Ethernet (you have to replace rtl8111.kext with nullethernet.kext for iMessage and FaceTime);
10. HDMI video/audio with 2.0 support;
11. USB type C;
12. Audio with jack 3.5 without distortion or loss of stereo;

Tested and doesn't work:

1. Sleep in AC mode;
2. NVIDIA graphic card (disabled);

Let me know if there are any problems!
Any advice and improvement are welcome!

Enjoy.

You can download EFI from Release page: https://github.com/xXConcasXx/asus-n552vw-monterey/releases
