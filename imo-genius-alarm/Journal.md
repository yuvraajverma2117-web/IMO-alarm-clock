# Journal

Source record for the IMO GENIUS ALARM project, prepared 2026-11-04 from its [Stardance page](https://stardance.hackclub.com/projects/59242) and the local files listed below. Devlog wording is preserved as posted; timestamps are the page's UTC timestamps.

## Project goal

The project page describes an alarm clock for timing a long maths session. It lists the category as Hardware, three devlogs, and six total hours.

## Published devlogs

### 2026-09-11 · 46m 1s logged

> Just completed PCB design tutorial now i will edit it to meet my needs and it will look what i need.Also it was like frustrating how to get the u2 esp32 c3 smd i just used u1 for first prototype i have changed it btw but now i cannot find footprint for it ( footprints for xiao esp32-c3) like there is a .pretty file i open it but nothing loads from it !!

[Original devlog](https://stardance.hackclub.com/projects/59242/devlogs/55090) · [Image](images/devlogs/2026-09-11-devlog-55090.webp)

### 2026-10-26 · 4h 40m 13s logged

> MADE the PCB 3d model , schematic and connected all the wires , it was my first time so maybe not that good .

[Original devlog](https://stardance.hackclub.com/projects/59242/devlogs/69298) · [Image 1](images/devlogs/2026-10-26-devlog-69298-1.webp) · [Image 2](images/devlogs/2026-10-26-devlog-69298-2.webp)

### 2026-10-29 · 46m 15s logged

> I started to make a 3d cad model of my Alarm Clock.

[Original devlog](https://stardance.hackclub.com/projects/59242/devlogs/70197) · [Image](images/devlogs/2026-10-29-devlog-70197.webp)

## Files gathered

- The local KiCad project includes `.kicad_pro`, `.kicad_pcb`, `.kicad_sch`, and a CSV component export. The CSV lists nine push switches, nine 1N4148 diodes, a buzzer, and a XIAO ESP32-C3; its U1 designation says SMD but its footprint says DIP.
- Two local KiCad STEP files were included: the alarm-clock-named electronic assembly export and `tft_display.step`. A local Fusion 360 `.f3d` file was also found; its saved preview shows a PCB assembly.
- The found Fusion preview and STEP export depict/identify board assembly data, not a demonstrated finished enclosure. Although the newest devlog says enclosure CAD work started, no separate enclosure CAD source was found among the matching project files.
- No firmware source or hardware test evidence was found in the matching project folders. The gathered files therefore document design work, not a verified functioning device.
- The KiCad PCB artwork contains personal identifying details, and its 3D model references include absolute paths into the original Mac Downloads folder. Review those before making the repository public or expecting a clone to render identically.

The three devlog entries' logged times sum to **6h 12m 29s**; Stardance's project header displays **6 total hours**.
