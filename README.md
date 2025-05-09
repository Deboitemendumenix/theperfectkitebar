# ThePerfectKiteBar (TPKB)

An **open-source kite control bar** designed for all **chill kite-foil enthusiasts** — maximizing session enjoyment with the added benefits of flexibility, customization, and full DIY freedom.

Development began in **2023**, driven by the lack of suitable off-the-shelf products — most commercial options were either too expensive, too complex, unnecessarily heavy, or built around same design across many brands.

The first functional version of TPKB was **tested in spring 2024**, followed by multiple iterative refinements based on real-world user expreience.

Key design priorities include:
- Minimal weight without compromising strength
- Full **field-serviceability** with common tools
- **Low-cost manufacturing** using accessible 3D printing services
- Easy **spare part replacement**
- **Glove-friendly operation**, especially in cold water (5°C and below)
- Seamless usability in both **cold northern climates** and **tropical destinations** (e.g. Caribbean)

---

## Project Purpose

ThePerfectKiteBar is an open hardware project focused on designing and sharing components of a kite control bar system optimized for kite-foiling.

This project is intended for:

- DIY enthusiasts
- Riders seeking lightweight or custom solutions
- Experimental design exploration
- Field replacement and customization of bar components

All parts are designed with parametric flexibility in mind — allowing for adaptation to different materials, manufacturing methods, and rope/tube sizes.

---

## Project Organization and Directory Structure

Main components of the project are organized like this:

- `/bar/` → The main bar body
- `/bar_center_piece/` → Center insert parts
- `/bar_end/` → End pieces for the bar
- `/swivel/` → Swivel component to untwist lines
- `/trim/` → Depower trim and V-splitter
- `/quick_release/` → Quick release system (Coming soon)

Each component has its own folder, containing:

- Its own `README.md` file with details
- Subfolders indicating key design constraints (tube diameter, bearing type, rope diameter, etc.)
- Variants reflecting different design ideas

---

## Design Philosophy: Variant vs Version

| Term    | Meaning                                                             | How it's handled                       |
| ------- | ------------------------------------------------------------------- | -------------------------------------- |
| Variant | Different design direction or conceptual approach                   | Separate folder or filename indication |
| Version | Evolution of the same variant (small changes, tweaks, improvements) | Managed via Git version control        |

Example filename (STL version to print)

```
bar/carbon_tube_od24_id22mm/bar_end/leader_line_3mm/variant_7/bar-end_24_22_sls.*
```

- `bar` folder = part of the bar (vs QR etc.)
- `carbon_tube_od24_id22mm` = must use carbon tube with these OD/ID
- `leader_line_3mm` = must use 3mm leadr (steering) lines 
- `variant` = 7 
- `version` = _git commit id_

---

## Navigation Guide

To explore any component:

1. Navigate to: `hardware/3D_models/<component_name>/`
2. Open: `README.md`
3. Inside you will find:
   - Part purpose
   - Design constraints
   - 3D printing instructions
   - Relevant assembly notes
   - Images and previews
   - Available variants

Example links:

- [Bar Center Piece](hardware/bar/carbon_tube_od24_id22mm/bar_center_piece/README.md)
- [Swivel](hardware/swivel/sheeting_rope_4mm/bearing_ZR51103/swivel_housing_and_shaft/variant_4/README.md)
- Quick Release → Coming Soon

---

## General 3D Print Material Selection Guide

Unless explicitly specified otherwise in a part's `README.md`, the recommended default material for most 3D printed components is:

- [PA12 Nylon (3201PA-F)](https://jlc3dp.com/help/article/3201PA-F-Nylon) — proven material with excellent UV resistance, toughness, and durability. Field-tested over multiple seasons in snow and water kiting environments (-20°C to +30°C, freshwater and seawater conditions).

### Material Recommendations by Use Case

| Part / Component | Recommended Material | 3D Printing Technology | Notes |
|------------------|----------------------|-------------------------|-------|
| Most components (default) | [3201PA-F Nylon](https://jlc3dp.com/help/article/3201PA-F-Nylon) | SLS (Selective Laser Sintering) | Standard go-to material for durability and reliability |
| White-colored parts (e.g., left bar-end, QR case) | [Precimid-1172 Pro Nylon](https://jlc3dp.com/help/article/Precimid-1172-Pro) | SLS | Slightly more expensive, but produces white parts without need for dyeing |
| V-splitter and Cleat base | [PA12 HP Nylon](https://jlc3dp.com/help/article/PA12-HP-Nylon) | MJF (Multi Jet Fusion) | Offers better strength for small structural parts |
| Swivel metal parts (housing and shaft) | [316L Stainless Steel](https://jlc3dp.com/help/article/316L-Stainless-Steel) | SLM (Selective Laser Melting) | SLM 3D printed, or CNC machined (future: titanium possible) |
| Quick Release (QR) mechanism flat parts | Titanium sheet | Flat-cut (Laser, Waterjet) | From titanium sheet of exactly specified thickness |

> Note: Most online 3D printing services offer part dyeing; however, this is optional as the selected materials provide functional durability without color treatment.

> Note 2: Expect printing services like [JLC3PD](https://jlc3dp.com/) to warn you about the printing accuracy of some STL files. It's is safe to ignore as it's doesn't impact performance nor the safety of the prints. Here is a typical email sent by [JLC3PD](./images/jlc3dp_warning.jpeg).
