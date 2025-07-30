
#  Robotic Arm Joint – 3D Printing Setup & Material Recommendation

##  STL File
This project includes a 3D printable **robot arm joint** that was converted into STL format and prepared for FDM printing using **AnkerMake Studio**.

##  Slicer: AnkerMake Studio

We used AnkerMake Studio to slice the STL file and prepare it for printing on the **AnkerMake M5** printer with a **0.4 mm nozzle**.

### Screenshot of the final slicing setup:
[View slicing screenshot (PDF)](docs/slicing-screenshot.pdf)

---

## Material Recommendation: **PETG**

###  Why PETG?
PETG (Polyethylene Terephthalate Glycol) was chosen over standard PLA+ because:

- **High impact resistance** — ideal for joints and moving parts.
- **Better flexibility** — less brittle than PLA+.
- **Heat resistance up to ~80°C** — suitable for mechanical parts that might face friction or motor heat.
- **Low warping** — prints well on open printers like the AnkerMake M5.
- **Strong inter-layer adhesion** — critical for load-bearing parts like robotic joints.

---

## Final Printing Settings (AnkerMake Studio)

| Setting                     | Value               |
|----------------------------|---------------------|
| **Printer**                | AnkerMake M5 (0.4mm)|
| **Material**               | PETG (recommended), PLA+ (used) |
| **Layer Height**           | 0.2 mm              |
| **Wall Line Count**        | 3                   |
| **Top/Bottom Layers**      | 5                   |
| **Infill Density**         | 40% (Grid)          |
| **Print Speed**            | 50 mm/s             |
| **Supports**               | Enabled (Touching buildplate) |
| **Adhesion**               | Brim                |
| **Model Size**             | 64.76 x 53.08 x 77.80 mm |
| **Filament Used**          | 11.82 m (35.26 g)   |
| **Estimated Time**         | 1h 30m              |



