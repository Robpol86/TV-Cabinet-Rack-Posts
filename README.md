# TV Cabinet Rack Posts

3D printable rack posts with square holes for a Majestic EX 70-inch TV stand (Standout Designs).

* Cabinet dimensions (mm): **500** (W) x **460** (H) x **538** (D)
* Holes front offset: **112**
* Holes rear offset: **102**
* Top corner clearance with screw: **4.95**
* Door width: **20**
* Center of square hole distance: **465**

Acrylic door fans holder:

* Outer dimensions (mm): **403** (W) x **362** (H)
* Screw holes: **5**
* Screw hole nearest center offset: **15** (X) x **15** (Y)
* Screw hole spacing: **125**
* Fan hole: **135**
* Wire hole (slot): **5** (W) x **8** (H)
* Wire hole offset (nearest point) from nearest fan hole center: **0** (X) x **20** (Y)

## Protocase Notes and Design Constraints

> TODO: Apply .05" fillets to corners.

### Material

> TODO: Increase to 3 mm.

304 Stainless Steel (A240 TP304 2B) 14 Gauge (**1.981 mm**)

### Colors

[Proto-Stock Matt Black, Low Gloss, Smooth Hybrid](https://www.protocase.com/img/products/mcf/powdercoat/matte-black-proto-stock.jpg)

### Bend Radius

https://www.protocase.com/resources/bend-radius.php

Category        |           Thickness | Minimum Bend | Bend Radius
--------------- | ------------------: | ------------:| ----------:
Stainless Steel | 14 Gauge (1.981 mm) |      6.98 mm |      1.9 mm

### K-Factor

> TODO: Derive k-factor from changed bend radius in eDrawing file sent by Protocase for v0.1.

* **0.440**

## Cura Settings

This is for a **Monoprice Maker Select 3D Printer v2** configured as a **Prusa i3** printer in Cura.

* Profile: **0.2**
* Infill: **20%**
* Infill Pattern: **Octet**
* Build Plate Adhesion: **Skirt**
* Skirt Distance: **6 mm**
* Support Placement: **Touching Buildplate**
* Support Overhang Angle: **50**
* Support Horizontal Expansion: **2**
* *Add support blocker to the rack holes*

## Planned Use

This section is to determine if the depth of the rack is sufficient in the short term.

   U | Current      | Future L      | Future R
---: | ------------ | ------------- | -------------
   1 | Patch Panel  | Patch Panel   | Patch Panel
   2 | Switch       | Switch        | Switch
   3 |              | pfSense + RPi | pfSense + RPi
   4 |              | SAN + Worker  | SAN + Worker
   5 |              | SAN + Worker  | SAN + Worker
   6 | pfSense + FS |               | GPU + Worker
   7 | pfSense + FS |               | GPU + Worker
   8 | Drawer       | Drawer        |
   9 | UPS          | UPS           | UPS
  10 | UPS          | UPS           | UPS

### Depths

* Posts (inner): **461 mm**
* Protocase Rails (C2907-18): **457 mm**
* Travla Rails: *2 inches too long, will sit on shelf*
* Drawer: **348 mm**
* UPS: *No depth because the rails won't fit. Will sit on the bottom.*
