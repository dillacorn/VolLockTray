# VolLockTray

Windows tray app that keeps your **system output (speaker/headphone)** volume fixed at a user-chosen percentage. It targets the **default playback device** and **corrects instantly** whenever something tries to change it (event-driven).

> Some hardware/app combos “helpfully” adjust your system volume. VolLockTray pins it where you want it.

---

## Features

- Locks output volume to a chosen target (1–100%).
- Simple tray UI: Pause/Resume, Set target volume, Install/Remove autorun, Exit.
- No admin required. Per-user autorun.
- Lightweight single EXE. No dependencies. No telemetry. No log files.
- Uses Windows Core Audio APIs (`IAudioEndpointVolume`).
- [NirCmd](https://www.nirsoft.net/utils/nircmd.html) NOT required — this is a standalone application developed by me!

---

## Icon Credit
Icon: **“Audio speakers Icon”** by [Papirus Dev Team](https://www.iconarchive.com/artist/papirus-team.html) on [iconarchive.com](https://www.iconarchive.com/show/papirus-devices-icons-by-papirus-team/audio-speakers-icon.html)

---

Want to lock your mic volume instead?
- Check out [MicLockTray](https://github.com/dillacorn/MicLockTray)


Need a Linux 🐧 solution?
- Check out my script [miclock.sh](https://github.com/dillacorn/arch-hypr-dots/blob/main/config/hypr/scripts/miclock.sh)
