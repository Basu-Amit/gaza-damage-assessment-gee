# Gaza Damage Assessment using Google Earth Engine

## Author
Dr. Amit Kumar Basukala  

If you use this work, please provide appropriate credit.

---

## Overview
This project performs damage assessment in Gaza before and after October 7, 2023 using:

- NDVI (vegetation index)
- NDBI (built-up index)
- Google Cloud Score+ (cloud masking)

---

## Methodology

Damage classification is based on:

- Increase in NDBI (built-up / rubble signal)
- Decrease in NDVI (vegetation loss)

### Classes:
- 0 → Not destroyed  
- 1 → Semi-destroyed  
- 2 → Completely destroyed  

---

## Outputs

- Destruction classification map
- NDVI change map
- NDBI change map
- Area statistics (km²)
- Swipe comparison UI (before vs after)

---

## Requirements

- Google Earth Engine account  
- Code Editor: https://code.earthengine.google.com/

---

## Usage

1. Copy script into GEE Code Editor
2. Define your AOI
3. Run script
4. Start export tasks from **Tasks tab**

---

## Disclaimer

This is a **remote sensing-based estimation**, not ground-truth validated.
Results depend on thresholds and data quality.

---

## License

MIT License (or specify your own)
