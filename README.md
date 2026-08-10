# Mailbox Lab

An interactive design lab for a parametric, laser-cut **house-shaped mailbox** — built for the Jewish Life bulletin board at Davis Academy's Lower School.

**Live lab: [techrabbi.org/mailbox-lab](https://techrabbi.org/mailbox-lab/)**

Adjust the house dimensions, roof pitch, windows, door, and finger-joint sizing with live preview, then export ready-to-cut SVG sheets sized for a Glowforge Spark (8.5×11 in bed). Includes a card tray and pencil well; artwork features a Star of David gable window and a mezuzah on the door frame.

## Contents
- `index.html` / `mailbox-lab.html` — the self-contained lab (fonts and libraries embedded; works offline)
- `lab-template.html` + `build.py` + `lib/` — source template and build script
- `*.svg`, `*.pxd` — artwork sources (door + mezuzah, star gable window)
- `exported sheets/`, `v1/` — cut sheets from earlier iterations

## Cutting notes
Designed for 1/8 in (3 mm) cherry ply on a Glowforge Spark, 11 in usable cut window. Kerf and finger sizing are adjustable in the lab.
