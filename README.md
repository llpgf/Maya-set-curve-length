# Set Curve Length Tool for Maya 2026

A Python tool for Autodesk Maya 2026 to measure, adjust, and normalize the lengths of NURBS curves directly inside Maya.  
This script comes with a **custom UI** to make curve length operations fast and artist-friendly.

---

## Features

- **View curve length info** for any selected NURBS curves (average, min, max).  
- **Normalize curves to a common length**:  
  - Shortest curve  
  - Longest curve  
  - Average curve length  
- **Incrementally adjust curve length** (increase or decrease by user-defined value).  
- **Interactive Maya UI** with instant feedback and one-click actions.  
- **Shelf-ready**: Easily callable from a Maya shelf button.

---

## Requirements

- **Autodesk Maya 2026** (or compatible version with Python 3)  
- Maya’s built-in `maya.cmds` and `maya.mel` modules (no extra libraries required)  

---

## Installation

1. Download `set_curve_length.py` from this repository.  
2. Copy it to your Maya scripts folder:  
   - Windows: `Documents/maya/scripts`  
   - macOS: `~/Library/Preferences/Autodesk/maya/scripts`  
   - Linux: `~/maya/scripts`  
3. In Maya’s Python tab, run:  
   ```python
   import set_curve_length
   set_curve_length.main()
