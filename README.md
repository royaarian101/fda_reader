# Topcon OCT FDA Visualisation using oct_converter

## Overview
This project demonstrates the use of **oct_converter** to inspect and visualise **Topcon OCT data**
stored in FDA/FDS containers.

The workflow focuses on:
- Visualising Topcon OCT volumes (B-scans)
- Displaying retinal layer boundaries when available
- Visualising fundus / SLO images
- Printing key patient, device, and acquisition metadata

The code is intended for **data inspection and quality control**, not full proprietary decoding.

---

## Features
- OCT volume geometry and number of B-scans
- Fundus / SLO image size and data type
- Selected metadata: patient ID, laterality, device model (3D OCT-1000 series), bits per pixel, acquisition date, and pixel spacing

---

## Libraries
- Python
- `oct_converter`
- `numpy`
- `matplotlib`

---

## Notes
- Topcon FDA files are vendor-dependent and may expose limited metadata.
- Not all Topcon files include fundus or segmentation information.
- The implementation safely handles missing or partial metadata.

