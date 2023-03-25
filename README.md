# Thinkpad T460 Hackintosh

This set up is based on OpenCore 0.8.0 to work with Macos Monterey
<img width="698" alt="About This Mac" src="https://user-images.githubusercontent.com/9517130/227723304-ed341ce5-8e48-481a-8b7a-7037023b54c1.png">

im just Uploading this EFI for Reference so Please dont expect any updates


# Laptop's Hardware:
- <b>Model</b>: Thinkpad T460 (20FN003LGE)
- <b>CPU</b>: Intel(R) Core(TM) i5-6300U CPU @ 2.40GHz
- <b>GPU</b>: Intel HD Graphics 520
- <b>Storage</b>: Samsung 256GB SSD
- <b>RAM</b>: 16 GB PC3L-12800 1600MHz DDR3L
- <b>Screen</b>: 14" FHD 1080P IPS
- <b>Wi-Fi</b>: Intel Dualband-Wireless-AC 8260
- <b>Ethernet</b>: Intel I219-V PCIe Gigabit Ethernet
- <b>Sound</b>: Realtek ALC3245 (same as ALC239)
- <b>Camera</b>: 720p integrated
- <b>Battery</b>: 3-cell (23Wh) + 3-cell (23Wh)
- <b>Bios</b>: 1.43

---

# Working:
- Intel HD 520 Graphics with 2048MB allocated
- CPU Power Management
- Both Batterys (Battery life is around 5H with the 3cell External attached)
- All USB ports
- HDMI port (including HDMI Audio)
- Intel I219V Ethernet
- Realtek ALC239 Audio
- Wi-Fi & Bluetooth
- Internal camera
- Trackpad and Trackpoint with Buttons
- Keyboard (incuding most fn Keys)
- DRM support (Netflix tested on Firefox)
- SD Card Reader (Slower than in Windows)
- MacOS Monterey 12.4

# Partially Working:
- Wifi & Bluetooth (if Bluetooth and WIFI are used at the same time Wifi seems rather unstable)
- Sleep (Sometimes works sometimes doesnt and may wake up randomly im sure thats caused by the Intel Wifi Stuff)

# Not Working:
- Fingerprint Reader
- Sidecar Wireless

# additional Notes:

Battery Hotswapping works fine: just close the Lid to perform the Swap and it should update the Battery percentage accordingly
("Service Recommended" Warning can be ignored)

If my Laptop falls or gets hit by something near the Dockingstation port it may hardlock and needs to restart i didnt observe that behavior under Windows

Trackpad Driver needs 3 Seconds to initialize upon start
