# Hybrid AS/RS: Horizontal Carousel + Gantry Robot

This repository documents a mechanical design project for a hybrid Automated Storage and Retrieval System (AS/RS) that combines a horizontal carousel storage module with a 2-axis Cartesian gantry robot for pharmaceutical logistics.

The full Autodesk Inventor CAD dataset is stored on Google Drive because the project contains many binary CAD files and is too large for a practical GitHub source repository.

## CAD Dataset

Full CAD folder:

[Google Drive - Inventor/Do_an](https://drive.google.com/drive/folders/1Sn_CB8pcfmrpL1zXy3Kl_hejoQp6ZOSC?usp=sharing)

Drive structure:

```text
Inventor/Do_an
├── Ban_ve_mo_hinh
│   ├── Gantry
│   └── Kho_xoay_ngang
└── Ban_ve_thuc_te
    ├── Ban_ve_gantry
    ├── Ban_ve_kho_xoay_ngang
    ├── Gantry
    └── Kho_xoay_ngang
```

See [docs/cad-data-map.md](docs/cad-data-map.md) for a more detailed map of the CAD data.

## Project Overview

The project studies, designs, and fabricates a compact AS/RS concept for hospital and pharmaceutical storage environments where floor area is limited and ceiling height can be under 3 m.

The proposed system is composed of two main mechanical subsystems:

| Subsystem | Purpose |
| --- | --- |
| Horizontal carousel | Stores totes/trays in a rotating high-density layout. |
| 2-axis gantry robot | Moves to the target storage location and handles retrieval/placement. |
| Telescopic fork end-effector | Extends into the storage position to pick or place a tote. |

The design target described in the project report includes 25 kg tote handling, improved storage density compared with static shelving, and mechanical validation through hand calculations and finite element analysis.

## Mechanical Scope

Key design areas covered by the CAD package:

- Horizontal carousel frame and rotating storage structure.
- Chain/sprocket drive layout for the carousel module.
- Gantry frame, linear motion structure, and sliding assemblies.
- Motor mounts, bearings, couplings, and support brackets.
- Pick-and-place mechanism/end-effector concepts.
- Manufacturing drawings for selected fabricated parts.
- FEA-related Inventor files for selected load-bearing components.

## My Contributions

- Developed 3D CAD models for the horizontal carousel and gantry robot subsystems in Autodesk Inventor.
- Prepared 2D technical drawings for selected fabricated components using AutoCAD.
- Performed dynamic simulation and stress analysis to support mechanical design validation.
- Organized CAD files and documentation for portfolio review.

## Design Highlights

- Hybrid AS/RS layout combining dense carousel storage with robotic access.
- Low-height configuration intended for constrained indoor pharmacy/logistics spaces.
- Rack-and-pinion and guided linear motion concepts for gantry travel.
- Chain-driven horizontal carousel architecture.
- Telescopic fork concept for tote retrieval.
- Structural checks focused on deflection, stress, and safety factor of critical members.

## How To Review The CAD Model

1. Open the Google Drive folder and download the full `Inventor/Do_an` directory.
2. Keep the folder structure unchanged so Inventor assembly references remain valid.
3. Start with these top-level assemblies:
   - `Ban_ve_mo_hinh/Gantry/Gantry.iam`
   - `Ban_ve_mo_hinh/Kho_xoay_ngang/Kho_xoay_ngang.iam`
   - `Ban_ve_thuc_te/Gantry/Gantry.iam`
   - `Ban_ve_thuc_te/Kho_xoay_ngang/Kho_xoay_ngang.iam`
4. Use the drawing folders for manufacturing-oriented views and part documentation.

## Repository Purpose

This GitHub repository is intentionally lightweight. It is meant to:

- Present the project clearly for reviewers, instructors, and engineering portfolios.
- Explain the system architecture and mechanical design scope.
- Provide stable navigation to the CAD dataset stored on Google Drive.
- Avoid pushing large binary CAD files into Git history.

## Source Report

The project report is titled:

`Research, Design, and Fabrication of a Hybrid AS/RS Integrating Horizontal Carousel and Gantry Robot for Pharmaceutical Logistics`

The report describes the design rationale, operational requirements, motion theory, mechanical calculations, material selection, and structural validation for the AS/RS concept.

## Team

Student project, University of Economics Ho Chi Minh City, College of Technology and Design, Institute of Intelligent and Interactive Technologies.

Advisor: PhD. Trinh Duc Cuong.

## License

No open-source license has been declared for the CAD files or project documentation. Please contact the project authors before reusing the design, drawings, or CAD dataset.
