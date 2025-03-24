# Photoluminescence Comparison
# Automated, fast and simple

## Overview

This repository contains a Python-based standalone executable for comparing multiple Photoluminescence (PL) data. The program focuses on easy and fast visualization of the experimental data.

For questions, feature requests, bug reports, or collaboration opportunities, please contact the [**developer**](https://github.com/JosueHernandez0000). If you found this tool helpful, you can show your support by: [**Buying me a coffee!**](https://buymeacoffee.com/josue.hernandez) Every coffee helps me stay awake to keep improving the tool, adding new features, and providing you with even better analysis capabilities.

### Table of Contents
1. [Overview](#overview)
2. [Functionality](#functionality)
3. [Main Outputs](#Outputs)
4. [How to Use](#how-to-use)
5. [Technical Details](#technical-details)
6. [License](#license)


---
## 2. Functionality
1. **Plots multiple PL spectra in the same plot**: Plots experimental data, all files must be in .ssm format and stored in the same folder `raw_data`.

## 3. Main Outputs
The code is meant to be a quick and easy way to plot and visualize experimental XRD data. The main output of the program is:

<div align="center">
   <img src="plots/PL plot (Normalized Intensity).png" alt="PL_comparison" width="500">
</div>


## 4. How to Use
Follow these steps to use the software:
1. **Clone the repository to your own machine**
2. **Make sure the following folder structure is followed**:
```
PL VA 1.0.1/
  
│
├── plots/                        # Stores the generated plots
|
├── PL_raw_data/
│   ├── your_data_1.ssm      # PL data to be analyzed
|   └── your_data_1.ssm      # PL data to be analyzed
|
├── README.txt             # Documentation for the project.
├── LICENSE     
└── PL_VA_v1.0.0.exe      # Standalone .exe file
```

3. **Run the .exe file**
4. **Select all the files you want to compare**
4. **Open the plots in the plots folder**


## 5. Technical Details

The sensitivity value can be adjusted to identify more or less peaks.

## 6. License

This project is licensed under the MIT License — see the `LICENSE` file for details.
