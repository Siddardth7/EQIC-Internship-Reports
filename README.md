# EQIC Internship Reports – Design and Manufacturing Internship

## Overview
This repository documents a comprehensive industrial internship undertaken at EQIC (Engineering Quality Improvement Centre) during 2025. The internship focused on the end‑to‑end design and manufacturing of a plastic spool product, covering CAD modelling, injection mould design, process planning, tooling manufacture, prototype production, mechanical testing and documentation.

The repository collates final reports, drawings, bills of materials and extracted figures from the internship deliverables. It aims to provide future interns and engineering students with a detailed reference on industrial product development, particularly injection moulding of thermoplastics.

## Internship Objectives
- **Product design** – generate a robust CAD model for a plastic spool used in packaging applications, incorporating ergonomic features and manufacturability considerations.
- **Mould design & manufacture** – design a two‑plate injection mould with appropriate gating, runner and cooling systems; prepare detailed manufacturing drawings; oversee CNC machining and assembly of mould components.
- **Process planning & optimisation** – develop an injection moulding process plan including melt temperature, injection velocity, packing and cooling parameters; optimise cycle time and quality.
- **Analysis & validation** – perform finite element analysis (FEA) on the spool to ensure structural integrity; simulate mould filling and cooling behaviour; adjust the design to reduce stresses and shrinkage.
- **Testing & evaluation** – manufacture prototypes using the new mould; conduct mechanical testing (tensile, bending and impact) and dimensional inspection; analyse results and recommend improvements.
- **Documentation** – compile detailed reports, drawings, BOM lists, process flow diagrams and test data for handover and future reference.

## Work Packages

### 1. Product Design & CAD Modelling
The internship began with conceptual design of the spool. Various geometries were evaluated for strength, material usage and ease of winding. SolidWorks was used to create 3D models and engineering drawings with tolerances. The final design employed fillets, ribs and hollow sections to balance rigidity and weight. Assembly drawings and exploded views were prepared for communication with manufacturing.

### 2. Injection Mould Design
A two‑plate injection mould was designed to produce the spool in a single shot. Key design decisions included:
- **Parting plane and core/cavity layout** – chosen to ensure easy ejection and minimise undercuts.
- **Gating and runner system** – a balanced runner network feeding a centrally located pin gate to promote uniform filling.
- **Ejection system** – a combination of ejector pins and a stripper plate to release the part without deformation.
- **Cooling channels** – optimised placement of water lines to reduce cycle time and prevent warpage.
Detailed mould drawings specifying material, heat treatment and surface finish were generated. Manufacturing tolerances adhered to industry standards.

### 3. Manufacturing & Assembly
The mould components (plates, inserts, cores, cavity blocks, sprue bush) were machined using CNC milling and turning. Hardened tool steel was selected for wear surfaces. A BOM enumerated raw materials, standard parts (guide pillars, bushings, springs) and purchased components. The assembled mould was fitted on a 150‑ton injection moulding machine for trials.

### 4. Process Planning
A process sheet was prepared specifying:
- **Material selection** – high‑density polyethylene (HDPE) chosen for its toughness and ease of moulding.
- **Machine settings** – melt temperature (190‑200°C), mould temperature (40°C), injection pressure and time, packing pressure, cooling time.
- **Cycle time optimisation** – experiments determined an optimum cycle of ~25 s balancing part quality and productivity.
Process capability studies were performed to ensure consistent quality.

### 5. Simulation & Structural Analysis
FEA using ANSYS was carried out on the spool model to evaluate stress distribution under axial and radial loads typical of winding operations. The analysis guided local thickness increases and rib placement. Mould flow simulation predicted filling patterns, air entrapment and cooling rates. These simulations reduced trial‑and‑error in the workshop.

### 6. Prototype Testing
Samples moulded with the new tooling were tested on a universal testing machine. Tensile and bending tests measured modulus, strength and elongation. Results were compared with material datasheets to validate process settings. Dimensional checks verified compliance with drawing tolerances and identified areas for tool adjustment. Photographs and graphs of test results are provided in the `figures/` folder.

## Repository Contents
- `reports/` – internship reports (DOCX and PDF) describing each phase of the project in detail.
- `figures/` – extracted images from the reports (CAD drawings, FEA results, process flow diagrams, BOM tables, test graphs).
- `README.md` – this detailed summary of the internship project.

## Usage
This repository serves as an educational example of a complete product development cycle using injection moulding. Readers are encouraged to explore the reports and figures to understand design trade‑offs, tooling considerations, simulation techniques and testing procedures. The materials may be reused for academic coursework or as a baseline for future interns at EQIC.

---

© 2025 EQIC Internship Project – All rights reserved. Distributed under the MIT License.
