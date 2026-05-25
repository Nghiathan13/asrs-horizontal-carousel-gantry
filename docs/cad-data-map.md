# CAD Data Map

The Autodesk Inventor CAD dataset is hosted on Google Drive:

[Google Drive - Inventor/Do_an](https://drive.google.com/drive/folders/1Sn_CB8pcfmrpL1zXy3Kl_hejoQp6ZOSC?usp=sharing)

## Why CAD Files Are Stored Outside GitHub

The local CAD dataset contains more than 1,000 files and is roughly 677 MB. Most files are binary Inventor files (`.ipt`, `.iam`, `.idw`) plus drawings and simulation artifacts. Keeping these files directly in Git would make cloning, reviewing, and versioning inefficient.

GitHub is used here as the public-facing documentation layer, while Google Drive is used as the CAD storage layer.

## Local File Summary

Observed from the local `Inventor/Do_an` folder:

| Extension | Count | Notes |
| --- | ---: | --- |
| `.ipt` | 973 | Inventor part files |
| `.iam` | 75 | Inventor assembly files |
| `.pdf` | 27 | Exported drawings/reports |
| `.dwg` | 10 | 2D CAD drawings |
| `.idw` | 3 | Inventor drawing files |
| `.STEP` | 2 | Neutral CAD exchange files |
| Other | 7 | Inventor/FEA support outputs |

## Folder Roles

### `Ban_ve_mo_hinh`

Prototype/model-scale CAD used to communicate the main concept and mechanism layout.

Main subfolders:

- `Gantry`: gantry frame, motor module, sliders, belt tensioning, pickup mechanism, fasteners, and related components.
- `Kho_xoay_ngang`: horizontal carousel module, chain path, storage rack, rotating frame, motor, shaft, bearings, and fabrication drawings.
- `Canh_tay_robot`: robot arm related model folder.

### `Ban_ve_thuc_te`

Fabrication-oriented or full-scale design data.

Main subfolders:

- `Ban_ve_gantry`: gantry drawing package.
- `Ban_ve_kho_xoay_ngang`: horizontal carousel drawing package.
- `Gantry`: actual gantry structure, vertical sliding mechanism, horizontal sliding mechanism, pickup mechanism, and frame.
- `Kho_xoay_ngang`: actual carousel structure, spring/guide mechanism, chain path, rack frame, rotating frame, motor mount, and coupling components.

## Recommended Review Path

For a fast technical review:

1. Read the GitHub README to understand the system intent and architecture.
2. Open the Drive folder and inspect the two top-level branches: `Ban_ve_mo_hinh` and `Ban_ve_thuc_te`.
3. Open the main `.iam` assemblies before individual `.ipt` part files.
4. Review drawing folders after understanding the assembly hierarchy.
5. Treat `OldVersions` folders as CAD history/reference data, not as the primary review target.

## Suggested Future Repository Additions

Useful additions if the project is prepared for a formal engineering portfolio:

- Rendered images of the full AS/RS system.
- A short demo video or GIF of the gantry and carousel motion.
- Exported BOM tables.
- PDF manufacturing drawings for key fabricated parts.
- A short design-calculation summary with load assumptions, factors of safety, and FEA results.
