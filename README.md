<div align="center">

# Hi, I'm TryCoffee

**Linux and systems tinkerer.** I'd rather understand a tool and rebuild it than accept its defaults.<br>
I write desktop software that lives close to the machine: screen capture on the GPU, raw disk writes, video pipelines.

![C++](https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Qt](https://img.shields.io/badge/Qt_6-41CD52?style=flat-square&logo=qt&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA_/_NVENC-76B900?style=flat-square&logo=nvidia&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch_/_CachyOS-1793D1?style=flat-square&logo=archlinux&logoColor=white)

</div>

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### <img src="assets/heavendesk-icon.svg" width="26" align="top"> Heavendesk

Low-latency remote desktop for **Windows and Linux**, built from scratch in C++.
The screen is captured and encoded on the graphics card, so it feels like sitting at the machine, not watching a video of it.

- Wayland, X11 and Windows hosts, every monitor as its own stream
- Reach a machine at the login screen, no open session needed
- Works on strict networks: only outgoing HTTPS on port 443
- File transfer and a remote terminal since 0.2

[![Website](https://img.shields.io/badge/heavendesk.com-e8c987?style=flat-square)](https://heavendesk.com)
[![Org](https://img.shields.io/badge/GitHub-Heavendesk-181717?style=flat-square&logo=github)](https://github.com/Heavendesk)
[![Status](https://img.shields.io/badge/status-free_beta-5b6cff?style=flat-square)](https://heavendesk.com/downloads)

<sub>Closed source. Free during the beta.</sub>

</td>
<td width="50%" valign="top">
<a href="https://heavendesk.com"><img src="assets/heavendesk.png" alt="Heavendesk app"></a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/TryCoffee/kiln"><img src="assets/kiln.png" alt="Kiln"></a>
</td>
<td width="50%" valign="top">

### <img src="assets/kiln-icon.svg" width="26" align="top"> Kiln

USB flasher for **Linux, Windows and macOS**. Every write is read back and compared, and it only ever offers USB drives, SD cards and removable disks.

- Raw image writes (Linux ISOs, `.img`) with verification
- Windows 11 install sticks, with optional Rufus-style tweaks: skip TPM and Secure Boot checks, no Microsoft account
- Ventoy disks in one click

[![Release](https://img.shields.io/github/v/release/TryCoffee/kiln?style=flat-square&color=e2401f)](https://github.com/TryCoffee/kiln/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/TryCoffee/kiln/total?style=flat-square)](https://github.com/TryCoffee/kiln/releases)
[![Website](https://img.shields.io/badge/kiln--usb.pages.dev-e2401f?style=flat-square)](https://kiln-usb.pages.dev)
[![License](https://img.shields.io/badge/license-GPL--3.0-blue?style=flat-square)](https://github.com/TryCoffee/kiln/blob/main/LICENSE)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### DRAW

**D**aVinci **R**esolve **A**AC **W**orkaround. Resolve on Linux can't import AAC audio, so DRAW batch-converts the audio of `.mp4` and `.mkv` files to lossless FLAC and copies the video untouched.

- Skips files that are already FLAC (checked with `ffprobe`)
- Real per-file progress, and Stop really stops
- PyQt6, follows your system theme

[![Repo](https://img.shields.io/badge/GitHub-DRAW-181717?style=flat-square&logo=github)](https://github.com/TryCoffee/DaVinci-Resolve-AAC-workaround)
[![License](https://img.shields.io/badge/license-AGPL--3.0-blue?style=flat-square)](https://github.com/TryCoffee/DaVinci-Resolve-AAC-workaround/blob/main/LICENSE)

</td>
<td width="50%" valign="top">
<a href="https://github.com/TryCoffee/DaVinci-Resolve-AAC-workaround"><img src="assets/draw.png" alt="DRAW"></a>
</td>
</tr>
</table>

---

## GitHub Stats

<div align="center">
<img src="metrics.svg" alt="GitHub metrics and contributions calendar">
</div>
