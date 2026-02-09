# OCT FDA Visualisation using oct_converter

## Overview
This project uses the **oct_converter** library to inspect and visualise OCT data stored in FDA/FDS files.

The workflow includes:
- Visualisation of OCT volumes (B-scans)
- Display of retinal layer boundaries (when available)
- Visualisation of fundus / SLO images
- Printing key patient, device, and acquisition metadata

The focus is on **data inspection and quality control**, not full vendor-level decoding.

---

## Features
- OCT volume shape and number of B-scans
- Fundus image size and resolution
- Selected metadata: patient ID, laterality, device model, bits per pixel, acquisition date, and pixel spacing

---

## Libraries
- Python
- `oct_converter`
- `numpy`
- `matplotlib`

---

## Notes
- FDA/FDS files are vendor-dependent and may contain partial metadata.
- Not all files include fundus images or segmentation data.
- The code safely handles missing metadata fields.

