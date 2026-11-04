# IMO GENIUS ALARM

A hardware alarm-clock project by **@YuviVerma**. The Stardance project describes the goal as setting a stopwatch or alarm for a long maths session. This local transfer package was assembled on 2026-11-04 from the project page, its three published devlogs, and matching design files found on the Mac.

> **Review before publishing:** the original KiCad board artwork includes personal identifying details (a full name, a date-like string, and a town/postcode). These source files are included unchanged. No GitHub repository has been created or published from this package.

## Contents

- `Journal.md` — dated, source-grounded record of the three devlogs and the files gathered.
- `images/devlogs/` — four WebP images downloaded from the three Stardance devlogs.
- `hardware/kicad/` — KiCad project, PCB, schematic, and exported component CSV.
- `hardware/3d-models/` — the KiCad STEP assembly export and a TFT display STEP model.
- `hardware/fusion/` — a local Fusion 360 `.f3d` file and its PNG preview.

## File notes

The KiCad CSV lists nine push switches, nine 1N4148 diodes, a buzzer, and a XIAO ESP32-C3. Its U1 designation says `XIAO-ESP32-C3-SMD`, while its footprint column says `XIAO-ESP32-C3-DIP`; verify this mismatch before ordering or manufacturing. The PCB also contains absolute 3D-model paths into the original Mac Downloads folder and `${AMZPATH}` references, so its 3D view may need repair after cloning.

The Fusion preview depicts a PCB assembly, not a clock enclosure. The KiCad STEP file identifies itself as a KiCad electronic-assembly export. No separate enclosure CAD source or firmware source was found among the matching project files. The newest devlog says enclosure CAD work had started, so the included assembly should not be presented as a finished alarm-clock case or tested product.

No license was selected or added. The original KiCad preferences, temporary files, and duplicate copies were left out. The duplicate KiCad board and schematic found in `IMO Alarm Clock 2` were byte-identical to the selected project files.

## Stardance source

- [IMO GENIUS ALARM project](https://stardance.hackclub.com/projects/59242)
- [2026-10-29 devlog — alarm-clock CAD started](https://stardance.hackclub.com/projects/59242/devlogs/70197)
- [2026-10-26 devlog — PCB and schematic](https://stardance.hackclub.com/projects/59242/devlogs/69298)
- [2026-09-11 devlog — PCB tutorial and footprint work](https://stardance.hackclub.com/projects/59242/devlogs/55090)
