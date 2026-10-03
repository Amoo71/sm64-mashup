# SM64 Mashup (web build)

A browser game based on a fork of [sm64js](https://github.com/sm64js/sm64js) (the JavaScript port of the Super Mario 64 decompilation), extended with enemies, items and models taken from free-licensed games (Freedoom, Blasphemer, LibreQuake, OpenArena, SuperTux, SuperTuxKart, Minetest, Shattered Pixel Dungeon).

**Play:** https://amoo71.github.io/sm64-mashup/

## No ROM included

This repository contains **no Nintendo ROM and no extracted Nintendo textures, sounds or models**. On first start the page asks you to load your own, legally owned/dumped **Super Mario 64 (US, `.z64`) ROM**. The ROM is processed only locally in your browser; the extracted data is cached in the browser's IndexedDB for this site, so you only need to pick it once per browser.

## Controls

Keyboard: arrows = stick, Space = A, B = B, Z = Z, Enter = Start, J/L = camera, F = fire/use item, 1-9 = inventory slot, 0 = no item. Gamepads are supported. On phones/tablets touch controls appear automatically (play in landscape).

## Hosting

Static files only, all paths are relative, so it works from any sub-folder. Must be served over http(s) (opening `index.html` via `file://` does not work).

## Licenses

- sm64js: see [`LICENSE-sm64js.txt`](LICENSE-sm64js.txt) (WTFPL) and the bundled third-party notices in `main-*.js.LICENSE.txt`.
- All mashup assets: see [`MASHUP_LICENSES/`](MASHUP_LICENSES/) for the license, attribution and upstream credits of every asset source (GPL-2.0, GPL-3.0, BSD-3-Clause, Freedoom BSD license, etc.).
- Super Mario 64 is a trademark of Nintendo. This is an unofficial fan project, not affiliated with or endorsed by Nintendo.
