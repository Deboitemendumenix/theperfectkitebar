# ThePerfectKiteBar (TPKB) — Assembly Guide

- **Repository:** [github.com/aniva/theperfectkitebar](https://github.com/aniva/theperfectkitebar)
- **Last Updated:** November 19, 2025

---

## Table of Contents

1. [Overview](#overview)
2. [Bar Assembly Instructions (OD 22 mm — Variant 7)](#1-bar-assembly-instructions)
   - [Bill of Materials](#bar-bill-of-materials)
   - [Step-by-Step Assembly](#bar-step-by-step-assembly)
3. [Quick Release (QR) Assembly Instructions (4 mm Bolt — Variant 6)](#2-quick-release-qr-assembly-instructions)
   - [Bill of Materials](#qr-bill-of-materials)
4. [Swivel Assembly Instructions](#3-swivel-assembly-instructions)
   - [Bill of Materials](#swivel-bill-of-materials)
   - [Step-by-Step Assembly](#swivel-step-by-step-assembly)
5. [Trim Assembly Instructions (4 mm Sheeting Rope / 1.4 mm Front Line — Variant 3)](#4-trim-assembly-instructions)
   - [Bill of Materials](#trim-bill-of-materials)
6. [Annexes](#annexes)
   - [Ordering 3D Prints from JLC3DP](#annex-a-ordering-3d-prints-from-jlc3dp)
   - [AliExpress Ordering Notes](#annex-b-aliexpress-ordering-notes)
   - [Sample Rope Order (Fogh Marine)](#annex-c-sample-rope-order-fogh-marine)

---

## Overview

For line cutting targets and rope splicing lengths, refer to the [Rope Splicing & Cutting Dimensions Guide](rope_dimensions.md).

This guide provides complete bill-of-materials (BOM) tables and step-by-step instructions for building **ThePerfectKiteBar (TPKB)** using a carbon fiber tube with a **22 mm outer diameter (OD)** and **20 mm inner diameter (ID)**.

---

## 1. Bar Assembly Instructions

**Configuration:** Carbon Tube OD 22 mm / ID 20 mm — Variant 7

![Complete Bar Overview](../images/image12.png)

### Bar Bill of Materials

We recommend ordering 3D-printed parts through [JLC3DP](https://jlc3dp.com/). See [Annex A](#annex-a-ordering-3d-prints-from-jlc3dp) for ordering instructions.

#### 3D-Printed Bar Parts

| Item | Qty | Material & Ordering Notes | Model |
| :--- | :---: | :--- | :---: |
| **Bar End** | 2 | • 1× [SLS 3201PA-F Nylon](https://jlc3dp.com/help/article/3201PA-F-Nylon) (Black)<br>• 1× [SLS 1172Pro Nylon](https://jlc3dp.com/help/article/Precimid-1172-Pro) (White)<br>*(Order one of each color to distinguish left and right bar ends.)* | [STL](https://github.com/aniva/theperfectkitebar/blob/main/hardware/bar/carbon_tube_od22_id20mm/bar_end/leader_line_2.5mm/variant_7/bar-end_22-20_sls.stl) |
| **Bar End Knob** | 2 | • 1× [SLS 3201PA-F Nylon](https://jlc3dp.com/help/article/3201PA-F-Nylon) (Black)<br>• 1× [SLS 1172Pro Nylon](https://jlc3dp.com/help/article/Precimid-1172-Pro) (White)<br>*(Order one of each color to match the bar ends.)* | [STL](https://github.com/aniva/theperfectkitebar/blob/main/hardware/bar/carbon_tube_od22_id20mm/bar_end/leader_line_2.5mm/variant_7/bar-end-knob_22-20_sls.stl) |
| **Center Piece (M2.5 × 12 mm)** | 1 | [SLS 3201PA-F Nylon](https://jlc3dp.com/help/article/3201PA-F-Nylon) (Black) | [STL](https://github.com/aniva/theperfectkitebar/blob/main/hardware/bar/carbon_tube_od22_id20mm/bar_center_piece/variant_7/bar-center-piece_22_m2.5x12_sls.stl) |

#### 3D-Printed Assembly Tools

| Item | Qty | Material | Model |
| :--- | :---: | :--- | :---: |
| **Drill Guide** | 1 | SLM [316L Stainless Steel](https://jlc3dp.com/help/article/316L-Stainless-Steel) | [STL](https://github.com/aniva/theperfectkitebar/blob/main/hardware/tools/drilling/2mm_bolt/drill-guide_od22-od24_slm.stl) |
| **Drill Guide Adapter** | 2 | SLA [CBY Photosensitive Resin](https://jlc3dp.com/help/article/CBY-Photosensitive-Resin) | [STL](https://github.com/aniva/theperfectkitebar/blob/main/hardware/tools/drilling/2mm_bolt/drill-guide-adapter_od22_sla.stl) |
| **Alignment Jig** | 2 | SLA [CBY Photosensitive Resin](https://jlc3dp.com/help/article/CBY-Photosensitive-Resin) | [STL](https://github.com/aniva/theperfectkitebar/blob/main/hardware/tools/drilling/2mm_bolt/alignment_jig_od22_sla.stl) |

#### Hardware & Consumables

| Item | Qty | Specifications | Supplier Link |
| :--- | :---: | :--- | :---: |
| **Carbon Fiber Tube** | 1 | OD 22 mm × ID 20 mm | [AliExpress](https://www.aliexpress.com/item/1005006772445126.html) [[note](#annex-b-aliexpress-ordering-notes)] |
| **Heat-Shrink Tubing (Grip)** | 1 | OD 25 mm, 1 m length | [AliExpress](https://www.aliexpress.com/item/1005003672543021.html) [[note](#annex-b-aliexpress-ordering-notes)] |
| **O-Ring** | 2 | OD 19 mm × ID 15 mm, CS 2 mm | [AliExpress](https://www.aliexpress.com/item/1005001460478918.html) [[note](#annex-b-aliexpress-ordering-notes)] |
| **Bungee Cord** | 3 ft | 2.5 mm shock cord (Paracord Planet or equivalent) | [Amazon](https://www.amazon.ca/gp/product/B06XKXK98Z/) |
| **Leader Line (Red)** | 6 ft | Kingfisher Ropes — 2.5 mm Compact Braid Rope (Red) | [Fogh Marine](https://shop.foghmarine.com/compact-braid-25mm-rope.html) |
| **Leader Line (Blue)** | 6 ft | Kingfisher Ropes — 2.5 mm Compact Braid Rope (Blue) | [Fogh Marine](https://shop.foghmarine.com/compact-braid-25mm-rope.html) |
| **Stainless Steel Rings** *(for adjustable leaders)* | 2 | OD 9 mm × ID 6 mm, Stainless Steel | [AliExpress](https://www.aliexpress.com/item/1005003827310501.html) [[note](#annex-b-aliexpress-ordering-notes)] |
| **Hex Socket Cap Screws** *(for center piece)* | 2 | M2.5 × 12 mm, 316 Stainless Steel (DIN 912) | [McMaster-Carr](https://www.mcmaster.com/92290A062/) |
| **Hex Nuts** *(for center piece)* | 2 | M2.5, 316 Stainless Steel (DIN 934) | [McMaster-Carr](https://www.mcmaster.com/94150A310/) |
| **Countersunk Flat-Head Screws** *(for bar ends)* | 8 | M2 × 18 mm, **304** Stainless Steel (DIN 7991) | [McMaster-Carr](https://www.mcmaster.com/92125a101/) |
| **Hex Nuts** *(for bar ends)* | 8 | M2, 316 Stainless Steel (DIN 934) | [McMaster-Carr](https://www.mcmaster.com/94150A305/) |
| **Whipping Twine** *(for line splicing)* | 40 m | 0.8 mm waxed whipping twine | [Amazon](https://www.amazon.ca/dp/B08M25M796) |

---

### Bar Step-by-Step Assembly

#### 1. Cleaning the 3D-Printed Parts

> [!IMPORTANT]
> Before assembly, thoroughly clean all 3D-printed components. SLS and MJF prints often retain loose sintering powder packed inside internal channels and bolt holes. Use small brushes or stiff wire to clear all passages. Perform this step in a well-ventilated area, as it generates significant fine nylon dust.

#### 2. Installing the Bar-End Bungees

1. Thread the bungee cord through the bar end and cap:

   ![Insert bungee into bar end](../images/image8.png)

2. Tie a figure-8 stopper knot on one side, leaving a generous tail:

   ![Tie figure-8 knot on first side](../images/image35.png)

3. Tie a second figure-8 knot on the opposite side. Adjust the tension so the cap snaps snugly onto the bar end while remaining easy to pull out and secure:

   ![Tie second knot on opposite side](../images/image15.png)

4. Once satisfied with the tension, trim both bungee tails to approximately **1 cm** and tuck them neatly into the internal bar channel. Install the O-ring around the base of the bar end, then repeat the process for the second bar end:

   ![Trim bungee tails and install O-ring](../images/image14.png)

#### 3. Cutting the Carbon Tube & Drilling Holes

*(Use the 3D-printed Drill Guide, Adapters, and Alignment Jigs to cut the carbon tube to length and drill the center and bar-end mounting holes.)*

#### 4. Splicing & Installing the Adjustable Leader Lines

Follow this procedure for both **6 ft leader lines** (red and blue):

1. Measure from one end of the leader line and place marks at **12 cm** (the buried tail section) and **17 cm** (forming a **5 cm** eye loop):

   ![Mark leader line at 12 cm and 17 cm](../images/image36.png)

2. Bunch the braid slightly to loosen the weave at the 17 cm mark, and make another entry/exit mark **15 cm** further down the line:

   ![Mark 15 cm bury section](../images/image27.png)

3. Thread a splicing fid or looped pull-wire through the center of the line between those two points:

   ![Insert looped wire into line](../images/image33.png)

4. Hook the end of the leader line into the wire loop and pull it back through the core of the line to form the eye loop:

   ![Pull tail through core](../images/image24.png)

5. To create a smooth taper at the buried tail end, pull out and trim two or three strands at **2 cm** and **1 cm** from the tip:

   ![Taper the buried tail end](../images/image32.png)

6. Milk the outer braid smoothly over the buried tail until the tail disappears inside the core. Verify that the eye loop begins and ends cleanly at your reference marks:

   ![Smooth outer sleeve over buried tail](../images/image26.png)

7. Thread the spliced leader line into the bar end and anchor the loop into the internal recess. Ensure the line is seated tightly and deeply inside the channel:

   | | |
   | :---: | :---: |
   | <img src="../images/image11.png" alt="Seat leader line in bar end" width="420"> | <img src="../images/image16.png" alt="Leader line seated inside channel" width="420"> |

8. **Important:** Slide the stainless steel ring onto the leader line before splicing the second end. This ring will be used to fine-tune the leader line length:

   ![Slide stainless steel adjustment ring onto leader line](../images/image7.png)

9. Create an eye splice at the opposite end of the leader line following the exact same steps:

   ![Splice loop at opposite end](../images/image13.png)

10. Lock both splices in place using **0.8 mm whipping twine** stitched a few centimeters below each eye loop. Trim any frayed ends and lightly seal them with a lighter:

    | | |
    | :---: | :---: |
    | <img src="../images/image2.png" alt="Lock splice with whipping twine 1" width="420"> | <img src="../images/image1.png" alt="Lock splice with whipping twine 2" width="420"> |

#### 5. Final Bar Assembly & Heat-Shrink Grip Installation

1. On both bar ends, verify that the O-rings are seated and press the M2 hex nuts firmly into their internal hexagonal recesses. *(Tip: Thread an M2 bolt from the outside to pull each nut fully into its seat, then remove the bolt.)* Install **only one** bar end onto the carbon tube first (here, the red leader is installed on the left side):

   | | |
   | :---: | :---: |
   | <img src="../images/image20.png" alt="Seat M2 nuts and O-ring in bar end" width="420"> | <img src="../images/image37.png" alt="Install first bar end onto tube" width="420"> |

2. Slide the first section of heat-shrink tubing onto the bar, starting flush against the installed bar end and extending to approximately **4 mm** short of the center piece (**TODO** cm total length). Shrink the tubing evenly with a heat gun.

   > [!WARNING]
   > The bar ends and center piece are 3D-printed nylon—avoid concentrating excess heat directly on the plastic components.

3. Slide the center piece onto the tube, followed by the second section of heat-shrink tubing, and finally install the second bar end:

   ![Install center piece, second grip, and right bar end](../images/image28.png)

4. Shrink the second grip into place with the heat gun and fasten all M2 and M2.5 bolts:

   ![Shrink second grip with heat gun](../images/image29.png)

5. Your bar assembly is complete:

   ![Completed kite bar](../images/image22.png)

---

## 2. Quick Release (QR) Assembly Instructions

**Configuration:** 4 mm Bolt — Variant 6

### QR Bill of Materials

We recommend ordering 3D-printed parts through [JLC3DP](https://jlc3dp.com/). See [Annex A](#annex-a-ordering-3d-prints-from-jlc3dp) for details.

#### 3D-Printed QR Parts

| Item | Qty | Material | Model |
| :--- | :---: | :--- | :---: |
| **QR Case** | 1 | [SLS 3201PA-F Nylon](https://jlc3dp.com/help/article/3201PA-F-Nylon) (Black) | [STL](https://github.com/aniva/theperfectkitebar/blob/749f86c8f5551f4d8672b70101d38b576acc4239/hardware/quick_release/4mm_bolt/titanium_gr5_0.125_0.187in/variant_6/qr-case_m4_sls.stl) |
| **Slider Rope Wheel** | 1 | [MJF PA12-HP Nylon](https://jlc3dp.com/help/article/PA12-HP-Nylon) | [STL](https://github.com/aniva/theperfectkitebar/blob/749f86c8f5551f4d8672b70101d38b576acc4239/hardware/quick_release/4mm_bolt/titanium_gr5_0.125_0.187in/variant_6/slider-rope-wheel_7x12.5.stl) |

#### QR Hardware

| Item | Qty | Specifications | Supplier Link |
| :--- | :---: | :--- | :---: |
| **QR Titanium Spacer Tube** | 2 × 13 mm | OD 6 mm × ID 4 mm (cut two 13 mm spacers from stock tube) | [AliExpress](https://www.aliexpress.com/item/1005004429547885.html) [[note](#annex-b-aliexpress-ordering-notes)] |

---

## 3. Swivel Assembly Instructions

### Swivel Bill of Materials

We recommend ordering 3D-printed parts through [JLC3DP](https://jlc3dp.com/). See [Annex A](#annex-a-ordering-3d-prints-from-jlc3dp) for details.

#### 3D-Printed Swivel Parts

| Item | Qty | Material | Model |
| :--- | :---: | :--- | :---: |
| **Swivel Cap** | 1 | [SLS 3201PA-F Nylon](https://jlc3dp.com/help/article/3201PA-F-Nylon) | [STL](https://github.com/aniva/theperfectkitebar/blob/c854ea01d97799a941306836fb42b6cf8d601892/hardware/swivel/sheeting_rope_4mm/bearing_ZR51103/swivel-cap/variant_4/swivel-cap_sls.stl) |
| **Swivel Cap Retainer** | 1 | [SLS 3201PA-F Nylon](https://jlc3dp.com/help/article/3201PA-F-Nylon) | [STL](https://github.com/aniva/theperfectkitebar/blob/c854ea01d97799a941306836fb42b6cf8d601892/hardware/swivel/sheeting_rope_4mm/bearing_ZR51103/swivel-cap/variant_4/swivel-cap-retainer_sls.stl) |
| **Swivel Housing** | 1 | SLM [316L Stainless Steel](https://jlc3dp.com/help/article/316L-Stainless-Steel) | [STL](https://github.com/aniva/theperfectkitebar/blob/c854ea01d97799a941306836fb42b6cf8d601892/hardware/swivel/sheeting_rope_4mm/bearing_ZR51103/swivel_housing_and_shaft/variant_4/swivel-housing_4.5x42x17x3x9_slm.stl) |
| **Swivel Shaft** | 1 | SLM [316L Stainless Steel](https://jlc3dp.com/help/article/316L-Stainless-Steel) | [STL](https://github.com/aniva/theperfectkitebar/blob/c854ea01d97799a941306836fb42b6cf8d601892/hardware/swivel/sheeting_rope_4mm/bearing_ZR51103/swivel_housing_and_shaft/variant_4/swivel-shaft_17x3x9_slm.stl) |

#### Swivel Hardware & Lines

| Item | Qty | Specifications | Supplier Link |
| :--- | :---: | :--- | :---: |
| **Ceramic Thrust Bearing** | 1 | ZR51103 Ceramic Bearing | [AliExpress](https://www.aliexpress.com/item/1005004924283394.html) [[note](#annex-b-aliexpress-ordering-notes)] |
| **Safety Line Metal Ring** | 1 | M3 × 15 mm ID, 304 Stainless Steel Welded Round Ring | [AliExpress](https://www.aliexpress.com/item/1005005646746570.html) [[note](#annex-b-aliexpress-ordering-notes)] |
| **Safety Line** | 6 ft | 2.5 mm Marlow Excel D12 Max SK78 Rope | [Fogh Marine](#annex-c-sample-rope-order-fogh-marine) |

---

### Swivel Step-by-Step Assembly

#### 1. Splicing the Power Line & Chafe Cover

1. Form an eye loop at one end of the power line: bury **20 cm** of tail and leave **5 cm** for the eye loop. **Do not** stitch the loop yet:

   ![Splice 20 cm and leave 5 cm loop](../images/image4.png)

2. Cut **97 cm** of Dyneema chafe cover (shaft sleeve). Open a small separation in the weave near one end so that the short tail of the cover is roughly **¾ the length of the eye loop**. Thread the power line into the chafe cover tail-first (sliding the cover over the line), then bring it back out on the opposite side of the loop in the same manner so the cover tails wrap around the loop base:

   ![Insert power line through chafe cover](../images/image10.png)

3. Once threaded, the assembly should look like this:

   ![Power line threaded through chafe cover](../images/image25.png)

4. Whip/stitch the chafe cover and power line together up to the base of the loop, and bury the cover tail into the loop. **Do not** splice the far end of the rope yet:

   ![Stitch chafe cover to base of loop](../images/image34.png)

#### 2. Assembling the Swivel & Power Line

1. Assemble the stainless steel swivel housing, ceramic bearing, and swivel shaft as shown, ensuring all components are seated squarely:

   ![Assemble swivel components](../images/image18.png)

2. Using a pull-wire, draw the spliced eye loop of the power line through the swivel assembly:

   ![Pull power line loop through swivel](../images/image23.png)

3. Stop pulling once the eye loop emerges through the swivel shaft as shown:

   ![Loop positioned inside swivel](../images/image21.png)

4. Pass the free end of the power line through the eye loop and cinch the lark's head knot down tightly against the swivel shaft:

   ![Tighten knot inside swivel](../images/image6.png)

5. Install the swivel cap and retainer, making sure the safety-line pass-through hole is aligned with the channel behind the knot:

   ![Install swivel cap and align safety line hole](../images/image38.png)

6. Stretch the chafe cover taut along the power line and splice/bury the top end of the cover into the core of the power line. Stitching is not required at this end, as it will be clamped by the trim assembly:

   ![Splice top end of chafe cover into power line](../images/image5.png)

#### 3. Assembling & Routing the Safety Line

1. Splice an eye loop onto one end of the **6 ft** (2.5 mm) safety line using the same splicing technique used for the leader lines, capturing either the stainless steel ring or the swivel:

   ![Splice safety line onto ring](../images/image19.png)

2. Route both the safety line and the sleeved power line through the center piece of the bar:

   ![Route safety line and power line through bar center piece](../images/image3.png)

3. Slide the trim components onto the lines. Position the trim assembly so that the power line between the cleat base and the base is approximately **65 cm**:

   ![Install trim components with 65 cm power line between cleat base and base](../images/image9.png)

   ![Completed swivel, bar, and trim assembly](../images/image17.png)

---

## 4. Trim Assembly Instructions

**Configuration:** 4 mm Sheeting Rope / 1.4 mm Front Line — Variant 3

### Trim Bill of Materials

We recommend ordering 3D-printed parts through [JLC3DP](https://jlc3dp.com/). See [Annex A](#annex-a-ordering-3d-prints-from-jlc3dp) for details.

#### 3D-Printed Trim Parts

| Item | Qty | Material | Model |
| :--- | :---: | :--- | :---: |
| **Cleat Base** | 1 | [MJF PA12-HP Nylon](https://jlc3dp.com/help/article/PA12-HP-Nylon) | [STL](https://github.com/aniva/theperfectkitebar/blob/749f86c8f5551f4d8672b70101d38b576acc4239/hardware/trim/sheeting_rope_4mm/cleat/variant_3/cleat-base_4_mjf.stl) |
| **Trim Stopper** | 1 | [SLS 3201PA-F Nylon](https://jlc3dp.com/help/article/3201PA-F-Nylon) | [STL](https://github.com/aniva/theperfectkitebar/blob/749f86c8f5551f4d8672b70101d38b576acc4239/hardware/trim/sheeting_rope_4mm/cleat/variant_3/trim_stopper_4_mjf.stl) |
| **V-Splitter (1.4 mm)** | 1 | [MJF PA12-HP Nylon](https://jlc3dp.com/help/article/PA12-HP-Nylon) | [STEP](https://github.com/aniva/theperfectkitebar/blob/749f86c8f5551f4d8672b70101d38b576acc4239/hardware/trim/sheeting_rope_4mm/front_line_1.4mm/v-splitter/variant_3/v-splitter_4x14_mjf.step) |

---

## Annexes

### Annex A: Ordering 3D Prints from JLC3DP

1. Create an account on JLC3DP and open the [3D Printing Quote page](https://jlc3dp.com/3d-printing-quote).
2. Upload the STL/STEP models linked in the Bill of Materials tables above.
3. Select the specified printing process and material (**SLS 3201PA-F**, **SLS 1172Pro**, **MJF PA12-HP**, **SLA CBY Resin**, or **SLM 316L Stainless Steel**) for each part.
4. When prompted for part classification/description (used by JLC3DP to verify that parts are not firearm components), select **"Toy -> Other"** and enter **"kite bar"** in the description field.
5. Save each configured item to your cart.
6. **Note:** You may receive a [automated review/warning email](https://github.com/aniva/theperfectkitebar/blob/main/../images/jlc3dp_warning.jpeg) regarding thin walls or part geometry; simply reply to confirm and authorize JLC3DP to proceed with production.

### Annex B: AliExpress Ordering Notes

> [!NOTE]
> AliExpress product pages often bundle multiple sizes or variants under a single listing URL. **Always double-check the exact dimensions and material specifications in the Bill of Materials table before placing your order.**

### Annex C: Sample Rope Order (Fogh Marine)

Below is a reference rope and cleat order from **Fogh Marine** with typical lengths and uses:

| # | Product | Length / Qty | Est. Cost | Application |
| :---: | :--- | :---: | :---: | :--- |
| 1 | **Racing Micro Cleat** — 1–6 mm (1/32"–1/4") Rope | 1 | — | Trim cleat |
| 2 | **Dyneema Chafe Cover XS** (4–6 mm), Black | 4 ft | $6.60 ($1.65/ft) | Protective sleeve over power line for smoother bar travel |
| 3 | **4 mm Marlow Excel D12 Max SK78 Rope** | 7 ft | $15.40 ($2.20/ft) | Center power line |
| 4 | **2.5 mm Compact Braid Rope (Red)** | 3 ft | $2.40 ($0.80/ft) | Pigtails on steering lines (left) |
| 5 | **2.5 mm Compact Braid Rope (Blue)** | 3 ft | $2.40 ($0.80/ft) | Pigtails on steering lines (right) |
| 6 | **2.5 mm Compact Braid Rope (Red)** | 6 ft | $6.60 ($1.10/ft) | Left rear leader line |
| 7 | **2.5 mm Compact Braid Rope (Blue)** | 6 ft | $6.60 ($1.10/ft) | Right rear leader line |
| 8 | **2.5 mm Marlow Excel D12 Max SK78 Rope** | 15 ft | $20.25 ($1.35/ft) | Safety line and adjustable front-line pigtails |
