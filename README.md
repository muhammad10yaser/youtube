# youtube
Youtube auto Loader (8-00.13.60) except 9.05,11.40


Added Relapse - thanks to @edisnord,PLK
Preferred exploit for FW 8.00–13.60 (except 9.05 and 11.40) when an active network connection (Wi-Fi or Ethernet) is detected
Automatically falls back to Lapse on FW <= 10.01 if no active network interface is detected (or on 9.05)
Replaces P2JB (removed)
Added 1s delay before autoloading to allow elfldr to stabilize after exploit handoff
Updated elfldr to v0.26
Updated kexp to v0.8
Updated unified-autoloader to v0.1.5
includes bundled Payload Manager v0.5.2
CI: Generate download0.dat UFS2 filesystem image and include in releases (thanks Feyzee61)
Build: Download prebuilt dependencies matching pinned submodules instead of latest (./build.sh -d)
