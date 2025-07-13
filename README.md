# AE-Adaptive-Transition-Detection

This repository provides a lightweight and extensible framework for detecting **adaptive transitions in Acoustic Emission (AE) signals**, with a focus on **signal decay detection** during **additive manufacturing (AM)** processes. The methods implemented here are designed to be generalizable to other AE datasets for applications in fault detection, phase change monitoring, and signal segmentation.

---

## Overview

Acoustic Emission (AE) signals are widely used in real-time monitoring of structural integrity and manufacturing health. In additive manufacturing, AE signals can reflect material deposition, crack formation, cooling, and process termination. This repository provides methods to:

- Detect the **start of signal decay or transition** in AE signals.
- Apply multiple detection strategies including:
  - Root Mean Square (RMS) trend tracking
  - Low-pass filtering
  - Continuous Wavelet Transform (CWT)
- Compare decay start points across methods.
- Visualize and export results for further analysis.
