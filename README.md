# AtiNAMatiC OS releases

Releases for the **AtiNAMatiC OS** guitar pedal: a Raspberry Pi 5 with a Blokas Pisound and a touchscreen that boots straight into AtiNAMatiC.

## Build a new pedal

1. Download the newest `AtiNAMatiC-OS-v<version>.zip` (or `.img.xz`) from [Releases](../../releases).
2. Flash it to a 16 GB+ microSD card with Raspberry Pi Imager ("Use custom") or balenaEtcher. There's no need to unzip it.
3. Put the card in the Pi and power on. `README-FLASH.txt` in the release has the details: screens, Wi-Fi, settings.

## Update a pedal

You never need to re-flash. Updates keep your presets, NAM models, IRs, settings, Wi-Fi and Bluetooth.

- **Over Wi-Fi:** on the pedal, open the menu (3 dots) and choose **Updates**, then **WI-FI**, then **CHECK FOR UPDATES**.
- **From a USB stick:** copy `AtiNAMatiC-v<version>.atinaupdate` to a USB stick and use **Updates**, then **USB STICK**.
- **From a computer or phone:** on the pedal choose **Updates**, then **COMPUTER / PHONE**. In a browser on the same network, open `http://atinamatic.local`, type the code the pedal shows, and drop in the `.atinaupdate` file. The same page backs up and restores your presets and settings.

Every update is digitally signed. A pedal installs Wi-Fi and browser updates only if the signature checks out.
