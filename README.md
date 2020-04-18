# TV Cabinet Rack Posts

3D printable rack posts with square holes for a Majestic EX 70-inch TV stand (Standout Designs).

* Cabinet dimensions (mm): **500** (W) x **460** (H) x **538** (D)
* Holes front offset: **112**
* Holes rear offset: **102**
* Top corner clearance with screw: **4.95**
* Door width: **20**
* Center of square hole distance: **465**

## Protocase Notes and Design Constraints

### Material

304 Stainless Steel (A240 TP304 2B) 14 Gauge (**1.981 mm**)

### Colors

Candidates:

* Proto-Stock Matt Black, Low Gloss, Smooth Hybrid
    * https://www.protocase.com/img/products/mcf/powdercoat/matte-black-proto-stock.jpg
* Jet Black, Medium Gloss, Smooth Polyester-Epoxy Blend
    * https://www.protocase.com/img/products/mcf/powdercoat/jet-black.jpg
* Federal Standard 595 Color FS 17038 Black, Full Gloss, Smooth Polyester Powder
    * https://www.protocase.com/img/products/mcf/powdercoat/federal-standard-595-17038.jpg
* Federal Standard 595 Color FS 37038 Flat Black, Smooth Flat Epoxy Poweder
    * https://www.protocase.com/img/products/mcf/powdercoat/federal-standard-595-37038-epoxy.jpg

### Silkscreen

TODO unit numbers and lines separating each unit

### Marking

TODO version number of model, corresponds with git tag, watch out for mirroring

### Bend Radius

https://www.protocase.com/resources/bend-radius.php

Category        |           Thickness | Minimum Bend | Bend Radius
--------------- | ------------------: | ------------:| ----------:
Stainless Steel | 14 Gauge (1.981 mm) |      6.98 mm |      1.9 mm

### K-Factor

Protocase doesn't list it anywhere, but searching online I'm getting these numbers:

* **0.480**
    * Brophy (probably for softer steel)
* **0.450** (or lower)
    * http://sheetmetal.me/formulas-and-functions/k-factor/
* **0.440**
    * Fusion 360 default
* **0.435**
    * https://www.mcadcentral.com/threads/k-factor.23221/#post-127572
* **0.433**
    * https://www.youtube.com/watch?v=f3DC0wyLFv0 (comment from Marc Prudhomme)

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
