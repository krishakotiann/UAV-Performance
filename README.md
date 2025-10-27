# Design and Analysis of Propeller with Winglets for Improved UAV Performance  

## Overview  
This project investigates the **aerodynamic enhancement of UAV propellers** through the integration of **winglets**. Using the **NACA 4412 airfoil**, three winglet configurations—**vertical winglet**, **wingtip fence**, and **backswept winglet**—were designed, fabricated, and experimentally analyzed.  
The main objective was to **reduce induced drag** and **improve thrust efficiency** for small UAVs by studying how geometric modifications affect aerodynamic performance.

---

## Objectives  
- Design UAV propellers with and without winglets using the NACA 4412 airfoil.  
- Fabricate propellers using **3D printing (ABS material)** for experimental testing.  
- Measure thrust under static and freestream conditions to compare performance.  
- Identify the most efficient winglet configuration for maximum thrust improvement.  

---

## Methodology  

### 1. CAD Modeling  
- Propellers designed in **CATIA V5**.  
- Key parameters:  
  - Diameter: 7 in  
  - Pitch: 4.5 in  
  - Root Chord: 16 mm  
  - Tip Chord: 7 mm  
  - Twist Angles: 12°, 7°, 4° (root to tip)  

### 2. Winglet Configurations  
| Winglet Type | Description | Key Parameters |
|---------------|--------------|----------------|
| **Vertical Winglet** | Simple upward extension | 15° sweep, 9 mm height |
| **Wingtip Fence** | Double-sided vertical plates | 9 mm height, 3 mm tip height |
| **Backswept Winglet** | Smooth, curved extension swept backward | 45° sweep, 9.1 mm height |

### 3. Fabrication  
- **FDM 3D printing** using **ABS filament**.  
- Printing parameters: 0.2 mm nozzle, 100% infill, fine layer height.  
- Orientation optimized to minimize overhangs and improve strength.

### 4. Experimental Testing  
- Conducted between **4000–7000 RPM** using a **1400 KV BLDC motor** and **11.1V LiPo battery**.  
- Thrust measured via **digital scale** in two conditions:  
  - Static (no flow)  
  - Freestream (20 m/s airflow in wind tunnel)  
- RPM monitored using a **digital tachometer**.  
- Data plotted as **Thrust vs RPM** and **% Thrust Increment vs RPM**.

---

## Key Results  

| Configuration | Avg. Thrust Gain (Static) | Avg. Thrust Gain (Freestream) | Observation |
|----------------|----------------------------|-------------------------------|--------------|
| **Vertical Winglet** | Up to **71%** | Up to **67%** | Most effective in reducing induced drag |
| **Wingtip Fence** | Up to **43%** | Up to **42%** | Moderate gains, especially at lower RPM |
| **Backswept Winglet** | Up to **14%** | Up to **10%** | Least improvement observed |

**Highlights:**  
- All winglet designs improved thrust compared to the baseline.  
- The **vertical winglet** consistently delivered the **highest aerodynamic benefit**.  
- Performance gains were most significant at **lower RPMs**, where tip vortices dominate.  

---

## Conclusion  
Winglet integration effectively enhances **UAV propeller aerodynamic efficiency**.  
Among all tested designs, the **vertical winglet** demonstrated the highest improvement in thrust performance, confirming its ability to minimize tip vortices and induced drag.  
This provides a **cost-effective modification** to enhance **endurance**, **stability**, and **energy efficiency** in small UAVs.

---

## Future Work  
- Perform **CFD simulations** to analyze vortex flow and pressure distribution.  
- Investigate **new winglet geometries** such as curved, split, or adaptive designs.  
- Test at **different flight velocities and angles of attack**.  
- Apply **machine learning** for automatic shape optimization.

---

## Tools & Technologies  
- **Design:** CATIA V5  
- **Fabrication:** FDM 3D Printing (ABS)  
- **Testing:** Thrust Rig, Tachometer, Wind Tunnel (20 m/s)  
- **Analysis:** Experimental thrust data and performance comparison  

---

## Citation  
If you use this work, please cite:  
> Kotian, K., Navaz Fahir, S. M., & Lalit Kishore, P. (2025). *Design and Analysis of Propeller with Winglets for Improved UAV Performance.* SRM Institute of Science and Technology.

---

## Authors  
- **Krisha Kotian Manish**  
- **S. Mohamed Navaz Fahir**  
- **Lalit Kishore P**  
- **Guide:** Dr. R. Mohammed Arif (Assistant Professor, Dept. of Aerospace Engineering, SRM IST)

---

## Visuals  
Include the following images in your repository for better presentation:  
- CAD renders of each winglet configuration  
- Experimental setup photos  
- Thrust vs RPM graphs  

---

## Institution  
**SRM Institute of Science and Technology, Kattankulathur, Chennai**  
Department of Aerospace Engineering – Batch of 2025
