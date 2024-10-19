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
