# JCALLY JM98Max Sleep / Hibernate / Standby Fix

Firmware and tool to fix the sleep/hibernate/standby issue on the **JCALLY JM98Max USB DAC**.

---

## ⚠️ Critical Warnings

> [!CAUTION]
> **DO NOT DISCONNECT OR CUT POWER DURING FLASHING!**  
> Never unplug the DAC, power down, or interrupt your PC while firmware is flashing. Doing so can permanently brick your DAC.

> [!IMPORTANT]
> **SELECT THE EXACT HARDWARE ID:**  
> When selecting the device in the downloader software, ensure you choose the exact device matching:  
> `VID_0666&PID_0881`. Selecting the wrong device may flash incorrect hardware.

> [!IMPORTANT]
> **WAIT 5–10 SECONDS AFTER 100%:**  
> Once the flashing progress bar reaches **100%**, **DO NOT** immediately unplug the device or close the program. Wait **5 to 10 seconds** for the write cycle to safely finalize before closing the software.

---

## Included Files

- [`odt_usb_downloader_v1.2.0.exe`](odt_usb_downloader_v1.2.0.exe) — Firmware flashing utility (Windows).
- [`JM98MAX  Firmware Hibernate Fix.bin`](JM98MAX%20%20Firmware%20Hibernate%20Fix.bin) — Firmware binary with the sleep/hibernate/standby fix.
- [`Instruction.mp4`](Instruction.mp4) — Video walkthrough demonstration.

---

## Step-by-Step Instructions

1. **Connect the DAC**: Plug your JCALLY JM98Max DAC into a stable USB port on your Windows PC.
2. **Launch the Flasher**: Run `odt_usb_downloader_v1.2.0.exe` (run as Administrator if prompted).
3. **Select Firmware**: Load the `JM98MAX  Firmware Hibernate Fix.bin` file into the utility.
4. **Select Target Device**: Verify and select the device corresponding to `VID_0666&PID_0881` (or `VID_0666APID_0881`).
5. **Start Flashing**: Initiate the update/download process.
6. **Wait for Completion**:
   - Keep the device plugged in and powered continuously.
   - When the progress reaches **100%**, wait an extra **5 to 10 seconds** for safety.
7. **Finish**: Close `odt_usb_downloader_v1.2.0.exe`, then unplug and reconnect your DAC.

---

## Video Tutorials & Credits

- **Original Video Tutorial & Files Source**: [YouTube Guide by Original Creator](https://www.youtube.com/watch?v=EQdu0Cr16PQ)  
  *All original files and solution credit belong to the author of the YouTube guide. Provided By JCALLY Official Support*
- **Local Video Guide**: Refer to `Instruction.mp4` included in this repository. Provided By JCALLY Official Support
