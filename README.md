# Bat-Board PCB

A custom-designed PCB created in EasyEDA, built from scratch with custom footprints, clean trace routing, and a Bat-signal silkscreen graphic because empty PCB space is a wasted opportunity.

![final pcb preview](https://cdn.hackclub.com/01a077be-89bc-7fcd-964a-31bdf6fcb4f8/image.png)

## Overview

This project is a custom circuit board designed to demonstrate schematic capture, footprint mapping, and PCB layout optimization. Everything from mapping individual component footprints on EasyEDA to component placement, routing, and silkscreen customization was handled in-house.

## Features

* **Custom Schematic Capture:** Sourced and mapped all necessary components directly within EasyEDA.
* **Optimized PCB Layout:** Arranged components manually to keep traces as short and clean as possible.
* **Custom Silkscreen Design:** Includes personal project details alongside a custom Bat-signal silkscreen graphic on the top layer.
* **Production Ready:** Built with standard manufacturing clearances, ready to export Gerber files for fab ordering.

## Circuit & Design Process

1. **Schematic Design:** Mapped out all component connections, pinouts, and power/ground nets to ensure proper signal flow.
2. **Footprint Assignment:** Hunted down and verified exact physical footprints on EasyEDA so components match physical parts during soldering.
3. **Component Placement & Routing:** Imported netlists into the PCB editor and manually arranged components to minimize cross-routing and congestion.
4. **Graphics & Aesthetics:** Added custom silkscreen text and vector artwork on the front silkscreen layer (`F.Silkscreen`).

## Gallery

| Schematic Draft | Component Footprint Layout |
| :---: | :---: |
| ![schematic draft](https://cdn.hackclub.com/01a077bd-a759-7f15-9d54-73a136cca92a/image.png) | ![pcb footprint layout](https://cdn.hackclub.com/01a077be-043e-73ca-9b8f-54bcab9387b2/image.png) |

| Bat-Signal Silkscreen | PCB Final Preview |
| :---: | :---: |
| ![batman silkscreen detail](https://cdn.hackclub.com/01a077be-2ad8-70bb-a5dc-cddcbaac30a2/image.png) | ![final pcb preview](https://cdn.hackclub.com/01a077be-89bc-7fcd-964a-31bdf6fcb4f8/image.png) |

## How to Assemble

1. **Export Gerbers:** Generate and download the Gerber files from the EasyEDA editor.
2. **Order PCB:** Submit the zip file to your preferred PCB fab (e.g., JLCPCB).
3. **Source Parts:** Order the required components based on the schematic footprints.
4. **Solder Components:** Solder smaller passive components and ICs first, followed by larger connectors.

## Known Issues

* Pending PCB fabrication funding before ordering physical boards and testing hardware assembly.

## Credits

* **Designer:** Pratham Rupera (`theonlydesigner`)
* **EDA Tool:** EasyEDA
* **Platform:** Built for Hack Club
