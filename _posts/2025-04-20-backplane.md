---
layout: post
title: "My first PCB: The Backplane Board for UniUD E-Racing"
---

During my first year with the **UniUD E-Racing Team** ([formulasae.uniud.it](https://formulasae.uniud.it/)), I had to redesign the **Backplane board**, a critical component for the vehicle's control system. 

The Backplane acts as the central interconnection hub, managing all input connectors and hosting the Brain and Telemetry boards via dedicated pin header connectors. My role involved the entire development cycle, from conceptual schematics to the physical assembly and testing.

### Phase 1: Schematic Design
Using **Altium Designer**, I developed the updated schematics to improve signal routing and reliability. This phase was crucial for defining the electrical connections between the core processing units and the vehicle's sensors.

<div style="width: 100%; margin: 20px 0;">
  <img src="/assets/images/backplane-schematic.png" style="display: block; max-width: 100%; height: auto; margin: 0 auto; border: 1px solid #ddd;">
  <p align="center" style="font-size: 0.9em; color: #666; margin-top: 10px;"><i>Figure 1: Detailed schematic capture in Altium Designer.</i></p>
</div>

### Phase 2: PCB Layout (2D & 3D)
The layout was engineered to be compact yet robust. I optimized the trace routing in the **2D layout** to ensure high-speed data integrity, while the **3D model** was essential to verify clearances and the mechanical fit of the pin headers.

<div style="display: flex; justify-content: space-between; gap: 10px; width: 100%; margin: 20px 0;">
  <div style="flex: 1;">
    <img src="/assets/images/backplane-2d.png" style="display: block; width: 100%; height: auto; border: 1px solid #ddd;">
  </div>
  <div style="flex: 1;">
    <img src="/assets/images/backplane-3d.png" style="display: block; width: 100%; height: auto; border: 1px solid #ddd;">
  </div>
</div>
<p align="center" style="font-size: 0.9em; color: #666;"><i>Figure 2: 2D and 3D views of the PCB layout in Altium Designer.</i></p>

### Phase 3: Assembly & On-Vehicle Integration
Beyond the design, I performed the **manual soldering** of all connectors and headers. The final stage involved the physical integration: the Backplane successfully hosts the **Brain** and **Telemetry** boards, acting as the foundation of the electronics stack.

<div style="width: 100%; margin: 20px 0;">
  <img src="/assets/images/backplane-on-car.png" style="display: block; max-width: 100%; height: auto; margin: 0 auto; border: 1px solid #ddd;">
  <p align="center" style="font-size: 0.9em; color: #666; margin-top: 10px;"><i>Figure 3: The Backplane fully assembled with Brain and Telemetry boards, mounted inside the racing car.</i></p>
</div>

### Technical Conclusion
By redesigning the Backplane, we achieved a more modular and reliable electronics suite. This project allowed me to bridge the gap between complex EDA software and practical hardware implementation in a high-performance environment.