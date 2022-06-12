# Surface Laptop 3 MacOS Moterey OpenCore
Surface Laptop 3 MacOS Monterey OpenCore

![SL3](https://github.com/rchiruma/SurfaceLaptop3-OpenCore/blob/main/SLP3.png)

## Surface Specs

* Intel® Core™ i5-1035G7 Quad-Core
* 8 GB LPDDR4x RAM
* Intel® Iris™ Plus
* SSD 256 GB


## What works:

1. Display with Full Acceleration
2. WiFi with Airpoirtitlm
3. Bluetooth
4. Keyboard (BigSurface.Kext)
5. Touchpad (BigSurface.Kext)
6. Ambient Light Sensor (BigSurface.Kext)
7. Brigthness/Power Buttons (BigSurface.Kext)
8. Audio with AppleALC (Realtek	ALC274) Layout ID 35
9. DisplayPort via USB-C
10. Webcam in facetime
11. BatteryStatus
12. Sleep and Wakeup (Via Keyboard)

## What does not work:

Touchscreen

## Breif How to
- Create your macOS installed USB
- Download the EFI above nd add your SMBIOS values for SerialNumber, MLB, ROM, BoardSerial etc.
- Copy the EFI to your EFI partition

## Trackpad Tweak
Also go to "SystemPreferences->TrackPad" and turn off "Force Click and haptic feedback" and turn on "Tap to Click" for the best experience
![Trackpad Tweak](https://github.com/rchiruma/SurfaceLaptop3-OpenCore/blob/main/Trackpad.png)

## Debug version
This is using Debug version of opencore. Feel free to switch to release version when you get it all working
