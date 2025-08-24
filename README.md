# Sheet Metal Processor Housing

## Overview

This repository showcases a sheet metal processor housing designed in **SolidWorks** to demonstrate my skills in CAD modeling, sheet metal design, and technical documentation. The project includes a complete assembly, individual part models, detailed technical drawings, a Bill of Materials (BOM), and STEP files for interoperability. The design is optimized for manufacturing and assembly precision.

## Project Details

The processor housing is a sheet metal enclosure designed for a desktop computer CPU, ensuring structural integrity, thermal management, and component alignment. The project highlights proficiency in:

- Sheet metal design (bends, cutouts, and tolerances).
- Assembly modeling with precise mating.
- Technical drawing creation with GD&T (Geometric Dimensioning and Tolerancing).
- BOM generation for manufacturing.
- Exporting interoperable STEP files for collaboration.

### Components

The project consists of five primary models:

1. **Case Assembly (`CASE_ASSY.SLDASM`)**:
   - The main enclosure assembly, integrating all components.
   - Features an **exploded view** in the technical drawing to illustrate assembly sequence and component relationships.
2. **Card Guide Middle (`MAX_CARD_GUIDE_MIDDLE.SLDPRT`)**:
   - A central guide for aligning internal components (e.g., circuit boards) within the housing.
   - Designed with precise slot dimensions for secure fitment.
3. **Card Guide Left (`MAX_CARD_GUIDE_LEFT.SLDPRT`)**:
   - Left-side guide for component alignment, mirroring the right guide.
   - Optimized for sheet metal bending and manufacturability.
4. **Card Guide Right (`MAX_CARD_GUIDE_RIGHT.SLDPRT`)**:
   - Right-side guide, ensuring symmetry and alignment with the middle guide.
5. **Max Housing (`MAX_HOUSING`)**:
   - Model for the main enclosure.

### Technical Drawings

- **Individual Part Drawings**:
  - Detailed drawings for each part (`MAX_CARD_GUIDE_MIDDLE.SLDPRT`, `MAX_CARD_GUIDE_LEFT.SLDPRT`, `MAX_CARD_GUIDE_RIGHT.SLDPRT`, `MAX_HOUSING`).
  - Include dimensions and sheet metal bend annotations.
- **Assembly Drawing**:
  - Comprehensive drawing for `CASE_ASSY.SLDASM` with an exploded view.
  - Includes a **Bill of Materials (BOM)** listing all components, including fasteners (`MAX_flat head 100 screw.SLDPRT`, `MAX_flat washer type a narrow_ai.sldprt`, `MAX_machine screw nut hex_ai.sldprt`).
- **PDF Exports**:
  - All drawings are exported as PDFs for easy sharing and review (located in the `PDF/` folder).

### STEP Files

- STEP files (`.stp`) are provided for all parts and the assembly (`CASE_ASSY.stp`) to enable:
  - Interoperability with other CAD software (e.g., Fusion 360, etc.).
  - Manufacturing or CNC machining compatibility.
