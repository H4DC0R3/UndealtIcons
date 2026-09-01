# Undealt — Icons

Item icons for **Undealt** (Steam AppID 5205880), served to the Steam Inventory Service.

This repository is public because it has to be: Steam downloads and caches each icon from an open
URL. It holds images and nothing else.

## Contents

| Path | What |
|---|---|
| `cards/v1/small/` | 200×200 icons |
| `cards/v1/large/` | 1024×1024 icons |
| `cards/v1/cards.json` | id, name, suit, value and rarity |
| `cards/v1/index.html` | contact sheet |

## Versioned folders

Steam **caches** each icon, so replacing a file at the same URL is not guaranteed to reach
anyone. New art ships as a new folder (`v2`, `v3`, …) and the item schema is pointed at it.

**Never edit a folder that has been published.**
