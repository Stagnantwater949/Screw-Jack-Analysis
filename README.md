# Screw Jack Analysis

This repository contains a standard mechanical analysis of a screw jack. The analysis focuses on the design and performance evaluation of the screw jack's components.

All the expressions and formulas used in this analysis can be found in various Mechanical Design textbooks and are adopted from "Design of Machine Elements - Shigley".

## Overview

The screw jack is a simple device used for lifting heavy loads, consisting of a screw, a nut, and a handle that transforms rotary motion into linear motion. This project assesses the design by calculating critical parameters such as torque, stresses, and dimensions based on user inputs.

## Required Inputs
To run the MATLAB code, the following inputs are required:

1. **Load to be lifted (W)**: Enter the load (KN).
2. **Screw material Tensile Strength (Sst)**: Enter the tensile strength of the screw material (MPa).
3. **Screw material Shear Strength (Sss)**: Enter the shear strength of the screw material (MPa).
4. **Bearing pressure (Pb)**: Enter the bearing pressure between the nut and screw (MPa).
5. **Factor of Safety (Nf)**: Enter the desired factor of safety (No Units).
6. **Coefficient of friction (mu)**: Enter the coefficient of friction between the screw and nut (No Units).
7. **Coefficient of collar friction (mu1)**: Enter the coefficient of collar friction (No Units).
8. **Nut Tensile Strength (Snt)**: Enter the tensile strength of the nut material (MPa).
9. **Nut Compressive Strength (Snc)**: Enter the compressive strength of the nut material  (MPa).
10. **Nut Shear Strength (Sns)**: Enter the shear strength of the nut material  (MPa).
11. **Max lift height (max_lift)**: Enter the lift height in millimeters (mm).

## Outputs Calculated
The code calculates the following outputs:

### 1. Screw Design Outputs:
- **Screw Major Diameter (do)**: The outer diameter of the screw.
- **Screw Minor Diameter (dc)**: The inner diameter of the screw.
- **Screw Helix Angle**: The angle of the screw thread (in degrees).
- **Friction Angle**: The angle of friction between the screw and nut (in degrees).
- **Torque Required to Rotate the Screw (T1)**: The torque needed to lift the load (in Nmm).
- **Torsional Shear Stress Induced (τ)**: The shear stress caused by the applied torque (in MPa).
- **Direct Compressive Stress (σC)**: The stress caused by the axial load (in MPa).

### 2. Safety Checks:
- **Safety Check for Induced Stresses**: A statement indicating whether the induced shear and compressive stresses are within permissible limits.

### 3. Maximum Principal Stresses:
- **Maximum Shear Stress (τ_max)**: Calculated based on maximum shear stress theory (in MPa).
- **Maximum Normal Stress (σ_max)**: Calculated using maximum normal stress theory (in MPa).
- **Safety Check for Maximum Principal Stresses**: A statement indicating whether the maximum stresses are within permissible limits.

### 4. Nut Design Outputs:
- **Safe Tensile Stress for Nut**: Allowable tensile stress for the nut (in MPa).
- **Safe Compressive Stress for Nut**: Allowable compressive stress for the nut (in MPa).
- **Safe Shear Stress for Nut**: Allowable shear stress for the nut (in MPa).
- **Height of Nut**: Height of the nut based on the number of threads in contact (in mm).
- **Transverse Shear Stress for Screw and Nut**: Shear stress calculations for both the screw and the nut (in MPa).

### 5. Nut Collar Design Outputs:
- **Collar Inner Diameter (D1)**: Inner diameter of the collar (in mm).
- **Collar Outer Diameter (D2)**: Outer diameter of the collar (in mm).
- **Thickness of Nut Collar (t1)**: Thickness of the nut collar (in mm).

### 6. Screw Head Dimensions:
- **Head Diameter (D3)**: Diameter of the screw head (in mm).
- **Outer and Inner Diameters of Cup (Dcup, dcup)**: Dimensions of the cup fitted with the screw (in mm).

### 7. Handle Dimensions:
- **Torque Required to Overcome Friction (T2)**: Torque needed at the handle (in Nmm).
- **Diameter of Handle (Dh)**: Diameter calculated for the handle based on applied torque (in mm).

### 8. Body Dimensions:
- **Diameter of Body at Top (D5)**: Diameter of the body at the top (in mm).
- **Thickness of Body (t3)**: Thickness of the body (in mm).
- **Inside and Outside Diameters of Body at Bottom (D6, D7)**: Inner and outer diameters at the bottom of the body (in mm).
- **Thickness of Base (Tb)**: Thickness of the base (in mm).
- **Height of Body (Hb)**: Total height of the body (in mm).

### 9. Plots
The code also includes plots to visualize the relationships between various parameters, enhancing the analysis and understanding of the screw jack design.
