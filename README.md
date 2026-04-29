# **⚙️ Planetary Gear Engine (Community Edition)**

<img width="400" height="400" alt="Planetary_Gear_Gen_T1" src="https://github.com/user-attachments/assets/701e156d-261a-4c76-baa7-844ff80fe769" />

A mathematically precise, browser-based planetary gear generator. Visualize assemblies in real-time and export perfect 2D profiles (SVG, DXF) for laser cutting, CNC routing, and blueprinting.

## **🚀 Quick Start**

Try the tool right now: https://madeinnewyork87.github.io/OpenPlanetaryGearGen/GearGen-T1.html

OR

This entire application is bundled into a single, HTML file.

1. Download or clone this repository.  
2. Double-click planetary\_gear\_free.html to open it in any modern web browser.  
3. Start designing

## **✨ Free Features (Tier 1\)**

* **Kinematic Validation:** The engine restricts inputs to mathematically valid planetary configurations (Sun, Planet, and Ring ratios).  
* **Live Hardware-Accelerated Preview:** Drag to rotate, scroll to zoom, and watch your gear train spin in real-time.  
* **Precise Clearances:** Manually adjust the Module (Size), Pressure Angle, Clearance Coefficients, and Backlash.  
* **2D Manufacturing Exports:** Export perfectly optimized vectors as **SVG** or **DXF** (R12 ASCII) tailored for laser cutters and waterjets.  
* **Profile Saving:** Save and load your gear configurations locally via JSON.

## **💎 Need 3D Printing or CAD Exports?**

If you need to 3D print your gears or integrate them into professional assemblies (SolidWorks, Fusion 360, Inventor), check out the upgraded tiers.

### **🛠️ [Tier 2: Maker Edition](https://m87.lemonsqueezy.com/checkout/buy/25be5fef-a293-4d93-89ea-2c64810bb275) \- $19.99 Lifetime**

Built for 3D printing enthusiasts.

* **3D Mesh Export:** High-resolution manifold **OBJ/STL** exports.  
* **Herringbone Gears:** Toggle Double Helical designs with adjustable twist angles.  
* **Conical Bevels:** Slice the top and bottom layers of your gears into perfect circular cones to eliminate "elephant's foot" on FDM/SLA prints.

### **🚀 [Tier 3: Pro Edition](https://m87.lemonsqueezy.com/checkout/buy/63d6f42c-d4bf-4de5-b1c3-5c9cb39d05a1) \- $49.99 Lifetime**

Built for professional mechanical engineers and CAD designers.

* **Solid B-Rep STEP Export:** Export mathematically true, smooth ISO-10303-21 STEP solids (no faceted meshes\!).  
* **Profile Shifting (![][image1]):** Independently adjust sun and planet profile shifts to dictate exact operative center distances and prevent undercutting.  
* **Quality Control (MOP):** Dynamically calculates Measurement Over Pins based on your designated pin diameter.  
* **Stress Analytics:** Real-time Lewis Root Stress (MPa) estimations based on input torque (Nm).

<img width="400" height="400" alt="Planetary_Gear_PRO" src="https://github.com/user-attachments/assets/2b70e860-a737-49f5-b7f0-0b5d653ca819" />

### **Feature Comparison**

| Feature | Tier 1 (Free) | Tier 2 (Maker) | Tier 3 (Pro) |
| :---- | :---- | :---- | :---- |
| **Open Source (MIT License)** | ✅ | ❌ | ❌ |
| Real-time 3D Preview | ✅ | ✅ | ✅ |
| 2D Vector Export (SVG/DXF) | ✅ | ✅ | ✅ |
| 3D Mesh Export (OBJ) | ❌ | ✅ | ✅ |
| Double Helical (Herringbone) | ❌ | ✅ | ✅ |
| Anti-Elephant's Foot Bevels | ❌ | ✅ | ✅ |
| Profile Shift Controls (![][image1]) | ❌ | ❌ | ✅ |
| Solid CAD Export (STEP) | ❌ | ❌ | ✅ |
| QC (MOP) & Stress Analytics | ❌ | ❌ | ✅ |

## **🚀 Support the Developer**

I build independent, math-heavy engineering tools. If this free community edition saved you hours of CAD sketching, **the best way to support the project is to upgrade to the Maker or Pro tiers\!**

## **📄 Licensing & Open Source**

**Tier 1 (Community Edition):** This version is fully open-source and available under the [MIT License](http://docs.google.com/LICENSE). You are free to view, modify, and distribute the source code of this tier, as well as use the exported DXF and SVG files for any commercial or personal project.

**Tier 2 (Maker) & Tier 3 (Pro):** These upgraded versions are **closed-source and proprietary**. Purchasing these tiers grants you a single-user license to run the software and use the exported files (OBJ, STL, STEP, SVG, DXF) commercially, but the source code itself may not be redistributed, shared, published, or copied.

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAoAAAAVCAYAAAB/sn/zAAAAx0lEQVR4XmNgGAVUB7KysiZycnK+ML6ioqIdUMwNWQ0jUIGPvLz8FSguBvK1gfQFIL4B1KAPVqWgoHAKqNMWpgso+R+IDwCxJ4gN1FQOlhAVFeWBKZKRkZEGSv4DSrrAxLACkAKgwudAWgldDg6ATuAAKtoKxK1IwszGxsasYBZQ4hcQrwWZAjIN5DaYKiDbEuQcUBCIAzmvQJJAEw8B6XdA2gOkCEg3Avm7YZoYoSY+AeIaJSUlOSD9F8QHKlwFNE0IpnCwAwBDkS4d5OiLPAAAAABJRU5ErkJggg==>
