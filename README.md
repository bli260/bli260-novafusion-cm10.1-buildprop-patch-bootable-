# bli260-novafusion-cm10.1-buildprop-patch-bootable-
i created a patched build.prop for the gt-i18190N originally from gt-i18190 remastered with meta AI (Had to otherwise i wouldve been lost) booted it up tested the OS its stable but for preinstalled usability like lyanoh market or linphone i will upload the rom soon

# CREDITS - CM10.1 Golden V1.0 Alpha - GT-I8190N

Base ROM:
- Novafusion / TeamCanjica - CM10.1 GT-I8190 (golden) original
- CyanogenMod Team - CM10.1 / Android 4.2.2

Device:
- Samsung - GT-I8190N (golden)

Patch (this mod):
- Base: GT-I8190 -> Target: GT-I8190N
- Only build.prop edited
- No kitchen rebuild, system folder mod
- Apps not uploaded yet
- V1.0 Alpha Stable

Future:
- V1.5 with apps (Nova Launcher etc.)

Tester: Me (solo)

License: Apache 2.0 / GPL v2


new credits comming to v1.5 there wont be a v1.4 or a v1.1

# Bug notice

### Recovery / Thanks
- Phil3759 - PhilZ Touch Recovery (original)
- Android-Andi @ XDA - PhilZ Touch for golden / S3 Mini port & kernel work
- Novafusion - CM10.1 golden base

# CM10.1 Golden V1.0 Alpha - GT-I8190N (VoIP Edition)

**Device:** Samsung GT-I8190N (golden)  
**Base ROM:** GT-I8190 CM10.1 by Novafusion  
**Android:** 4.2.2 - CM10.1  

### Build Info
- Type: system folder mod (no kitchen rebuild)
- Patch: build.prop only (I8190 -> I8190N)
- Version: V1.0 Alpha Stable
- No apps yet in V1.0

### Concept - VoIP / WiFi-only
**No telephony, No NFC - by design.**

- No RIL / No baseband / No SIM
- No NFC
- Why? Porting takes too much time, focusing on WiFi stability
- Calls via VoIP over WiFi (SIP) only
- EFS SAFE, not formatted

**Requirements:**
- WiFi for everything
- SIP account + VoIP app for calls

### Status
WiFi-only device. Not a daily driver if you need SIM or NFC.

### Roadmap
- V1.0: build.prop patch, WiFi-only
- V1.5: + Nova Launcher + VoIP apps
- No V1.1 / V1.4, next is V1.5

### Credits
- Novafusion / TeamCanjica
- CM Team
- Tester: Me (solo)

### Warning
BACKUP EFS BEFORE FLASHING! Flash at own risk.

- **IMEI Status:** EFS folder NOT empty, nothing missing = IMEI is present, but not recognized in V1.0/V1.5 due to missing N libs
- **Contribute / Bugs:** For stability bugs or contributions -> email: dedsec61@proton.me (free to email)